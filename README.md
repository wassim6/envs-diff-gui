# 🔐 Gestionnaire d'Environnements

Une application web moderne pour comparer et gérer les fichiers `.env` entre différents environnements (développement, qualification, production).

## 🌟 Fonctionnalités

- **Upload multiple** : Chargez plusieurs fichiers `.env` simultanément
- **Détection automatique** : Détection automatique des environnements basée sur les noms de fichiers
- **Comparaison visuelle** : Tableau de comparaison avec mise en surbrillance des différences
- **Édition en ligne** : Modifiez les valeurs directement dans l'interface
- **Export individuel** : Téléchargez chaque fichier `.env` modifié
- **Gestion par environnement** : Support pour dev, qal, prd et autres environnements personnalisés

## 🚀 Utilisation

1. **Sélection de fichiers** :
   - Cliquez sur la zone de dépôt ou glissez-déposez vos fichiers `.env`
   - Support pour les fichiers nommés `.env.dev`, `.env.qal`, `.env.prd`, etc.

2. **Comparaison** :
   - Visualisez toutes les variables dans un tableau comparatif
   - Les colonnes sont colorées selon l'environnement

3. **Édition** :
   - Modifiez les valeurs directement dans le tableau
   - Ajoutez de nouvelles variables avec le bouton "➕ Ajouter une variable"

4. **Export** :
   - Téléchargez des fichiers `.env` mis à jour individuellement
   - Exportez tous les environnements en une fois

## 💡 Astuces macOS

Sur macOS, les fichiers `.env` sont cachés par défaut. Pour les voir :
- Dans la boîte de dialogue : Appuyez `Cmd + Shift + .`
- Sélectionnez plusieurs fichiers à la fois

## 🛠️ Environnements supportés

- `dev` - Développement (vert)
- `qal` - Qualification (jaune)
- `prd` - Production (rouge)
- `staging` - Staging (bleu)
- `test` - Test (violet)
- `production` - Production alternative (rose)

## 📋 Prérequis

- Navigateur web moderne
- Aucun serveur requis - fonctionne entièrement côté client

## 🔒 Sécurité

Toutes les opérations se déroulent dans votre navigateur. Aucun fichier n'est envoyé sur un serveur externe.

---

*Application créée avec ❤️ en HTML/CSS/JavaScript pur*
