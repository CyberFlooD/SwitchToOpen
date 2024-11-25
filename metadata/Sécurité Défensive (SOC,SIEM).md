# 🛡️ Sécurité Défensive (SOC/SIEM/Firewall/WAF)
Cette section est dédiée aux outils de **Sécurité Défensive**, spécialement conçus pour les centres opérationnels de sécurité (SOC) et les systèmes d'information et d'événements de sécurité (SIEM). Ces outils sont utilisés pour la surveillance, la détection, et la réponse aux incidents.

## 📖 Table des Matières
1. [Elastic Stack (ELK)](#elastic-stack-elk)
2. [Wazuh](#wazuh)
3. [Graylog](#graylog)
4. [Splunk (Community Alternatives)](#splunk-community-alternatives)
5. [TheHive](#thehive)
6. [MISP](#misp)
7. [Cortex](#cortex)
8. [OpenCTI](#opencti)
9. [Security Onion](#security-onion)
10. [Zeek](#zeek)
11. [Snort](#snort)
12. [Suricata](#suricata)
13. [pfSense](#pfsense)
14. [OPNsense](#opnsense)
15. [IPFire](#ipfire)
16. [Vulture](#vulture)
17. [BunkerWeb](#bunkerweb)
18. [ModSecurity](#modsecurity)
19. [NAXSI](#naxsi)

---

## Elastic Stack (ELK)
- **Catégorie** : SIEM et Analyse des Logs
- **Tags** : `Linux`, `Java`, `Apache`, `Web-based`, `Log Management`, `SIEM`, `Data Analytics`
- **Description** : Elastic Stack (ELK) est une suite d'outils pour l'analyse des logs et la gestion des données, comprenant Elasticsearch, Logstash, et Kibana. Elle permet d'ingérer, analyser, et visualiser les données de sécurité.
- **Langage principal** : Java
- **Licence** : Apache 2.0
- **Interface** : Web
- **Système d'exploitation** : Linux, macOS, Windows
- **Documentation** : [Elastic Stack Documentation](https://www.elastic.co/guide/index.html)
- **Référentiel GitHub** : [https://github.com/elastic/elasticsearch](https://github.com/elastic/elasticsearch)

---

## Wazuh
- **Catégorie** : SIEM et Détection des Intrusions
- **Tags** : `Linux`, `Windows`, `Python`, `GPL`, `Web-based`, `SIEM`, `IDS`
- **Description** : Wazuh est une plateforme open source de détection des intrusions et d'analyse des logs. Elle offre des fonctionnalités avancées de SIEM et de détection des menaces.
- **Langage principal** : Python
- **Licence** : GPL
- **Interface** : Web
- **Système d'exploitation** : Linux, Windows
- **Documentation** : [Wazuh Documentation](https://documentation.wazuh.com/)
- **Référentiel GitHub** : [https://github.com/wazuh/wazuh](https://github.com/wazuh/wazuh)

---

## Graylog
- **Catégorie** : Gestion des Logs et Analyse
- **Tags** : `Linux`, `Java`, `Web-based`, `Log Management`, `SIEM`
- **Description** : Graylog est un outil open source de gestion et d'analyse des logs, permettant une collecte centralisée des logs et une analyse en temps réel.
- **Langage principal** : Java
- **Licence** : Apache 2.0
- **Interface** : Web
- **Système d'exploitation** : Linux
- **Documentation** : [Graylog Documentation](https://docs.graylog.org/)
- **Référentiel GitHub** : [https://github.com/Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server)

---

## Splunk (Community Alternatives)
- **Catégorie** : SIEM et Analyse des Logs
- **Tags** : `Linux`, `Windows`, `Java`, `Web-based`, `Log Management`, `SIEM`
- **Description** : Splunk est un outil commercial pour l'analyse des logs, mais des alternatives open source existent, telles que Graylog et Elastic Stack.
- **Langage principal** : Java
- **Licence** : Propriétaire (Community Alternatives disponibles)
- **Interface** : Web
- **Système d'exploitation** : Linux, Windows
- **Documentation** : [Splunk Documentation](https://docs.splunk.com/Documentation/Splunk)
- **Référentiel GitHub** : *Non applicable pour la version commerciale*

---

## TheHive
- **Catégorie** : Gestion des Incidents
- **Tags** : `Linux`, `Java`, `Apache`, `Web-based`, `Incident Response`
- **Description** : TheHive est une plateforme open source de gestion des incidents, conçue pour faciliter les enquêtes sur les menaces et la réponse aux incidents de sécurité.
- **Langage principal** : Java
- **Licence** : Apache 2.0
- **Interface** : Web
- **Système d'exploitation** : Linux
- **Documentation** : [TheHive Documentation](https://docs.thehive-project.org/)
- **Référentiel GitHub** : [https://github.com/TheHive-Project/TheHive](https://github.com/TheHive-Project/TheHive)

---

## MISP
- **Catégorie** : Partage de Menaces et Renseignement
- **Tags** : `Linux`, `PHP`, `Apache`, `Web-based`, `Threat Intelligence`
- **Description** : MISP (Malware Information Sharing Platform) est une plateforme de partage d'informations sur les menaces, utilisée pour la collecte et la diffusion des indicateurs de compromission (IOC).
- **Langage principal** : PHP
- **Licence** : AGPL
- **Interface** : Web
- **Système d'exploitation** : Linux
- **Documentation** : [MISP Documentation](https://www.misp-project.org/documentation.html)
- **Référentiel GitHub** : [https://github.com/MISP/MISP](https://github.com/MISP/MISP)

---

## Cortex
- **Catégorie** : Analyse des Incidents et Threat Intelligence
- **Tags** : `Linux`, `Java`, `Apache`, `Web-based`, `Incident Analysis`, `Threat Intelligence`
- **Description** : Cortex est un outil open source utilisé pour l'analyse automatisée des observables. Il permet aux SOC de mener des investigations rapides et efficaces en s'appuyant sur une vaste collection de connecteurs analytiques.
- **Langage principal** : Java
- **Licence** : Apache 2.0
- **Interface** : Web
- **Système d'exploitation** : Linux
- **Documentation** : [Cortex Documentation](https://docs.thehive-project.org/cortex/)
- **Référentiel GitHub** : [https://github.com/TheHive-Project/Cortex](https://github.com/TheHive-Project/Cortex)

---

## OpenCTI
- **Catégorie** : Threat Intelligence Platform (TIP)
- **Tags** : `Linux`, `Node.js`, `GraphQL`, `Web-based`, `Threat Intelligence`, `TIP`
- **Description** : OpenCTI est une plateforme open source de Threat Intelligence permettant de collecter, stocker, et analyser des données sur les cybermenaces. Il offre une interface intuitive et une API GraphQL pour une intégration facile dans les environnements SOC.
- **Langage principal** : Node.js, Python
- **Licence** : Apache 2.0
- **Interface** : Web
- **Système d'exploitation** : Linux
- **Documentation** : [OpenCTI Documentation](https://www.opencti.io/docs)
- **Référentiel GitHub** : [https://github.com/OpenCTI-Platform/opencti](https://github.com/OpenCTI-Platform/opencti)

---

## pfSense
- **Catégorie** : Pare-feu
- **Tags** : `BSD`, `Web-based`, `Firewall`, `Network Security`
- **Description** : pfSense est un pare-feu open source basé sur FreeBSD, offrant une large gamme de fonctionnalités, notamment le filtrage des paquets, le NAT, et la gestion VPN.
- **Langage principal** : C, PHP
- **Licence** : Apache 2.0
- **Interface** : Web
- **Système d'exploitation** : FreeBSD
- **Documentation** : [pfSense Documentation](https://docs.netgate.com/pfsense/en/latest/)
- **Référentiel GitHub** : [https://github.com/pfsense/pfsense](https://github.com/pfsense/pfsense)

---

## OPNsense
- **Catégorie** : Pare-feu
- **Tags** : `BSD`, `Web-based`, `Firewall`, `Network Security`, `VPN`
- **Description** : OPNsense est un pare-feu open source basé sur FreeBSD, conçu pour offrir une sécurité réseau avancée. Il propose des fonctionnalités de pare-feu, de VPN, d'IDS/IPS, et de proxy web, avec une interface utilisateur moderne.
- **Langage principal** : C, PHP
- **Licence** : BSD
- **Interface** : Web
- **Système d'exploitation** : FreeBSD
- **Documentation** : [OPNsense Documentation](https://docs.opnsense.org/)
- **Référentiel GitHub** : [https://github.com/opnsense/core](https://github.com/opnsense/core)

---

## IPFire
- **Catégorie** : Pare-feu
- **Tags** : `Linux`, `Web-based`, `Firewall`, `Network Security`
- **Description** : IPFire est une distribution Linux dédiée à la sécurité, intégrant un pare-feu avancé avec des fonctionnalités de proxy, VPN, et IDS.
- **Langage principal** : C
- **Licence** : GPL
- **Interface** : Web
- **Système d'exploitation** : Linux
- **Documentation** : [IPFire Documentation](https://wiki.ipfire.org/)
- **Référentiel GitHub** : [https://github.com/ipfire](https://github.com/ipfire)

---

## Vulture
- **Catégorie** : Web Application Firewall (WAF)
- **Tags** : `Linux`, `Nginx`, `Firewall`, `WAF`, `Web Security`
- **Description** : Vulture est un WAF open source conçu pour protéger les applications web contre les attaques courantes telles que les injections SQL et XSS. Il s'intègre facilement avec Nginx et fournit une protection robuste avec un faible impact sur la performance.
- **Langage principal** : C
- **Licence** : GPL
- **Interface** : CLI, Configuration via Nginx
- **Système d'exploitation** : Linux
- **Documentation** : [Vulture Documentation](https://github.com/vulture-waf/vulture)
- **Référentiel GitHub** : [https://github.com/vulture-waf/vulture](https://github.com/vulture-waf/vulture)

---

## BunkerWeb

- **Catégorie** : Web Application Firewall (WAF)
- **Tags** : `Linux`, `Web-based`, `Firewall`, `WAF`, `Web Security`
- **Description** : BunkerWeb est un WAF moderne et léger conçu pour offrir une protection proactive contre les menaces web. Il dispose de fonctionnalités avancées de détection des attaques et d'une interface utilisateur intuitive pour une gestion facile.
- **Langage principal** : Rust
- **Licence** : MIT
- **Interface** : Web
- **Système d'exploitation** : Linux
- **Documentation** : [BunkerWeb Documentation](https://bunkerweb.dev/docs)
- **Référentiel GitHub** : [https://github.com/bunkerweb/bunkerweb](https://github.com/bunkerweb/bunkerweb)

---

## ModSecurity
- **Catégorie** : Web Application Firewall (WAF)
- **Tags** : `Linux`, `Apache`, `Nginx`, `Firewall`, `WAF`
- **Description** : ModSecurity est un pare-feu d'application web open source capable de détecter et de bloquer les attaques web courantes. Il peut être intégré à Apache, Nginx, et IIS.
- **Langage principal** : C
- **Licence** : Apache 2.0
- **Interface** : CLI
- **Système d'exploitation** : Linux, Windows
- **Documentation** : [ModSecurity Documentation](https://github.com/SpiderLabs/ModSecurity/wiki)
- **Référentiel GitHub** : [https://github.com/SpiderLabs/ModSecurity](https://github.com/SpiderLabs/ModSecurity)

---

## NAXSI
- **Catégorie** : Web Application Firewall (WAF)
- **Tags** : `Linux`, `Nginx`, `Firewall`, `WAF`, `Web Security`
- **Description** : NAXSI (Nginx Anti XSS & SQL Injection) est un module WAF pour Nginx, conçu pour protéger les applications web contre les attaques XSS et SQL Injection.
- **Langage principal** : C
- **Licence** : GPL
- **Interface** : CLI, Nginx Config
- **Système d'exploitation** : Linux
- **Documentation** : [NAXSI Documentation](https://github.com/nbs-system/naxsi)
- **Référentiel GitHub** : [https://github.com/nbs-system/naxsi](https://github.com/nbs-system/naxsi)


---

## 🤝 Contributions
Vous pouvez contribuer en proposant des outils supplémentaires via des **pull requests** ou en ouvrant des **issues** pour suggérer des modifications.
Consultez le fichier `CONTRIBUTING.md` pour plus d'informations.

---
