Objectifs : 

• Construire une application qui pilote la WEBCAM d’un ordinateur, (1) elle doit – en temps réel - détecter les personnes présentes sur la vidéo, (2) reconnaître ceux qui font partie de la promotion (indique « inconnu » sinon), (3) indiquer l’émotion qui l’anime (joie, peur, tristesse, surprise, etc.), (3) indiquer son genre, (4) indiquer son âge. Lorsque l’application est stoppée, la vidéo (MP4) (contenant les indications idoines en incrustation) doit être enregistrée dans un dossier dédié, la liste des personnes apparues dans la vidéo doit être sauvegardé dans un fichier texte du même nom (que le MP4).

• N’oublions pas qu’une vidéo est une suite d’images. La fluidité de traitement (vidéo sans saccades) est un véritable enjeu ici.

• Le dispositif doit s’appuyer sur un modèle prédictif à partir d’une base de photos d’identité étiquetés des étudiants.



Livrables :

L’application (avec une interface graphique Dash, Streamlit, autres...) doit :

(1) Démarrer la webcam

(2) Détecter les personnes présentes,les détourer

(3) Reconnaître chaque personne à partir de la base de photos d’identité de la promotion (inconnu sinon), afficher son nom

(4) Indiquer également sur l’image webcam, ses sentiments, son âge et son sexe

A l’arrêt de l’exécution, la vidéo (.MP4) doit être enregistrée avec les informations adéquates. On doit pouvoir l’ouvrir avec n’importe quel logiciel de lecture de vidéo (VLC, Média Player, etc.). Le fichier (.TXT) contenant la liste des personnes repérées dans la vidéo doit être enregistré avec le même nom que le MP4.
