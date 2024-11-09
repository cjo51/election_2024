# election_2024
Data on the UK 2024 General Election

## Description of repository
The goal of this repository is to analyse the voting behaviours of the 2024 UK General Election

### Get the data

1. create a Kaggle account: https://www.kaggle.com/
2. get API keys and user name
    - Go to your account, and click on your profile in the top right
    - Then click on "Settings"
    - Scroll down to the API section and click on "Create New Token"
    - Get your username and API key from there
We have written a data loader function for you in the "nba/data_loader.py".This allows you to download the data with by running the script from the terminal. Run the following command in the terminal being at the root of the repository.

python election_results/data_loader.py -u "your_user_name" -k "your_api_key" -d "kartik70/uk-2024-general-election-preliminary-data"

Replace "your_user_name" and "your_api_key" with your username and API key. This creates a json file at "~/.kaggle/kaggle.json" with your username and API key, which is used to authenticate your account and download the data.