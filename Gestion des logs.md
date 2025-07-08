<div style="display: flex; align-items: center; justify-content: space-between;">
  <h1>📊  Gestion de logs</h1>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Catégorie-Gestion%20de%20logs-5050f0?style=for-the-badge&logo=kibana"/>
  <img src="https://img.shields.io/badge/Open%20Source-100%25-brightgreen?style=for-the-badge&logo=opensourceinitiative"/>
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge&logo=github"/>
  <img src="https://img.shields.io/github/last-commit/CyberFlooD/SwitchToOpen?label=Last%20Update&color=informational&style=for-the-badge&logo=github"/>
</p>


## Sommaire 📖 <a id="sommaire"></a>
1. [📊 Collecte, analyse et gestion centralisée des logs](#collecte-logs)
2. [🔍 Surveillance des événements et détection d'intrusions (SIEM)](#siem)
3. [🛠️ Collecte et routage des logs](#collecte-routage)
4. [📈 Monitoring et visualisation des logs](#monitoring-visualisation)
5. [🚀 Outils de gestion des logs spécifiques aux environnements conteneurisés](#gestion-logs-conteneurises)

---

## 📊 Collecte, analyse et gestion centralisée des logs <a id="collecte-logs"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Graylog** | GPLv3 | Collecte et analyse des logs | Graylog est une plateforme open source de gestion centralisée des logs, reposant sur Elasticsearch pour l’indexation et offrant une interface web puissante pour la recherche, l’alerte et l’analyse avancée. Elle convient aux environnements d’entreprise nécessitant des recherches complexes et une conformité accrue | <div align="center"><a href="https://www.graylog.org/">🔗</a></div> |
| **ELK Stack** | Apache 2.0	 | Gestion complète des logs | L’ELK Stack (Elasticsearch, Logstash, Kibana) est la référence open source pour la collecte, l’analyse et la visualisation de logs, avec une grande flexibilité pour l’ingestion, le stockage et l’exploration de gros volumes de données | <div align="center"><a href="https://www.elastic.co/what-is/elk-stack">🔗</a></div> |
| **Fluentd** | Apache 2.0	 | Collecteur de logs | Fluentd est un collecteur de logs open source, capable d’agréger, transformer et router les logs vers de multiples destinations, s’intégrant facilement dans des architectures distribuées et cloud natives | <div align="center"><a href="https://www.fluentd.org/">🔗</a></div> |
| **Loki** | AGPLv3	 | Intégration avec Prometheus | Loki, développé par Grafana, est un système de gestion de logs optimisé pour les environnements cloud-native et Kubernetes, utilisant un index basé sur les labels pour une scalabilité et une efficacité de stockage accrues, avec intégration native à Grafana | <div align="center"><a href="https://grafana.com/oss/loki/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔍 Surveillance des événements et détection d'intrusions (SIEM) <a id="siem"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Wazuh** | 	GPLv2 et Apache 2.0 (selon composant) | SIEM et détection des menaces | Wazuh est une plateforme open source gratuite de SIEM et XDR, combinant analyse de logs, détection d’intrusions, conformité et réponse aux incidents en temps réel. Elle est hautement évolutive, compatible multi-OS et cloud, et dispose d’une large communauté active | <div align="center"><a href="https://wazuh.com/">🔗</a></div> |
| **OSSIM** | GPLv3 | Gestion des événements de sécurité | OSSIM (Open Source SIEM) d’AlienVault centralise la gestion des événements de sécurité, l’analyse de logs et la détection d’intrusions. Il intègre de nombreux outils open source pour la corrélation, la visualisation et la gestion des alertes | <div align="center"><a href="https://cybersecurity.att.com/products/ossim">🔗</a></div> |
| **Prelude** | GPLv2	 | Détection d'intrusions | Prelude est un SIEM modulaire open source, spécialisé dans la détection d’intrusions multi-source et la corrélation d’événements. Il se distingue par son interopérabilité et son architecture évolutive adaptée aux environnements complexes | <div align="center"><a href="https://www.prelude-siem.org/">🔗</a></div> |
| **Security Onion** | GPLv2 | Détection des menaces réseau | Security Onion est une distribution open source dédiée à la détection des menaces réseau, intégrant SIEM, IDS/IPS et outils de forensic. Elle offre une interface complète pour la surveillance, l’analyse et l’investigation des incidents de sécurité | <div align="center"><a href="https://securityonion.net/">🔗</a></div> |
| **T-Guard** | AGPLv3 | Solution unifiée de sécurité | T-Guard est une solution open source unifiée de sécurité, combinant Wazuh, outils de DFIR et d’analyse réseau, pour une gestion centralisée des alertes et des incidents. Elle vise une intégration poussée et un pilotage simplifié de la sécurité opérationnelle | <div align="center"><a href="https://docs.tguard.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🛠️ Collecte et routage des logs <a id="collecte-routage"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Rsyslog** | GPLv3	 | Collecteur de logs puissant | Rsyslog est un collecteur de logs open source très répandu sur Linux/Unix, offrant un routage performant, la journalisation centralisée et un filtrage avancé. Il supporte de nombreux protocoles et formats, et s’intègre facilement dans des architectures SIEM ou ELK | <div align="center"><a href="https://www.rsyslog.com/">🔗</a></div> |
| **Fluentd** | Apache 2.0 | Collecte et routage des logs | Fluentd est un collecteur et routeur de logs open source, capable d’agréger, transformer et distribuer les logs vers de multiples destinations. Il est très utilisé dans les environnements cloud et Kubernetes pour sa flexibilité et sa large compatibilité | <div align="center"><a href="https://www.fluentd.org/">🔗</a></div> |
| **Logstash** | Apache 2.0 | Transformation et envoi des logs | Logstash, composant de la suite ELK, permet de collecter, transformer et envoyer les logs vers Elasticsearch ou d’autres systèmes. Il dispose d’un vaste écosystème de plugins pour le parsing, l’enrichissement et le routage des données | <div align="center"><a href="https://www.elastic.co/logstash">🔗</a></div> |
| **Syslog-ng** | GPLv2 / LGPLv2.1 | Collecteur de logs avancé | Syslog-ng est un collecteur de logs avancé, open source, reconnu pour ses capacités de filtrage, de transformation et de sécurisation des flux de logs. Il s’adapte aussi bien aux petites infrastructures qu’aux environnements d’entreprise exigeants | <div align="center"><a href="https://www.syslog-ng.com/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📈 Monitoring et visualisation des logs <a id="monitoring-visualisation"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Kibana** | Elastic License | Visualisation de logs | Interface de visualisation et d’analyse pour Elasticsearch, idéale pour explorer, analyser et visualiser les logs | <div align="center"><a href="https://www.elastic.co/kibana">🔗</a></div> |
| **Grafana** | AGPLv3 (core), Grafana Enterprise (commercial) | Monitoring et visualisation | Plateforme de monitoring et de visualisation multi-sources, extensible, utilisée notamment avec Loki pour les logs | <div align="center"><a href="https://grafana.com/">🔗</a></div> |
| **GoAccess** | GPLv2 | Visualisation en temps réel | Analyseur de logs web en temps réel en ligne de commande ou interface web légère | <div align="center"><a href="https://goaccess.io/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🚀 Outils de gestion des logs spécifiques aux environnements conteneurisés <a id="gestion-logs-conteneurises"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Promtail** | AGPLv3 | Gestion des logs des conteneurs | Collecte les logs des pods/containers et les envoie vers Loki pour agrégation et visualisation | <div align="center"><a href="https://grafana.com/docs/loki/latest/clients/promtail/">🔗</a></div> |
| **Fluent Bit** | Apache 2.0	 | Collecteur de logs léger | Collecteur de logs ultra-léger, optimisé pour Kubernetes et environnements cloud natifs | <div align="center"><a href="https://fluentbit.io/">🔗</a></div> |
| **Vector** | MPL 2.0 | Collecte et transformation des logs | Plateforme moderne de collecte, transformation et routage des logs, compatible avec de nombreux systèmes | <div align="center"><a href="https://vector.dev/">🔗</a></div> |
| **Filebeat** | Apache 2.0	 | Agent léger pour logs | Agent léger pour expédier les logs de conteneurs, systèmes et applications vers Elasticsearch ou Logstash | <div align="center"><a href="https://www.elastic.co/beats/filebeat">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🤝 Contributions

Tu connais un outil open-source oublié ici ? Propose-le via **pull request** ou **issue** 💬

---
