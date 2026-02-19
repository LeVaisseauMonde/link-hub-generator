# ⬡ Page de Liens

> Créez votre page de liens personnalisée — alternative gratuite à Linktree, sans compte

[![Live](https://img.shields.io/badge/LIVE-Essayer_l'outil-c8ff00?style=flat-square&labelColor=0a0a0a)](https://levaisseaumonde.github.io/link-hub-generator/)
[![BlackCrow](https://img.shields.io/badge/BlackCrow_OS-Hub-333?style=flat-square&labelColor=0a0a0a)](https://levaisseaumonde.github.io/BlackCrow/)

---

## Fonctionnalités

- Créer une page de liens complète (bio, avatar, boutons)
- Personnaliser thème, couleurs, style des boutons
- Prévisualisation en direct desktop / mobile / tablette
- Télécharger le fichier HTML final — hébergeable n'importe où
- Sauvegarde automatique en local dans le navigateur
- Aucun compte, aucun abonnement, aucune pub

---

## Utilisation

1. Ouvrir [l'outil](https://levaisseaumonde.github.io/link-hub-generator/)
2. Renseigner nom, bio, avatar
3. Ajouter vos liens
4. Choisir le thème et le style
5. Télécharger votre page HTML

La page générée est un fichier HTML standalone — hébergeable sur GitHub Pages, Netlify, ou n'importe quel hébergeur.

---

## Intégration BlackCrow OS

Cet outil fait partie de la suite [BlackCrow OS](https://levaisseaumonde.github.io/BlackCrow/), l'interface système de l'univers [Le Vaisseau-Monde](https://www.vaisseau-monde.fr).

La navbar est chargée dynamiquement depuis le hub central :

```html
<div id="bc-navbar"></div>
<script>
  fetch('https://levaisseaumonde.github.io/BlackCrow/navbar.html')
    .then(r => r.text())
    .then(html => document.getElementById('bc-navbar').innerHTML = html);
</script>
```

---

## Liens

- 🌐 [vaisseau-monde.fr](https://www.vaisseau-monde.fr)
- 📺 [YouTube @VaisseauMonde](https://www.youtube.com/@VaisseauMonde)
- 🔗 [BlackCrow OS](https://levaisseaumonde.github.io/BlackCrow/)

---

*QLVVP 🖤*
