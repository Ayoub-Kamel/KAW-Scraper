
# WAK Scraper

## WAK Scraper :

est une bibliothèque Python permettant de récupérer des données financières des sociétés cotées à la Bourse de Casablanca, telles que les dividendes, les cours historiques des actions, et d'autres informations disponibles sur le site officiel.

## Installation
>Pour installer WAK, utilisez la commande suivante :
pip install wak

## Utilisation
### Fonction principale : <code>get_stock_history()</code></h3>
La fonction <code>get_stock_history()</code> permet d'importer l'historique des cours des actions de la Bourse de Casablanca.</p>

Paramètres :
#### names: Le ticker (symbole) de l'action, par exemple <code>"BCP"</code> pour la Banque Centrale Populaire.
#### start : La date de début au format <code>"YYYY-MM-DD"
#### end: La date de fin au format <code>"YYYY-MM-DD"

### Exemple d'utilisation :
from wak import get_stock_history

#### Récupérer les cours historiques de la BCP entre 2020-01-01 et 2020-12-31
get_stock_history(names="BCP", start="2020-01-01", end="2020-12-31")



#### get_dividendes(name)
La fonction get_dividendes() :
    renvoie les dividendes versés par une société cotée.
    
--> Exemple d'utilisation 
    from wak import get_dividendes
    #### Récupérer les dividendes de la BCP
    get_dividendes(name="BCP")</code></pre>
    

#### get_ratios(name)    
La fonction: get_ratios():
    renvoie les principaux ratios boursiers d'une société cotée.
    
--> Exemple d'utilisation :
    from wak import get_ratios
    #### Récupérer les ratios boursiers de la BCP
    get_ratios(name="BCP")</code></pre>

#### get_carnet_ordres(name)</code></h4>
La fonction get_carnet_ordres():
    renvoie le carnet d'ordres (ordres d'achat et de vente) d'une action pour la journée en cours.
    
--> Exemple d'utilisation :
    from wak import get_carnet_ordres
    #### Récupérer le carnet d'ordres de la BCP pour aujourd'hui
    get_carnet_ordres(name="BCP")

    

Pour plus d'informations, visitez notre site web https://kamel.ma ou contactez-nous à ayoub@kamel.ma

