View the challenge here:

```
https://www.kaggle.com/competitions/cmi-flu-internal-prediction-challenge/data
```

To download the data:

- Create a Kaggle account and API token.
- Copy the API token to .env.example and rename it to .env.
- Install the Kaggle CLI: `pip install kaggle`
- Accept the competition rules and run these commands:

```
source .env
kaggle competitions download -c cmi-flu-internal-prediction-challenge
```

Extract files and move them to the data folder.