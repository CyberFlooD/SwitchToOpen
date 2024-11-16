## 🛠 Outil : Trivy
- **Catégorie** : DevSecOps > Sécurité des Conteneurs
- **Tags** : `Linux`, `Docker`, `Kubernetes`, `Go`, `GPL`, `CLI`, `Stable`, `DevSecOps`, `Cloud`, `CI/CD`
- **Description** : Trivy est un scanner de vulnérabilités léger et performant conçu pour analyser les conteneurs, les images Docker, les fichiers systèmes, et les dépôts Git. Il permet de détecter les vulnérabilités, les mauvaises configurations, et les secrets exposés dans vos artefacts.
- **Langage principal** : Go
- **Licence** : GPL v3
- **Interface** : CLI (ligne de commande)
- **Système d'exploitation** : Linux, macOS, Windows
- **Compatibilité cloud** : Docker, Kubernetes, GitHub Actions, GitLab CI
- **Utilisateurs cibles** : DevSecOps, Administrateurs système, Développeurs
- **Niveau utilisateur** : Intermédiaire, Expert
- **Statut de développement** : Stable
- **Popularité** : 🌟🌟🌟🌟🌟 (plus de 18k étoiles sur GitHub)
- **Documentation** : [Documentation officielle](https://aquasecurity.github.io/trivy/)
- **Référentiel GitHub** : [https://github.com/aquasecurity/trivy](https://github.com/aquasecurity/trivy)
- **Support communautaire** : Actif (Slack, GitHub Discussions)

### **Fonctionnalités principales :**
1. **Analyse des conteneurs** : Scanne les images Docker et Kubernetes pour détecter les vulnérabilités connues.
2. **Détection des mauvaises configurations** : Identifie les configurations incorrectes dans les conteneurs et les fichiers d'infrastructure.
3. **Analyse des secrets exposés** : Repère les clés API et autres secrets sensibles accidentellement exposés dans le code source.
4. **Intégration CI/CD** : Compatible avec GitHub Actions, GitLab CI, et autres systèmes CI pour l'automatisation des scans.

### **Installation rapide :**
```bash
# Installation via Homebrew (macOS/Linux)
brew install aquasecurity/trivy/trivy

# Installation via Docker
docker pull aquasec/trivy

# Exemple de scan d'une image Docker
trivy image nginx:latest
