Explication Saé : https://iut-b.univ-lille.fr/quest-ce-que-les-sae/


				Consignes : 
Projet n°7 Application Web à usage interne de l’entreprise : du full-covoiturage domicile-travail, domicile-loisir et travail-loisir ** difficulté strong **


-------


Description 
Problématique professionnelle / Cahier des charges
Votre groupe de projet est sollicité pour développer un outil informatique répondant aux besoins des étudiants de votre formation universitaire. Il s'agit d'organiser la mise en contact des étudiants qui étudient dans la même ville, qui habitent dans la même ville, et qui se rendent aux mêmes endroits pour ses études, ses loisirs ou pour ses courses. Peut-être qu'ils se déplacent aux mêmes moments. C'est ce que l'application va déterminer et proposer des déplacements en commun, et peut-être en mobilité partagée (covoiturage).

En quelque sorte, vous êtes invités à réfléchir à une application qui cartographie la domiciliation, les lieux de loisir et de courses, et le même lieu commun d'étude au Dpt R&T de Montbéliard d'un groupe d'étudiants de l'université en BUT1 R&T, une application qui recense les modalités de déplacement (pied, vélo, bus, Voiture Individuelle, ...), et si le déplacement se fait en VI, alors vous préciserez les capacités de covoiturages (véhicule, nombre de places disponibles, participation demandée (financière ou autre)), et une application qui met en contact l'offre et la demande, pour chaque jour de la semaine à venir.

Pour chaque étudiant, nous renseignerons la domiciliation principale ou secondaire depuis laquelle l'étudiant se rend au dpt R&T, la disponibilité d'un véhicule (type, nb places, immatriculation, etc., carte grise, contrôle technique, assurance), les lieux de courses et de loisirs (adresse, arrêt de bus, moyen de transport utilisé, durée moyenne), nous renseignerons ses informations universitaires : formation, groupe; sous-groupe, le début de cours (-15') et la fin de cours (+15') pour chaque jour de la semaine à venir (lundi au samedi).

Ces informations devront être saisies de 2 manières :
- tout d'abord sous la forme d'un fichier json ou csv;
- puis depuis une base de donnée renseignée ou bien à renseigner depuis une interface web ou mobile.

Ensuite la mise en contact est opérée par le système en informant des similitudes (ceux qui habitent au même endroit, ceux qui se rendent aux mêmes cours, ceux qui se rendent au même loisir, au même lieu pour faire ses courses), puis en proposant des équipages. À l'initialisation, il y aura autant d'équipages que de véhicules. Chaque participant de l'équipage aura à valider ou invalider un trajet aller et un trajet retour par jour de la semaine. Un étudiant pourra quitter un équipage et rejoindre un autre. Il pourra rejoindre un équipage s'il n'en avait pas jusque-là et si l'équipage qu'il rejoint est incomplet. Un étudiant pourra annuler un véhicule ou ajouter un véhicule s'il n'en avait pas jusque-là. 

Cette solution sur laquelle vous planchez est expérimentale car elle est complexe dans tous les cas à prendre en compte. Aussi c'est un parti pris de proposer un cahier des charges imparfait et évolutif.
Cette version peut-être vue comme une solution qui cartographie les principaux lieux de domiciliation, de loisir et de courses, les véhicules et les déplacements domicile-travail, domicile-loisir et travail-loisir des étudiants. Elle propose une interface de gestion des informations pour organiser des déplacements en groupe, voire un co-voiturage des étudiants. 

Vous pouvez donc choisir de concevoir cet outil sous forme d’un site Web ; l’outil sera ainsi facilement
accessible des utilisateurs, grâce à un simple navigateur Web ou une application mobile.
Le professionnel doit alors - en plus du développement - documenter les fonctionnalités de son outil et former les utilisateurs à son utilisation.

Description des étapes de cette SAÉ :

Initiez-vous au développement d’une application Web en partant des besoins utilisateurs.
Vous devez donc
mettre en place votre environnement de travail;
choisir et utiliser les technologies Web adéquates pour produire votre site Web, mettre en place la gestion des données du site et programmer leur traitement. La production du site web pourra se réaliser depuis le "rt-projet server";
présenter le travail réalisé aux utilisateurs pour les former à son utilisation, certains utilisateurs pouvant être anglophones.


La SAÉ pourra être réalisée par un groupe de 2 étudiants ou de 3 étudiants.

Partant du cahier des charges précédent fourni, et pour un binôme d’étudiants, la SAÉ pourra être mise en oeuvre avec différentes
étapes ou sections :
Section 1 : mise en place de l’environnement de développement :
Utilisation d’une machine virtuelle ou accès à distance aux ressources (par exemple : ferme ESX, Proxmox, Guacamole, Docker, . . . ), partage par clés USB
Installation ou utilisation d’un serveur web non chiffré (type Nginx ou Apache)
Utilisation possible d’un framework python (Django, Flask) ou JavaScript (jQuery), Java (play), etc. . .

Section 2 : réalisation documentée incluant :
Algorithmique (script serveur, dépôt de codes)
Technologie Web (HTML, css)
Base de données avec manipulation de données (ajout, suppression, modification)

Section 3 : organisation d’une session de formation en français et anglais à l’application Web auprès des collaborateurs de la société, avec documentation de l’application en anglais.

Modalités d’évaluation

Site fonctionnel et dynamique
Données manipulées dans un fichier csv ou json, et aussi depuis une BDD (ajout, suppression, modification)
Documentation technique, informative
Tutoriel d’installation, d’utilisation
Dépôt du code
Démonstration
Présentation de l’outil utilisé pour le développement
Méthode de validation (exemple : cahier de tests, tests unitaires)

____________________________________________________________________________________

-> Méthode de travail :
1/ Prenez connaissance de votre sujet.
Et élaborez le premier jet de votre présentation de soutenance finale : 
- slide 1 : Titre personnalisé, sponsor (BUT 1 R&T SAé23), équipe, date, jury
- slide 2 : Le sujet
- slide 3 : votre organisation
- <à venir>
- Slide de remerciement et d'invitation à poser des questions

2/ Concevez la vision globale de votre projet web :
- front-end : hw+sw+contenu envisagé des interfaces côté client
- back-end : hw+sw+contenu envisagé

Vous ajoutez les rôles (e-u, administrateur(s)) et les principales fonctionnalités de votre application. Vous précisez tous les formats de données que vous envisagez de manipuler.

3/ vous concevez les premières interfaces, les premières fonctions (input + traitement+output), le MCD/MPD de la BdD, les formats des fichiers csv ou json ou autre manipulés.

4/ vous décrivez l'environnement complet de développement, idem pour la production, vous répartissez votre travail en fonction des étapes importantes du SAé, ...

5/ vous préparez les rendus intermédiaires et finaux. L'objectif final doit guider vos choix. Ne perdez donc jamais de vue la soutenance finale, la dms, la formation pour l'usage de votre application.

____________________________________________________________________________________


=> Rendu final : 
Remettez vos travaux au fur et à mesure que votre projet avance en respectant le nommage suivant :
- toujours préfixer vos rendus par le n° du groupe_sa composition_le type du rendu_ le n° de version et la date si nécessaire;
- 1_IntitialisationPrésentation (ppt ou équivalent)
- 2_VueGlobale de votre projet (croquis, photo d'un tableau, ...) faisant apparaître tous les éléments importants du projet : hw (utilisés en développement et en production), sw (utilisés ou développés), le rôle et les acteurs (utilisateurs finaux, administrateurs, ...), les principales fonctionnalités de votre application (numérotées dans un scénario), les principales données échangées (requêtes, formats), 1 schéma de chaque interface (client et serveur, ...).
- mise en ligne de votre code sous github et en production, indenté, commenté.
- 3_GuideDeDéveloppement succinct : installations, outils d'édition, techniques de débogage (exemples), mise en production, qui contacter/crédits
- 4_GuideDUtilisation pour le end-user et pour l'administrator.
- 5_SoutenanceFinale, avec une 5bis_VidéoDms de 5' de démonstration, avec 5ter_Tutoriel des photos ou screen shots pour une dms hors ligne et pour un tutoriel.








=> Le code du site est disponible sous un autre dépot github : Sae23-George-Raynaud-Mirbey-site


