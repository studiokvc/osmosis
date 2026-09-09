# Parcours français — Osmosis

## 1. Finalité
Osmosis est un DEX Cosmos avec pools, liquidité concentrée et gouvernance on-chain.

## 2. Architecture
Modules Cosmos SDK, Keepers, pools GAMM, concentrated-liquidity et superfluid staking.

## 3. Swap
Le routeur sélectionne les pools, applique les frais et vérifie les limites de prix.

## 4. Liquidité
Les positions représentent une exposition à l’invariant et aux variations de prix.

## 5. Sécurité
Contrôler permissions, paramètres de pool, arrondis et appels intermodules.

## 6. Gouvernance
Les paramètres économiques sont modifiés par propositions et votes.

## 7. Erreurs fréquentes
Slippage trop faible, route invalide, pool désactivé ou décalage de décimales.

## 8. Lecture du code
Lire x/gamm, x/concentrated-liquidity, le routeur puis les tests.

## 9. Exploitation
Suivre liquidité, volumes, frais, positions et événements de gouvernance.

## 10. Glossaire
Keeper, pool, tick, position, route, slippage et IBC.

Parcours documentaire : aucun test ni déploiement exécuté.
