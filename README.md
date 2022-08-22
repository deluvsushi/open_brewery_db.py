# open_brewery_db.py
Web-API for [openbrewerydb.org](https://www.openbrewerydb.org) website which is free dataset with public information on breweries, cideries, brewpubs, and bottleshops

## Example
```python
import open_brewery_db
open_brewery_db = open_brewery_db.OpenBreweryDB()
random_brewery = open_brewery_db.get_random_brewery()
print(random_brewery)
```
