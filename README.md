
#KAW Scraper

##KAW Scraper :

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

### Autres Fonctions

#### get_dividendes(name)
La fonction get_dividendes() :
    renvoie les dividendes versés par une société cotée.
    
--> Exemple d'utilisation 
    from wak import get_dividendes
    #### Récupérer les dividendes de la BCP
    get_dividendes(name="BCP")</code></pre>
    

-->get_ratios(name)    
#### La fonction: get_ratios():
renvoie les principaux ratios boursiers d'une société cotée.
    
--> Exemple d'utilisation :
    from wak import get_ratios
    #### Récupérer les ratios boursiers de la BCP
    get_ratios(name="BCP")</code></pre>

    get_carnet_ordres(name)</code></h4>
    <p>La fonction <code>get_carnet_ordres()</code> renvoie le carnet d'ordres (ordres d'achat et de vente) d'une action pour la journée en cours.</p>
    <p><strong>Exemple d'utilisation :</strong></p>
    <pre><code>from wak import get_carnet_ordres

# Récupérer le carnet d'ordres de la BCP pour aujourd'hui
get_carnet_ordres(name="BCP")</code></pre>

    <h2>Contribuer</h2>
    <p>Les contributions sont les bienvenues ! N'hésitez pas à soumettre des demandes de fonctionnalités, des rapports de bugs, ou des pull requests via notre <a href="https://github.com/votre-utilisateur/WAK">dépôt GitHub</a>.</p>

    <h2>Contact</h2>
    <p>Pour plus d'informations, visitez notre <a href="https://votre-site-web.com">site web</a> ou contactez-nous à <a href="mailto:votre.email@example.com">votre.email@example.com</a>.</p>

    <footer>
        <p>&copy; 2024 WAK Scraper - Tous droits réservés</p>
    </footer>

</body>
</html>
