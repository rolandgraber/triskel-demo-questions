# Triskel Demo Questions

Application de gestion de questions pour site.triskel.ch/demo

## Installation

```bash
npm install
```

## Développement

```bash
# Démarrer le serveur de développement
npm run dev

# Compiler le CSS (dans un autre terminal)
npm run build:css
```

## Structure des fichiers JSON

Chaque sujet est stocké dans un fichier JSON distinct dans le dossier `src/data/topics/`.

Exemple de structure d'un sujet :

```json
{
  "title": "Titre du sujet",
  "slug": "titre-du-sujet",
  "description": "Description du sujet",
  "isOpen": true,
  "questions": [
    {
      "id": "1",
      "name": "Nom de l'utilisateur",
      "question": "Texte de la question",
      "timestamp": "2025-02-23T08:00:00Z",
      "visible": true
    }
  ]
}
```