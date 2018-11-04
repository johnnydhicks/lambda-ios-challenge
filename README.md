# Lambda iOS Challenge - All About Me
Welcome to Lambda School. We are looking forward to helping you learn iOS development over the next 6 months. As a way to introduce yourself to us and to help us see where you’re at in your iOS journey, we’ve put together this 1 hour Xcode challenge. 

For this project, you are going to create an iOS app with four screens using segues to navigate from one screen to another (embed in UINavigationController). Requirements and Hints for each screen can be found below.

Note: This will be a challenge, but do your best to get as much done as possible within the hour. If you get stuck on one screen, move on to another screen and come back to it at the end. 

Good luck!

## Name Generator

[AllAboutMeImages/Screen Shot 2018-11-03 at 8.29.06 PM.png]

For the name generator, you will need to set up a view controller with 5 textfields. You will need a textfield for your first name, last name, factor 1, factor 2, and a limit. You will also need to include a button that when tapped will *print out* all of the numbers from 0 to your entered limit, but when the number is divisible by `factor 1`  it should print out the `first name` . When the number is divisible by   `factor 2` it should print out your `last name`  and when it is divisible by `factor 1` and `factor 2` it should print out a combined form of your first and last name. 

Note: This may look familiar to the “Lambda School” challenge you did during the intro course. Another common name for this algorithm is “FizzBuzz”.

Hint: To convert your textfields’ factors and limits into integers, you can initialize a new property with a value of `Int([textfield's text goes here])` .  

## Favorite Color
[image:61DA3928-62D4-4EB8-ABF1-7C8D49F7E054-4859-0000050782D01CCC/Screen Shot 2018-11-03 at 8.40.27 PM.png]
[image:1FC4E6AA-1A40-45CC-B8A2-20DE6C417827-4859-000005086F731A30/Screen Shot 2018-11-03 at 8.40.34 PM.png]

On this screen you will create a really simple interface with one `switch` that when toggled on will change the screen from white to your favorite color and vice versa. 

## Favorite Apps
[image:4FBAF4A1-338E-46F4-8A49-E0092AC8BBCE-4859-000005425CC193C8/Screen Shot 2018-11-03 at 8.44.19 PM.png]

Here you will create an interface with one textfield and a button that will allow you to create a list of your favorite apps, appending one at a time to a text label above.

Hint: To combine elements of an  `array`  with a new line after each element, you can use the method on array type `.joined(separator: String)` .

## Hobbies
[image:531EA1CD-7537-4659-9619-A72AB2C9445F-4859-0000060FC7BB1B5A/Screen Shot 2018-11-03 at 9.00.03 PM.png]

For this last screen. Create a simple tableview that shows a list of your hobbies.

