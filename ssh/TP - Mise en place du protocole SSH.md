# 1. Installation de SSH


<img src="image/Screenshot 2026-11-18 214637.png" alt="Screenshot 2026-11-18 214637.png">


<img src="image/Screenshot 2026-11-18 213659.png" alt="Screenshot 2026-11-18 213659.png">


<img src="image/Screenshot 2026-11-18 214331.png" alt="Screenshot 2026-11-18 214331.png">

Vérifier que le port 22 est ouvert

<img src="image/Pasted image 20261118220336.png" alt="Pasted image 20261118220336.png">


# 2. Connexion SSH depuis le client

<img src="image/Pasted image 20261118220942.png|624" alt="Pasted image 20261118220942.png|624">


<img src="image/Pasted image 20261118221341.png" alt="Pasted image 20261118221341.png">

# 3. Configuration des clés SSH
	
	3.1 Générer une paire de clés SSH sur la machine serveur :

<img src="image/Pasted image 20261118221921.png" alt="Pasted image 20261118221921.png">

	3.1 Vérifier la présence du fichier

<img src="image/Pasted image 20261118222441.png" alt="Pasted image 20261118222441.png">

	3.3 Voir son contenu

<img src="image/Screenshot 2026-11-18 222430.png" alt="Screenshot 2026-11-18 222430.png">

	3.4 Copier la clé publique du serveur sur le client

Le client étant ma machine Windows ne disposant pas de serveur SSH, la copie de la clé publique du serveur vers le client a été réalisée depuis le client plutôt que depuis le serveur ; le résultat est identique : la clé publique du serveur est présente sur le client.

<img src="image/Pasted image 20261118224608.png" alt="Pasted image 20261118224608.png">

	3.5 verification de la presence du fichier sur le client

<img src="image/Pasted image 20261118225537.png" alt="Pasted image 20261118225537.png">

	3.6 verification de la connectivite sans mot de passe

L’authentification par clé se fait sur la machine qui reçoit la connexion : pour que le client Windows se connecte sans mot de passe au serveur, sa clé publique doit être enregistrée dans le fichier `authorized_keys` du serveur.

<img src="image/Pasted image 20261118230917.png" alt="Pasted image 20261118230917.png">


# 4. Tunnel ssh en ligne de commande


<img src="image/Pasted image 20261119001308.png" alt="Pasted image 20261119001308.png">



<img src="image/Pasted image 20261119001224.png" alt="Pasted image 20261119001224.png">




<img src="image/Screenshot 2026-11-18 232454.png" alt="Screenshot 2026-11-18 232454.png">



<img src="image/Screenshot 2026-11-18 233338.png" alt="Screenshot 2026-11-18 233338.png">


Sur la base de donnee

<img src="image/Pasted image 20261119011653.png" alt="Pasted image 20261119011653.png">