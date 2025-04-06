
# 🎌 Flag Guessing Game

## 🧩 Présentation du projet ✅

**Flag Guessing Game** est une application web qui permet aux utilisateurs de deviner les drapeaux du monde.  
Le backend est fourni sous forme de fichier `.jar` déjà compilé avec **Spring Boot**, et le frontend est développé en **React.js**.  
Le tout est orchestré avec **Docker Compose** pour faciliter l’exécution locale.

---

## 🛠️ Technologies utilisées ✅

- **Backend :** Java 17, Spring Boot (packagé en `.jar`)
- **Frontend :** React.js (Vite)
- **Base de données :** MySQL
- **Conteneurisation :** Docker, Docker Compose

---

## ⚙️ Instructions de build et d’exécution locale ✅

### 1. Cloner le projet
```bash
git clone https://github.com/kossidev/flag-guessing-game.git
cd flag-guessing-game
```

### 2. Lancer l'application avec Docker Compose
```bash
docker compose up --build
```

> Le fichier `.jar` situé dans `Backend/` est utilisé directement pour lancer le service backend.

### 🔗 Accès à l'application :
- Frontend : `http://localhost:3000`
- API Backend : `http://localhost:8080`

---

## 📦 Lien vers l’image Docker (Docker Hub) ✅

🔗 [https://hub.docker.com/r/kossidev/flag-guessing-game](https://hub.docker.com/r/kossidev/flag-guessing-game)

---

## 🧰 Commandes utiles ✅

### Démarrer l’application
```bash
docker compose up --build
```

### Arrêter l’application
```bash
docker compose down
```

### Nettoyer tous les conteneurs et volumes
```bash
docker compose down -v
```

---

## 👨‍💻 Auteur(s) / Équipe ✅

- **Nom :** Kossi Dev
- **Email :** kossi.dev@example.com
- **GitHub :** [https://github.com/kossidev](https://github.com/kossidev)

---

## 📝 Licence

Ce projet est sous licence MIT.
