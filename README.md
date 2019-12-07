# Domoticz pour YunoHost

> Ce paquet permet d'installer [Domoticz](https://domoticz.com) rapidement et facilement sur un serveur YunoHost directement depuis le binaire pré-compilé.
Si vous n'avez pas YunoHost, [voir ici](https://yunohost.org/#/install) comment installer et en profiter.

> *This package allow you to install [Domoticz](https://domoticz.com) quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

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

**Version packagée :** Domoticz 4.10717 (version stable au 21/05/2019)
**Shipped version:** Domoticz 4.10717

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


Le projet amont ne fourni pas de binaire pour i386. Testé sur x86-64 et armhf.
*Upstream don't provide i386 binnary. Tested on x86-64 and armhf*


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
