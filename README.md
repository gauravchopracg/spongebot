# Spongebot
This repo illustrates, how to build a chatbot by using dialogflow

# Getting Started
Before, you can build a chatbot go to [Dialogflow](https://dialogflow.com/) and go to console in the top right corner. Sign in with your gmail account and create an agent, give your bot a name! We're going to call ours a 'SpongeBot. 

# Configuring
After creating an agent, we will start with changing Default Welcome Intent in Intents section

![recognized_389de515-picture5.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/389de515-picture5.png)

Default will look like this, we are going to create a special welcoming response that suits our restaurant: Krabby Patty.

![recognized_f3003311-picture7.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/f3003311-picture7.png)

"Hello! Welcome to Krabby Patty. My name is SpongeBot."

After that, click the 'Save' button at the top. We are now going to create new intents, Click on '+' new to the 'Intent' button in the left menu.

* Home Delivery

![recognized 84dc1d87-picture12-705x552.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/84dc1d87-picture12-705x552.png)

* Specials
![recognized b2b30f49-picture14-705x581.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/b2b30f49-picture14-705x581.png)

Once We did that, it time for our bot to start taking orders. Click on '+' next to the 'Entities' button in the left menu. Enter the values of the Patty Buns and Toppings separately
![recognized ae3cd7c7-picture36-705x173.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/ae3cd7c7-picture36-705x173.png)

![recognized d15b2638-picture17-705x316.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/d15b2638-picture17-705x316.png)

![recognized 6d371214-picture18-705x214.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/6d371214-picture18-705x214.png)

We can link them to our bot by creating a new Intent 'Placing Orders', scroll to Actions & Parameters and enter the 'Entity' that you created, starting with the '@' symbol and 'Value', starting with the '$' sign.

![recognized f8ed98b7-picture19-705x302.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/f8ed98b7-picture19-705x302.png)

## Integration
To test how the chatbot would appear when functional. Navigate to the 'Integraion' section in the left column and toggle to 'Web Demo' and turn it on 

![recognized f8ed98b7-picture19-705x302.png](https://cdn-gcp.marutitech.com/wp-media/2019/08/f8ed98b7-picture19-705x302.png)

You can check the demo at:
https://bot.dialogflow.com/c147c066-bf2a-45d0-825b-65d3b216bd8d

