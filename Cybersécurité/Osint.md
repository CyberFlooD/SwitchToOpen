# Outils de reconnaissance et d'OSINT


## OSINT général et collecte d'informations sur des cibles

- **[Discover](https://github.com/leebaird/discover)** : Scripts bash personnalisés utilisés pour automatiser diverses tâches de test de pénétration, notamment la reconnaissance, l'analyse,l'énumération et la création de charges utiles malveillantes à l'aide de Metasploit. À utiliser avec Kali Linux..
- **[Argus](https://github.com/jasonxtn/Argus)** : Argus est un outil tout-en-un basé sur Python, conçu pour simplifier la collecte d'informations et les opérations de reconnaissance.
- **[OSINT Framework](https://osintframework.com/)** : Site qui regroupe des outils et des ressources pour la collecte d'informations open source.
- **[ReconDog](https://github.com/s0md3v/ReconDog)** : Outil open source de collecte d'informations et d'OSINT avec des fonctionnalités automatisées pour rechercher des cibles à partir de domaines, adresses IP, etc.
- **[Datasploit](https://github.com/DataSploit/datasploit)** : Outil OSINT open source conçu pour automatiser la collecte d'informations à partir de différentes sources publiques.
- **[FOCA](https://github.com/ElevenPaths/FOCA)** : Outil de reconnaissance d'informations publiques sur des serveurs et domaines, en extrayant des métadonnées de documents (PDF, Word, etc.).
- **[OSRFramework](https://github.com/i3visio/osrframework)** : Suite d'outils pour la collecte d'informations OSINT, y compris des noms d'utilisateur, domaines, adresses e-mail, etc.

## Collecte d'informations sur les domaines
- **[whois](https://www.whois.com/)** : Outil permettant de récupérer des informations sur un domaine (propriétaire, registrar, dates d'enregistrement, etc.).
- **[Sublist3r](https://github.com/aboul3la/Sublist3r)** : Outil open source de collecte de sous-domaines utilisant des sources publiques comme Google, DNSdumpster, et Virustotal.
- **[Amass](https://github.com/OWASP/Amass)** : Framework open source pour la découverte de sous-domaines, la cartographie réseau et la collecte d'informations sur une infrastructure cible.
- **[DNSRecon](https://github.com/darkoperator/dnsrecon)** : Outil de reconnaissance DNS qui collecte des informations DNS sur une cible, y compris les enregistrements de zones DNS.
- **[MassDNS](https://github.com/blechschmidt/massdns)** : Outil de résolution DNS rapide pour découvrir des sous-domaines ou d'autres informations à partir de l'infrastructure DNS.
- **[WebCheck](https://web-check.xyz/)** : Outil complet donnant une analyse détaillée sur un nom de domaine

## Recherche sur les adresses IP et les infrastructures
- **[Shodan](https://www.shodan.io/)** : Moteur de recherche pour découvrir des équipements connectés à Internet (serveurs, routeurs, systèmes IoT, etc.).
- **[Onyphe](https://www.onyphe.io/)** : ONYPHE est une solution de gestion de surface d'attaque et de découverte de surface d'attaque conçue comme un moteur de recherche de cyberdéfense.
- **[Censys](https://censys.io/)** : Plateforme permettant de rechercher des informations sur les services, certificats et infrastructures disponibles sur Internet.
- **[Nmap](https://nmap.org/)** : Outil d'analyse réseau pour la découverte des hôtes et des services sur un réseau informatique.
- **[Netcraft](https://www.netcraft.com/)** : Service en ligne permettant de collecter des informations sur les sites web, leurs serveurs et leurs infrastructures.

## Collecte d'informations à partir des moteurs de recherche
- **[theHarvester](https://github.com/laramies/theHarvester)** : Outil open source de collecte d'emails, de noms de domaine, d'adresses IP et de sous-domaines à partir de sources publiques comme Google, Bing, et Shodan.
- **[Recon-ng](https://github.com/lanmaster53/recon-ng)** : Framework open source pour la reconnaissance automatisée avec des modules qui permettent de collecter des informations à partir de sources publiques (Google, LinkedIn, etc.).
- **[Spiderfoot](https://www.spiderfoot.net/)** : Outil open source de collecte d'informations automatisée à partir de sources publiques comme moteurs de recherche, réseaux sociaux, bases de données WHOIS, etc.

## OSINT (Open Source Intelligence) sur les réseaux sociaux et les personnes
- **[Maltego](https://www.maltego.com/)** : Outil de reconnaissance avancée et de visualisation de données pour cartographier les relations entre des personnes, des entreprises, et des infrastructures.
- **[Social-Engineer Toolkit (SET)](https://github.com/trustedsec/social-engineer-toolkit)** : Framework de tests de sécurité orienté ingénierie sociale, permettant de mener des attaques de reconnaissance ciblées.
- **[Sherlock](https://github.com/sherlock-project/sherlock)** : Outil de reconnaissance qui permet de rechercher des pseudonymes d'utilisateurs sur plusieurs plateformes sociales (Twitter, Instagram, etc.).
- **[Twint](https://github.com/twintproject/twint)** : Outil open source permettant de collecter des informations sur des comptes Twitter sans utiliser l'API Twitter officielle.
- **[GHunt](https://github.com/mxrch/GHunt)** : Outil permettant de collecter des informations sur les comptes Google (Gmail, YouTube, etc.) à partir de sources publiques.

## Recherche de fuites de données et de credential stuffing
- **[Dehashed](https://www.dehashed.com/)** : Moteur de recherche pour les bases de données piratées ou compromises, permettant de vérifier si des comptes ou mots de passe ont été exposés.
- **[Have I Been Pwned](https://haveibeenpwned.com/)** : Service en ligne permettant de vérifier si une adresse e-mail ou un nom d'utilisateur a été impliqué dans une fuite de données.
- **[Holehe](https://github.com/megadose/holehe)** : Outil permettant de vérifier si un e-mail est utilisé pour s'inscrire à différents services en ligne (utile pour le credential stuffing).
- **[LeakLooker](https://github.com/woj-ciech/LeakLooker)** : Outil de recherche pour découvrir des bases de données mal configurées ou exposées (Elasticsearch, MongoDB, etc.).

## OSINT sur l'historique web et les métadonnées
- **[Wayback Machine](https://archive.org/web/)** : Service d'archive d'Internet permettant de voir l'historique d'un site web et de vérifier les anciennes versions de pages web.
- **[ExifTool](https://exiftool.org/)** : Outil permettant d'extraire les métadonnées de fichiers comme les images (JPEG, PNG), documents (PDF), et vidéos pour obtenir des informations cachées sur la cible.
- **[Metagoofil](https://github.com/laramies/metagoofil)** : Outil open source pour extraire les métadonnées de documents publics afin d'identifier des informations sensibles sur les infrastructures cibles.

## Cartographie et géolocalisation
- **[Google Earth](https://earth.google.com/)** : Outil permettant de visualiser des cartes, des images satellite et des informations géographiques pour la reconnaissance des cibles.
- **[GeoCreepy](https://www.geocreepy.com/)** : Outil open source de géolocalisation basé sur les informations publiques partagées par les utilisateurs sur les réseaux sociaux.
- **[ExifTool](https://exiftool.org/)** : Outil qui permet également d'extraire les données de géolocalisation des images ou fichiers partagés publiquement.
