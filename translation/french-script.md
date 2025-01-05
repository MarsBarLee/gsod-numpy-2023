Comment contribuer à Numpy - Texte

Page 1

“À l'Université de Monty”
Bob:"Ouf, je suis tellement content qu'on ait fini le TP. ",
(Bob est soulagée après avoir terminé une séance de travaux pratiques.)

Alice: "Maaiiiis, on n'a pas encore terminé."
(Alice rappelle à Bob qu'il reste encore du travail à faire.)

Bob:"On doit examiner les données des images cellulaires, c'est ça ? Avec NumPy ?",
(Bob fait référence à la nécessité d'analyser les données d'images cellulaires à l'aide de NumPy, ce qui indique qu'ils travaillent sur un traitement de données scientifiques.)

Chris:"Oui... et je n'ai aucune idée de comment utiliser NumPy. Alors merci de m'avoir retrouvé après le cours pour m'aider.",
(Chris admet qu'ils ne sait pas comment utiliser NumPy et exprime sa gratitude pour l'aide qui va lui être apporté.)

Alice:"Pas de problème ! On est contents d’aider. J’ai déjà utilisé NumPy dans un cours d’informatique.",
(Alice est confiante et rassure Chris, en mentionnant une expérience préalable avec NumPy dans un contexte différent (informatique).)


Page 2

Alice: "Tu te souviens de ce qu'on a fait au laboratoire, hein ?",

Chris: "Oui, on a terminé de colorer les cellules.",

Alice: "Donc maintenant, toutes les informations des images cellulaires sont regroupées dans un fichier compressé. Donc on utilise NumPy pour extraire le fichier.",
(Alice explique que les images des cellules sont compressées dans un fichier, et que NumPy est utilisé pour gérer l'extraction.)
[Coloration, numérisation, images, compression, fichier npz, décompression.]

Bob: "Des tableaux ? Comment les images peuvent-elles être, en fait, une série de nombres ?",
(Bob est confus quant à la manière dont les images peuvent être représentées sous forme de tableaux de nombres.)

Bob: "On ne peut pas juste ouvrir l'image... en tant qu'image ? Et la regarder avec nos yeux ?",
(Chris demande pourquoi ils ne peuvent pas simplement visualiser l'image au lieu de travailler avec des tableaux.)

Alice: "Eh bien, dans la recherche en microbiologie, nous examinons des tonnes et des tonnes d'images de cellules. Et avec les tableaux de NumPy (ndarray), nous pouvons traiter et analyser bien plus rapidement que de passer manuellement les images une par une."
(Alice explique qu'en recherche, de nombreuses images doivent être traitées, et que l'utilisation des ndarrays de NumPy accélère le processus d'analyse.)

Chris:  "Je peux travailler avec 3 images.",

Chris:  "Mais 400 images ? En rien qu'une séance de laboratoire ?",

Bob:  "Mhhhh, c'est logique, je suppose.",
  
Page 3

Chris: "Ok ! Alors, comment on commence ?",

Alice: "Commençons par créer un fichier Python.",

Alice: "Dans le fichier, je vais commencer par importer NumPy.",
(Alice explique que la première étape pour commencer un script Python consiste à importer la bibliothèque NumPy.

Alice: "Notre professeur nous a donné nos images cellulaires sous forme d’un fichier .npz nommé cell_images.npz.",
(Alice explique qu'ils ont reçu les images cellulaires dans une archive compressée NumPy (au format .npz).)

Alice: "Utilisons la fonction np.load() avec le fichier cell_images.npz.",
(Alice explique l'utilisation de la fonction load de NumPy pour ouvrir le fichier .npz.)

Alice: "Et voici notre fichier .npz ouvert.",
(Alice met en évidence le contenu du fichier après avoir utilisé la fonction np.load().)

Chris: "Super ! Mais... il y a beaucoup de fichiers. Comment savoir lequel est le nôtre ?"
(Bob est confus face aux nombreuses entrées de données dans le fichier chargé et se demande comment identifier le bon fichier.)

Alice:"Tu as raison. Je veux mes images cellulaires de la séance de 10 h."

Alice: "'npzfile A' ne me dit pas si ces données viennent du TP de 10h ou de celui de 15h.",
(est frustré parce que le nom du fichier ne permet pas de savoir à quelle session de laboratoire les données appartiennent.)

Alice:"Puisque cela ressemble à un dictionnaire, utilisons la fonction keys().",
(Alice propose d'exploiter la structure semblable à un dictionnaire du fichier pour examiner ses clés et identifier les bonnes données.)

Chris:"Dictionnaire ? Clés ?",
(Chris n'est pas sûr de comprendre comment fonctionnent les dictionnaires dans ce contexte.)

Alice:"Je vois. Comme je vois un keysview, c'est que c'est bien un objet semblable à un dictionnaire.",
(Alice Let's change our approach. Let's use the function list() to turn all this into a proper list.)

Alice: "Les attributs de l'objet 09-09-10AM sont un dictionnaire contenant des paires clé-valeur, où la clé est le nom du fichier et la valeur est l'image elle-même (sous forme de tableau)."

Alice:"Changeons d'approche. Utilisons la fonction list() pour transformer tout cela en une véritable liste.",
(Alice suggère de convertir les clés en une liste pour rendre les données plus faciles à manipuler.)

Alice: "Maintenant, nous avons transformé nos fichiers .npz en une liste d'objets ! La liste d'objets représente nos sessions de laboratoire."

Alice: "Chaque session de laboratoire est un objet. Je veux voir les images de l'objet 09-09-10AM."

Alice:"Voyons tous les noms de fichiers des objets 09-09-10AM... Voilà ! Nous avons maintenant les images cellulaires capturées pendant notre laboratoire de 10h !",
(Alice trouve les données pertinentes après avoir listé les clés et identifie les bonnes images.)   

Page 4

Bob: "C'EST-QUOI-CE-BOR***?!"

Bob: "Pourquoi on ne peut pas voir le nom du fichier juste là ? 
(Bob est frustré que les noms de fichiers ne soient pas visibles.)

Bob: "Tu as dit que NumPy était plus rapide ! Que c'était mieux que de le faire à la main !" 
(Bob est contrarié que NumPy ne rende pas la tâche plus facile.)

Alice: "Je m'attendais à ce que keysview me donne le nom du fichier. Mais en réalité, ce n'est pas le cas." 
(Alice explique que le keysview n'a pas donné le résultat attendu)

Bob: "Donc, tu dois contourner ses bizarreries !" 
(Bob encourage Alice à trouver une solution pour contourner le problème.)

Alice: "Je peux contourner cela puisque je sais comment inspecter les objets..." 
(Alice assure qu'elle sait comment gérer malgré le problème.)

Chris: "Mais, tout va bien tant que ça fonctionne." 
(Chris essaie de minimiser le problème, en se concentrant sur le fait que cela fonctionne.)

Bob: "Je ne pense pas qu'on devrait accepter un "tant que ça marche !" Ça nous complique la vie !" 
(Bob réagit en affirmant qu'ils ne devraient pas se contenter de solutions sous-optimales.)

Alicec: "Tu as raison. C'est difficile, mais on peut changer ça !" 
(Alice est d'accord avec le point de vue de Bob et exprime de l'espoir pour une amélioration.)

Page 5

Alice: "NumPy est un logiciel open source. N'importe qui peut contribuer et modifier le code. Même en tant qu'étudiants en master, nous pouvons faire des suggestions, comme rendre plus facile l'ouverture des fichiers .NPZ. Ensuite, d'autres personnes peuvent se baser sur cette suggestion et transformer cette fonctionnalité en réalité !" 
(Alice explique que la nature open-source de NumPy permet aux utilisateurs d'améliorer ses fonctionnalités.)

Alice: "De cette manière, nous pouvons contribuer à la science ouverte !" 
(Chris souligne le lien entre la contribution à NumPy et l'avancement de la science ouverte.)

Bob: "Maiiiiiis ! Qu'est ce qu'on doit réellement faire ?" 
(Bob n'est pas sûr de savoir comment ils peuvent commencer à contribuer à NumPy.)

Alice: "Puisque NumPy est un outil utilisé en microbiologie, nous construisons des outils qui rendent la recherche scientifique plus collaborative et transparente ! N'est-ce pas incroyable ?" 
(Alice souligne que l'amélioration de NumPy peut avoir un impact positif sur la recherche scientifique, notamment dans des domaines comme la microbiologie.)

Alice: "Euh... Je pense qu'on est censé créer un problème sur GitHub.com, en disant qu'on a un problème, et suggérer une solution..." 
(Alice se souvient que contribuer à NumPy commence par créer des issues sur GitHub pour résoudre des problèmes.)

Alice: "D'accord, donc je n'ai jamais contribué ou quoi que ce soit encore, mais j'ai beaucoup appris lors de cette conférence sur la science ouverte le semestre dernier !" 
(Alice réfléchit à ses connaissances en science ouverte, mais admet qu'elle n'a pas encore contribué.)

Chris: "J'ai un compte GitHub. On peut essayer avec le mien !" 
(Chris propose d'utiliser son compte GitHub pour commencer.)

Alice: "Super ! Allons sur NumPy.org pour trouver leur page GitHub." 
(Alice suggère qu'ils visitent le site Web de NumPy pour trouver leur dépôt GitHub.)

Page 6

Alice: "Sur NumPy.org." 
(Alice navigue sur le site web de NumPy.

Alice: "On clique ici !" 
(Alice indique la section du site web à explorer davantage.)

Chris: "Euh , je regarde NumPy.org et euh..." 
(Chris semble incertain de l'endroit où aller ensuite sur le site.)

Alice: "Non, je suis presque sûr qu'on peut commencer par GitHub. Cliquons ici." 
(Alice dirige Chris vers le dépôt GitHub de NumPy pour commencer à contribuer.)

Bob: "Cela a l'air compliqué. Une liste de diffusion, Slack, des appels communautaires ? C'est trop !" 
(Bob se sent submergé par les options communautaires disponibles sur le site de NumPy.)

Alice: "Ça y est ! Maintenant, nous sommes sur la page GitHub de NumPy, avec une liste d'issues." 
(Alice atteint avec succès la page GitHub de NumPy, où les issues sont listés.)

Alice: "Créons une nouvelle issue ici. Ce que nous voulons, c'est une demande de fonctionnalité" 
(Alice explique qu'ils doivent créer un nouveau problème pour demander une fonctionnalité.)

Alice: " Créons une issue." 
(Alice se prépare à rédiger leur demande de fonctionnalité.)

Page 7

Alice : (Écrit) "Afficher les noms de fichiers dans l'archive npz ?"
(Alice crée une demande de fonctionnalité concernant la difficulté d'identifier les noms de fichiers dans les fichiers .npz.)

Alice : "Salut, nous sommes des étudiants en microbiologie utilisant NumPy pour examiner nos images cellulaires."
(Alice explique le contexte de leur utilisation des fichiers .npz.)

Chris : "Je ne sais pas comment utiliser les clés."
(Chris exprime de la confusion concernant les clés de style dictionnaire dans les objets NumPy.)

Alice : "Ah oui ! Laisse-moi ajouter cette partie..."
(Alice propose d'aider en clarifiant comment fonctionnent les clés dans les objets NumPy.)

Page 8

Bob : "Maintenant, dis leur de résoudre le problème."
(Bob est impatient d’obtenir une solution et veut que l’action soit immédiate.)

Chris : "Je ne pense pas qu’on doive être aussi exigeants !"
(Chris suggère une approche plus diplomatique pour leur demande de fonctionnalité.)

Alice : "Et si on proposait une solution possible ?"
(Alice propose de suggérer une solution.)

Alice : (Écrit) "Est-ce que les noms de fichiers pourraient être plus faciles à voir ? Genre juste quand on ouvre un npz ?"
(Alice propose une solution potentielle pour améliorer l’interaction avec les fichiers .npz.)

Alice : (Écrit) "Je dois être plus précise tu penses ? Je ne sais pas comment écrire le code pour la solution..."
(Alice demande à Chris si elle devrait apporter des précisions à sa solution.)

Chris : "Espérons que quelqu'un le fera ?"
(Chris exprime l'espoir que quelqu'un d'autre puisse proposer une solution technique.)

Bob : "Et bim ! Envoyé ! Sur internet !"
(Bob célèbre après que leur demande de fonctionnalité ait été soumise avec succès.)

Page 9

Bob : "Après tout ce travail, j’ai besoin d’une pause."

Alice : "M-mais on n’a pas fini notre devoir !"

Alice : "On peut toujours utiliser NumPy, c’est juste... un peu pénible."

Chris : "J’ai les notifications de GitHub activées. Alors ne t’inquiète pas, on aura une réponse."

[Le temps passe, ils se détendent.]

Chris : "Oh, quelqu’un a répondu !!"

[Ils se précipitent avec excitation pour vérifier la réponse.]

Bob : "Arghh, bon ! Regardons ça."

Page 10

[Regardant l'issue GitHub créée pour afficher les noms de fichiers dans l'archive npz]

Alice : "Donc voici l'issue qu'on a créée..."

Alice : "Wow, un mainteneur a commenté, et quelqu’un d’autre... ?"

Chris : "Qui sont ces personnes ?"

Chris : "Ils disent quoi ?"

Chris : "Il faut qu’on fasse quelque chose maintenant ?!"

[Alice explique qui est un mainteneur et un contributeur, l'image explique comment la discussion et la contribution se font]

Alice : "La première personne est un mainteneur."

Alice : "Le mainteneur dirige NumPy en coordonnant avec de nombreuses personnes pour la vision globale."

Alice : "La deuxième personne est un contributeur."

Alice : "Ils veulent aider ! Résoudre notre problème en faisant une demande de modification (pull request) !"

Contributeur : "Je peux aider."

Alice : "Ensemble, les mainteneurs et les contributeurs ajoutent de nouvelles fonctionnalités, corrigent des bugs et écrivent de la documentation pour améliorer NumPy."

Page 11

Chris : "Le contributeur a fait une pull request ! C’est quoi ?"

Alice : "Une pull request demande à apporter des modifications au code de NumPy. Celle-ci modifie les fichiers npz."

[Il y a un commentaire de pull request d’un contributeur disant qu’il peut aider, en fournissant une solution pour corriger le problème, et en soumettant la pull request.]

Alice : "On peut voir les modifications que le contributeur a faites dans le code."

Chris : "Honnêtement, je ne comprends pas trop ce qui est changé..."

[Alice pointe vers le résumé de la pull request soumise par le contributeur, expliquant les changements effectués dans le code.]

Alice : "C’est pas grave, voici un résumé des modifications apportées."

[Chris jette un coup d’œil sur la pull request]

Chris : "Je me demande ce que le contributeur est en train de faire..."

Chris : "Il doit tout savoir sur NumPy pour faire une pull request comme ça..."

Page 12

[La partie suivante montre le contributeur en train de réfléchir de son côté]

"Pendant ce temps, loin, très loin, le créateur de cette pull request pense ..."

Contributeur : "Ah, je ne sais rien sur NumPy ?"

Contributeur : "Attends - Ne sois pas trop dur avec toi-même. Tu connais NumPy."

[Le contributeur regarde sa pull request qui est en train d'être revue avec succès.]

Contributeur : "Je suis content qu’un mainteneur ait révisé mon travail. Mais comment répondre ?"

Contributeur : "La revue a dit que j'avais oublié X. Ce qui a du sens."

Contributeur : "La plupart de ma pull request fonctionne déjà. Donc je suis à 80% du travail."

Contributeur : "Il me reste juste à réécrire certaines parties et finir les 20% restants !"

[Le contributeur réfléchit un peu à sa contribution et examine la révision reçue du mainteneur. Le contributeur réalise qu'il reste encore 20% de travail à accomplir.]

Page 13

[ Quelque part dans le laboratoire, le contributeur repense à l'époque où il faisait face au même problème avec les fichiers npz.]

Contributeur : "Ces étudiants... je ressens une sorte de complicité. Ça fait des années que je n'ai pas été dans un laboratoire."

Contributeur : "Mais je me souviens d'avoir travaillé sur le même problème lié au fichier npz."

Contributeur : "Pourquoi je n'ai pas soumis ma propre issue ? En disant que j'avais aussi besoin d'aide ?"

Contributeur : "J'ai fini par créer mes propres solutions de contournement."

Contributeur : "Si j'avais soumis mes solutions de contournement sous forme de pull request il y a toutes ces années..."

Contributeur : "Peut-être que j'aurais pu aider d'autres personnes confrontées au même problème ?"

Contributeur : "J'étais probablement trop concentré sur la fin de ma thèse pour soumettre une pull request."

Contributeur : "Je suis content de pouvoir contribuer maintenant."

Contributeur : "Je me demande comment va le mainteneur."

Contributeur : "Il doit tout savoir sur NumPy... bien plus que moi."

[Le contributeur réfléchit au passé, lorsqu'il faisait face à un problème avec le fichier npz et se dit qu'une issue aurait pu être soumise plus tôt.]

Page 14

[Pendant ce temps, très loin, le mainteneur de NumPy réfléchit...]

Mainteneur : [Sirotant son café] "Je vois que le contributeur a mis à jour sa PR en fonction de mes commentaires."

Mainteneur : "Je vais revoir le code et vérifier s'il est prêt à être fusionné."

[Le mainteneur jette un œil aux modifications révisées et fusionne la pull request.]

Mainteneur : "Je suis content que ces étudiants m'aient signalé le problème qu'ils rencontrent."

Mainteneur : "Ça fait un an que je n'ai plus été professeur en laboratoire, donc je ne suis pas toujours au courant de ces problèmes."

Mainteneur : "Je suis heureux que les futurs étudiants puissent trouver plus facilement leur chemin avec les fichiers npz."

["Le mainteneur examine la pull request et se sent reconnaissant envers les étudiants qui ont soulevé le problème auquel ils étaient confrontés."]

Page 15

"Deux mois plus tard"

Alice : "Regardez cet e-mail !"

[Tous les trois vérifient l'e-mail qu'ils ont reçu après s'être inscrits à la liste de diffusion de NumPy.]

"Il vient de la liste de diffusion de NumPy. Je me suis inscrite pour suivre notre problème."

Alice : "Maintenant, la fonctionnalité demandée est là, dans cette version."

[Un aperçu du mail montrant les fonctionnalités dans la version.]

Bob : "Ça a l'air bien... mais est-ce que ça fonctionne vraiment ?"

[Ils essaient maintenant le code d'exemple pour charger un fichier npz et tester si la nouvelle fonctionnalité a bien été mise à jour... et ça fonctionne !!!!!!!!]

[Tous, très excités et choqués] : "Whaaa ! C'est tellement plus facile de voir si les images des cellules viennent du labo de 10h ou de 14h !"

Page 16

Bob : "Woooah. Je comprends maintenant."

Bob : "C'est trop cool de savoir que j'ai fait une différence dans NumPy !"

[Bob raconte l'histoire de comment ces changements ont commencé avec une simple issue.]
[L'étudiant écrit une issue, le contributeur écrit une pull request, le mainteneur examine la pull request, la pull request est fusionnée et le code ajouté à la base de code de NumPy, une version mise à jour de NumPy est publiée dans le monde entier.]

Bob : "Ça a commencé avec une personne et ça a grandi à partir de là ! Le problème du fichier npz et NumPy a été construit par de nombreuses personnes, toutes collaborant et s'appuyant les unes sur les autres."

[L'excitation continue]

"Maintenant, je veux rejoindre le prochain appel communautaire de NumPy."

"Je veux comprendre le code de NumPy aussi."

"Je veux aussi soumettre ma propre pull request."

"Rencontrer ces contributeurs qui nous ont aidés."

"Décortiquer, poser des questions."

"Wow, ils sont passés d'être les plus grands sceptiques à être les plus grands fans de NumPy !"

"Vas-y !"

"Fin"
