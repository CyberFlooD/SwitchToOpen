<div style="display: flex; align-items: center; justify-content: space-between;">
  <h1>️🛡️ Sécurité</h1>
  <img src="Img/switchtoopen1.png" alt="Description de l'image" width="150" height="150">
</div>

## Sommaire 📖 <a id="sommaire"></a>
1. [🛡️ Antivirus et protection des endpoints](#antivirus)
2. [🔥 Pare-feu et prévention des intrusions (IDS/IPS)](#pare-feu)
3. [📊 Analyse de logs et monitoring](#analyse-logs)
4. [🔍 Gestion des vulnérabilités](#gestion-vulnerabilites)
5. [📈 Plateformes de gestion et de visualisation des vulnérabilités](#plateformes-gestion)
6. [🔑 Cryptographie et gestion des clés](#cryptographie)
7. [🛡️ Chiffrement de disque et protection des données](#chiffrement-disque)
8. [🔎 Gestion des informations et événements de sécurité (SIEM)](#gestion-informations)
9. [👤 Gestion des identités et accès (IAM)](#gestion-identités)
10. [🔬 Forensic et réponse aux incidents](#forensic)
11. [📋 Audit de sécurité et conformité](#audit-securite)
12. [📧 Outils de protection des emails](#protection-emails)
13. [🕵️ Création de honeypots](#honeypots)
14. [📋 Hygiène informatique](#hygiene)

---

## 🛡️ Antivirus et protection des endpoints <a id="antivirus"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **ClamAV** | GPLv2 | Détection de logiciels malveillants, scan des e-mails et fichiers | Antivirus open source utilisé pour scanner les e-mails, fichiers, et systèmes | <div align="center"><a href="https://www.clamav.net/">🔗</a></div> |
| **OpenAntiVirus Project** | GPL | Création d'outils antivirus et de sécurité réseau | Projet pour développer des outils antivirus et de sécurité réseau | <div align="center"><a href="http://www.openantivirus.org/">🔗</a></div> |
| **Linux Malware Detect (LMD)** | GPLv2 | Détection de malwares pour Linux | Spécialisé dans la détection de malwares ciblant les systèmes Linux | <div align="center"><a href="https://www.rfxn.com/projects/linux-malware-detect/">🔗</a></div> |
| **Rootkit Hunter (rkhunter)** | GPL | Détection de rootkits, backdoors, et exploits | Permet de vérifier la présence d'intrusions sur le système Linux | <div align="center"><a href="http://rkhunter.sourceforge.net/">🔗</a></div> |
| **chkrootkit** | GPL | Détection de rootkits sur Linux | Permet de vérifier la présence d'intrusions sur le système Linux | <div align="center"><a href="http://www.chkrootkit.org/">🔗</a></div> |
| **Wazuh** | GPLv2, avec une exception explicite autorisant le lien avec OpenSSL. | HIDS, EDR, XDR, surveillance des endpoints et détection des menaces | Monitoring complet des endpoints | <div align="center"><a href="https://wazuh.com/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔥 Pare-feu et prévention des intrusions (IDS/IPS) <a id="pare-feu"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **pfSense** | Apache 2.0 | Pare-feu et routeur | Basé sur FreeBSD, offre des fonctionnalités de pare-feu | <div align="center"><a href="https://www.pfsense.org/">🔗</a></div> |
| **OPNsense** | BSD 2-Clause | Pare-feu avec IDS/IPS intégré | Pare-feu offrant des fonctionnalités de détection/prévention d'intrusions | <div align="center"><a href="https://opnsense.org/">🔗</a></div> |
| **Snort** | GPLv2 | IDS/IPS | Système de détection et de prévention d'intrusions | <div align="center"><a href="https://www.snort.org/">🔗</a></div> |
| **Suricata** | GPLv2 | IDS/IPS avancé | IDS/IPS avec des fonctionnalités avancées | <div align="center"><a href="https://suricata.io/">🔗</a></div> |
| **CrowdSec** | MIT | IPS collaboratif | Détection comportementale + blocage collaboratif via bouncer | <div align="center"><a href="https://suricata.io/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📊 Analyse de logs et monitoring <a id="analyse-logs"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Graylog** | SSPL (non reconnue comme open source par l’Open Source Initiative (OSI) | Gestion et analyse des logs | Collecte et analyse des logs de manière centralisée | <div align="center"><a href="https://www.graylog.org/">🔗</a></div> |
| **OpenSearch** | Apache 2.0 | Alternative libre à Elastic | Suite open source de recherche et d’analytique distribuée, issue d’un fork d’Elasticsearch 7.10, développée par Amazon | <div align="center"><a href="https://www.elastic.co/elk-stack">🔗</a></div> |
| **OSSEC** | GPLv2 | Analyse des logs et détection des intrusions | Un système open source de détection d’intrusions basé sur l’hôte (HIDS) qui analyse en temps réel les journaux, contrôle l’intégrité des fichiers, surveille le registre Windows, détecte les rootkits et génère des alertes pour protéger les systèmes Linux, Windows, macOS, Solaris, etc. | <div align="center"><a href="https://www.ossec.net/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔍 Gestion des vulnérabilités <a id="gestion-vulnerabilites"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **OpenVAS** | GPLv2 | Scanner de vulnérabilités | Scanner de vulnérabilités complet | <div align="center"><a href="https://www.openvas.org/">🔗</a></div> |
| **Nikto** | GPLv2 | Scanner de vulnérabilités web | Scanner de vulnérabilités des applications web | <div align="center"><a href="https://cirt.net/Nikto2">🔗</a></div> |
| **Wapiti** | GPLv2 | Scanner de vulnérabilités web | Scanner de vulnérabilités des applications web | <div align="center"><a href="http://wapiti.sourceforge.net/">🔗</a></div> |
| **ArcherySec** | Apache 2.0 | Gestion des vulnérabilités et tests | Tests de sécurité automatisés et gestion des vulnérabilités | <div align="center"><a href="https://archerysec.github.io/archerysec/">🔗</a></div> |
| **Drozer** | Apache 2.0 | Sécurité des applications mobiles | Audits de sécurité des applications mobiles | <div align="center"><a href="https://github.com/WithSecureLabs/drozer">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📈 Plateformes de gestion et de visualisation des vulnérabilités <a id="plateformes-gestion"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Faraday Community** | GPLv3	+ Version Pro payante | Collaboration et gestion des vulnérabilités | Plateforme pour la gestion centralisée des vulnérabilités | <div align="center"><a href="https://faradaysec.com/">🔗</a></div> |
| **DefectDojo** | Clause | Gestion des vulnérabilités | Outil open source pour centraliser, gérer et suivre les résultats des scans de vulnérabilités, avec déduplication et reporting avancé | <div align="center"><a href="https://www.defectdojo.org/">🔗</a></div> |
| **Dradis** | GPLv2 (Community Edition) | Gestion des vulnérabilités et rapports | Plateforme pour la gestion des vulnérabilités et la génération de rapports de tests de sécurité | <div align="center"><a href="https://dradisframework.com/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔑 Cryptographie et gestion des clés <a id="cryptographie"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **GnuPG** | GPLv3 | Chiffrement et signature | Outil de chiffrement et de signature numérique | <div align="center"><a href="https://gnupg.org/">🔗</a></div> |
| **Let’s Encrypt** | MPL 2.0 | Certificats SSL/TLS | Certificats SSL/TLS gratuits et automatisés | <div align="center"><a href="https://letsencrypt.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🛡️ Chiffrement de disque et protection des données <a id="chiffrement-disque"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **VeraCrypt** | Apache 2.0	 | Chiffrement de disque | Outil de chiffrement de disque complet | <div align="center"><a href="https://www.veracrypt.fr/">🔗</a></div> |
| **LUKS** | GPLv2 | Chiffrement de disque | Chiffrement des volumes sous Linux | <div align="center"><a href="https://gitlab.com/cryptsetup/cryptsetup">🔗</a></div> |
| **Cryptomator** | GPLv3 | Chiffrement de fichiers | Chiffrement de fichiers pour le cloud | <div align="center"><a href="https://cryptomator.org/">🔗</a></div> |
| **EncFS** | GPLv2 | Chiffrement de fichiers | Système de fichiers chiffré en espace utilisateur, compatible Linux et macOS | <div align="center"><a href="https://vgough.github.io/encfs/">🔗</a></div> |
| **eCryptfs** | GPLv2 | Chiffrement de fichiers | Système de fichiers crypté empilé pour Linux, intégré au noyau Linux | <div align="center"><a href="https://ecryptfs.org/">🔗</a></div> |
| **CryFS** | GPLv3 | Chiffrement de fichiers | Système de fichiers chiffré conçu pour le stockage cloud, protège la structure des dossiers | <div align="center"><a href="https://www.cryfs.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔎 Gestion des informations et événements de sécurité (SIEM) <a id="gestion-informations"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Wazuh** | Open Source | Détection des menaces, gestion des incidents | Plateforme SIEM open source pour la détection des menaces et la gestion des incidents | <div align="center"><a href="https://wazuh.com/">🔗</a></div> |
| **OSSEC** | Open Source | Détection d'intrusion basée sur l'hôte (HIDS) | Système de détection d'intrusion gratuit et open source basé sur l'hôte | <div align="center"><a href="http://www.ossec.net">🔗</a></div> |
| **ELK Stack** | Open Source | Collecte, analyse, visualisation des logs | Suite open source pour la collecte, l'analyse et la visualisation des logs, souvent utilisée comme SIEM | <div align="center"><a href="https://www.elastic.co/elk-stack">🔗</a></div> |
| **AlienVault OSSIM** | Open Source | SIEM tout-en-un | Solution SIEM open source qui combine plusieurs outils de sécurité dans une seule plateforme | <div align="center"><a href="https://cybersecurity.att.com/products/ossim">🔗</a></div> |
| **Security Onion** | Open Source | Surveillance de sécurité | Distribution Linux open source pour la surveillance de la sécurité avec des fonctionnalités SIEM | <div align="center"><a href="https://securityonion.net/">🔗</a></div> |
| **Prelude SIEM** | Open Source | Corrélation des événements de sécurité | SIEM open source axé sur la corrélation des événements de sécurité | <div align="center"><a href="https://www.prelude-siem.org/">🔗</a></div> |
| **MozDef** | Open Source | Réponse aux incidents automatisée | SIEM open source développé par Mozilla pour automatiser la réponse aux incidents de sécurité | <div align="center"><a href="https://github.com/mozilla/MozDef">🔗</a></div> |
| **SIEMonster** | Open Source | Surveillance des événements de sécurité | Solution SIEM open source scalable pour la surveillance des événements de sécurité | <div align="center"><a href="https://siemonster.com/">🔗</a></div> |
| **OpenEDR** | Open Source | Endpoint Detection and Response (EDR) | C'est plutôt un EDR, gratuit et open source | <div align="center"><a href="https://www.openedr.com/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔐 Plateformes de gestion d'identités (IAM) <a id="gestion-identités"></a>

| 🌐 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
|**Keycloak**| Apache 2.0 | Authentification unique (SSO), IAM | Solution open source complète pour l’authentification, l’autorisation, supporte OpenID Connect, OAuth2, SAML. Intégration facile avec LDAP/Active Directory.	 | <div align="center"><a href="https://www.keycloak.org/">🔗</a></div> |
|**Gluu**| MIT | IAM, Authentification, Autorisation | Plateforme IAM open source avec SSO, MFA, gestion centralisée des identités, supporte OAuth2, OpenID Connect, SAML, SCIM. Plus gourmande en ressources que Keycloak.	 | <div align="center"><a href="https://www.gluu.org/">🔗</a></div> |
|**FreeIPA**| GPLv3 | Gestion centralisée des identités LDAP/Kerberos, gestion des hôtes, certificats	 | Solution IAM complète orientée Linux, intégrant LDAP, Kerberos, CA, gestion des politiques de sécurité, avec console web et CLI. | <div align="center"><a href="https://www.freeipa.org/">🔗</a></div> |
|**Authelia**| Apache 2.0 | Compagnon des reverse proxies (nginx, Traefik, HAProxy...) | Authelia est un serveur open-source d’authentification et d’autorisation qui joue le rôle de portail d’authentification unique (SSO) et de gestion des accès (IAM) pour les applications web. Il s’intègre principalement comme un compagnon des reverse proxies (nginx, Traefik, HAProxy, etc.) et permet de protéger l’accès à vos services web en appliquant des politiques d’accès fines et en imposant l’authentification à un ou deux facteurs selon vos besoins | <div align="center"><a href="https://github.com/authelia/authelia">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔬 Forensic et réponse aux incidents <a id="forensic"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Autopsy** | Open source | Analyse forensique | Outil d'analyse forensique de disques durs | <div align="center"><a href="https://www.sleuthkit.org/autopsy/">🔗</a></div> |
| **The Sleuth Kit** | Open source | Suite d'outils forensiques | Ensemble d'outils pour l'analyse forensique | <div align="center"><a href="https://www.sleuthkit.org/">🔗</a></div> |
| **Volatility** | Open source | Analyse de la mémoire | Analyse forensique de la mémoire vive | <div align="center"><a href="https://www.volatilityfoundation.org/">🔗</a></div> |
| **GRR** | Open source | Framework forensique | Google Rapid Response - Framework d’investigation à distance | <div align="center"><a href="https://grr.dev/">🔗</a></div> |
| **FastIR** | Open source | Collecte d'artéfacts | Collecte d'artéfacts sur une machine Windows | <div align="center"><a href="https://github.com/SekoiaLab/Fastir_Collector">🔗</a></div> |
| **Velociraptor** | Open source | Forensics et réponse aux incidents | Plateforme de forensics et de réponse aux incidents à distance | <div align="center"><a href="https://docs.velociraptor.app/">🔗</a></div> |
| **LiME** | Open source | Extracteur de mémoire | Outil d'extraction de mémoire pour Linux | <div align="center"><a href="https://github.com/504ensicsLabs/LiME">🔗</a></div> |
| **Xplico** | Open source | Forensics réseau | Plateforme de forensics sur les packets réseaux PCAP | <div align="center"><a href="https://www.xplico.org/">🔗</a></div> |
| **Moloch** | Open source | Forensics réseau | Plateforme de captures de packets réseaux | <div align="center"><a href="https://github.com/aol/moloch">🔗</a></div> |
| **Bulk_Extractor** | Open source | Analyse forensique | Extraction d'infos depuis un dump mémoire ou des images disques | <div align="center"><a href="https://github.com/simsong/bulk_extractor">🔗</a></div> |
| **UAC** | Open source | Collecte d'artéfacts | Collecte d'artéfacts pour la réponse aux incidents sur Unix-Like | <div align="center"><a href="https://github.com/tclahr/uac">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📋 Audit de sécurité et conformité <a id="audit-securite"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Lynis** | Open source | Audit de sécurité sous Linux | Outil d'audit de sécurité pour Linux | <div align="center"><a href="https://cisofy.com/lynis/">🔗</a></div> |
| **Scout Suite** | Open source | Audit de sécurité multi-cloud | Outil d'audit de sécurité pour les environnements multi-cloud | <div align="center"><a href="https://github.com/nccgroup/ScoutSuite">🔗</a></div> |
| **OpenSCAP** | Open source | Audit de conformité | Audit de conformité et scanner de vulnérabilités | <div align="center"><a href="https://www.open-scap.org/">🔗</a></div> |
| **CISO Assistant** | Open source | Gestion des risques cyber | Gestion des activités cyber et des audits | <div align="center"><a href="https://github.com/intuitem/ciso-assistant-community">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📧 Outils de protection des emails <a id="protection-emails"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **MailScanner** | Open source | Protection contre les virus et les spams | Outil de protection des emails contre les virus et les spams | <div align="center"><a href="https://www.mailscanner.info/">🔗</a></div> |
| **SpamAssassin** | Open source | Filtrage anti-spam | Outil de filtrage anti-spam open source | <div align="center"><a href="https://spamassassin.apache.org/">🔗</a></div> |
| **ClamAV** | Open source | Antivirus pour les emails | Outil antivirus pour scanner les emails | <div align="center"><a href="https://www.clamav.net/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🕵️ Création de honeypots <a id="honeypots"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Trapster Community** | Open source | Création de honeypots | Plateforme pour la création de honeypots | <div align="center"><a href="https://github.com/0xBallpoint/trapster-community">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📋 Hygiène informatique personnelle <a id="hygiene"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Personal Security Checklist** | Open source, MIT, CC4.0 | Checklist, guide d’auto-évaluation de la posture cyber| Une checklist complète et accessible qui vous guide pas à pas pour renforcer votre posture cyber personnelle | <div align="center"><a href="[https://www.clamav.net/](https://digital-defense.io/)">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)


