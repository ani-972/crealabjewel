
# Stripe Backend

Ce backend utilise Express.js et Stripe pour gérer les paiements.

## Démarrage local

1. Crée un fichier `.env` avec ta clé secrète Stripe :
```
STRIPE_SECRET_KEY=sk_live_xxxxxxxx
```

2. Installe les dépendances :
```
npm install
```

3. Démarre le serveur :
```
node server.js
```

## Endpoint disponible

- `POST /create-payment-intent`
