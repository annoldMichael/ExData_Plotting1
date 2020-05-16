##  Introduction

Cette affectation utilise des données de
la <a href="http://archive.ics.uci.edu/ml/"> UC Irvine Machine
Learning Repository </a>, un référentiel populaire pour l'apprentissage automatique
jeux de données. En particulier, nous utiliserons le "Ménage individuel
ensemble de données sur la consommation d'énergie électrique "que j'ai mis à disposition sur
le site web du cours:


* <b> Dataset </b>: <a href="https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip"> Consommation d'électricité </a> [20Mb]

* <b> Description </b>: Mesures de la consommation électrique en
un ménage avec un taux d'échantillonnage d'une minute sur une période de près de
4 années. Différentes quantités électriques et certaines valeurs de sous-comptage
sont disponibles.


Les descriptions suivantes des 9 variables de l'ensemble de données sont prises
de
l '<a href="https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption"> UCI
site Web </a>:

<ol>
<li> <b> Date </b>: date au format jj / mm / aaaa </li>
<li> <b> Heure </b>: heure au format hh: mm: ss </li>
<li> <b> Global_active_power </b>: puissance active moyenne mondiale par minute des ménages (en kilowatt) </li>
<li> <b> Global_reactive_power </b>: puissance réactive moyenne des ménages dans le monde (en kilowatt) </li>
<li> <b> Tension </b>: tension moyenne en minutes (en volt) </li>
<li> <b> Global_intensity </b>: intensité du courant mondial moyen en minutes par ménage (en ampères) </li>
<li> <b> Sub_metering_1 </b>: sous-compteur d'énergie n ° 1 (en watt-heure d'énergie active). Il correspond à la cuisine, contenant principalement un lave-vaisselle, un four et un micro-ondes (les plaques chauffantes ne sont pas électriques mais au gaz). </li>
<li> <b> Sub_metering_2 </b>: sous-compteur d'énergie n ° 2 (en wattheures d'énergie active). Il correspond à la buanderie, contenant un lave-linge, un sèche-linge, un réfrigérateur et une lumière. </li>
<li> <b> Sub_metering_3 </b>: sous-compteur d'énergie n ° 3 (en wattheures d'énergie active). Il correspond à un chauffe-eau électrique et à un climatiseur. </li>
</ol>

##  Chargement des données





Lors du chargement de l'ensemble de données dans R, veuillez tenir compte des éléments suivants:

* L'ensemble de données comprend 2 075 259 lignes et 9 colonnes. Première
calculer une estimation approximative de la quantité de mémoire dont l'ensemble de données aura besoin
en mémoire avant de lire dans R. Assurez-vous que votre ordinateur en a assez
mémoire (la plupart des ordinateurs modernes devraient être bien).

* Nous n'utiliserons que les données des dates 2007-02-01 et
2007-02-02. Une alternative consiste à lire les données à partir de ces dates
plutôt que de lire dans l'ensemble de données et de sous-ensemble à ceux
Rendez-vous.

* Il peut être utile de convertir les variables de date et d'heure en
Classes de date / heure dans R utilisant les `strptime ()` et `as.Date ()`
les fonctions.

* Notez que dans cet ensemble de données, les valeurs manquantes sont codées comme «?» .


##  Création de parcelles

Notre objectif global ici est simplement d'examiner comment la consommation d'énergie des ménages
varie sur une période de 2 jours en février 2007. Votre tâche consiste à
reconstruire les parcelles ci-dessous, qui ont toutes été construites
en utilisant le système de traçage de base.

Tout d'abord, vous devrez créer et cloner le référentiel GitHub suivant:
[ https://github.com/rdpeng/ExData_Plotting1 ] (https://github.com/rdpeng/ExData_Plotting1)


Pour chaque parcelle, vous devez

* Construisez le tracé et enregistrez-le dans un fichier PNG d'une largeur de 480
pixels et une hauteur de 480 pixels.

* Nommez chacun des fichiers de tracé comme `plot1.png` , ` plot2.png` , etc.

* Créez un fichier de code R séparé ( `plot1.R` , ` plot2.R` , etc.) qui
construit le tracé correspondant, à savoir le code dans `plot1.R` constructions
l' intrigue `plot1.png` . Votre fichier de code ** doit inclure du code pour la lecture
les données ** afin que le tracé puisse être entièrement reproduit. Tu devrais aussi
inclure le code qui crée le fichier PNG.

* Ajoutez le fichier PNG et le fichier de code R à votre référentiel git

Lorsque vous avez terminé l'affectation, poussez votre référentiel git vers
GitHub pour que la version GitHub de votre référentiel soit à jour
Date. Il doit y avoir quatre fichiers PNG et quatre fichiers de code R.


Les quatre parcelles que vous devrez construire sont présentées ci-dessous. 


###  Terrain 1


! [ tracé de morceau sans nom-morceau-2 ] (figure / sans nom-morceau-2.png)


###  Terrain 2

! [ tracé de morceau sans nom-morceau-3 ] (figure / sans nom-morceau-3.png)


###  Terrain 3

! [ tracé de morceau sans nom-morceau-4 ] (figure / sans nom-morceau-4.png)


###  Terrain 4

! [ tracé de morceau sans nom-morceau-5 ] (figure / sans nom-morceau-5.png)
