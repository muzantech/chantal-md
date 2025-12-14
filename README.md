<p align="center">
  <img src="https://files.catbox.moe/gpsy0t.jpg" width="200" height="200" alt="CHANTAL MD">
</p>

<h1 align="center">✨ CHANTAL MD ✨</h1>

<p align="center">
  <b>Bot WhatsApp Multi-Fonctions</b><br>
  <i>Powered by MUZAN SIGMA</i>
</p>

<p align="center">
  <a href="#installation">Installation</a> •
  <a href="#commandes">Commandes</a> •
  <a href="#configuration">Configuration</a> •
  <a href="#faq">FAQ</a>
</p>

---

## 🚀 Installation

### Prérequis

- [Node.js](https://nodejs.org/) v18 ou supérieur
- [FFmpeg](https://ffmpeg.org/) (pour les médias)
- [Git](https://git-scm.com/)

### Installation rapide

```bash
# 1. Cloner le projet
git clone https://github.com/muzantech/chantal-md.git
cd chantal-md

# 2. Installer les dépendances
npm install

# 3. Lancer le bot
npm start
```

### Premier lancement

1. **Démarrez le bot** avec `npm start`
2. **Scannez le QR code** avec WhatsApp → Paramètres → Appareils connectés
3. **Envoyez `.addowner`** dans n'importe quel chat
4. **C'est prêt !** Vous êtes propriétaire du bot 🎉

---

## 📱 Commandes

### Menu Principal
| Commande | Description |
|----------|-------------|
| `.menu` | Afficher tous les menus |
| `.menu ai` | Menu Intelligence Artificielle |
| `.menu download` | Menu Téléchargement |
| `.menu sticker` | Menu Stickers |
| `.menu group` | Menu Groupes |
| `.menu owner` | Menu Propriétaire |

### Commandes Owner
| Commande | Description |
|----------|-------------|
| `.myid` | Voir votre identifiant |
| `.addowner` | Devenir propriétaire |
| `.addowner [id]` | Ajouter un propriétaire |
| `.delowner [id]` | Supprimer un propriétaire |
| `.listowner` | Liste des propriétaires |
| `.setup` | Configuration guidée |

### Commandes Groupes
| Commande | Description |
|----------|-------------|
| `.kick @user` | Expulser un membre |
| `.kickall` | Expulser tous les non-admins |
| `.promote @user` | Promouvoir en admin |
| `.demote @user` | Rétrograder un admin |
| `.linkgc` | Obtenir le lien du groupe |
| `.tagall` | Mentionner tout le monde |

### Téléchargement
| Commande | Description |
|----------|-------------|
| `.play [titre]` | Télécharger musique YouTube |
| `.ytmp4 [url]` | Télécharger vidéo YouTube |
| `.tiktok [url]` | Télécharger vidéo TikTok |
| `.ig [url]` | Télécharger post Instagram |

### Stickers
| Commande | Description |
|----------|-------------|
| `.sticker` | Créer un sticker (répondre à une image) |
| `.toimg` | Convertir sticker en image |
| `.tomp4` | Convertir sticker en vidéo |

---

## ⚙️ Configuration

### Configuration rapide via WhatsApp

Envoyez `.setup` au bot pour une configuration guidée.

### Configuration manuelle

Modifiez le fichier `settings.js` :

```javascript
// Votre numéro (sera owner automatiquement)
global.owner = ["votre_numero"];

// Informations du bot
global.info = {
    nomorbot: "0",
    namabot: "CHANTAL MD",
    nomorowner: "votre_numero",
    namaowner: "votre_nom"
}
```

---

## 🔌 Système de Plugins

CHANTAL MD supporte les plugins externes !

### Installer un plugin
```
.plugin install https://exemple.com/plugin.js
```

### Lister les plugins
```
.plugin list
```

### Supprimer un plugin
```
.plugin remove nom_plugin
```

---

## ❓ FAQ

### Le bot ne répond pas ?
- Vérifiez que le bot est connecté (session active)
- Vérifiez que vous êtes owner (`.listowner`)
- Redémarrez le bot

### Comment devenir owner ?
1. Envoyez `.myid` pour voir votre ID
2. Envoyez `.addowner` pour vous ajouter

### Le QR code ne s'affiche pas ?
- Supprimez le dossier `sessions/`
- Relancez le bot

### Comment ajouter un autre owner ?
```
.addowner 33612345678
```

---

## 📞 Support

- **WhatsApp Channel** : [CHANTAL MD](https://whatsapp.com/channel/0029VbBIAP58KMqoJluW8r06)

---

## 📜 Licence

Ce projet est sous licence GPL-3.0. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

<p align="center">
  <b>⭐ N'oubliez pas de mettre une étoile si ce projet vous plaît ! ⭐</b>
</p>

<p align="center">
  <i>Powered by MUZAN SIGMA</i>
</p>

