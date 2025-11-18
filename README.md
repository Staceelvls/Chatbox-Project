<h1><img src="images/s2pbanner1.JPG"</img></h1>

<h2>Description</h2>
I genuinely think chatbots are super helpful and save a ton of time, which is why I focused this project on building one. Because I love reading and am always open to new recommendations, I used Amazon Lex to create the "Bookworm Buddy". This chatbot asks for a user's preferred genre and immediately suggests a book. I create the chatbot to  demonstrate skills in the chatbot setup, specifically by inputting the user's goal (Intent) and collecting necessary data (Slots). By choosing the no code method, I focused on configuring the AWS service architecture to allow me to demonstrate the conversational design and logic without relying on complex back-end development.
<br />

  
<h2>🖥️Environments Used💻 </h2>

- <b>Amazon Web Services</b> 
- <b>Amazon Lex</b>

## Project walk-through:



### 1. 🏗️ Create the Chatbot 
  I created the chatbot using Amazon Lex and assigned basic Amazon Lex permissions.
<img src="images/2bucketscreated.JPG" width="800" />
  
---

### 2. 📝 Define Custom Data
I created a custom Slot Type named BookGenre (because Genre was not available in the presets) and populated it with a specific list of genres for the bot to understand.


<img src="images/iamrole.JPG" width="800" />  

---  
### 3. 💻 Established the Intent
I taught the bot to recognize a request for a book recommendation by creating the Intent (GetBookRecommendation) and adding training phrases (Utterances).


<img src="images/lambda.JPG" width="800" />

---
### 4. ✅ Set the Final Response
I configured the Closing Response to deliver the final book recommendation message once the required {Genre} input is successfully collected.


<img src="images/trigger.JPG" width="800" />

---
### 5. 🚀 Deploy and Test
The final step was to Save all configurations and build the bot to activate the model for testing.


<img src="images/testscreenshot.JPG" width="800" />


---

<h2>Goal:</h2>
To successfully configure and deploy a cloud-based chatbot using Amazon Lex, demonstrating the ability to gather user input (Genre) and deliver a targeted response using no-code fulfillment.
