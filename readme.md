# Projet e-commerce php

## Configuration

Le dossier du projet devrai être placé dans C:\xampp\htdocs\xampp
Le dossier du projet devrai s'appeler "vrai php" pour que tout fonctionne bien, si des liens seront corrompus

## Paiement

Pour utiliser le système de paiement, un compte paypal sandbox doit être utiliser.
Un compte comme celui ci ; 
email : sb-ndhzc26594807@personal.example.com mdp : 3G@Qd+3K 

## Config xampp

Modifie php.ini dans xampp : C:\xampp\php\php.ini :

[mail function]
; For Win32 only.
; https://php.net/smtp
;SMTP=localhost
; https://php.net/smtp-port
;smtp_port=25
SMTP=smtp.gmail.com
smtp_port=587
sendmail_from = ynovmailoff@gmail.com
sendmail_path = "\"C:\xampp\sendmail\sendmail.exe\" -t"

----------------------------------------------------------------------

Modifie sendmail.ini dans xampp : C:\xampp\sendmail\sendmail.ini : 

smtp_server=smtp.gmail.com
smtp_port=587
error_logfile=error.log
debug_logfile=debug.log
auth_username=ynovmailoff@gmail.com
auth_password=azkkssxmkrjslbog
force_sender=ynovmailoff@gmail.com

----------------------------------------------------------------------

## OPTIONEL : 


Vérification de compte par mail lors de l'inscription 

-------------------------------------------------------------------------

Barre de recherche page "catalogue.php" : vous pouvez rechercher pantalon = pa / pan / pant / panta / pantal / pantalo / pantalon
                                                                 veste = ve / ves / vest / veste 
                                                                 basket = ba / bas / bask / baske / basket

-------------------------------------------------------------------------

Création de cookie a la connexion cookie pour stocker le nom de l'utilisateur + Pop up de bienvenue et de code promo.

-------------------------------------------------------------------------

Systeme de notation et de commentaires dans "Voir détails" de l'onglet basket, pantalon et veste.

-------------------------------------------------------------------------

Code promo opérationel dans la page panier 

-------------------------------------------------------------------------

Points de fidélité dans la page profil

                                        
