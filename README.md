# Scrap & Stars

**Scrap & Stars** est un jeu incrémental (idle game) spatial développé pour Discord. 
Plongez dans le vide sidéral, réveillez une station abandonnée et reconstruisez votre empire à partir de simples débris de ferrite.

---

##  L'Équipe
*   **Meegy-exe** : Co-Developer & Game Designer
*   **Maximo4** : Co-Developer & Game Designer

---

## Le Concept
Inspiré par l'univers de *No Man's Sky* et la mécanique addictive de *Cookie Clicker*, le jeu vous place aux commandes d'une station spatiale en ruine. 
*   **Phase 1 : Survie.** Générez manuellement de l'énergie pour stabiliser l'IA de bord.
*   **Phase 2 : Collecte.** Minez des astéroïdes pour récupérer de la poussière de ferrite.
*   **Phase 3 : Expansion.** Automatisez la récolte avec des drones et réparez les modules de la station.

---

## Structure du Projet
Le projet est propulsé par **React + Vite**.

    text
    src/
    ├── assets/          # Images, icônes et sons spatiaux
    ├── components/      # Composants React (Boutons, HUD, Log de texte)
    ├── data/            # Fichiers de configuration (Prix des items, textes de l'histoire)
    ├── hooks/           # Logique de jeu (Game Loop, timers)
    ├── App.jsx          # Cœur de l'application
    └── main.jsx         # Point d'entrée