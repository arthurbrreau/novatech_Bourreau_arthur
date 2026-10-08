Partie 3 mission 5 : 
1 : 54dcaf2 
2 : f9eb246
3 : 6 commits 
Commande utilisée : git log --oneline --graph --all


Partie 5 mission 8 : J'ai utilisé git reset --mixed HEAD~1 pour que le commit soit annulé, que la modification soit gardée mais supprimée du staging. git reset --hard HEAD~1 aurait aussi supprimée les modifications du staging, mais les aurait supprimés du fichier de travail. 

Mission 9 : On utilise git revert plutot que reset car le commit a déja été partagé. Il esy donc préférable d'utiliser revert. 