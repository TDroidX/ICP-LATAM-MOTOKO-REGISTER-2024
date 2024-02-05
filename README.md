# ICP-LATAM-MOTOKO-REGISTER-2024
BIENVENIDO A NUESTRO PROGRAMA DE CERTIFICACIÓN EN MOTOKO
El proyecto es sencillo, consiste en un formulario el cual pueda registrar el nombre, numero telefonico, nombre de la mascota y sintomas, esto lo guarda en una blockchain y deja el registro almacenado con un ID para su respectivo chequeo, 
su funcionalidad consiste en un CRUD, con el cual puedas manejar de manera sencilla la información proporcionada mediante el uso de MOTOKO.

### PAQUETES NECESARIOS PARA SU EJECUCIÓN:

###  WSL
```bash
wsl --install
```

###  ABRIR UBUNTU
```bash
sudo apt update
```

```bash
sudo apt install curl
```

###  INSTALAR NODE.JS, NVM Y NPM
###  https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-wsl
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash
```
```bash
nvm install --lts
```

###  INSTALAR VSCODE
```bash
https://code.visualstudio.com/download
```
###  Instalar la version de su sitema operativo e instalar la extensión de WSL en VsCode.

###  INSTALAR GIT 
Si tienes Linux/WSL:
```bash
sudo apt install git
```


###  Si tienes Mac:
```bash
https://git-scm.com/download/mac
```

###  INSTALAR DFX 
https://internetcomputer.org/docs/current/developer-docs/setup/install/
```bash
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
```
```bash
dfx --version
```
###  CLONAR REPOSITORIO 
```bash
https://github.com/TDroidX/ICP-LATAM-MOTOKO-REGISTER-2024/tree/main
```
```bash
cd ICP-Developer
```
```bash
npm install
```
```bash
dfx start --background --clean
```
```bash
dfx deploy
```
###  SI FALLA AL CORRER EJECUTAS 
```bash
dfx generate
```
###  LUEGO 
```bash
dfx deploy
```
```bash
npm run serve
```

Por ultimo abres el link que te proporciona para ir a la ejecucion de tu blockchain y ejecutar el formulario.
