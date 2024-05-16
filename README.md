
# Agribot

This agribot answers all your questions related to agriculture.

NOTE: This bot will have less accuracy as it is just a simple implementation of basic NLP preprocessing techniques.




## Authors

- [@Bhuvan588](https://github.com/Bhuvan588)


## Dataset

The dataset used is Farmer Call Query dataset. 

Link: https://www.kaggle.com/datasets/daskoushik/farmers-call-query-data-qa


## Working

The bot first uses a function which uses basic NLP preprocessing techniques like converting to lower case, removing special characters, lemmatization to preprocess the user query. Then it compares it with all the rows of the 'questions' column of the dataset using cosine similarity. It then returns the query corresponding to the highest score
## Deployment

This project's code was written on Google Colab and partially deployed using Anvil. 

You need to keep your notebook running to make the public URL work. You can check out Anvil software for more info

## Drawbacks

It is a very basic bot.

It may suffer due to duplicate rows which may have the same meaning . 

Less interactive
## Related

I am thinking of taking this project forward when I learn more about different tech and frameworks. 

![WhatsApp Image 2024-05-16 at 9 27 00 PM](https://github.com/Bhuvan588/Agribot/assets/68458621/780859d8-0141-4e37-a017-7b5627bf67c5)
