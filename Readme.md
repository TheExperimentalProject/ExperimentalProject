# Experimental Project

Attention ce projet est rattaché à aucune entreprise et donc pas à Zenika.
Des Zénika sont à l'intiative de ce projet mais Zénika ne pilote pas ce projet.

Ce projet est un projet qui vise à être open source.
Travailler sur ce projet sur votre temps libre si vous le souhaitez uniquement :).

# But

Le but de se projet est de faire des expérimentations. Tant sur :
- la gestion du projet / produit
- l'annomation de la communauté
- les technos
- les pratiques de dev
- ETC

# Manifeste du projet

Nous, membres de ce projet, garantissons faire notre maximum pour :
- être bienveillant
- être ouvert
- être collaboratif

# Produit(s)

Pour faire des expérimentations il faut une base. Quoi de mieux qu'un projet fédérateur un minimum complexe !

Nous travaillons de le domaine de l'IT et avons fait les constats suivants :
- Pour un client il n'est pas simple de trouver le développeur qui possède l'expertise recherché
- Dans une ESN, il n'est pas simple de trouver le consultant qui répond aux demandes d'un client
- Pour un dev, faire son CV n'est pas toujours très agréable / fun (outils pas au top, bcp de duplication entre des outils (CVs, formations, expertises, LinkedIn, etc))

## Jukuzen

Produit imaginé par Benoit C. Pas le blabla d'un CV, on se focus sur les compétences et sur les apétences.

Les buts :
- permettre aux clients de trouver les experts qui matchent le mieux avec leurs besoins.
- permettre aux commerciaux de savoir si des consultants disposent de l'expertise recherché.

https://docs.google.com/presentation/d/1P6EUpPUTZy5e3Bj7idOZEHU1MGsGMuGC1sdv8Gz11yc/edit#slide=id.p1

## app CV

Application permettant au consultant de rédiger son cv.

### resume Zenika

Les reproches fait à https://resume.zenika.com

UX
• Peu user friendly, long et fastidieux
• On passe 1/2 journée à ajouter une mission
• Un espace d'écriture du CV plus "intuitif" et plus simple en terme de lisibilité (WYSIWYG)
• Scroll non synchronisé entre la partie saisie et la partie préview (encore un argument pour le WYSIWYG)
• Pas de versioning des CVs d'où les écrasements et l'impossibilité de restaurer une version antérieure
• Pas possible de supprimer un CV

Export PDF
• Simplifier l'export : pourquoi devoir passer par une impression ?
• Toujours très compliqué de mettre en forme les sauts de page
• Mise en forme vraiment fastidieuse
• Hasardeux

Les features à ajouter
• Paragraphe "à propos du consultant"
• Grille de compétences
• Moteur de recherche sur les compétences
• Anonymisation
• Version anglaise
• Avoir 2 versions d'un même CV : une en 1+1 slides et une autre complète
• Export Word ou équivalent
• Permettre de donner une URL au client plutôt qu'un export pdf ==> Valider avec le DPO pour RGPD : Marie
• Décorréler complètement le fond de la forme => JSON, YAML, XML, etc.
• Gérer le cycle de vie des CVs
• Une navigation plus aisée (Recherche, Résultats, ...)
• Une manière simple de permettre à quelqu'un qui n'a pas encore de compte Zenika de créer son CV dans la base CV => Extraction JSON from LinkedIn ou DoYouBuzz

Piste de solution
• Utiliser le standard JSON-Resume
• Utiliser le standard FRESH + HackMyResume
• Utiliser un service existant : https://www.codeur.com/blog/outils-creer-cv-en-ligne/
• Utiliser un template Google Docs

Des liens intéressants permettant d'ouvrir le champ de vision sur la CVthèque 
• CV de Yann LE TANOU en mode 1+1 slide :
https://docs.google.com/presentation/d/1udqMdMF_U_VMD5L5GbfhC-EZ6Xhor0HGSMZFOiK87L0
• Slideware de Jérome Bourgeon (Singapore) sur les success stories de nos clients : 
https://docs.google.com/presentation/d/1cTKsM0Hpy405_byHZj4oPvH9e-XYwinQLLKa5XZdQrA
À partir du slide 25, on peut imaginer ce que serait l'extraction de toute cette donnée pour en faire le CV d'une seule personne.

## Profil

Outil pour aider un consultant à se créer son image / faire valoir son profil.
Le but serait de pouvoir afficher son flux d'actu de ses actions sur divers services. Un genre de "github activities" mais multi services.
L'idée est de créer son image professionnelle en partie au travers de ce flux d'activité. X contributions sur Github, Y réponses sur StackOverflow, Z posts / commentaires linkedIn etc. Ca permet de mieux cerner le bonhomme.
On peut imaginer pas mal de choses et suivant le niveaux de granularité ça peut même être bcp plus pertinant qu'un simple CV.

Le but n'est pas de créer une plateforme mais plus un client qui génère quelque chose (json, web component, etc) que le dev s'approprie (customisation) et utilise là ou il le souhaite. Dans son site web perso par exemple.
