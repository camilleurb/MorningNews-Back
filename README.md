# Morning News Backend

## Description
Ce projet est le backend de l'application Morning News. Il s'agit d'une API construite avec Express.js qui récupère directement les articles depuis un service web externe pour les fournir à l'application frontend.

## Fonctionnalités
- API pour récupérer les articles depuis un web service externe.
- Gestion des utilisateurs pour la connexion et l'authentification.

## Installation
1. Clonez le dépôt :
    ```bash
    git clone https://github.com/camilleurb/morning-news-backend.git
    ```

2. Accédez au répertoire du projet :
    ```bash
    cd morning-news-backend
    ```

3. Installez les dépendances :
    ```bash
    yarn install
    ```

4. Configurez les variables d'environnement dans un fichier `.env` en vous basant sur le fichier `.env.example`.

5. Démarrez le serveur :
    ```bash
    yarn start
    ```

## Utilisation
L'API est maintenant accessible à l'URL `https://morning-news-back-sage.vercel.app/`. Vous pouvez utiliser des outils comme ThunderClient pour tester les différentes routes et vérifier les réponses.

## Technologies utilisées
- Node.js
- Express.js
- UID2 et bcrypt pour la sécurisation des données utilisateurs 

## Contribution
Les contributions sont les bienvenues ! Si vous avez des suggestions ou des améliorations, veuillez suivre les étapes suivantes :

1. Fork le projet.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Commitez vos modifications (`git commit -m 'Add some AmazingFeature'`).
4. Poussez vers la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

## Auteur
- **Camille Urbain** - [GitHub](https://github.com/camilleurb)

## Licence
Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Remerciements
Merci d'utiliser l'API Morning News !
