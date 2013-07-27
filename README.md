#INSTALLATION !

Ce plugin s’installe via [package control](http://wbond.net/sublime_packages/package_control).
La procédure d’installation de package control se trouve [ici](http://wbond.net/sublime_packages/package_control/installation).

Une fois l’installation terminée, ouvrer la console de Sublime text 2 ( *Tools => Command palette* ), et sélectionnez la commande **« Add repository »**.
Il suffit maintenant d’ajouter le dépôt GitHub, dans la console en bas qui vient de s’ouvrir.

	https://github.com/phenix-factory/Sublime-SPIP

Une fois cela fait, rouvrez la console Sublime Texte ( *Tools => Command palette* ) et cherchez **« Install package »**. Ensuite, cherchez Sublime-SPIP.

Enjoy !

##SUBLIME-SPIP 0.9

* Ajoute un snippet pour les saisie (appeler via SAISIE).
* Ajoute la fonction set_request.
* Corrige <INCLURE>.
* Ajoute #FORMULAIRE_EDITER_LOGO.

##SUBLIME-SPIP 0.8.6

* Ajoute les fonctions de session SPIP: session_set et session_get.

##SUBLIME-SPIP 0.8.5

* Ajoute les paramètre à balise_img.

##SUBLIME-SPIP 0.8.4

* Ajoute le filtre |supprimer_tags.

##SUBLIME-SPIP 0.8.3

* Ajoute la find_in_path
* Modifier icone_inline pour être plus générique
* Ajoute icone_horizontale (Spip 3)
* Supprime le snippet icone_inline puisqu'il est maintenant dans le fichier php générale.


##SUBLIME-SPIP 0.8.2

* Amélioration de la gestion de l'API SQL de SPIP
* Amélioration de generer_url_ecrire

##SUBLIME-SPIP 0.8.1

* Correction d'un conflit sur le mot "BOUCLE" entre #COMPTEUR_BOUCLE/TOTAL_BOUCLE et les snippets pour créer des ... BOUCLE.

##SUBLIME-SPIP 0.8

* Corretion des paramètres des fonctions sql_.
* Correction de certaines balises.
* Ajout de #FORM dans le snippet du formulaire CVT html.
* Ajout d'un Snippet pour créer des icones admin SPIP via PHP.

##SUBLIME-SPIP 0.7

* Ajout des filtres SPIP
* Ajout de la fonction PHP get_session()
* Correction de <INCLURE>
* Correction de #NOTES
* Correction de #PS
* Correction de #SOUSTITRE et #SURTITRE
* Ajoute de #URL_PAGE
* Correction des bug des snippets LANG et formulaires

##SUBLIME-SPIP 0.6

* Ajout d'un scope pour n'afficher les balise SPIP que dans des fichier html
* Ajout de la balise #TEXTE
* Correction du snippet **spip_formCVT_php**
* Ajout de l'option redirect dans le snippet **spip_formCVT_php**

##SUBLIME-SPIP 0.5

* Ajout de sql_get_select
* Ajout de sql_fetsel
* Ajout de sql_getfetsel
* Ajout de sql_countsel
* Ajout d'un snipet "template" pour les fichiers de langue de spip: **SPIP_lang**
* Ajout de de snippet pour les formulaire CVT de spip: **spip_formCVT_html** et **spip_formCVT_php**

* Correction de sql_quote
* Correction des complétions pour les critières

##SUBLIME-SPIP 0.4

Ajout des fonction PHP

* debut_grand_cadre
* fin_grand_cadre
* recuperer_fond

* Correction du bug de debut_cadre_relief

##SUBLIME-SPIP 0.3

Correction de include_spip.
Correction de #PAGINATION

Ajout d'un snippet pour sql_fetch

Ajout de: 
* gros_titre
* debut_cadre_relief
* debut_cadre_relief
* generer_url_ecrire
* _request
* sql_select
* sql_update
* sql_updateq
* sql_quote
* \#URL_ECRIRE
* {transitteration}

##SUBLIME-SPIP 0.2

Debut du fichier pour l'auto-complétion PHP avec inclde_spip (Oui une seule fonction, j'ai la flemme)

* Ajout de la balise #COMPTEUR_BOUCLE
* Ajout des critères SPIP:
* {par }
* {inverse}
* {tout}

##SUBLIME-SPIP 0.1

* Ajoute les balises des squelettes SPIP à Sublime Text 2.
* Utiliser BOUCLE pour obtenir un squelette de boucle basique.