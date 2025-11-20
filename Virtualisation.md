<div style="display: flex; align-items: center; justify-content: space-between;">
  <h1>🌐 Virtualisation</h1>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Catégorie-Virtualisation-9cf?style=for-the-badge&logo=proxmox"/>
  <img src="https://img.shields.io/badge/Open%20Source-100%25-brightgreen?style=for-the-badge&logo=opensourceinitiative"/>
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge&logo=github"/>
  <img src="https://img.shields.io/github/last-commit/CyberFlooD/SwitchToOpen?label=Last%20Update&color=informational&style=for-the-badge&logo=github"/>
</p>


## Sommaire 📖 <a id="sommaire"></a>
1. [🖥️ Hyperviseurs de type 1 (Bare-metal)](#hyperviseur-type-1)
2. [💻 Hyperviseurs de type 2 (Virtualisation hébergée)](#hyperviseur-type-2)
3. [📦 Virtualisation de conteneurs](#virtualisation-conteneurs)
4. [☁️ Virtualisation légère pour environnements spécifiques](#virtualisation-legere)
5. [🌐 Outils de virtualisation réseau](#virtualisation-reseau)
6. ...

---

## 🖥️ Hyperviseurs de type 1 (Bare-metal) <a id="hyperviseur-type-1"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Proxmox VE** | AGPLv3 | Support des conteneurs et des machines virtuelles KVM | Solution de virtualisation open source avec support des conteneurs et des machines virtuelles KVM | <div align="center"><a href="https://www.proxmox.com/en/proxmox-ve">🔗</a></div> |
| **XCP-ng** | GPLv2 (Linux, Xen), LGPLv2+, BSD et autres licences libres selon composants | Gestion complète des machines virtuelles et du réseau | Hyperviseur open source basé sur XenServer | <div align="center"><a href="https://xcp-ng.org/">🔗</a></div> |
| **KVM (Kernel-based Virtual Machine)** | GNU General Public License (GPL) | Virtualisation native sous Linux | Technologie permettant d'exécuter des systèmes d'exploitation invités sur des serveurs | <div align="center"><a href="https://www.linux-kvm.org/">🔗</a></div> |
| **Xen Project** | GPLv2 | Exécution de plusieurs systèmes d'exploitation invités | Hyperviseur permettant d'exécuter plusieurs systèmes d'exploitation invités sur des serveurs physiques | <div align="center"><a href="https://xenproject.org/">🔗</a></div> |
| **oVirt** | Apache License 2.0 | Gestion des datacenters | Plateforme de gestion de la virtualisation basée sur KVM | <div align="center"><a href="https://www.ovirt.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 💻 Hyperviseurs de type 2 (Virtualisation hébergée) <a id="hyperviseur-type-2"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **VirtualBox (édition open source)** | Open source | Création et exécution de machines virtuelles | Permet de créer et exécuter des machines virtuelles sur des systèmes d'exploitation hôtes | <div align="center"><a href="https://www.virtualbox.org/">🔗</a></div> |
| **GNOME Boxes** | Open source | Gestion des machines virtuelles | Interface simple pour la gestion des machines virtuelles, utilisant libvirt et KVM sous Linux | <div align="center"><a href="https://wiki.gnome.org/Apps/Boxes">🔗</a></div> |
| **QEMU** | Open source | Émulation de différentes architectures | Émulateur permettant de virtualiser des systèmes d'exploitation ou d'émuler différentes architectures matérielles | <div align="center"><a href="https://www.qemu.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📦 Virtualisation de conteneurs <a id="virtualisation-conteneurs"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Docker** | Open source | Environnements isolés pour les applications | Plateforme de conteneurisation permettant d'exécuter des applications dans des environnements isolés | <div align="center"><a href="https://www.docker.com/">🔗</a></div> |
| **LXC (Linux Containers)** | Open source | Exécution de systèmes Linux isolés | Système de conteneurisation permettant d'exécuter plusieurs systèmes Linux isolés sur un seul hôte | <div align="center"><a href="https://linuxcontainers.org/">🔗</a></div> |
| **Podman** | Open source | Gestion des conteneurs sans démon | Alternative à Docker pour la gestion des conteneurs sans démon | <div align="center"><a href="https://podman.io/">🔗</a></div> |
| **Kubernetes** | Open source | Gestion des applications conteneurisées | Plateforme pour l'orchestration des conteneurs | <div align="center"><a href="https://kubernetes.io/">🔗</a></div> |
| **rkt (Rocket)** | Open source | Conteneurisation sécurisée | Outil de conteneurisation conçu pour des environnements plus sécurisés que Docker | <div align="center"><a href="https://coreos.com/rkt/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## ☁️ Virtualisation légère pour environnements spécifiques <a id="virtualisation-legere"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Multipass** | Open source | Machines virtuelles légères | Solution pour exécuter des machines virtuelles légères sous Linux, Windows et macOS | <div align="center"><a href="https://multipass.run/">🔗</a></div> |
| **Vagrant** | Open source | Automatisation des environnements de développement | Outil pour automatiser la création et la gestion des environnements de développement virtuels | <div align="center"><a href="https://www.vagrantup.com/">🔗</a></div> |
| **Firecracker** | Open source | MicroVMs légères | MicroVMs pour des déploiements rapides de conteneurs et de fonctions serverless | <div align="center"><a href="https://firecracker-microvm.github.io/">🔗</a></div> |
| **bhyve** | Open source | Virtualisation rapide et efficace | Hyperviseur léger natif sous FreeBSD | <div align="center"><a href="https://bhyve.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🌐 Outils de virtualisation réseau <a id="virtualisation-reseau"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Open vSwitch** | Open source | Automatisation des réseaux virtualisés | Commutateur virtuel conçu pour automatiser les réseaux dans des environnements virtualisés | <div align="center"><a href="https://www.openvswitch.org/">🔗</a></div> |
| **Flannel** | Open source | Réseau pour conteneurs Kubernetes | Permet de configurer un réseau overlay simple pour Kubernetes | <div align="center"><a href="https://github.com/flannel-io/flannel">🔗</a></div> |
| **Calico** | Open source | Réseau pour environnements cloud et conteneurisés | Solution de mise en réseau pour les environnements cloud et conteneurisés | <div align="center"><a href="https://www.projectcalico.org/">🔗</a></div> |
| **Cilium** | Open source | Connectivité et sécurité des réseaux de conteneurs | Solution pour la connectivité et la sécurité des réseaux de conteneurs | <div align="center"><a href="https://cilium.io/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🤝 Contributions

Tu connais un outil open-source oublié ici ? Propose-le via **pull request** ou **issue** 💬

---
