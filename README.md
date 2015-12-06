An english version of this text is available in [README.en.md](README.en.md).

Dans le climat d'insécurité actuel dû à la menace terroriste, de 
nombreux pays (dont la France, le Royaume-Uni et les États-Unis) ont
attiré l'attention sur les difficultés rencontrées par les équipes 
chargées d'identifier les terroristes et d'empêcher les attentats. 
Le chiffrage des données est un obstacle majeur pour ces équipes, et
par conséquent une menace indirecte pour la population. 

Les acteurs politiques Français, craignant de paraître inactifs face à 
cette menace mais n'ayant ni la compétence ni le temps pour étudier le
problème en détail, ont choisi de s'attaquer aux exemples les plus
médiatisés (WhatsApp, la messagerie Apple, le réseau Tor). Notre projet
a pour objectif de tirer l'alarme sur l'étendue réelle des capacités
terroristes au chiffrage des données.

Le fichier `index.html` ci-dessus est une application de messagerie
sécurisée, offrant le même niveau de garanties que bon nombre 
d'applications commerciales. Cette application fonctionne sur 
Windows, Linux, OS X, iOS, Android et même FirefoxOS. Elle est accessible
directement par le web, sans validation préalable par un App Store. 
Son utilisation n'est pas facilement détectable, puisque noyée dans un 
océan de trafic très similaire. Davantage d'informations techniques 
sont disponibles en anglais dans [INFO.md](INFO.md).

Pour autant, cette application n'est pas un chef d'œuvre d'intelligence 
ou de développement informatique. Son code contient moins de 100 lignes.
Un informaticien moyen pourrait la ré-écrire à partir de rien en une 
journée à peine, et il est probable que les réseaux terroristes aient 
de tels informaticiens dans leurs rangs.

**Contraindre les applications de messagerie légales à fragiliser la
protection de leurs données n'empêchera pas les réseaux terroristes de
mettre en place leurs propres réseaux chiffrés.**

C'est pourquoi il est nécessaire d'informer les acteurs politiques 
Français de l'étendue réelle du combat contre les communications 
indéchiffrables, au travers d'une liste de propositions concrètes : 

## 1. Documentation cryptographique

Il faut restreindre l'accès à toute forme de manuel ou de documentation 
concernant les algorithmes cryptographiques, de la même façon que 
les manuels de chimie décrivant la réalisation d'explosifs sont
aujourd'hui sous surveillance. Le code source d'applications
cryptographiques est lui-même une forme de documentation, et la
lecture ou la contribution à des projets cryptographiques open 
source doit faire l'objet d'une surveillance. 

## 2. Restriction des capacités de calcul

Il faut limiter la capacité de toute forme de matériel informatique à 
effectuer des opérations cryptographiques non autorisées. Le modèle
d'App Store actuel (où une entreprise est chargée de valider au 
préalable chaque application) est prometteur, puisque cela oblige un
réseau terroriste à soumettre son application de communication à un
comité de validation avant de pouvoir l'utiliser.

La mise en place de ce système demande bien sûr quelques sacrifices
mineurs, à savoir l'interdiction de modèles de distribution des 
applications non soumis à approbation: 

 - Les navigateurs internet devront mettre en place un système de 
   certification du code JavaScript exécuté. _Cette méthode serait
   la façon idéale d'empêcher l'application `index.html` de fonctionner._
 - Les systèmes d'exploitation open source ou logiciel libre devront 
   faire valider leur code et le code de chacune des applications par 
   un système "boîte noire" installé sur la machine et qui décidera 
   s'il s'agit ou non d'une version autorisée. 

## 3. Restriction des capacités de développement

Il n'est pas raisonnable de limiter les capacités de calcul des équipes
de développeurs, puisque ceux-ci réalisent dans le cadre de leur travail
quotidien de nouvelles applications, et qu'il n'est pas envisageable de
soumettre ces "brouillons" à approbation préalable.

Il faut donc travailler à la création de machines dédiées au 
développement informatique et soumise à la même forme de réglementation
que les armes à feu: 

 - Présence d'un numéro de série, qui est repris de façon indélébile 
   dans chaque application créé par cette machine.
 - La création d'une licence "développeur" autorisant la possession 
   d'une telle machine, avec une responsabilité personnelle du
   développeur sur l'usage qui en est fait. 
 - La création d'un fichier international des développeurs et des
   numéros de série de leurs machines.
  
**En conclusion**, nous espérons que les acteurs politiques mondiaux
agiront rapidement pour mettre en place ces mesures afin de nous 
protéger.