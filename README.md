# Chatbot for Suicide Preventtion
Built an automated bot system using HTML5, CSS, Bootstrap and JS creating using Google chatbot APIs that takes a collection of phrases based on an input received from user end.

Ryerson Engineering Competition 
November 17, 2018
Ryerson University
SBI
Neel Bhavsar, Yusef Khedr, Wrichiek Kar, Rylan Lobo


# Design Process
After receiving the problem, we began the ideation process. We utilized the whiteboard method n order to ideate effectively. Looking at our problem and coming up with possible programming solutions that are currently available, after listing these current solutions we selected the possible programmable solution. We then narrowed down to what we thought was possible to create within the time period and with our programming capabilities. Through this we came up with the idea of creating some sort bot based on the idea of companionship to combat suicidal thoughts.  When attempting to code this idea, we came across many problems, through these problems we would change our approach multiple times until we ended up with our final approach. 

We split up our work by Front End coders and Back End coding, having one member work on front end, whilst the other 3 worked on back end. We believe that this is a fair distribution of work. Front End coders used they’re time learning how to utilize the back end code while back end coders spent most of the time trying to alter the API in order to meet our needs. About ½ the time frame was spent learning online and the other half used to integrate our knowledge into the code. 

We thought alot about our target audience and how to make our code truly useful rather than computationally appealing. 

# Design Justification

For our website design we wanted to have a site that focused on the interaction between the user and a bot. This bot would provide a platform for the user to express themselves and their feelings, while simultaneously giving them someone to talk to. In addition to the bot, the website provides information on how to get in contact with a distress centre if the user is contemplating suicide or having any suicidal thoughts. The other link is for an addiction centre in Toronto that can help the user fight an addiction by entering rehab, if the user believes that addiction is leading to suicidal thoughts or harming their life in any capacity. For the design of the bot, we wanted it to be able to hold a conversation with the user, rather than prompting the user what to say. This allows the user to express themselves however they feel and they can also choose what topics to discuss. The bot is designed to detect key words and phrases inputted from the person, and based on the words/phrase said, the bot will respond with a randomized response related to the topic entered by the user. For example, someone who is talking about self harm would get a response urging them not to do it or telling them alternate actions to help combat and resist their urges.  

Code Explanation
We utilized HTML5 to layout the relevant information of the website such as the header, body of the text whereas CSS was used to implement the styling of the website. Various types of backgrounds, layouts, styles, fonts and colour schemes were implemented to optimize the display of the website’s front end. Bootstrap and Javascript were used to implement the APIs such as google translate to provide various language translations.

For the chat application, we found an open source API that did exactly what we were looking for. We tailored it to our needs so that it can give an appropriate answer based on a suicidal response. We incorporated a feature so that it can also maintain small-talk as our users may just be looking to have a conversation. This API was amazing for our needs, as we have hardly any experience with node JS and other web app languages. Essentially open source API, had a UI that made it simple for people to tailor. We would add keywords, intentions, and more in order to make it reply, we made it utilize machine learning in order to make it less forced, for example if we inserted “i want to kill myself” it would also accept something it learned as similar like “i feel like killing myself”.

