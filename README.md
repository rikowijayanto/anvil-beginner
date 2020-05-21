=========== ANVIL DOCUMENTATION ==========================

This file describes how to use anvil for building graphical user interface in python

Narration : Anvil is the one of the streaming GUI builder that can be used to make our code more interesting and complete. We can build our own
apps using Anvil by sign up on https://anvil.work and then design our apps. Anvil file will be treated as the client, our code on Google Colaboratory,
Jupyter Notebook, Spyder, or also etc as the server by connecting a special key.


In my learning, I used Google colaboratory to build the apps.

First, we have to open Anvil, sign up, and then create our own apps. I give you a simple example.
Below is the example of my design on Anvil.

![1](https://user-images.githubusercontent.com/43143626/82526022-13857a80-9b5d-11ea-9936-30347c0490a1.JPG)


To connect with our code in Google Colaboratory or Jupyter Notebook, we have to activate the Uplink, generate the key, and then run it into our base. Our base code will be treated as the server.

![2](https://user-images.githubusercontent.com/43143626/82526031-16806b00-9b5d-11ea-882d-57966bc537ba.JPG)

Generate the key, copy the uplink, and also code as the bridge.

![3](https://user-images.githubusercontent.com/43143626/82526032-16806b00-9b5d-11ea-96f5-59e54b524feb.JPG)

We have to install the Anvil server, run the connection, and then create a function as usual with some parameter.
Don't forget to call the callable using @anvil.server.callable

![4](https://user-images.githubusercontent.com/43143626/82526035-17190180-9b5d-11ea-8b53-8322aed88ddc.JPG)

Because we want to make a calculation when "Hitung" button is clicked, so we will create a call function inside the button. The step is, from design pattern, double click the button, and you will see function of button click. We have to make sure that button fuction that we call is button_click (...).

Then, we define the result as the variable and we have to connect to our server using anvil.server.call ("function name", param1, param2, ... ). To get the value from the text box, we only call by self.textboxname.text and if we wanna set into another text box, we only create self.textboxresult.text.

![5](https://user-images.githubusercontent.com/43143626/82526036-17b19800-9b5d-11ea-8601-531ebeaaaa18.JPG)

Finally, we can run the application by clicking RUN button above the dashboard. And see, our application already deployed and can be accessed well.

![6](https://user-images.githubusercontent.com/43143626/82526037-184a2e80-9b5d-11ea-820c-07acfb122c05.JPG)


NOTE :
1. This is the simple application for an example, we can develop our app based on our creativity and our liking
2. We have to connect to internet to run the app and the server should be ran over and over

