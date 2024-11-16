# Sécurité

## Antivirus et protection des endpoints

<details>
<summary>Déplier</summary>

- [ClamAV](https://www.clamav.net/) (Antivirus)
- [Wazuh](https://wazuh.com/) (Surveillance des endpoints et détection des menaces)

</details>

## Pare-feu et prévention des intrusions (IDS/IPS)

<details>
<summary>Déplier</summary>

- [pfSense](https://www.pfsense.org/) (Pare-feu basé sur FreeBSD)
- [OPNsense](https://opnsense.org/) (Pare-feu avec IDS/IPS intégré)
- [Snort](https://www.snort.org/) (IDS/IPS)
- [Suricata](https://suricata.io/) (IDS/IPS avec fonctionnalités avancées)

</details>

## Analyse de logs et monitoring

<details>
<summary>Déplier</summary>

- [Graylog](https://www.graylog.org/) (Gestion et analyse des logs)
- [ELK Stack](https://www.elastic.co/elk-stack) (Elasticsearch, Logstash, Kibana)
- [OSSEC](https://www.ossec.net/) (Analyse des logs et détection des intrusions)

</details>

## Gestion des vulnérabilités

<details>
<summary>Déplier</summary>

- [Nessus Essentials](https://fr.tenable.com/products/nessus/nessus-essentials)) (Scanner de vulnérabilités)
- [OpenVAS](https://www.openvas.org/) (Scanner de vulnérabilités)
- [Nikto](https://cirt.net/Nikto2) (Scanner de vulnérabilités web)
- [Wapiti](http://wapiti.sourceforge.net/) (Scanner de vulnérabilités web)
- [ArcherySec](https://archerysec.github.io/archerysec/) (Gestion des vulnérabilités et tests de sécurité)
 
</details>
    
## Plateformes de gestion et de visualisation des vulnérabilités

<details>
<summary>Déplier</summary>

- [Faraday](https://faradaysec.com/) (Plateforme open source permettant aux équipes de sécurité de collaborer, d'analyser et de gérer les vulnérabilités de manière centralisée)
- [DefectDojo](https://www.defectdojo.org/) (Outil open source conçu pour centraliser et gérer les résultats des scans de vulnérabilités, avec des tableaux de bord pour la gestion des risques)
- [Dradis](https://dradisframework.com/) (Plateforme open source pour la gestion des vulnérabilités et des rapports de tests de sécurité)

</details>

## Cryptographie et gestion des clés

<details>
<summary>Déplier</summary>

- [GnuPG](https://gnupg.org/) (Chiffrement et signature)
- [HashiCorp Vault](https://www.vaultproject.io/) (Gestion des secrets et des clés de chiffrement)
- [Let’s Encrypt](https://letsencrypt.org/) (Certificats SSL/TLS gratuits et automatisés)

</details>

## Chiffrement de disque et protection des données

<details>
<summary>Déplier</summary>

- [VeraCrypt](https://www.veracrypt.fr/) (Chiffrement de disque)
- [LUKS](https://gitlab.com/cryptsetup/cryptsetup) (Chiffrement des volumes sous Linux)
- [Cryptomator](https://cryptomator.org/) (Chiffrement de fichiers pour le cloud)

</details>

## Gestion des informations et événements de sécurité (SIEM)

<details>
<summary>Déplier</summary>

- [Wazuh](https://wazuh.com/) (SIEM, surveillance des hôtes et gestion des incidents)
- [OSSIM](https://cybersecurity.att.com/products/ossim) (AlienVault Open Source SIEM)

</details>

## Gestion des identités et accès (IAM)

<details>
<summary>Déplier</summary>

- [Keycloak](https://www.keycloak.org/) (Gestion des identités et accès)
- [Gluu](https://www.gluu.org/) (IAM open source)
- [FreeIPA](https://www.freeipa.org/) (Authentification centralisée, domaine et sécurité pour Linux)

</details>

## Forensic et réponse aux incidents

<details>
<summary>Déplier</summary>

- [Autopsy](https://www.sleuthkit.org/autopsy/) (Analyse forensique)
- [The Sleuth Kit](https://www.sleuthkit.org/) (Suite d'outils forensiques)
- [Volatility](https://www.volatilityfoundation.org/) (Analyse de la mémoire)
- [GRR](https://grr.dev/) (Google Rapid Response - Framework d’investigation à distance)
- [FastIR](https://github.com/SekoiaLab/Fastir_Collector) (Un outil de collecte d'artéfacts sur une machine Windows
- [Velociraptor](https://docs.velociraptor.app/) (Une plateforme de forensics et de réponse aux incidents à distance)
- [LiME](https://github.com/504ensicsLabs/LiME) (Un extracteur de mémoire pour Linux)
- [Xplico](https://www.xplico.org/) (Une plateforme de forensics sur les packets réseaux PCAP)
- [Moloch](https://github.com/martinpaljak/moloch) (Une palteforme de captures de packets réseaux, et qui peut-être utilisée dans le cadre de forensics)
- [Bulk_Extractor](https://github.com/simsong/bulk_extractor) (Un outil d'analyse forensics permettant d'extraire des infos utiles (des numéros de carte bancaire, des adresses e-mail, des URL, des adresses IP ...etc) depuis un dump mémoire, binaire, images disques ...etc
- [UAC](https://github.com/tclahr/uac) (Un outil de collecte d'artéfacts pour la réponse aux incidents sur les système Unix-Like)

</details>

## Audit de sécurité et conformité

<details>
<summary>Déplier</summary>

- [Lynis](https://cisofy.com/lynis/) (Audit de sécurité sous Linux)
- [Scout Suite](https://github.com/nccgroup/ScoutSuite) (Audit de sécurité multi-cloud)
- [OpenSCAP](https://www.open-scap.org/) (Audit de conformité et scanner de vulnérabilités)
- [CISO Assistant](https://github.com/intuitem/ciso-assistant-community) (Plateforme GRC pour centraliser et piloter les activités cyber, y compris les audits)

</details>

## Outils de protection des emails

<details>
<summary>Déplier</summary>

- [MailScanner](https://www.mailscanner.info/) (Protection des emails contre les virus et les spams)
- [SpamAssassin](https://spamassassin.apache.org/) (Filtrage anti-spam)
- [ClamAV](https://www.clamav.net/) (Antivirus pour les emails)

</details>

## Création de honeypots

<details>
<summary>Déplier</summary>

- [Trapster Community](https://github.com/0xBallpoint/trapster-community) (Création de honeypots)

