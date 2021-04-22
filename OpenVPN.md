# Installation OpenVPN sur PfSense

## Configuration de PfSense

Dans l'onglet VPN > OpenVPN, choisir un wizard

Choisir l'authentification LDAP ou locale en fonction du cas

### Créer une autorité de certificats

Remplir
- nom du certificat
- la longueur de la clé de chiffrement
- durée de vie du certificat
- informations régionales.

### Créer un certificat serveur

Remplir les champs comme pour l'autorité de certificats

### Configuration réseau

Choisir l'interface réseau sur laquelle les utilisateurs vont se connecter

### Cryptographie

Penser à activer l'accélération Hardware, ça sert toujours sur un Packard Bell !

### Réseau tunnel
Renseigner le réseau IP utilisé par les utilisateurs du VPN en notation CIDR.
