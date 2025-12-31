Commande pour push vos codes sur github (à faire à chaque fois que vous avez fait des modifications que vous voulez partager): 
Pour projet Clément:
git pull
git add projet_clement.ipynb && git commit -m "Description de vos changements" && git push

Pour projet Aurélie:
git pull
git add projet_aurelie.ipynb && git commit -m "Description de vos changements" && git push

Pour projet Marion:
git pull
git add projet_marion.ipynb && git commit -m "Description de vos changements" && git push


Pour le full projet:
git pull
git add projet_full.ipynb && git commit -m "Description de vos changements" && git push

ATTENTION ne pas modifier le projet_full en même temps sinon on aura des problèmes de branching


Pour récupérer les modifications des autres:
git pull


Pour run sur SCITAS
D'abord(pour 3h de run): Sinteract -a env540 -g gpu:1 -t 3:00:00
Suivit de: source scitas_venv/bin/activate && papermill ipeo_code.ipynb ipeo_code_executed.ipynb --log-output
