# Consigne

	A la fin du TP, veuillez téléverser (sur votre espace Moodle) :
	- un fichier texte contenant un lien vers votre github (ou autre plateforme d'hébergement git) ;
	**OU** 
	- une archive (zip, rar ou tar) contenant l'ensemble de vos fichiers de travail :
		- scripts et codes ;
		- documents tableur ;
		- fichier contenant les réponses ;
		- ou autre.
	
	**Nom du fichier : NOM_Prenom.ext**

# Exercice 1 - Conception d'un scénario - Authentification

	En vous basant sur la logique du Cas Concret 1, concevez un scénario dans lequel Alice peut s'assurer que c'est Bob qui lui a envoyé le message.
	
	Remarque : 	Un(e) ou plusieurs étudiant(e)s iront présenter leur solution.
				L'intervention sera éventuellement comptée dans la note finale.
	
# Exercice 2 - Conception d'un scénario - Intégrité

	A partir de toutes les notions vues jusqu'à présent et en vous basant sur la logique du Cas Concret 1, concevez un scénario dans lequel Alice peut s'assurer de l'intégrité d'un message envoyé **en clair** dans le réseau (on suppose que c'est une information publique).
	
	Alice doit pouvoir vérifier :
		- Que c'est Bob qui lui a envoyé le document ;
		- Si le document a subi des modifications durant le transport.
	
	Remarque : 	Un(e) ou plusieurs étudiant(e)s iront présenter leur solution.
				L'intervention sera éventuellement comptée dans la note finale.
	
# Exercice 3 - Conception d'un scénario - Limite du chiffrement asymétrique

	En vous basant sur la logique du Cas Concret 1, concevez un scénario d'attaque présentant une limite du chiffrement asymétrique.
	
	Remarque : 	Un(e) ou plusieurs étudiant(e)s iront présenter leur solution.
				L'intervention sera éventuellement comptée dans la note finale.
				
# Exercice 4 - Conception d'une solution - Correction de la limite au chiffrement asymétrique

	Tentez de concevoir une solution à (ou aux) limite(s) du chiffrement asymétrique identifiée(s) à l'exercice 3.
	
	Remarque : 	Un(e) ou plusieurs étudiant(e)s iront présenter leur solution.
				L'intervention sera éventuellement comptée dans la note finale.

# Exercice 5 - Chiffrement asymétrique sur ordinateur & gestion de certificats

	Installer le logiciel 'Kleopatra'
	Générer une paire de clés
	Communiquer à un voisin votre clé publique
	Vérifier et valider l'empreinte de votre correspondant
	Chiffrer et signer un fichier
	Envoyer le fichier
	Déchiffrez le fichier reçu

	Lorsque vous rendrez votre travail, procédez comme suivant :
	
	- (répertoire Nom_Prenom)
		|
		|-- clé publique
		|
		|-- Rendu chiffré avec votre clé privée (archive ou autre)
		
	Vous archiverez le dossier racine et le pousserez sur Moodle.

# Exercice 6 - Signature (uniquement)

	A l'aide de votre clé privée, signez un document
	Vérifiez la signature du document 
	Modifier le document signé
	Revérifiez la signature du document
	
	Que constatez-vous ?

# Exercice 7 - Gestion de clés sur Linux

	Génerer une paire de clés sur votre machine hôte (mac, windows ou linux)
	Installez une Linux dans un container Docker ou une machine virtuelle
	Faites en sorte de pouvoir vous connecter à la machine Linux sans avoir à spécifier le mot de passe (utilisation de la clé privée)
	
	Comment avec vous fait ?
	
	Remarque : Pour aller plus loin, vous pouvez même créer un alias...

# Exercice 8 - Certificats & Navigateurs : prenez 5 minutes 
	
	Aller jeter un oeil à la liste des autorités de certification déjà présentes dans vos navigateurs
	Dans votre navigateur, regardez en détail un certificat
