# 🌿 Plant Disease Detection — Frontend

> Interface web pour le système de détection de maladies des plantes.  
> Projet académique — ESTM Dakar | L3 Réseaux & Télécommunications

---

## 📌 Description

Interface utilisateur qui permet d'envoyer des images de plantes et d'afficher le diagnostic retourné par l'**API Flask backend**. Servie via un serveur Flask léger qui communique avec le backend sur le port 5000.

---

## ⚙️ Stack technique

| Composant | Technologie |
|-----------|------------|
| Serveur frontend | Python / Flask |
| Interface | HTML / React |
| Communication | API REST (fetch vers backend:5000) |

---

## 📁 Structure du projet

```
-en avant/
├── app.py            # Serveur Flask — sert index.html sur port 3000
├── index.html        # Interface utilisateur
└── requirements.txt  # Dépendances Python
```

---

## 🚀 Installation & lancement

### Prérequis
- Python 3.9+
- Le **backend** doit tourner sur `http://localhost:5000`

### Installer les dépendances
```bash
pip install -r requirements.txt
```

### Lancer l'interface
```bash
python app.py
```
Interface disponible sur `http://localhost:3000`

---

## 🔗 Repos liés

- ⚙️ **Backend API Flask + YOLO** → [`-backend`](https://github.com/ndeyematy-web/-backend)
- 📷 **Firmware ESP32-CAM** → [`-firmware`](https://github.com/ndeyematy-web/-firmware)

---

## 👩‍💻 Auteure

**Ndèye Maty Gueye** — L3 Réseaux & Télécommunications, ESTM Dakar  
[![Email](https://img.shields.io/badge/Email-ndeyematygueye5%40gmail.com-blue?style=flat&logo=gmail)](mailto:ndeyematygueye5@gmail.com)

---

> Projet réalisé dans le cadre du cursus académique ESTM — 2025/2026
