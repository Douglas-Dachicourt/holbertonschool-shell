EXPLICATIONS DES TACHES REALISEES POUR CE PROJET 

* PROJET O- ALIAS:
  *Enonce : Creer un script permettant de generer un alias portant le nom 'ls' et qui effectue la fonction suivante : 'rm *' 
  -> Solution : on cree l'alias à l'aide de la commande 'alias' suivi d'un espace et du nom voulu 'ls' , on égalise le tout avec le signe      '=' puis on renseigne la commande que l'on souhaite, ici : 'rm *' avec deux simples quotes.

* PROJET 1- HELLO YOU:
  *Enonce : Creer un scrip qui affiche un message d'accueil avec le nom de l'utilisateur du systeme actuel sous le format : 'hello user'*
  -> Solution : on affiche le resultat souhaite grace a l'expression/commande 'echo' suivi du message souhaite, ici 'hello $USER'.
  USER est une variable deja connu de notre systeme. C'est pourquoi, pour l'afficher nous utilisons simplement le '$' suivi de son nom : 
  'USER'

* PROJET 2- PATH :
  *Enonce : ajouter un dossier '/action' au PATH et afficher la globalité du chemin concerne. Faire en sorte que le dossier soit 
  affiché/consulté en dernier par le shell*
  -> Solution : on exporte le PATH avec la commande 'export' pour pouvoir le modifier: 'export PATH'. Pour pouvoir le modifier, on egalise 
  cet export grace au signe '=' puis on utilise le symbole '$' puis PATH. On ajoute le dossier grace au caractere ':' puis le dossier 
  '/action'.

* PROJET 3- PATHS :
  *Enonce : Creer un script qui permet de compter le nombre de dossiers dans le chemin 'PATH'*
  
  
