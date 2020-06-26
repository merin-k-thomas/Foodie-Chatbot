# Foodie-Chatbot
An Indian startup named 'Foodie' wants to build a conversational bot (chatbot) which can help users discover restaurants across several Indian cities. The main purpose of the bot is to help users discover restaurants quickly and efficiently and to provide a good restaurant discovery experience.

The bot takes the following inputs from the user:
1. **City**: Take the input from the customer as a text field. Foodie works only in Tier-1 and Tier-2 cities. 
2. **Cuisine Preference**: Take the cuisine preference from the customer. The bot should list out the following six cuisine categories (Chinese, Mexican, Italian, American, South Indian & North Indian) and the customer can select any one out of that.
3. **Average budget for two people**: Segment the price range (average budget for two people) into three price categories: lesser than 300, 300 to 700 and more than 700. The bot should ask the user to select one of the three price categories.

The bot will display the top 5 restaurants in a sorted order (descending) of the average Zomato user rating (on a scale of 1-5, 5 being the highest). The format will be: {restaurant_name} in {restaurant_address} has been rated {rating}.

Finally, the bot will ask the user whether he/she wants the details of the top 10 restaurants on email. If the user replies 'yes', the bot should ask for user’s email id and then send it over email. Else, just reply with a 'goodbye' message. The mail should have the following details for each restaurant:

- Restaurant Name
- Restaurant locality address
- Average budget for two people
- Zomato user rating

Deploy the model on Slack.
