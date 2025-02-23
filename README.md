# Application Quiz Code de la Route - Android (Java)

📌 **Description**

Ce projet est une application Android développée en **Java** qui propose un quiz interactif sur le **Code de la Route**. L'utilisateur doit se connecter via une page de connexion qui interagit avec une API pour obtenir les questions du quiz. À la fin du quiz, l'application affiche le score de l'utilisateur basé sur ses réponses.

---

## 🚀 Fonctionnalités

### 👥 **Utilisateur**
- 🔑 **Page de connexion** : Authentification de l'utilisateur via une API (nom d'utilisateur et mot de passe).
- 📋 **Quiz sur le Code de la Route** : Une série de questions sur le code de la route, avec des choix multiples.
- 🏆 **Affichage du score** : Une fois le quiz terminé, l'application affiche le score obtenu par l'utilisateur.
- 💾 **Sauvegarde des résultats** : Les scores peuvent être sauvegardés pour suivi ultérieur.

---

## 🛠 **Installation**

Suivez ces étapes pour installer et exécuter le projet localement.

### 1️⃣ **Cloner le dépôt**

```bash
git clone https://github.com/ton-repo/quiz-code-de-la-route-android.git
cd quiz-code-de-la-route-android
```

### 2️⃣ **Installer les dépendances**

Assurez-vous d'avoir installé **Android Studio** et que le SDK Android est correctement configuré sur votre machine.

Ouvrez le projet dans **Android Studio** et attendez que toutes les dépendances se téléchargent automatiquement.

### 3️⃣ **Configurer l'API**

L'application utilise une **API** pour récupérer les questions du quiz et valider les connexions. Vous devez définir l'URL de l'API dans votre projet :
- Ouvrez le fichier `res/values/strings.xml`.
- Modifiez l'URL de l'API pour correspondre à l'endpoint de votre serveur.

```xml
<resources>
    <string name="api_base_url">http://votre-api.com/</string>
</resources>
```

### 4️⃣ **Lancer l'application**

Lancez l'application dans **Android Studio** en cliquant sur **Run** ou en utilisant la commande suivante :

```bash
./gradlew installDebug
```

### 5️⃣ **Accéder à l'application**

Lancez l'application sur votre émulateur Android ou un appareil physique et accédez à la page de connexion.

---

## 🛠 **Technologies utilisées**

- 📱 **Android** : Application mobile développée pour Android.
- 🖥️ **Java** : Langage de programmation utilisé pour le développement Android.
- 🌐 **API REST** : API pour récupérer les questions du quiz et gérer l'authentification des utilisateurs.
- 🏷️ **JSON** : Format utilisé pour échanger des données entre l'application et l'API.

---

## 🤝 Contribution

Les contributions sont les bienvenues ! Voici comment contribuer :

1. Forker le projet.
2. Créer une branche.
```bash
git checkout -b feature-ma-fonctionnalité
```
3. Committer vos modifications.
```bash
git commit -m "Ajout d'une fonctionnalité"
```
4. Pousser la branche.
```bash
git push origin feature-ma-fonctionnalité
```
5. Ouvrir une Pull Request.

---

💻 Développé avec ❤️ en Java pour Android.
```

---

### Explications :
- **Page de connexion** : L'application commence avec une page de connexion où les utilisateurs peuvent se connecter via une API. Le nom d'utilisateur et le mot de passe sont vérifiés par l'API.
- **Quiz Code de la Route** : Une fois connecté, l'utilisateur peut répondre à des questions de type QCM. À la fin, l'application affiche le score en fonction des réponses correctes.
- **API** : L'API fournit les questions et valide les connexions. Vous devez configurer l'URL de l'API dans les paramètres du projet pour que l'application fonctionne correctement.

Ce modèle peut être personnalisé en fonction de l'API que vous utilisez et des fonctionnalités supplémentaires que vous souhaitez ajouter.