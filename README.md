# FireStorm-Resolution
Allumez l'emulateur, mettez l'apk vulnerable (Firestorm) 
avec la commande frida-ps -Uai vous devez trouver l'applicaton dans la liste des processus.
Mettez l'apk dans Jadx-GUI et cherchez la classe MainActivity et vous trouvez la methode Password()
<img width="934" height="278" alt="Capture d&#39;écran 2026-04-15 154740" src="https://github.com/user-attachments/assets/c5aba24d-fcb9-4999-b8ba-40f88c8c175d" />
Vous devez aussi chercher le fichier xml string ( res > values > string.xml ) 
<img width="1920" height="1020" alt="Capture d&#39;écran 2026-04-15 155701" src="https://github.com/user-attachments/assets/c83db6c1-fbf1-41f1-a24c-d43ed831464f" />
Crée un fichier nommé frida_firestorm.js avec le contenu suivant
<img width="1310" height="876" alt="Capture d&#39;écran 2026-04-15 155718" src="https://github.com/user-attachments/assets/27ad8729-06fe-4ddf-b2fe-333535265039" />
verifiez tout d'abord que vous etes en mode root et lancez le script 
<img width="960" height="1020" alt="Capture d&#39;écran 2026-04-15 162025" src="https://github.com/user-attachments/assets/248f463b-dec4-4128-8806-a85707636eaf" />
Vous allez obtenir le mot de passe Firebase, copiez le 
Crée un fichier get_flag.py et remplacez le mot de passe avec le mot de passe copier dans l'etape precedente 
<img width="1222" height="687" alt="Capture d&#39;écran 2026-04-15 173749" src="https://github.com/user-attachments/assets/605e7071-e9e8-4162-800d-b85af18a2727" />
Executez le script python et vous obtiendrez le token pour interagir avec la base de données.
<img width="691" height="141" alt="Capture d&#39;écran 2026-04-15 173811" src="https://github.com/user-attachments/assets/1e745f32-b01d-4367-ac72-2e729362cfc8" />
