# fish_species_assignment

This project focuses on predicting the fish species based off of the lenght, width, height and weight of the said fish.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.txt.
The imp libraries included are:
- pandas
- numpy
- flask
- gunicorn
- sklearn

```python
pip install -r requirements.txt
```

## Usage

```python
python FlaskApp.py
```

## Deployment

Currently the project is deployed on heroku.
The app can be accessed [here](https://predict-fish-species-ass.herokuapp.com)

## Files

- Fish_Species_LR_Sarvang_100838643.ipynb contains the model structure
- Fish.csv is the dataset
- FlaskApp.py is the main flask app
- templates/index.html has the html file
- static/css/style.css has the css file for the html
- classifier.pkl is the saved model

## Credits
- Noopa [linkedIn](https://www.linkedin.com/in/noopajagadeesh/?originalSubdomain=ca) : For guidance 


## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
