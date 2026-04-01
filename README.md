## Flipkart Chat Bot



## Create a virtual environment:
python -m venv venv


## Activate your virtual environment

```bash
venv\Scripts\activate
```

## Create a requirement.txt file and install it

```bash
pip install -r requirements.txt
```
## Create a .env file for keeping your environment variable.
- GROQ_API_KEY = "gsk_JOElTaKd7mCQo9bMnT4EwAHCxdFCte4EO"
- ASTRA_DB_API_ENDPOINT = "https://a8d7297e-16b3-4020-8960-81054f731a25-us-east-2.apps.astra.datastax.com"
- ASTRA_DB_APPLICATION_TOKEN = "AstraCS:TnEJBnBFeaIkaaZqQ:d66326e48341462f4dc2ec8922b51fc7839c140a6b95a2dc06fbeeeead40c4cd"
- ASTRA_DB_KEYSPACE = "default_keyspace"
- HF_TOKEN = "hf_CwWlvvzqTwzVqHabbjVpTphwW"


## Use setup.py for installing your local package.

- <either mention -e . inside your requirements.txt Or run python setup.py install >

