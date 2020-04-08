# Blog para curso de platzi git y github
"hyperblog mejorado"

Favor de no modificar este archivo a menos de ser necesario

## generate SSH KEY
~ ssh-keygen -t rsa -b 4096 -C "robert.hct@gmail.com"
passphrase: ""


## Comando para evaluar que las llaves estén corriendo
* eval $(ssh-agent -s)

## Añadir entidad con llave privada
* ssh-add ~/.ssh/id_rsa

## SSH en GITHUB

* cd proyecto1/

* git remote -v
* origin  https://github.com/CETHER/hyperblog.git (fetch)
* origin  https://github.com/CETHER/hyperblog.git (push)

Se cambia la url con el siguiente comando, y se copia la url de clone por ssh del repositorio de github
* git remote set-url origin git@github.com:CETHER/hyperblog.git

Ya hecho el cambio se visualiza la siguiente url
* git remote -v
* origin  git@github.com:CETHER/hyperblog.git (fetch)
* origin  git@github.com:CETHER/hyperblog.git (push)


# "El equipo CETHERDEV se despide atentamente"