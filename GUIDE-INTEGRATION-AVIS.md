# 📋 Guide d'Intégration - Section d'Avis Clients Grupo Ecocorum

## 📁 Fichiers créés

1. **customer-reviews-section.html** - Fichier HTML complet pour prévisualisation
2. **elementor-reviews-widget.html** - Code optimisé pour Elementor (À UTILISER)

---

## 🚀 Comment intégrer dans Elementor

### Étape 1 : Accéder à la page d'accueil
1. Connectez-vous au tableau de bord WordPress
2. Allez dans **Pages** → Trouvez votre page d'accueil
3. Cliquez sur **Modifier avec Elementor**

### Étape 2 : Ajouter le widget HTML
1. Dans Elementor, trouvez l'endroit où vous voulez ajouter la section d'avis
2. Cliquez sur le bouton **+** pour ajouter un nouveau widget
3. Cherchez le widget **HTML** dans la barre de recherche
4. Glissez-déposez le widget **HTML** à l'emplacement souhaité

### Étape 3 : Copier-coller le code
1. Ouvrez le fichier **elementor-reviews-widget.html**
2. Sélectionnez TOUT le contenu (Ctrl+A ou Cmd+A)
3. Copiez le code (Ctrl+C ou Cmd+C)
4. Retournez dans Elementor
5. Collez le code dans la zone de texte du widget HTML
6. Cliquez sur **Mettre à jour** ou **Publier**

---

## 🎨 Personnalisation

### Modifier les couleurs

Pour changer la couleur principale (actuellement orange) :
- Cherchez `#e67e22` dans le code et remplacez par votre couleur
- Cherchez `#d35400` et remplacez également

### Modifier les statistiques

Dans le code HTML, cherchez cette section :
```html
<div class="stat-item">
    <span class="stat-number">4.8</span>
    <div class="stat-label">⭐ Valoración media</div>
</div>
```

Modifiez les valeurs selon vos statistiques réelles.

### Ajouter/Modifier des avis

Dans la section JavaScript, cherchez `const reviews = [...]` et modifiez :

```javascript
{
    name: "Nom du client",
    location: "Ville",
    rating: 5,  // Note de 1 à 5
    text: "Texte de l'avis...",
    product: "Nom du produit",
    date: "Hace X días/semanas/meses"
}
```

### Modifier le bouton CTA

Cherchez cette ligne dans le HTML :
```html
<a href="#productos" class="cta-button">Ver nuestros productos</a>
```

Changez :
- `#productos` → L'URL de destination
- Le texte du bouton si nécessaire

---

## 🎯 Fonctionnalités incluses

✅ **Design responsive** - S'adapte parfaitement aux mobiles et tablettes
✅ **Animations au scroll** - Apparition progressive des cartes
✅ **Effets hover** - Interaction au survol des cartes
✅ **Système d'étoiles** - Notation visuelle de 1 à 5 étoiles
✅ **Avatars colorés** - Initiales des clients avec dégradés
✅ **Statistiques clés** - Mise en avant des chiffres importants
✅ **100% personnalisable** - Tous les textes et couleurs modifiables

---

## 📱 Aperçu des éléments

### Structure de la section :
1. **En-tête** - Titre et sous-titre
2. **Statistiques** - 3 indicateurs clés (note moyenne, clients, recommandation)
3. **Grille d'avis** - 6 cartes d'avis clients
4. **Bouton CTA** - Appel à l'action vers vos produits

### Informations affichées par avis :
- Avatar avec initiales
- Nom du client
- Localisation (ville)
- Note en étoiles (1-5)
- Texte de l'avis
- Produit concerné
- Date de l'avis

---

## 🔧 Dépannage

### Le code ne s'affiche pas
- Vérifiez que vous utilisez bien le widget **HTML** d'Elementor
- Assurez-vous d'avoir copié TOUT le code du fichier

### Les animations ne fonctionnent pas
- Rafraîchissez la page (Ctrl+F5)
- Vérifiez qu'il n'y a pas de conflits avec d'autres scripts

### Le design est cassé
- Vérifiez que le code CSS (entre `<style>` et `</style>`) est bien présent
- Assurez-vous qu'aucun CSS de votre thème n'interfère

### Pour tester en local
- Ouvrez le fichier **customer-reviews-section.html** dans votre navigateur
- Cela vous permettra de voir le rendu avant l'intégration

---

## 💡 Conseils d'utilisation

1. **Avis authentiques** - Remplacez les avis fictifs par de vrais témoignages clients
2. **Photos réelles** - Si possible, demandez des photos à vos clients (modifiez le code pour les avatars)
3. **Mise à jour régulière** - Ajoutez de nouveaux avis périodiquement
4. **Statistiques réelles** - Utilisez vos vraies données pour plus de crédibilité
5. **Appel à l'action** - Dirigez vers vos produits les plus vendus

---

## 📞 Besoin d'aide ?

Si vous avez des questions ou besoin d'assistance pour :
- Modifier le design
- Ajouter des fonctionnalités
- Intégrer avec un système d'avis existant (Google Reviews, Trustpilot, etc.)
- Personnaliser davantage le code

N'hésitez pas à demander !

---

## 📝 Notes importantes

- Ce code est **autonome** - il n'a besoin d'aucune bibliothèque externe
- Compatible avec **tous les navigateurs modernes**
- **Optimisé SEO** - Structure HTML sémantique
- **Léger** - Pas de dépendances, chargement rapide
- **RGPD friendly** - Pas de collecte de données

---

Bonne intégration ! 🚀🔥
