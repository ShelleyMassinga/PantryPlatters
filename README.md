![workflows style status badge](https://github.com/alyliann/PantryPlatters/actions/workflows/style.yaml/badge.svg)
# PantryPlatters
SEO Tech Developer program final project created by Alysa Vega, Chinyere Amasiatu, Myah Jackson-Solomon, and Shelley Massinga.
PantryPlatters is a recipe finder designed to inspire creativity and convenience in the kitchen by prioritizing what is in the user’s fridge and pantry, aiming to reduce food waste by using what is already available.

## Setup instructions

#### Libraries to install
* Flask-WTF
```
pip3 install Flask-WTF
```
* Flask-SQLAlchemy
```
pip3 install Flask-SQLAlchemy
```
* flask-behind-proxy
```
pip3 install flask-behind-proxy
```
* email_validator
```
pip3 install email_validator
```


## Running the code

To run `pantryplatters.py` in a terminal, type:
```
python3 pantryplatters.py
```

## How the code works

`pantryplatters.py` and `forms.py` provide the backend for the **PantryPlatters** program, with the files in `templates` and `static` providing the frontend.
PantryPlatter is a "what's in your fridge" recipe finder, using ingredients the user has to provide recipes. Users can create an account and save recipes to return to in the future.

### Obtaining a Spoonacular API Key

To get your own **Spoonacular API Key**, head to [Spoonacular](https://spoonacular.com/food-api) to [sign up](https://spoonacular.com/food-api/console#Dashboard) and obtain a free API Key, limited to **150 calls per day**.

To use your Spoonacular API Key with PantryPlatters, simply paste your API Key between the single quotes on Line 21 of `pantryplatters.py`.

### Obtaining a Secret Key

To get your own **DJANGO Secret Key**, open up your terminal and open up the Python Shell by simply typing which version of Python you have installed, for example ```python``` or ```python3```.


Once in the Python Shell, type ```import secrets``` and hit Enter. Next, type ```secrets.token_hex(16)``` and the shell should print out a key of letters and numbers.

To use your secret key with PantryPlatters, simply paste it between the single quotes on Line 16 of `pantryplatters.py`.
