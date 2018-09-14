# ruby-project-install

Installation plateforme ruby on rails


#  Etape 1 : Installation de brew

Brew est un outil pour MacOS qui permet d'installer en ligne de commande des applications ou des librairies

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`


# Etape 2 : Installation git

Git permet de sauvegarder et de versionner son code de façon decentraliser

`brew intall git`

# Etape 3 :  Installation de Xcode

Xcode est l'outil de compilation c++ / objectif C

`xcode-select --install`

# Etape 4 : Installation de RVM

RVM est un outil qui permet d'installer les librairies du langage ruby

`\curl -sSL https://get.rvm.io | bash -s stable`

la commande suivante permet d'afficher la liste de toutes les version de ruby

`rvm list known`

la commande suivante permet d'afficher la liste de toutes les versions de ruby installées sur le poste de travail

`rvm list`

# Etape 5 : Installation de versions de ruby

la commande suivante permet d'installer la version ruby Ruby 2.2.6

`rvm install 2.2.6`

la commande suivante permet d'installer la version ruby Ruby 2.3.3

`rvm install 2.3.3`

la commande suivante permet d'installer la version ruby Ruby 2.3.7

`rvm install 2.3.7`

la commande suivante permet d'installer la version ruby Ruby 2.4.4

`rvm install 2.4.4`

la commande suivante permet de selection la version de ruby utilisée par default sur son poste de travail

`rvm use 2.2.6 --default`

`rvm list`

# Etape 6 : Installation Postgres

la commande permet d'installer une base de donnée relationnelle

`brew install postgres`

# Etape 7 : Installation PgAdmin

`PgAdmin est la console de gestio de la base de donnee postgres`

https://www.postgresql.org/ftp/pgadmin/pgadmin4/v2.0/macos/

# Etape 8 : Installation heroku 

la commande suivante permet d'installer un environement pour deployer son application sur la plateforme cloud

`brew install heroku`

# Etape 9 : Creation projet blog

Installation de la version rails 5.0 associé à la version de ruby 2.3.7

`rvm use 2.3.7`

Utilisation d'un systeme de container pour separer les differentes version de ruby avec les differentes version du framework rails 

`rvm gemset create rails500`

`rvm 2.3.7@rails500`

`gem install rails -v 5.0`

`rails new blog`

`cd blog`

= > Generation des fichiers '.ruby-version .ruby-gemset'

`cd ..`

`cd blog`

Saisir la ligne de commande suivante pour verifier la version de ruby installée(2.3.7)

`ruby -v`

Saisir la ligne de commande suivante pour afficher les fichiers '.ruby-version .ruby-gemset'

`ls -a`









