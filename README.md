# Mapping mobility of Chinese officials between province


Je suis tombé sur le site http://chinavitae.com  qui compile le CV des hommes politiques chinois les plus importants.

Je me suis donc mis en tête de faire des cartes de réseaux à partir de ces infos, notamment pour voir si ceux qui étaient passés par Shenzhen se retrouvaient ensuite ailleurs. J'ai donc extrait les données du site China Vitae, puis essayé de constituer quelques cartes de réseaux. 
(Ce sont juste de rapides brouillons à ce stade).

Carte de la mobilité des hommes politiques chinois entre les provinces
La première ébauche de carte présente le réseau global entre les provinces :  https://app.topogram.io/topograms/PYCHNaBubGHLErZXo/view
Chaque point est une province.
Les relations entre les provinces sont : si un homme politique a exercé des fonctions dans les deux provinces (d'après son CV), cela crée un lien entre elles. 
On voit plein de cercles bizarres autour des points : ce sont les liens internes aux provinces (le lien dirige vers elle-même, puisque les transferts d'hommes politiques sont internes).

Carte de la mobilité des hommes politiques depuis/vers Shenzhen et Chengdu
Une des questions portaient sur Shenzhen. 
J'ai donc tenté de faire une carte des relations de Shenzhen : https://app.topogram.io/topograms/WhCjLGZFL5JMfEGZr/view 
Le principe est le même : un point=un lieu, un trait=une relation (l'épaisseur étant définie par le nombre de personnes impliquées dans les deux lieux).
Dans celui-ci, j'ai rajouté la bio des hommes politiques, ainsi qu'un lien vers leur CV sur China Vitae. 

On se demandait par exemple si il existait un lien entre Shenzhen et Chengdu.
Le voici : https://app.topogram.io/topograms/WhCjLGZFL5JMfEGZr/view#edge-HFPu99vTKABTBb6Nd
En fait, c'est un lien inverse puisqu'il est a fait ses études à Chengdu pour partir à Shenzhen.

Voici le même type de carte sur Chengdu : https://app.topogram.io/topograms/FS7AGfDJv8GXTtS9C/view 

Méthodo
J'ai compilé les étapes sous la forme d'un "notebook" qui mélange code et explications de la méthode : 
https://github.com/clemsos/china-political-maps/blob/master/China%20Political%20maps.ipynb 
