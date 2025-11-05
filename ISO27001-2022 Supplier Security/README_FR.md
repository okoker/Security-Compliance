# Auto-évaluation de Cybersécurité pour Fournisseurs ISO 27001:2022

Un outil d'évaluation HTML complet et autonome permettant aux fournisseurs d'évaluer et de documenter leur niveau de maturité en cybersécurité conformément aux normes ISO 27001:2022.

## Aperçu

Cet outil permet aux fournisseurs de compléter une auto-évaluation détaillée de cybersécurité couvrant 10 domaines de sécurité clés avec 39 questions. L'évaluation est enregistrée localement sous forme de fichier HTML qui peut être rouvert, modifié et partagé par e-mail.

## Caractéristiques Principales

- **Fichier HTML autonome** - Aucun serveur, base de données ou connexion Internet requis
- **Suivi automatique de la progression** - Barre de progression visuelle mise à jour lors de la réponse aux questions
- **Notation de maturité en temps réel** - Calcul instantané du score basé sur vos réponses
- **Persistance des réponses** - Enregistre les réponses directement dans le fichier HTML lors du téléchargement
- **Réouverture et modification** - Peut rouvrir et modifier les réponses avant la soumission finale
- **Support multilingue** - Disponible en anglais, espagnol, français et allemand

## Guide Rapide pour les Fournisseurs

### Étape 1 : Ouvrir l'Évaluation
1. Téléchargez le fichier `supplier-cybersecurity-assessment.html`
2. Double-cliquez sur le fichier pour l'ouvrir dans votre navigateur web
3. L'évaluation s'ouvrira hors ligne - aucune connexion Internet nécessaire

### Étape 2 : Compléter les Informations de l'Entreprise
Remplissez les champs requis en haut :
- Nom de l'Entreprise
- Personne de Contact
- Adresse E-mail
- Numéro de Téléphone
- Date d'Évaluation (remplie automatiquement avec la date du jour)

### Étape 3 : Répondre aux Questions de Sécurité
L'évaluation couvre 10 domaines de sécurité :
1. Politique et Gouvernance de la Sécurité de l'Information
2. Gestion des Actifs
3. Contrôle d'Accès
4. Protection des Données
5. Sécurité Physique et Environnementale
6. Sécurité des Opérations
7. Sécurité Réseau
8. Gestion des Incidents
9. Continuité des Activités
10. Conformité et Surveillance

Pour chaque question, sélectionnez votre niveau de maturité :

| Niveau | Points | Description |
|--------|--------|-------------|
| **Non Implémenté** | 0 | Contrôle non mis en place |
| **Partiellement Implémenté** | 1 | Contrôle partiellement mis en place, application incohérente |
| **Implémenté** | 3 | Contrôle mis en place et appliqué de manière cohérente |
| **Entièrement Mature** | 5 | Contrôle entièrement intégré, surveillé et continuellement amélioré |
| **Non Applicable** | N/A | La question ne s'applique pas à votre organisation |

### Étape 4 : Suivre Votre Progression
- La barre de progression affiche le pourcentage d'achèvement (basé sur les questions répondues)
- Le score se met à jour automatiquement lors de la réponse aux questions
- Visualisez votre score de maturité actuel en temps réel

### Étape 5 : Enregistrer Votre Évaluation
1. Cliquez sur le bouton **"💾 Enregistrer l'Évaluation sur le Disque"** en bas
2. Votre navigateur téléchargera un fichier nommé : `security_assessment-[votreentreprise]-[date].html`
3. Le fichier contient toutes vos réponses et peut être rouvert plus tard

### Étape 6 : Réviser ou Modifier (Optionnel)
1. Localisez le fichier enregistré dans votre dossier Téléchargements
2. Double-cliquez pour le rouvrir dans votre navigateur
3. Toutes vos réponses précédentes seront affichées
4. Apportez les modifications nécessaires
5. Cliquez à nouveau sur **"💾 Enregistrer l'Évaluation sur le Disque"** pour enregistrer la version mise à jour
6. Note : La date dans le nom du fichier sera mise à jour pour refléter quand vous l'avez enregistré pour la dernière fois

### Étape 7 : Soumettre au Client
1. Envoyez par e-mail le fichier HTML final enregistré à votre contact client
2. Ils peuvent l'ouvrir dans n'importe quel navigateur pour examiner vos réponses
3. Votre score de maturité sera visible dans le document

## Système de Notation

### Calcul du Score
- **Score maximum possible :** 195 points (39 questions × 5 points chacune)
- **La notation est cumulative :** Votre score total est la somme de toutes les questions répondues
- **Les réponses "Non Applicable"** ne contribuent pas au score

### Niveaux de Maturité

| Plage de Score | Niveau de Maturité | Description |
|----------------|-------------------|-------------|
| **0** | Aucune Évaluation | Évaluation non commencée |
| **1-50** | Initial | Améliorations significatives nécessaires |
| **51-100** | En Développement | Pratiques de sécurité de base en place |
| **101-150** | Défini | Bonnes pratiques de sécurité établies |
| **151-195** | Optimisé | Pratiques de sécurité matures |

## Détails Techniques

### Convention de Nommage des Fichiers
Les fichiers enregistrés suivent ce format :
```
security_assessment-nomentreprise-AAAA-MM-JJ.html
```
- Le nom de l'entreprise est tronqué à 12 caractères maximum
- La date se met à jour automatiquement à chaque enregistrement
- Exemple : `security_assessment-monentrepr-2025-11-05.html`

### Compatibilité des Navigateurs
- ✅ Chrome/Edge (recommandé)
- ✅ Firefox
- ✅ Safari
- ✅ Tous les navigateurs modernes

### Confidentialité et Sécurité des Données
- **Aucune donnée n'est transmise** - Tout reste sur votre ordinateur
- **Pas de suivi** - Pas d'analyse ni de connexions externes
- **Entièrement hors ligne** - Fonctionne sans Internet
- **Vous contrôlez le fichier** - Vous décidez quand et comment le partager

## Support

Pour des questions ou des problèmes :
- Vérifiez que vous utilisez un navigateur web moderne
- Assurez-vous que JavaScript est activé dans votre navigateur
- Vérifiez que vous avez la permission de télécharger des fichiers
- Essayez d'ouvrir le fichier dans un autre navigateur si des problèmes surviennent

## Licence

Cet outil est fourni tel quel à des fins d'évaluation de la sécurité des fournisseurs.

---

**Version :** 2.0  
**Dernière Mise à Jour :** Novembre 2025  
**Cadre de Conformité :** ISO 27001:2022
