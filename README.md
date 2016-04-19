FLVM website content
====================

Tout le contenu texte est sous licence [Creative Commons BY SA](http://creativecommons.org/licenses/by-sa/4.0/deed.fr)

## Markdown
Le contenu est formaté avec la syntaxte [Markdown](https://fr.wikipedia.org/wiki/Markdown).

## Images
Les images accompagnant les texte doivent avoir une dimension maximum **`648px`** de large, elles doivent être enregisrée au format **PNG** ou **JPG**.

Les images de sections (sur le coté de la page) doivent avoir une dimension de **`360px`** de large.

Les images de couverture doivent au format **`1600 × 780`** (ratio `0.49`).

## Heroes
Les contenu *heroes* sont affichée sur la page d'accueil avec une image plein écran. Les contenu sont gérés dans le dossier `content/heroes`.

De nouveaux *heroes* peuvent être créer, mais un seul sera affiché (le premier par ordre alpahbétique). L'image de couverture du *hero* doit être placé dans le dossier `covers` et doit être mentionné dans la *zone meta* du fichier de contenu.

Par exemple : 

Pour le *hero* Les petites toques, (`content/heroes/1_les-petites-toques.md`), la couverture est placé dans le dossier `covers` (`content/heroes/covers/les-petites-toques.jpg`), et en fait mention dans la *zone meta* de cette manière (à la 2e ligne) : 

	title: Laisse ton cartable et mets ton tablier&nbsp;!
	cover: les-petites-toques.jpg
	---

	Viens me retrouver après la classe, à partir de 17h du lundi au vendredi.
	Nous apprendrons ensemble trucs et astuces de pâtissier et cuisinier !

