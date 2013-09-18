Notebook sur la réserve parlementaire
==========
Ce projet a pour but de croiser différentes données pour mieux analyser les
données de la réserve parlementaire.

Pour l'instant, les données suivantes sont utilisées:
 * réserve parlementaire de 2011 [source](http://www.nosdonnees.fr/dataset/r-serve-parlementaire-2011-attribu-e-aux-collectivit-s-territoriales)
 * données GEOFLA de l'IGN (communes) [source](http://professionnels.ign.fr/geofla)
 * résultats des élections municipales pour les communes de plus de 3500 habs [source](http://www.data.gouv.fr/DataSet/572150?xtmc=élection%20municipale&xtcr=4)
 * activité des députés [source](http://www.nosdeputes.fr/synthese)

Usage
=====

Pour démarrer le notebook, lancer ipython:

`ipython notebook --notebook-dir notebooks --pylab inline`



TODO
====

 * ajouter les résultats des élections municipales pour les communes de moin de
   3500 habs
 * regarder si la réserve d'un député peut aller à un bénéficiaire d'un
   politique différent
 * ajouter les données de la réserve de 2012
 * ne pas traiter que les bénéficiaires de type 'commune'
 * faire une carto
