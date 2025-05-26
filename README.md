# 🎯 Test immédiat de votre documentation

## ⚡ En 2 minutes chrono

### 1. Vérifiez votre structure (30 sec)
```
votre-dossier-go-docs/
├── docs.json          # ← Doit être à la racine !
├── docs/
│   ├── index.mdx
│   ├── installation.mdx
│   └── ...
└── public/
    └── logo.svg
```

### 2. Ouvrez l'aperçu local (1 min)
1. **🌐 Allez sur** : https://docs.page/preview
2. **📁 Cliquez** : "Sélectionner le répertoire"
3. **🎯 Choisissez** : Votre dossier `go-docs` (celui qui contient `docs.json`)
4. **✅ Autorisez** : L'accès au système de fichiers

### 3. Testez instantanément (30 sec)
- **👀 Voyez** votre documentation en live !
- **✏️ Modifiez** un fichier `.mdx`
- **💾 Sauvegardez** (`Ctrl+S`)
- **🔄 Observez** les changements instantanés

---

## 🛠️ Workflow de développement

### Fenêtres recommandées :
```
[Écran 1] VS Code avec vos fichiers .mdx
[Écran 2] Navigateur avec https://docs.page/preview
[Terminal] Git pour commiter vos changements
```

### Test complet :
1. **Navigation** - Testez tous les liens du sidebar
2. **Contenu** - Vérifiez l'affichage du Markdown
3. **Mobile** - Testez la responsivité (F12 → mode mobile)
4. **Logo** - Vérifiez que votre logo s'affiche

---

## 🚨 Si ça ne marche pas

### Erreur "No docs.json found"
```bash
# Vérifiez que docs.json est bien à la racine
ls -la go-docs/
# Doit voir: docs.json

# Si il est dans un sous-dossier, déplacez-le :
mv go-docs/docs/docs.json go-docs/
```

### Erreur d'autorisation
- **Actualisez** la page (F5)
- **Re-sélectionnez** le dossier
- **Essayez** en navigation privée

### Contenu qui ne se charge pas
- **Vérifiez** la syntaxe Markdown
- **Regardez** la console F12 pour les erreurs
- **Testez** avec un fichier simple d'abord

---

## ✅ Une fois que ça marche

### Vous pourrez :
- ✨ **Modifier** vos pages en temps réel
- 🎨 **Ajuster** le design et la mise en page
- 🔗 **Tester** tous vos liens internes
- 📱 **Vérifier** l'affichage mobile
- 🚀 **Développer** sans déployer

### Prochaines étapes :
1. **Terminez** votre contenu avec l'aperçu
2. **Commitez** quand vous êtes satisfait
3. **Déployez** vers docs.page/GitHub Pages
4. **Partagez** avec votre équipe !

---

**🎉 Maintenant vous développez comme un pro ! Aperçu en temps réel = productivité maximale !**