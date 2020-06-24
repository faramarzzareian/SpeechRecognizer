# speechrecognizer
+ android app to recognize the speech
+ this application uses speech.recognizer classes of android sdk which is provided by google.
+ Analyze, Filter, Digitize
+ Speech recognition software can analyze the sounds you make by filtering what you say, digitizing it to a format it can “read”, and then analyzing it for meaning.
+ Then, based on algorithms and previous input, it can make a highly accurate educated guess as to what you are saying. It gets to know the speaker’s use of language.
# Shazam
+ an app that is used to instantly identify music, is another great example of how speech recognition technology works.
# models :
+ Small-vocabulary/many-users

These systems are ideal for automated telephone answering. The users can speak with a great deal of variation in accent and speech patterns, and the system will still understand them most of the time. However, usage is limited to a small number of predetermined commands and inputs, such as basic menu options or numbers.
+ Large-vocabulary/limited-users

These systems work best in a business environment where a small number of users will work with the program. While these systems work with a good degree of accuracy (85 percent or higher with an expert user) and have vocabularies in the tens of thousands, you must train them to work best with a small number of primary users. The accuracy rate will fall drastically with any other user.
# Design 
![1-design](https://user-images.githubusercontent.com/5400662/85582390-b0947100-b63d-11ea-8dcc-5716df989f13.jpg)
+ colors.xml which is define the main colors of app :
![color](https://user-images.githubusercontent.com/5400662/85583194-5516b300-b63e-11ea-91dc-cc487527efb7.png)
+ styles.xml defines the style of app :
![styles](https://user-images.githubusercontent.com/5400662/85583310-7081be00-b63e-11ea-8848-ce1d78342a4c.png)
+ strings.xml : I defined the app properties here :
+ ![strings](https://user-images.githubusercontent.com/5400662/85583543-a32bb680-b63e-11ea-8fc1-7275767b9a73.png)
+ in drawables i created a shape of background and positioned the png microphone :
how it should be when it is not active(not pressed) or how it should be wneh it is active(pressed)

+ ![drawables](https://user-images.githubusercontent.com/5400662/85583927-f867c800-b63e-11ea-927f-e7bb13554747.png)
+ manifest > androidmanifest.xml : in this file we set the permission for application to be able to record audio : 
+ ![manifests](https://user-images.githubusercontent.com/5400662/85584467-762bd380-b63f-11ea-9613-2277995f2b98.png)
+ Mainactivity.xml : we set the code to check if the permission of using the microphone by the app is granted or not. in higher level of android sdk user have to set this permission manually .
+ ![mainactivity](https://user-images.githubusercontent.com/5400662/85585068-fbaf8380-b63f-11ea-882e-a84be83ffcbc.png)
