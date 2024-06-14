# Chatbot-using-the-OpenAI-API

![image](https://github.com/selin-a/chatbot-using-the-OpenAI-API/assets/122975373/2ffa1bb8-3067-4290-8e36-c6f96cfb1703)

---

Here I'm using OpenAI's GPT-3.5 Turbo to build an AI-powered travel guide that will help visitors navigate the Olympics in Paris. 

The goal is to guide visitors through the various aspects of the upcoming Olympic Games such as:<br>
Event Information: Providing details on event schedules, venues, and ticketing.<br>
Transportation: Offering guidance on how to get to different Olympic venues and around the city.<br>
Local Attractions: Highlighting must-see Paris landmarks and cultural spots to explore during downtime.<br>
Dining and Entertainment: Recommending the best places to eat and enjoy Parisian culture.<br>


How to approach the project:<br>
1. Creating a developer account with OpenAI and the project API key:<br>
I started by securely storing the API key as an environment variable to ensure smooth and secure access to OpenAI’s services. For more information on pricing, see OpenAI's pricing page.

2. Defining the model and client:<br>
Next, I defined the GPT-3.5 Turbo model and set up the API client to connect with OpenAI's servers.

3. Defining the conversation:<br>
I structured the AI’s responses to provide detailed and engaging information about the Olympics events, venues, and other key attractions in Paris.

4. Creating a conversation loop:<br>
I implemented a loop that allows continuous handling of user queries, offering real-time, personalized answers to help users plan their Olympic experience. I set the parameters for fine-tuning the behavior of the language model to generate text outputs that meet specific requirements, to ensure determinism (temperature=0.0) and limit the length of generated responses (max_tokens=100).









