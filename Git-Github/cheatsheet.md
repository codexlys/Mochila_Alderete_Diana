# Comandos de Git

## Crear un repositorio
| Comando                                    | Descripción                      |
| :---:                                      | :---                             |
| ```git init```                             | Crear un nuevo repositorio local |
| ```git config user.name "[name]"```        | Configurar tus credenciales, se puede colocar el nombre que desees |
| ```git config user.email "[repo-email]"``` | Se colocar el correo asociado a la cuenta de github |
| ```git remote add origin [repo-url]```     | Vincula tu repositorio local con tu github |
| ```git branch -M main```                   | Renombra la rama actual a main   |

## Clonar un repositorio 
| Comando                                    | Descripción                      |
| :---:                                      | :---                             |
| ```git clone [repo-url]```                 | Clonar un repositorio existente de Github a tu local |

## Agregar cambios
| Comando                                    | Descripción                      |
| :---:                                      | :---                             |
| ```git add .```                            | Agrega cambios nuevos o modificaciones(no eliminaciones) que se encuentran en tu working directory al staging area |
| ```git add --all ó git add -A ```          | Agrega todos los cambios que se encuentran en todo el working directory al staging area  |
| ```git commit -m "[descripción cambios]"```| Describe los cambios que se han realizado |
| ```git push -u origin main ```             | Subir los cambios al repositorio remoto. El flag -u se usa para que los sgtes envios solo se ejecuten con git push
| ```git push origin main```                 | Subir los cambios al repositorio remoto |

## Otros comandos útiles
| Comando                                    | Descripción                      |
| :---:                                      | :---                             |
| ```git status```                           | Muestra el estado actual del repositorio de git, con respecto al local working directory y el staging area |
| ```git diff```                             | Muestra las diferencias entre los cambios realizados en los archivos del working directory y el commit más reciente
| ```git log```                              | Muestra el historial de commits de un repositorio |
| ```git remote -v```                        | Muestra una lista de los repositorios remotos que están asociados con el repositorio git actual |
| ```git remote set-url origin [repo-url]``` | Cambia de repositorio remoto    |

