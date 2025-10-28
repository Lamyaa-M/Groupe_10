Pour exécuter le scrapping :
python3 1_scrap_site_spa.py
temps de scrapping: 1m29 (pour collecter tous les données)


Pour l'API: (la clé API doit être ajoutée au code) 
python3 2_api_csv.py
==> Objectif: avoir des catégories à partir de la description 


Pour séparer les listes des catégories: 
python3 3_csv_mots_clés_séparés.py
==> Objectif: séparer la liste des catégories créée à partir de l'API pour avoir que les mots clés au lieu de la liste

Pour le CSV final:
python3 4_csv_final.py
==> Objectif: recatégoriser le résultat de l'API en grande catégorie pour avoir une analyse claire


==> Le CSV obtenu ne sera pas le même que le notre puisque notre fichier ne se met pas à jour 
