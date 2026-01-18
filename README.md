# wf-market-price-bot
small project to bulk update current warframemarket sell orders using the existing online listings

## To Run
1. create `credentials.json` file in the root repository and populate `email` and `password`
```
{
    "email": "email_here",
    "password": "password_here",
    "auth_type": "header"
}
```

2. run `python main.py`

The terminal will display the progress of updated orders out of all sell orders.

Extra information on the current live orders, the users orders and the decisions will be outputted to `logs.txt`