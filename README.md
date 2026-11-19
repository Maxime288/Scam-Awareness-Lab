# 🛡️ Scam Awareness Lab — L'arnaque au faux technicien

Projet pédagogique de **sensibilisation à la cybersécurité** : une reproduction statique d'une fausse alerte « Windows verrouillé », utilisée dans les arnaques au faux support technique, afin d'apprendre à la reconnaître et à réagir correctement.

> ⚠️ **Projet strictement éducatif.** Cette page n'a aucun lien avec Microsoft. Elle ne collecte aucune donnée, n'exécute aucun script et ne doit jamais être mise en ligne ni envoyée à un tiers pour le tromper.

---

## 🎯 Objectifs

- Comprendre le fonctionnement d'une arnaque au faux technicien (*tech support scam*).
- Identifier les techniques de manipulation utilisées : peur, urgence, fausse autorité.
- Savoir quels réflexes adopter si l'on tombe sur ce type de message.
- Servir de support de démonstration pour des ateliers de prévention.

---

## 🎭 Le scénario

Un internaute navigue sur le web et voit soudainement s'afficher en plein écran un faux message bleu, imitant un écran d'erreur Windows :

1. Un message alarmiste annonce que l'ordinateur est « verrouillé » et infecté.
2. Une liste de données « à risque » (identifiants, carte bancaire, fichiers) crée la panique.
3. Une consigne interdit de redémarrer : c'est le piège, car **redémarrer résout le problème**.
4. Un numéro de « support » invite la victime à appeler.
5. Au téléphone, un faux technicien demande une prise en main à distance ou un paiement.

---

## 🔍 Comment reconnaître l'arnaque (indices présents dans la page)

| Indice | Pourquoi c'est suspect |
|---|---|
| Message plein écran dans le navigateur | Windows n'affiche jamais d'alerte de ce type dans une page web |
| Numéro de téléphone « gratuit » | Microsoft n'affiche jamais de numéro d'urgence dans une alerte |
| « Ne redémarrez pas » | Technique pour empêcher la victime de fermer la fenêtre |
| Vocabulaire alarmiste (virus, espion, données à risque) | Provoque la peur pour couper la réflexion |
| Lien imitant un domaine officiel | Les liens et QR codes d'une fausse alerte ne sont pas fiables |
| Absence de vrai code d'erreur | « SPYWARE » n'est pas un vrai code d'arrêt Windows |

---

## ✅ Les bons réflexes

1. **Ne pas appeler** le numéro affiché.
2. **Ne pas cliquer** sur les liens ni scanner de QR code issu de l'alerte.
3. **Fermer le navigateur** (Alt + F4, ou le gestionnaire des tâches : Ctrl + Maj + Échap) ou **redémarrer** l'ordinateur.
4. **Ne jamais installer** de logiciel de prise en main à distance à la demande d'un inconnu.
5. **Lancer une analyse antivirus** si un doute subsiste.
6. En cas d'appel déjà passé ou de paiement effectué : **changer ses mots de passe**, **faire opposition à sa carte bancaire** et **signaler** l'arnaque.

### 📞 Où signaler

- [Cybermalveillance.gouv.fr](https://www.cybermalveillance.gouv.fr) : assistance et prévention
- [Signal Spam](https://www.signal-spam.fr) et [Internet-signalement.gouv.fr](https://www.internet-signalement.gouv.fr) : signalement de contenus frauduleux
- **17** ou le service de plainte en ligne **THESEE** : escroquerie sur Internet
- **Banque** : en cas de paiement effectué

---

## 📁 Structure du projet

```
Scam-Awareness-Lab/
├── index.html      # Page de simulation
├── style.css       # Mise en forme
├── images/
│   └── qrcode.png  # QR code de sensibilisation
└── README.md
```

Aucune dépendance : HTML et CSS uniquement.

---

## 🚀 Utilisation (en local uniquement)

```bash
git clone https://github.com/Maxime288/Scam-Awareness-Lab.git
cd Scam-Awareness-Lab
```

Ouvrez ensuite `index.html` dans un navigateur, ou lancez un serveur local :

```bash
python -m http.server 8000
# puis http://localhost:8000
```

### Cadre d'utilisation recommandé

- Présentation commentée lors d'un atelier ou d'une démonstration.
- Toujours **annoncer qu'il s'agit d'une simulation** avant de montrer la page.
- Ne jamais la déployer sur un hébergement public ni la partager sans explication à des personnes non averties.

---

## 🔒 Éthique et responsabilité

- Le contenu reproduit l'apparence d'une arnaque connue **à des fins de prévention uniquement**.
- Le numéro de téléphone affiché doit être **fictif** et ne rattacher aucune personne réelle.
- Les marques citées (Windows, Microsoft, Facebook) appartiennent à leurs propriétaires et sont mentionnées à titre de dénonciation de l'usurpation.
- L'auteur décline toute responsabilité en cas d'usage détourné.

---

## 🧰 Technologies

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

---

## 👤 Auteur

**Maxime Fau** — [@Maxime288](https://github.com/Maxime288)
Projet réalisé dans le cadre d'une formation vers le titre professionnel **Administrateur d'Infrastructures Sécurisées (AIS)**.

## 📄 Licence

Projet à usage pédagogique. Réutilisation autorisée pour la sensibilisation, sans usage malveillant.
