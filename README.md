# Curs Git 

### En aquest repositori podem observar algunes comandes de Git més essencials per poder treballar amb el controlador de versions Git. 

## Com Descarregar Git

<https://git-scm.com/downloads>

## Com afegir claus SSH de Github

<https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent>


## Comandes Git 
### "prova" és una branca d'exemple.
### "xxxxx" és un hash de un commit o branca d'exemple.

| Comanda                             | Descripció                                                                        |
| :---------------------------------- | :-------------------------------------------------------------------------------- |
| `git init`                          |  Començar un projecte o repositori en local amb Git.                              |
| `git status`                        |  Veure l'estat del repositori en què estem treballant.                            |
| `git add index.html`                |  Afegir o Trakejar un arxiu amb Git.                                              |
| `git add .`                         |  Afegir o Trakejar tot el directori en què ens situem.                            |
| `git commit -m "Missatge"`          |  Fer un commit amb un missatge de després de fer un add.                          |
| `git commit -a -m "Missatge"`       |  Fer un commit i add amb missatge a la vegada.                                    |
| `git log`                           |  Mostrar per consola un seguiment de les modificacions i commits del repositori.  |
| `git log --oneline --graph`         |  Mostra per consola un seguiment gràficament i cada commit en una línea.          |
| `git log --oneline -n 2`            |  Mostra per consola els dos últims commits en una línea.                          |
| `git reset xxxxx`                   |  Reset del repositori a una branca o commit concret a partir del seu hash.        | 
| `git restore index.html`            |  Recuperar l'estat d'un arxiu com estava en la branca o commit que us trobeu.     |
| `git remote add origin url`         |  Pujar el repositori local a Github mitjançant la url que et dona Github.         | 
| `git push`                          |  Pujar canvis d'un repositori de Github.                                          |
| `git checkout -b prova`             |  Crear una branca dins el repositori i accedir a ella.                            |
| `git branch`                        |  Observar per pantalla totes les branques del repositori.                         |
| `git branch prova`                  |  Crear una branca dins el repositori.                                             |
| `git push -u origin prova`          |  Pujar i crear la branca dins de Github.                                          |
| `git pull`                          |  Descarregar els últims canvis de la branca.                                      |
| `git merge prova`                   |  Fer un merge de una branca en local.                                             |
| `git pull origin prova `            |  Descarregar una branca de Github.                                                |
| `git rebase -i prova`               |  Reescriure els commits fets dins una branca.                                     |
| `git branch -D prova`               |  Eliminar una branca del repositori.                                              |
| `git commit --amend -m "Nou Títol"` |  Modificar el títol del anterior commit executat.                                 |
| `git stash`                         |  Guardar canvis en local.                                                         |
| `git stash list`                    |  Observar els stash guardats en local.                                            |
| `git stash pop`                     |  Recuperar canvis guardats en el stash.                                           |
| `git tag -a v0.1.0 -m "Títol"`      |  Crear una versió del repositori.                                                 |
| `git tag`                           |  Observar els tags que té el repositori.                                          |
| `git show v0.1.0`                   |  Informació detallada de la versió.                                               |
| `git push origin v0.1.0`            |  Pujar el tag creat a Github.                                                     |
| `git --help`                        |  Comanda per observar totes les comandes de Git amb més detall.                   |
