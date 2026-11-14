# 🌿 Anasthasia Fitness — Site Web Indépendant (Sans Wix)

Bienvenue dans le code source officiel du nouveau site internet de **Anasthasia Fitness**.

Ce site a été conçu pour être **100 % autonome, ultra-rapide et gratuit à héberger**, vous libérant totalement de l'abonnement mensuel Wix et de ses restrictions techniques.

---

## 📂 Architecture des Pages

Le site conserve fidèlement la structure exacte de votre plateforme originale :

* **`index.html`** : Page d'accueil officielle (Hero élégant avec citation, réassurance Hachette / Cédric Grolet / IFBB, les 3 piliers et votre histoire).
* **`philosophie.html`** : Votre vision détaillée (parcours personnel, méthode de Gasquet, Pilates, bienveillance sans privation).
* **`livre.html`** : Page dédiée au livre officiel *Body & Chef* (éditions Hachette Pratique, collaboration Cédric Grolet & Thomas Danigo, liens Fnac, Amazon, Cultura).
* **`boutique.html`** : E-shop interactif (Resistance Bands à 19,90 €, kits nomades, panier JavaScript, validation par WhatsApp ou Email).
* **`reserver.html`** : Prise de rendez-vous en ligne (coaching solo Paris, coaching duo, bilan visio, pack 10 séances).
* **`contact.html`** : Formulaire de contact direct, coordonnées complètes (Paris 15e, email, Instagram) et FAQ.

---

## 🚀 Comment publier ce site sur votre compte GitHub en 2 minutes

### Étape 1 : Créer le dépôt sur GitHub
1. Connectez-vous sur votre nouveau compte [GitHub](https://github.com).
2. Cliquez sur le bouton vert **« New »** (ou « Nouveau dépôt »).
3. Nommez votre dépôt (par exemple : `anasthasiafitness` ou `anasthasia-website`).
4. Laissez-le en **Public** et **ne cochez pas** « Add a README file » (nous en avons déjà un).
5. Cliquez sur **« Create repository »**.

### Étape 2 : Envoyer le code depuis votre Mac
Ouvrez votre Terminal et collez ces 3 lignes (en remplaçant `<VOTRE_PSEUDO>` par votre identifiant GitHub) :

```bash
cd "Downloads/Organisation réseau sociaux/site-anasthasiafitness"
git remote add origin https://github.com/<VOTRE_PSEUDO>/anasthasiafitness.git
git branch -M main
git push -u origin main
```

---

## 🌐 Comment activer l'hébergement gratuit (GitHub Pages)

Une fois le code envoyé sur GitHub :

1. Sur la page de votre dépôt GitHub, cliquez sur l'onglet **Settings** (Paramètres).
2. Dans le menu de gauche, cliquez sur **Pages**.
3. Sous **Build and deployment > Branch**, choisissez `main` puis laissez `/ (root)` et cliquez sur **Save**.
4. En quelques secondes, GitHub vous donne votre adresse web en ligne :
   `https://<VOTRE_PSEUDO>.github.io/anasthasiafitness/`

---

## 🔗 Comment connecter votre propre nom de domaine (`anasthasiafitness.com`)

Pour que votre site s'affiche sur votre vraie adresse `anasthasiafitness.com` sans payer Wix :

1. Dans les réglages **Settings > Pages** de GitHub, descendez jusqu'à **Custom domain**.
2. Tapez `www.anasthasiafitness.com` et cliquez sur **Save**.
3. Cochez la case **« Enforce HTTPS »** pour avoir le cadenas vert sécurisé gratuit.
4. Chez votre registraire de domaine (ex: OVH, Gandi, Ionos ou Google Domains), faites simplement pointer le DNS :
   * **CNAME** : `www` vers `<VOTRE_PSEUDO>.github.io`
   * **A Records** : Les 4 adresses IP de GitHub (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`).

---

## 🎨 Personnalisation & Maintenance

* **Modifier un texte ou un tarif :** Ouvrez simplement le fichier `.html` correspondant dans n'importe quel éditeur de texte et modifiez le texte.
* **Changer une photo :** Remplacez l'URL de l'image dans la balise `<img>` ou placez vos photos dans un dossier `assets/`.
* **Couleurs de la charte :**
  * Fond ivoire / lin : `#F9F8F5`
  * Or signature : `#C5A059`
  * Noir graphite : `#1A1A1A`
