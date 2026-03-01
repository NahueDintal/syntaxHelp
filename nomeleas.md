el path para .bashrc

export PATH="$HOME/.syntaxHelp/bin:$PATH"

enlace con un micro script para enlazar con el escript en el directorio...

echo '#!/bin/bash\n~/.syntaxHelp/bin/shelp "$@"' > ~/.local/bin/sy
chmod +x ~/.local/bin/sy


