# SNHU_CS-360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
This is an inventory managment application. There needs to be a login screen with database, a way to create a new user, and access to the application without logging in. Another database is needed to hold inventory information, with a way to add and remove items. Finally, the application needs to be able to send SMS notifications if granted permission.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The screens created were: Login, New User, Inventory, Add Item, and SMS Permissions. I kept the theme, sizes, and spacing between screen similar by creating variables for each in XMLs. The biggest user friendly feature of my app is the color coded borders in the inventory screen. Each item has a green, yellow, or red border depending on it's inventory level. This gives the user an instant glance at the status of the overall inventory as soon as the screen pops, without having to scroll and look at the quantity value of each item individually.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
I first focused on the different types of users, their needs, and how they would be using the app. I then starting designing the screens with the users in mind. Once I had a broad layout of the screens, I started defining default values and applying them to the screens for consistency. Finally, I coded the functionality of the app to make it work.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
I used the Android Studio built in emulator. This is a quick and immediate way to test the code without having to send it to an andorid device for testing. The emulator has many types of devices. If the layout was designed for a mobile phone, it might look bad on a tablet, or vice-versa. So being able to quickly check the layout on different devices helps create a profesionally looking app. It also allows testing of other limitations, such as sensors.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
The challenge that made me feel innovative was trying to keep consitancy between screens. It wasn't a difficult challenge and the fix seems more general correct practice, but figuring it out gave me an "aha!" moment. 

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The component that demonstrates my skills is the color changing border.
