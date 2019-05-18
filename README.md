## **Matrix/Synapse Homeserver Installer** 

### With this script you can automate the installation and preparation of the environment and the dependencies of Matrix / Synapse

#### The script has 3 parts, the installation of the environment required by Matrix, the installation of Python 3.6 (CentOS 7 has Python 2, but this version creates conflicts with Matrix / Synapse) and the installation and creation of the service environment, using pip we downloaded Synapse software and installed it
#### The script demands data such as your administrator password and the directory path where you want to create the Synapse environment. Once the process is finished, the program execution will leave a "synapse" folder in the indicated path.
#### Optionally, a menu is displayed, where you can generate the following things:

### - Generate the first parameters of the Matrix environment (Generate the communication server itself)
### - Generate TLS certificates for the server with Let'sEncrypt certbot
### - Download and compile Turn software for VoIP integration in the Matrix server
### - As a last option, you can exit the menu and finish the program with the 4th option

#### *NOTE: This script is written to work on CentOS 7, if you run it on another system that is not named, you will have to rewrite a large part of the code.*

