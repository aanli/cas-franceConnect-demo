CAS FranceConnect Demo
============================

Projet de démo d'utilisation de FranceConnect avec CAS.

# Versions

```xml
<cas.version>5.0.x</cas.version>
```

# Requirements
* JDK 1.8+

## Executable WAR

Run the CAS web application as an executable WAR.

```bash
./build.sh run
```
Make sure that user has permission to '/etc/cas'
   
On a successful deployment via the following methods, CAS will be available at:
* http://localhost:8080/cas

## Comment reconcilier l'identité FranceConnect avec l'identité CAS ?
Vous pouvez utiliser l'outil [ESUP-claExternalID](https://github.com/EsupPortail/claExternalID) qui permet d'enregistrer dans le profil LDAP l'identiant FC. À la prochaine connexion de l'utilisateur via FC, l'utilisateur est formellement identifié et recupère ses données enregistrées dans le système.
