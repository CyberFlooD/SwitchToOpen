<h1 align="center">🤖 Réponse Automatisée aux Incidents (SOAR & Gestion des alertes)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/SOAR-Automatisation-brightgreen?style=for-the-badge&logo=codecov"/>
  <img src="https://img.shields.io/badge/Incident%20Response-Open%20Source-informational?style=for-the-badge&logo=github"/>
  <img src="https://img.shields.io/badge/Made%20by-Dudix❤️-red?style=for-the-badge"/>
</p>

---

## Objectif

Cette section regroupe les outils open source dédiés à la **gestion des incidents de sécurité**, à leur **automatisation (SOAR)**, à l’**enrichissement d’alertes**, et à la **collaboration entre analystes SOC**.

---

## ⚙️ Outils de réponse aux incidents & SOAR

| 🌟 **Outil** | 🔑 **Licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **TheHive** | AGPLv3 | Gestion des incidents, cas, observables | Plateforme SOC centralisant les alertes, IOCs, cas à investiguer, connectée à MISP, Cortex, SIEMs | <div align="center"><a href="https://thehive-project.org/">🔗</a></div> |
| **Cortex** | AGPLv3 | Enrichissement automatisé des IOCs | Moteur d'analyse automatisée : résout, enrichit, attribue des scores aux indicateurs ou fichiers | <div align="center"><a href="https://www.thehive-project.org/">🔗</a></div> |
| **Shuffle** | MPL 2.0 | Orchestration de workflows (SOAR) | Crée des workflows de réponse automatisés (webhooks, alertes, scripts, enrichissements) via GUI | <div align="center"><a href="https://shuffler.io/">🔗</a></div> |
| **DFIR-IRIS** | GPLv3 | Investigation, forensic, timelines | Plateforme d’analyse post-incident, enrichissement de cas, génération de timelines, IR playbooks | <div align="center"><a href="https://dfir-iris.org/">🔗</a></div> |
| **Fast Incident Response (FIR)** | GPLv3 | Ticketing et investigation d'incidents | Suivi d’incidents et de campagnes, adapté aux CERTs, avec intégration d’enrichissement IOC | <div align="center"><a href="https://github.com/certsocietegenerale/FIR">🔗</a></div> |
| **IntelMQ** | GPLv3 | Traitement automatisé des flux CTI | Framework pour collecter, normaliser, enrichir et router automatiquement les alertes CTI | <div align="center"><a href="https://github.com/certtools/intelmq">🔗</a></div> |
| **DFIRTrack** | MIT | Documentation post-incident | Base de données pour consigner les éléments d’incidents, systèmes affectés, timelines | <div align="center"><a href="https://github.com/dfirtrack/dfirtrack">🔗</a></div> |

---

## 🔄 Cas d’usage

- Centraliser les alertes de SIEM/Wazuh
- Enrichir automatiquement les IOCs (IP, hash, URL)
- Créer des **playbooks automatisés** (ex. : “IOC détecté → enrichment → blocage → création de cas”)
- Coopération entre analystes SOC
- Documentation et traçabilité des investigations

---

## 🔗 À combiner avec

- [📊 SIEM (Wazuh, ELK, OSSIM)](./Outils%20SIEM.md)
- [🔍 CTI (MISP, OpenCTI)]([../cti-opencti](https://github.com/CyberFlooD/SwitchToOpen/blob/dev/Outils%20CTI%20et%20de%20pr%C3%A9vention%20des%20menaces%20cyber.md))
- [📈 Gestion des vulnérabilités (DefectDojo, Faraday)]([../S%C3%A9curit%C3%A9.md#plateformes-gestion](https://github.com/CyberFlooD/SwitchToOpen/blob/dev/S%C3%A9curit%C3%A9.md#gestion-vulnerabilites))

---

## 🤝 Contributions

Tu connais un outil open-source SOAR oublié ici ? Propose-le via **pull request** ou **issue** 💬

---

## 🖋️ Auteur

Made with ❤️ by [Dudix Consulting](https://github.com/CyberFlooD)
