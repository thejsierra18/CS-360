# CS-360
### Android Development

***Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?***

The goal of this project was to create an Inventory application that would be used to track items in a warehouse. It was required to have a database with two tables, one for users and one for items. The user has to be able to login, add or remove items as needed, and change the quantity of the items. If an item reaches a quantity of 0, then the application has to notify the user.

***What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?***

The screen that were necessary to support the user needs are a Login/Register screen, an Inventory Items screen, and an Add Item screen. I was able to create a minimalistic design, where the user is able to intuitively use the application.

***How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?***

My approach to code the application was to work through iterations. First by creating the UI, and after that adding functionality or solving issues in each iteration. For example, creating the database and user table, then implementing the backend for the Login screen, ensuring that it worked properly, and then moving onto another feature. This process can be used in the future as it is an Agile process.

***How did you test to ensure your code was functional? Why is this process important and what did it reveal?***

In order to test to ensure that my code was functional, I took advantage of the Android Studio emulator, running the application on a Virtual Device, and using the Debugger that is included. This allowed me to narrow down any bugs and solve them efficiently.

***Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?***

My main challenge with this application was to dynamically add or remove objects from the UI as needed. Specifically as items were added/removed or modified from the inventory, this changes had to be reflected on the UI. Although I don't think that I innovated in any way, I had to do a lot of research on how to properly implement this feature.

***In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?***

I was particularly succesful implementing the inventory screen and its functionality. Given that this was the most challenging feature of the project for me, I tried to make it work as good as it could be. I was able to dynamically modify the objects in the UI, and successfully send alerts to the user once an item ran out of stock.
