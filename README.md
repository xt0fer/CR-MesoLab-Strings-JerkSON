## WELCOME TO THE Painful Afternoon (Hurtlocker)

By this time you should have been introduced to Java Strings, Exceptions, Unit Testing, and Regex.

# You will need all of these today!

In this project you will find a file in the resource folder called RawData.txt. It was supposed to be a grocery list formated in JSON, but after a huge defeat this weekend in a game called Munchkin, Tariq, your fearless, yet petty, leader decided to reformat it in his own Object Notation. JerkSON... you are welcome.

##JerkSON Format

Just like Json, JerkSON is supposed to be a Key Value Pair data store.

In Json Key and Value are separated as such (Key:Value) where the colon is the separator.

In JerkSON, Key and Value could be separated by using any of the following (:, @, ^, *, %) and there is no guarntee that there isn't another hidden symbol separator. (There could be another one, or maybe there isn't , you tell me)... lol


In Json Key and Value pairs are separated by a ',' in JerkSON it's '##'

## Your Task
It's your job to build a JerkSON data parser that is able to read in the raw data and output a string formatted list that resembles (outputFormat.txt) 

There are some things to look out for.... If you haven't figured it out by now Tariq has many wonderful qualities, spelling isn't one of them, so Words may not be spelled correctly. You need to decipher what Tariq was trying to spell using pattern matching.

### For example:

In the shopping list Tariq has Cookies, but he could spell like Cookies, c00Kies, Co0kies and so on.

YOU ARE NOT ALLOWED to use any Java based string manipulation!!!!!!!!!!!!

You must use regex to detect the patterns and match them.


It's not guranteed that every Key will have a Value, and every Value will have a pair. For instance:

you may see something like this

`Name:Milk;Price:3.23;type:;expiration:1/24/2016##`

Notice how TYPE has a key but no Value.... if you try and parse this into an object your program could crash.

You will need to handle your exceptions!

I also expect you to report on how many exceptions you saw while parsing the data.


GOOD LUCK ZIPCODERS!!!! May the Odds be ever in your favor!!!!

