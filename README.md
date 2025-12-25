# Projet Réseaux – DNS, TCP, HTTP, HTTPS
Projet pédagogique en Python démontrant les protocoles réseau fondamentaux : DNS, TCP, HTTP et HTTPS (TLS), avec analyse du trafic via Wireshark.


## 📌 Objectif
Ce projet a pour but de comprendre le fonctionnement des communications réseau
en partant des bases (TCP) jusqu’aux protocoles applicatifs sécurisés (HTTPS),
en passant par le DNS.

---

## 📁 Contenu du projet

### 1. TCP – Client / Serveur
**Fichiers :**
- `server.py`
- `client.py`

📌 Communication TCP bas niveau avec `socket` :
- le serveur écoute sur un port
- le client se connecte
- échange de messages

---

### 2. HTTP – Serveur HTTP
**Fichier :**
- `http_server.py`

📌 Serveur HTTP simple avec `http.server` :
- gestion des requêtes GET
- réponses HTTP 200 OK
- observation du trafic avec Wireshark

---

### 3. HTTPS – Serveur sécurisé (TLS)
**Fichier :**
- `https_server.py`

📌 Ajout du chiffrement TLS avec `ssl` :
- certificat auto-signé
- connexion HTTPS sur le port 4443
- avertissement navigateur normal (certificat non reconnu)

➡️ L’erreur de confidentialité montre que TLS est bien actif.

---

### 4. DNS – Résolution de noms
**Fichier :**
- `dns_lookup.py`

📌 Traduction d’un nom de domaine en adresse IP :
- rôle fondamental du DNS
- première étape avant toute communication réseau

---

## 🔍 Outils utilisés
- Python 3
- Wireshark
- OpenSSL
- HTTP / HTTPS / TCP / DNS

---

## ✅ Conclusion
Ce projet montre la chaîne complète d’une communication réseau :

**DNS → TCP → HTTP → HTTPS**

Il permet de comprendre :
- le transport des données
- le rôle des protocoles
- la sécurité avec TLS

---

## 👤 Auteur
Ayman El Hamri
