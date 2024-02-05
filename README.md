# ICP-LATAM-MOTOKO-REGISTER-2024
BIENVENIDO A NUESTRO PROGRAMA DE CERTIFICACIÓN EN MOTOKO
El proyecto es sencillo, consiste en un formulario el cual pueda registrar el nombre, numero telefonico, nombre de la mascota y sintomas, esto lo guarda en una blockchain y deja el registro almacenado con un ID para su respectivo chequeo, 
su funcionalidad consiste en un CRUD, con el cual puedas manejar de manera sencilla la información proporcionada mediante el uso de MOTOKO.

PAQUETES NECESARIOS PARA SU EJECUCIÓN:

* WSL * 
-wsl --install

* ABRIR UBUNTU 
-sudo apt update
-sudo apt install curl

* INSTALAR NODE.JS, NVM Y NPM 
https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-wsl
-curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash
-nvm install --lts

* INSTALAR VSCODE 
-https://code.visualstudio.com/download
" Instalar la version de su sitema operativo e instalar la extensión de WSL en VsCode. "

* INSTALAR GIT 
Si tienes Linux/WSL:
-sudo apt install git

Si tienes Mac:
-https://git-scm.com/download/mac

* INSTALAR DFX 
https://internetcomputer.org/docs/current/developer-docs/setup/install/
-sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
-dfx --version

* CLONAR REPOSITORIO 
-https://github.com/TDroidX/ICP-LATAM-MOTOKO-REGISTER-2024/tree/main
-cd ICP-Developer
-npm install
-dfx start --background --clean
-dfx deploy
* SI FALLA AL CORRER EJECUTAS 
-dfx generate
* LUEGO 
-dfx deploy
-npm run serve

Por ultimo abres el link que te proporciona para ir a la ejecucion de tu blockchain y ejecutar el formulario.
