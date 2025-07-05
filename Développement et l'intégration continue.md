<div style="display: flex; align-items: center; justify-content: space-between;">
  <h1>📚 Outils de développement et d'intégration continue</h1>
  <img src="Img/switchtoopen1.png" alt="Description de l'image" width="150" height="150">
</div>

## Sommaire 📖 <a id="sommaire"></a>
1. [📂 Environnements de développement intégrés (IDE) et éditeurs de code](#ide-editeurs)
2. [🔗 Systèmes de contrôle de version](#controle-de-version)
3. [🔄 Intégration continue (CI) et déploiement continu (CD)](#ci-cd)
4. [⚙️ Gestion de configuration et Infrastructure as Code (IaC)](#gestion-configuration-iac)
5. [📦 Gestion des dépendances et des packages](#gestion-dependances)
6. [🚀 Gestion des conteneurs et orchestration](#conteneurs-orchestration)
7. [🛠️ Outils de gestion des tests automatisés](#tests-automatises)
8. [💻 Conteneurisation et virtualisation](#conteneurisation-virtualisation)

---

## 📂 Environnements de développement intégrés (IDE) et éditeurs de code <a id="ide-editeurs"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Visual Studio Code** | Licence propriétaire gratuite Microsoft + Code - OSS (GitHub)	Licence MIT | Éditeur de code extensible | Éditeur de code open source de Microsoft, très populaire pour son extensibilité et ses fonctionnalités de développement | <div align="center"><a href="https://code.visualstudio.com/">🔗</a></div> |
| **Atom** | MIT | Éditeur de code riche en plugins | Éditeur de code open source, développé par GitHub, avec un riche écosystème de plugins | <div align="center"><a href="https://atom.io/">🔗</a></div> |
| **VSCodium** | MIT | Éditeur de code riche en plugins | VSCodium est une version libre et open source de Visual Studio Code (VS Code), créée pour offrir une alternative sans télémétrie ni traçage de Microsoft. Il s'agit d'un fork du code source de VS Code, compilé et distribué sous licence MIT, mais sans les composants propriétaires et de suivi présents dans la version officielle distribuée par Microsoft | <div align="center"><a href="https://github.com/VSCodium/vscodium">🔗</a></div> |
| **Eclipse** | Eclipse Public License (EPL) 2.0 | IDE pour les projets Java | Environnement de développement intégré open source, largement utilisé pour les projets Java | <div align="center"><a href="https://www.eclipse.org/">🔗</a></div> |
| **Geany** | GPLv2 | Éditeur de texte léger | Éditeur de texte léger avec des fonctionnalités d'environnement de développement intégré | <div align="center"><a href="https://www.geany.org/">🔗</a></div> |
| **Vim** | GPL | Éditeur de texte puissant et personnalisable | Éditeur de texte open source, puissant et personnalisable, utilisé par les développeurs avancés | <div align="center"><a href="https://www.vim.org/">🔗</a></div> |


[🔝 Retour au sommaire](#sommaire)

---

## 🔗 Systèmes de contrôle de version <a id="controle-de-version"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Git** | GPLv2 | Système de contrôle de version décentralisé | Système de contrôle de version décentralisé, open source et largement utilisé | <div align="center"><a href="https://git-scm.com/">🔗</a></div> |
| **Gitea** | MIT | Alternative à GitHub, auto-hébergeable | Alternative légère et open source à GitHub, auto-hébergeable | <div align="center"><a href="https://gitea.io/en-us/">🔗</a></div> |
| **GitLab Community** | MIT + Version Enterprise | CI/CD intégrée | Plateforme de contrôle de version avec CI/CD intégrée, alternative open source à GitHub | <div align="center"><a href="https://about.gitlab.com/">🔗</a></div> |
| **Gogs** | MIT | Forge multiplateforme basée sur git | Gogs (Go Git Service) est une forge multiplateforme basée sur git écrite en Go | <div align="center"><a href="https://github.com/gogs/gogs">🔗</a></div> |
| **Forgejo** | GPLv3+ | Forge logiciel auto-hébergée | Forgejo est une forge logiciel légère auto-hébergée | <div align="center"><a href="https://codeberg.org/forgejo/forgejo">🔗</a></div> |
| **Fossil** | BSD 3-clause license | Gestion de versions décentralisée avec suivi de bugs | Système de gestion de versions décentralisé, avec suivi des bugs et gestion des tickets intégrés | <div align="center"><a href="https://www.fossil-scm.org/">🔗</a></div> |
| **Bazaar** | GPL | Système de contrôle de version distribué | Système de contrôle de version distribué | <div align="center"><a href="https://bazaar.canonical.com/en/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🔄 Intégration continue (CI) et déploiement continu (CD) <a id="ci-cd"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Jenkins** | MIT | Serveur CI extensible | Serveur open source d’intégration continue, extensible via des plugins | <div align="center"><a href="https://www.jenkins.io/">🔗</a></div> |
| **GitLab CI Community** | MIT + Enterprise Edition | CI/CD intégrée à GitLab | Système CI/CD intégré à GitLab, avec pipelines configurables par fichier `.gitlab-ci.yml` | <div align="center"><a href="https://about.gitlab.com/stages-devops-lifecycle/continuous-integration/">🔗</a></div> |
| **Drone** | Apache License 2.0 + Enterprise Edition | CI basée sur des conteneurs Docker | Système d'intégration continue open source basé sur des conteneurs Docker | <div align="center"><a href="https://www.drone.io/">🔗</a></div> |
| **GoCD** | Apache License 2.0	 | Déploiement continu | Outil open source pour le déploiement continu, avec pipelines visualisables | <div align="center"><a href="https://www.gocd.org/">🔗</a></div> |
| **Concourse CI** | Apache License 2.0	 | Outil CI/CD modulaire | Outil de CI/CD open source avec une approche modulaire et orientée pipelines | <div align="center"><a href="https://concourse-ci.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## ⚙️ Gestion de configuration et Infrastructure as Code (IaC) <a id="gestion-configuration-iac"></a>

| 🌟 **Outil**	| 🔑 **Type de licence**	| 🚀 **Fonctionnalités clés**	| 📝 **Description** | 🌐 **Lien Web**
|---|---|---|---|---|
|**Ansible**|	GPLv3	| Automatisation sans agent, gestion de configuration	| Outil simple et puissant d’automatisation IT, déploiement et gestion de configuration sans agent. |	<div align="center"><a href="https://www.ansible.com/">🔗</a></div> |
|**Terraform**|	MPL-2.0	| Infrastructure as Code multi-cloud	| Outil d’orchestration d’infrastructures déclaratif, supporte de nombreux fournisseurs cloud et on-premises. |	<div align="center"><a href="https://www.terraform.io/">🔗</a></div> |
|**Puppet**|	Apache License 2.0	| Gestion de configuration déclarative	| Plateforme mature pour automatiser la gestion et la configuration des infrastructures. |	<div align="center"><a href="https://puppet.com/">🔗</a></div> |
|**Chef Infra**|	Apache License 2.0	| Gestion de configuration basée sur Ruby	| Outil d’automatisation pour gérer les configurations et déploiements complexes. |	<div align="center"><a href="https://www.chef.io/">🔗</a></div> |
|**SaltStack (Salt)**|	Apache License 2.0	| Gestion de configuration et orchestration	| Outil d’automatisation et d’orchestration à grande échelle avec communication en temps réel. |	<div align="center"><a href="https://saltproject.io/">🔗</a></div> |
|**Pulumi**|	Apache License 2.0	| Infrastructure as Code avec langages de programmation |	Permet de définir l’infrastructure via des langages comme TypeScript, Python, Go, et C#. |	<div align="center"><a href="https://www.pulumi.com/">🔗</a></div> |
| **Packer** | MPL-2.0 | Construction des images système | Packer est un outil open source développé par HashiCorp, utilisé principalement pour automatiser la création d'images de machines virtuelles et de conteneurs. Il permet de définir des configurations (templates) pour générer des images reproductibles sur différentes plateformes (comme AWS, Azure, VMware, Docker, etc.) | <div align="center"><a href="https://github.com/hashicorp/packer">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 📦 Gestion des dépendances et des packages <a id="gestion-dependances"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Verdaccio** | MIT | Gestionnaire de packages npm | Gestionnaire de packages npm open source, auto-hébergeable | <div align="center"><a href="https://verdaccio.org/">🔗</a></div> |
| **Pulp** | BSD 3-clause | Plateforme pour gérer des dépôts de contenu | Plateforme open source pour gérer des dépôts de contenu comme des packages et conteneurs | <div align="center"><a href="https://pulpproject.org/">🔗</a></div> |
| **Composer** | MIT | Gestionnaire de dépendances | Gestionnaire de dépendances pour PHP | <div align="center"><a href="https://getcomposer.org/">🔗</a></div> |
| **Nexus** | OSS | Gestionnaire de dépendances et des packages | Gestionnaire d’artefacts multi-format | <div align="center"><a href="https://github.com/sonatype/nexus-public">🔗</a></div> |
| **Harbor** | Apache License 2.0	 | Gestionnaire d’artefacts | Registry open source pour images de conteneurs, charts Helm, avec sécurité, scan, RBAC et réplication. | <div align="center"><a href="https://github.com/goharbor/harbor">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🚀 Gestion des conteneurs et orchestration <a id="conteneurs-orchestration"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Docker (Engine)** | Apache License 2.0 | Plateforme de gestion de conteneurs | Plateforme open source pour la création et l'exécution de conteneurs | <div align="center"><a href="https://www.docker.com/">🔗</a></div> |
| **Kubernetes** | Apache License 2.0	 | Orchestration de conteneurs | Système open source d'orchestration de conteneurs pour le déploiement et la gestion à grande échelle | <div align="center"><a href="https://kubernetes.io/">🔗</a></div> |
| **Podman** | Apache License 2.0	 | Alternative à Docker sans démon | Alternative à Docker, open source et sans démon | <div align="center"><a href="https://podman.io/">🔗</a></div> |
| **Helm** | Apache License 2.0	 | Gestionnaire de paquets pour Kubernetes | Gestionnaire de paquets open source pour Kubernetes | <div align="center"><a href="https://helm.sh/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 🛠️ Outils de gestion des tests automatisés <a id="tests-automatises"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Selenium** | Apache License 2.0	 | Automatisation des tests navigateurs | Framework open source pour l'automatisation des tests de navigateurs web | <div align="center"><a href="https://www.selenium.dev/">🔗</a></div> |
| **JUnit (5)** | EPL 2.0 | Tests unitaires | Framework de tests unitaires pour Java | <div align="center"><a href="https://junit.org/junit5/">🔗</a></div> |
| **Mocha** | MIT | Framework de tests pour JavaScript | Framework de tests pour JavaScript. | <div align="center"><a href="https://mochajs.org/">🔗</a></div> |
| **Cucumber** | MIT | Tests basé sur des spécifications | Outil open source pour l'exécution de tests basés sur des spécifications en langage naturel. | <div align="center"><a href="https://cucumber.io/">🔗</a></div> |
| **Robot Framework** | Apache License 2.0	 | Tests d'acceptation et d'automatisation | Framework open source pour les tests d'acceptation et d'automatisation. | <div align="center"><a href="https://robotframework.org/">🔗</a></div> |

[🔝 Retour au sommaire](#sommaire)

---

## 💻 Conteneurisation et virtualisation <a id="conteneurisation-virtualisation"></a>

| 🌟 **Outil** | 🔑 **Type de licence** | 🚀 **Fonctionnalités clés** | 📝 **Description** | 🌐 **Lien Web** |
|---|---|---|---|---|
| **Vagrant ≤ 2.3.6** | MIT | Outil d'optimisation de la virtualisation | Outil open source pour la construction et la gestion d'environnements virtualisés via des scripts | <div align="center"><a href="https://www.vagrantup.com/">🔗</a></div> |
| **Vagrant ≥ 2.3.7** | Business Source License 1.1 (BSL)	(Non open-source!) | Outil d'optimisation de la virtualisation | Outil open source pour la construction et la gestion d'environnements virtualisés via des scripts | <div align="center"><a href="https://www.vagrantup.com/">🔗</a></div> |


[🔝 Retour au sommaire](#sommaire)
