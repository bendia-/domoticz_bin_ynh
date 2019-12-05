# Domoticz pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/domoticz.svg)](https://dash.yunohost.org/appci/app/domoticz)  
[![Install Domoticz with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=domoticz)

> Ce paquet permet d'installer [Domoticz](https://domoticz.com) rapidement et facilement sur un serveur YunoHost directement depuis le binaire pré-compilé.
Si vous n'avez pas YunoHost, [voir ici](https://yunohost.org/#/install) comment installer et en profiter.

> *This package allow you to install [Domoticz](https://domoticz.com) quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

:warning: L'installation prend entre 20 min et 1h30 suivant votre connexion et machine (téléchargement des sources Domoticz (36Mo) puis compilation), installation depuis la ligne de commande recommandée.
Raspberry 3B+ : ~1h (SWAP >= 500 Mo)

:warning: *Installation duration could be between 20min to 1h30 depending on your connection speed and CPU (download of Domoticz sources and compilation). Install from command line is recommanded.*

## Aperçu

Domoticz permet de gérer un système domotique :
- enregistrements, tracés de données capteurs (température, humidité, luminosité, ...)
- commander des actionneurs (lumières, volets, ...)
- créer des scénarii
De nombreux protocoles (RFLink, Zwave, MQTT, ...) et matériels sont [compatibles](https://www.domoticz.com/wiki/Hardware).

*Domoticz is a Home Automation System, allowing:*
- to save, to plot sensors datas (temperature, humidity, brightness, ...)
- to command switchs (light, shutters, ...)
- to create screnarii
*A lot of protocols (RFLink, Zwave, MQTT, ...) and hardware are [compatibles](https://www.domoticz.com/wiki/Hardware).*

**Version packagée :** Domoticz 4.9700 (version stable au 12/01/2019)
**Shipped version:** Domoticz 4.9700

## Captures d'écran

[Paramétrage](https://www.domoticz.com/wiki/Application_Settings)

## Demo

* (no demo site known)

## Configuration

(no specific configuration)

## Documentation

 * Official documentation: [wiki](https://www.domoticz.com/wiki/)
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## Fonctionnalités YunoHost

#### Support multi-utilisateurs

Pas de gestion utilisateur et encore moins multi-utilisateur depuis Yunohost.
*no user management from YunoHost.*

#### Architectures supportées

Testé sur x86-64
*Tested on x86-64*

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/domoticz%20%28Community%29/badge/icon)](https://ci-apps.yunohost.org/ci/apps/domoticz/)

## Limitations


* Pas de configuration de la langue Domoticz et utilisateurs depuis YunoHost

*no language nor Domoticz users management from YunoHost*



## Crédits
* Merci à Anubister et Aleks_

## Infos developpeurs
To try the testing branch, please proceed like that:
```
sudo yunohost app install https://github.com/anubister/domoticz_ynh/tree/testing --debug
or
sudo yunohost app upgrade domoticz -u https://github.com/anubister/domoticz_ynh/tree/testing --debug
```

## Liens

 * Report a bug: https://github.com/anubister/domoticz_ynh/issues
   Discussion sur xmpp:apps@conference.yunohost.org?join
 * App website: https://domoticz.com
 * YunoHost website: https://yunohost.org/
