# Portfolio BTS SIO SISR

Portfolio professionnel pour présenter mes projets et ma veille technologique réalisés durant ma formation BTS SIO option SISR.

## 📋 Contenu du portfolio

- **Page d'accueil** : Présentation et compétences
- **Page Projets** : Détail de mes missions et réalisations
- **Page Veille Technologique** : Articles et analyses sur la cybersécurité
- **Page Contact** : Formulaire et informations de contact

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer un repository GitHub

1. Allez sur [GitHub](https://github.com) et connectez-vous
2. Cliquez sur le bouton "New" pour créer un nouveau repository
3. Nommez-le : `votre-username.github.io` (remplacez "votre-username" par votre nom d'utilisateur GitHub)
4. Cochez "Public"
5. Cliquez sur "Create repository"

### Étape 2 : Préparer vos fichiers

Assurez-vous d'avoir tous ces fichiers dans un même dossier :
- index.html
- projets.html
- veille.html
- contact.html
- style.css
- README.md

### Étape 3 : Pousser les fichiers sur GitHub

Ouvrez un terminal dans le dossier contenant vos fichiers et exécutez :

```bash
# Initialiser git
git init

# Ajouter tous les fichiers
git add .

# Créer le premier commit
git commit -m "Premier commit - Portfolio BTS SIO SISR"

# Lier votre repository local au repository GitHub
git remote add origin https://github.com/votre-username/votre-username.github.io.git

# Envoyer les fichiers sur GitHub
git branch -M main
git push -u origin main
```

### Étape 4 : Activer GitHub Pages

1. Allez dans votre repository sur GitHub
2. Cliquez sur "Settings" (Paramètres)
3. Dans le menu de gauche, cliquez sur "Pages"
4. Sous "Source", sélectionnez "main" branch
5. Cliquez sur "Save"

**Votre site sera accessible à l'adresse :** `https://votre-username.github.io`

Le déploiement prend généralement 1-2 minutes.

## ✏️ Personnaliser le portfolio

### Modifier vos informations

1. **Page d'accueil (index.html)** :
   - Modifiez votre nom et description
   - Ajoutez votre photo professionnelle
   - Personnalisez les compétences

2. **Page Projets (projets.html)** :
   - Remplacez les exemples par vos vrais projets
   - Dupliquez les blocs `<div class="projet-card">` pour ajouter plus de projets
   - Modifiez les dates, contextes, et réalisations

3. **Page Veille (veille.html)** :
   - Changez la thématique si vous ne travaillez pas sur la cybersécurité
   - Ajoutez vos sources de veille
   - Remplacez les articles exemples par vos vraies analyses
   - Dupliquez les blocs `<article class="veille-card">` pour plus d'articles

4. **Page Contact (contact.html)** :
   - Ajoutez votre email, téléphone
   - Mettez à jour vos liens LinkedIn, GitHub, Twitter
   - Ajoutez un lien vers votre CV

### Modifier les couleurs

Dans le fichier `style.css`, modifiez les variables au début du fichier :

```css
:root {
    --primary-color: #2563eb;      /* Couleur principale */
    --secondary-color: #1e40af;    /* Couleur secondaire */
    --accent-color: #3b82f6;       /* Couleur d'accentuation */
}
```

Vous pouvez utiliser un outil comme [Coolors](https://coolors.co) pour choisir vos couleurs.

## 📱 Responsive Design

Le portfolio est entièrement responsive et s'adapte automatiquement aux :
- 💻 Ordinateurs de bureau
- 📱 Tablettes
- 📱 Smartphones

## 🔄 Mettre à jour votre portfolio

Pour ajouter de nouveaux projets ou articles de veille :

1. Modifiez les fichiers HTML localement
2. Testez vos modifications en ouvrant index.html dans votre navigateur
3. Poussez les modifications sur GitHub :

```bash
git add .
git commit -m "Ajout d'un nouveau projet"
git push
```

Vos modifications seront en ligne dans 1-2 minutes.

## 📚 Structure des fichiers

```
portfolio/
│
├── index.html          # Page d'accueil
├── projets.html        # Page des projets
├── veille.html         # Page veille technologique
├── contact.html        # Page de contact
├── style.css           # Styles CSS
└── README.md           # Ce fichier
```

## 🎨 Fonctionnalités incluses

- ✅ Design moderne et professionnel
- ✅ Navigation intuitive
- ✅ Cartes de projets détaillées
- ✅ Section veille technologique structurée
- ✅ Formulaire de contact
- ✅ Responsive (mobile, tablette, desktop)
- ✅ Animations et effets au survol
- ✅ Optimisé pour GitHub Pages

## 💡 Conseils

1. **Mettez régulièrement à jour** votre veille (au moins 1-2 articles par mois)
2. **Documentez bien vos projets** avec des captures d'écran si possible
3. **Ajoutez votre CV** en PDF dans le repository et liez-le depuis la page contact
4. **Utilisez des vraies technologies** dans vos tags pour montrer vos compétences
5. **Rédigez en français correct** sans fautes d'orthographe

## 🔗 Liens utiles

- [Documentation GitHub Pages](https://docs.github.com/pages)
- [Markdown Guide](https://www.markdownguide.org)
- [Git - Guide simple](https://rogerdudler.github.io/git-guide/index.fr.html)

## 📝 Licence

Ce portfolio est un exemple pédagogique. Vous êtes libre de l'utiliser et de le modifier pour votre propre usage.

---

**Bon courage pour votre BTS SIO !** 🎓
