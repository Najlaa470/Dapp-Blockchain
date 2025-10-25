**Décentralized Marketplace DApp
**

**1. Introduction**

Ce projet vise à concevoir et mettre en œuvre une application décentralisée (DApp) simulant un système de marché numérique. L'application permet la création, la consultation et l'achat de produits via des smart contracts déployés sur une blockchain Ethereum locale, simulée avec Ganache.

Il utilise des outils comme Solidity, Truffle, Ganache, React.js et Web3.js pour le front-end et l'interaction avec les contrats intelligents.

**2. Objectifs du projet**

Développer un contrat intelligent sécurisé pour la gestion de produits (création, achat, transfert de propriété). Implémenter une interface web permettant une interaction transparente avec la blockchain. Déployer et tester l'application en environnement local. Comprendre le cycle de vie complet d'une DApp, du contrat à l'intégration front-end.

**3. Environnement et outils utilisés**

Les outils principaux incluent Solidity pour l'écriture des contrats, Truffle pour le développement et le déploiement, Ganache pour la blockchain locale, MetaMask pour la simulation utilisateur, Web3.js pour l'interaction avec la blockchain, et React.js pour l'interface utilisateur.

**4. Conception et développement**

L'architecture repose sur une couche smart contracts (noyau métier) écrite en** Solidity** et déployée via **Truffle** sur un **réseau Ganache.** Le contrat principal, ProductMarketplace.sol, définit la structure d'un produit et inclut les fonctions de base pour la vente et l'achat.

Le front-end, développé avec **React.js**, permet aux utilisateurs d'interagir avec le contrat via **Web3.js**. Les vendeurs peuvent créer des produits, les acheteurs peuvent les consulter et effectuer des achats en Ether via **MetaMask**. Le contrat gère le transfert de fonds et marque les produits comme vendus.

Un backend optionnel **Node.js/Express** peut être ajouté pour la sauvegarde hors chaîne, l'authentification centralisée ou l'exposition d'API REST.

**5. Résultats et tests**

L'application fonctionne correctement en local. Les tests confirment que les vendeurs peuvent créer des produits, que les transactions sont exécutées avec transfert d'Ether, et que les produits sont bien marqués comme vendus après achat. Les événements blockchain permettent de reconstituer l'historique des ventes.
