# 🎲 Jeu de Grundy - Multijoueur & IA  

Ce projet a été réalisé en collaboration avec un autre étudiant de l'**IUT de Vannes**. Il propose une implémentation complète du **jeu de Grundy** avec plusieurs modes de jeu :  

- 🆚 **Joueur vs Joueur**  
- 🤖 **Joueur vs IA**  
- 🤖🤖 **IA vs IA**  

---

## 📖 Règles du Jeu de Grundy  

Le jeu de Grundy se joue avec un seul tas de bâtons :  

1. Un joueur doit choisir un tas contenant au moins deux bâtons.  
2. Il divise ce tas en deux sous-tas de tailles différentes.  
3. Les sous-tas doivent contenir un nombre entier et positif de bâtons.  
4. Le joueur suivant joue à son tour en répétant l'opération.  
5. Le joueur qui ne peut plus jouer (c'est-à-dire lorsqu'il ne reste que des tas de 1 bâtons) **perd** la partie.  

Le jeu nécessite stratégie et anticipation pour forcer l'adversaire dans une position perdante ! 💡  

---

## 📂 Fichiers du projet  

- **`grundy_Mathéo_gastel_Ervenn_rannou.ipynb`** → Notebook Jupyter contenant l'implémentation complète du jeu 🧠  

---

## 🛠️ Utilisation  

1. Ouvrez **`grundy_game.ipynb`** dans **Jupyter Notebook** ou un autre environnement compatible 💻.  
2. Choisissez le mode de jeu souhaité :  
   - **Joueur vs Joueur** 🆚 ( **PartieJvJ()** ) 
   - **Joueur vs IA** 🤖  ( **PartieJvIA()** ) 
   - **IA vs IA** 🤖🤖  ( **PartieIAvIA()** ) 
3. Lancez la partie et testez vos compétences en stratégie ou observez les décisions de l'intelligence artificielle 🧠.  

---

🎯 **Fonctionnement de l'IA** : C'est une IA par renforcement, c'est à dire qu'elle va commencer par des coups aléatoires puis s'améliorer au fur et à mesure qu'elle perde ou qu'elle gagne.
Vous pouver modifier les valeurs de récompenses ou de défaites comme vous le souhaitez (paramètre de base récompense=2 et défaite=1)


Amusez-vous bien ! 🚀😊  
