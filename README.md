# i-spindle
configuration d'un ispindle

Créer le montage suivant le schema. remplacer la resistance de deepsleep par un interrupteur a glissière
Ne pas toucher à l'esp, monter un interrupteur général.
La charge sefera par le module de charge et pas le wemos

Ne pas monter tout de suite la batterie, faire d'abbord la configuration et les tests sans batterie.

Lancer esp8266flasher

Charger le firware ispindle
deconnecter le cable usb et le rebrancher (important, le bouton reset ne fonctionne pas)

Se connecter en wifi au ispindle
configurer le reseau wifi
 et le tocken ubidots

 sur ubidots, se connecter 
 ne pas creer un nouveau device 


cliquer sur la photo de profil en haut a droite et cliquer sur API Credentials

En haut apparaissent 2 champs, c'est celui de droite a copier (Default token)

La configuration est maintenant ok
basculer le switch pour le deepsleep et lester le tube pour obtenir un angle de 25 degres

 
