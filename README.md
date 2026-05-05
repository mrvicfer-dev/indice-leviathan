# L'Indice Léviathan

Baromètre trimestriel mondial de l'avancée vers le contrôle étatique total.

**Par Victor Ferry** — [Patreon](https://patreon.com/VictorFerry)

## Structure du site

```
/
├── index.html              ← Page principale
├── methodologie.pdf        ← Document méthodologique
├── bulletins/
│   ├── indice-leviathan-Q1-2026.pdf
│   └── ...                 ← Ajouter les nouveaux bulletins ici
└── README.md
```

## Ajouter un nouveau bulletin

1. Déposer le PDF dans `bulletins/` avec le nom `indice-leviathan-QX-XXXX.pdf`
2. Dans `index.html`, trouver la section `bulletins-list` et ajouter un bloc `bulletin-item`
3. Mettre à jour les scores dans `#barometre` (7 cartes tentacules)
4. Mettre à jour le score hero et les signaux dans `#signaux`
5. Commit + push → GitHub Pages met à jour automatiquement

## Déployer sur GitHub Pages

1. Créer un repo GitHub (ex: `leviathan-index`)
2. Pousser tous les fichiers
3. Settings → Pages → Source : `main` branch, `/ (root)`
4. URL : `https://[username].github.io/leviathan-index`

## Score actuel — Q1 2026

**63/100 — P2 SERVITUDE — Vélocité +4,2 pts/an**
