# DataAnalysis_S2_M2MIAGE
Projet du deuxième semestre de M2 MIAGE encadré par Jenny Benois Pineau portant sur de l'anayse de données de personnes fragiles

## Architecture 
Ce projet hébergé sous Github est architecturé de la façon suivante.
* Dossier src : Contient le code source du projet
	* Dossier import : Contient tout le code concernant l'importation et la normalisation de données
	* Dossier processing : Contient tout le code concernant le traitement des données 
	* Dossier presenting : Contient tout le code concernant la presentation des données
* Dossier rsc : Contient toutes les ressources (images, code importé, son, ...) utilisées par le projet et notamment par la présentation
* Dossier doc : Contient la documentation du projet 

## Conventions de code
Ce projet est codé intégralement en Anglais et la documentation doit être faite en Français.

Au niveau du nommage des variables : 
* Les variables sont nommées en camel case : `maVariable` est donc préférable à `mavariable` ou encore `MaVariable`
* Les variables de classes sont nommées en camel case mais commencent par 'm_'; on aura donc `m_maVariableDeClasse`
* Les classes sont nommées en camel case mais en commençant par une majuscule; on aura donc `MaClasse`
* Les fonctions sont nommées en snake case; on aura donc `def ma_fonction(parametre)`
* Les méthodes (fonctions de classes) privées sont nommées en snake case et commencent par 'm_'; on aura donc `def m_ma_fonction_secrete(parametre)`
* Les variables constantes sont écrites en majuscule et les mots contenus sont séparés par des '_'; on aura donc `MA_CONSTANTE`
* Les fonctions doivent être précédées d'un fragment de code suivant les conventions du logiciel 'Doxygen' ([Documentation](https://fr.wikipedia.org/wiki/Doxygen#Les_tags_les_plus_utilis%C3%A9s))