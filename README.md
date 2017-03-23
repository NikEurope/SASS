
# SASS DOC


Sass info  http://www.sass-lang.com/guide

https://la-cascade.io/se-lancer-dans-sass/

Install Sass http://www.sass-lang.com/install


Ex SASS -> CSS : https://github.com/NikEurope/SASS/blob/master/ex.md



##Intégration graphique avec Sass

Installation


Ruby:

sudo yum install ruby ruby-devel -y


Compass:

gem install compass

gem install bootstrap-sass



Compilation: dans le dossier du thème lancer la compilation

cd themes/MySite

compass compile



Pour forcer la suppression des fichiers css et la recompilation des fichiers scss :

cd themes/cnas
compass clean && compass compile


# SASS DRUPAL :

Go to Themes > MyTheme:
Installation
Ruby
sudo yum install ruby ruby-devel -y


Compass
gem install compass
gem install bootstrap-sass


Compilation
dans le dossier du thème lancer la compilation
cd themes/cnas
compass compile

OU 

compass clean && compass compile - nettoyer et compiler le SASS avec CSS


Pour forcer la suppression des fichiers css et la recompilation des fichiers scss :
cd themes/MyTheme
compass clean && compass compile



## css 2 sass converter :

http://css2sass.herokuapp.com/

http://sebastianpontow.de/css2compass/




