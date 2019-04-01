Attaquer une machine c'est savoir être à la fois méthodique, procédurier mais aussi immaginatif. Une des premières approches pourrait être de se référer à la cyber kill chain. Si vous ne connaissez pas ce terme, il s'agit ni plus ni moins que d'un modèle conceptuel permettant de décrire les grandes étapes d'une attaque informatique. Ce modèle n'est pas parfait, mais pose de très bonnes bases et permet de donner un cheminement aux actions que l'on souhaite réaliser dans le cadre d'une attaque.
  
Tout d'abord, chaque test d'intrusion commence par une bonne reconnaissance de la victime. Vous devez être en mesure de répondre aux questions suivantes:
* quelle est l'adresse IP de la machine cible?  
* quels sont les ports ouverts?  
* quel est le systême d'exploitation utilisé?  
* quels sont les services exposés (ftp? http? ssh? ...)  
* quels contenu renvoient ces différents services? peut-on interagir avec (clients / navigateurs...)? que voit-on sans authentification préalable?    

De nombreux outils de reconnaissance sont disponibles. Certains finissent même pas optimiser cette étape en customisant ces outils. Dans la majorité des cas, les outils du menu "01- Information Gathering" de Kali Linux pourraient vous être utiles.  
Parmi ces derniers, je ne saurai que vous recommander:  
* netdiscover  
* nmap  
* dmitry  
   
C'est déjà plutôt pas mal pour un premier hint, non?  

Si vous pensez avoir terminé cette partie ou que, au contraire vous avez beaucoup cherché et ne voyez plus quoi faire pour arrivez a vos fins, ma reco est disponible dans les solutions ci jointe