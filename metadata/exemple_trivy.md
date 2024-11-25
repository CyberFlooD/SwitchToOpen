# 🛠 Trivy

## 🔍 Description
Trivy est un scanner de vulnérabilités léger et performant conçu pour analyser les conteneurs, les images Docker, les fichiers systèmes, et les dépôts Git. Il permet de détecter les vulnérabilités, les mauvaises configurations, et les secrets exposés dans vos artefacts.

## 📜 Détails
- **Catégorie** : DevSecOps > Sécurité des Conteneurs
- **Tags** : `Linux`, `Docker`, `Kubernetes`, `Go`, `GPL`, `CLI`, `Stable`, `DevSecOps`, `Cloud`, `CI/CD`
- **Langage principal** : Go
- **Licence** : GPL v3
- **Interface** : CLI (ligne de commande)
- **Système d'exploitation** : Linux, macOS, Windows
- **Compatibilité cloud** : Docker, Kubernetes, GitHub Actions, GitLab CI
- **Utilisateurs cibles** : DevSecOps, Administrateurs système, Développeurs
- **Niveau utilisateur** : Intermédiaire, Expert
- **Statut de développement** : Stable
- **Popularité** : 🌟🌟🌟🌟🌟 (plus de 18k étoiles sur GitHub)

## 🔗 Catégorie
[DevSecOps > Sécurité des Conteneurs](DevSecOps%20et%20S%C3%A9curit%C3%A9%20des%20Conteneurs.md).

## 🌟 Fonctionnalités Principales :
1. **Analyse des conteneurs** : Scanne les images Docker et Kubernetes pour détecter les vulnérabilités connues.
2. **Détection des mauvaises configurations** : Identifie les configurations incorrectes dans les conteneurs et les fichiers d'infrastructure.
3. **Analyse des secrets exposés** : Repère les clés API et autres secrets sensibles accidentellement exposés dans le code source.
4. **Intégration CI/CD** : Compatible avec GitHub Actions, GitLab CI, et autres systèmes CI pour l'automatisation des scans.

## 🚀 Installation Rapide :
### Via Homebrew (macOS/Linux)
```bash
brew install aquasecurity/trivy/trivy
```

### Via Docker
```bash
docker pull aquasec/trivy
```

### Exécution d'un Scan (ou autre commande pertinente)
```bash
trivy image nginx:latest
```

## 📚 Ressources et Support :
- **Documentation officielle** : [Documentation officielle](https://aquasecurity.github.io/trivy/)
- **Référentiel GitHub** : [https://github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **Support communautaire** : Actif (Slack, GitHub Discussions)

## 🌐 Sources et Tutoriels Intéressants
- [Tutoriel -> Intégrer la sécurité dès le départ avec Trivy](https://blog.stephane-robert.info/docs/securiser/outils/trivy/)
- [Tutoriel -> Trivy, un scanner de sécurité couteau suisse](https://blog.wescale.fr/trivy-un-scanner-de-s%C3%A9curit%C3%A9-couteau-suisse)
- [Cas d'utilisation -> DevSecOps sur Kubernetes avec l'outil Trivy](https://toungafranck.com/2024/05/25/devsecops-sur-kubernetes-avec-loutil-trivy/)
- [Vidéo YouTube -> Analyse de sécurité Kubernetes avec Trivy CLI et Trivy Operator (en anglais)](https://www.youtube.com/watch?v=bgYrhQ6rTXA)
