<h1> Exploring Dual AI Chatbot Conversational Dialogue Models</h1>

<h2>Description</h2>
Exploration consists the development of conversational AI agents engaging in dialogue conversation with each other and understanding the adapability of AI agents in conversational speech. 

<li>Project 1: The first project focuses on developing LLM-powered AI agents and engaging them in conversation, exploring the effects of different prompt engineering techniques to best execute the most natural flow of conversation. </li>

<li>Project 2: As a continuation of project 1, the second project focuses on the development of dual-AI agent conversations without the use of an API-based model and utilization of NLP tools to execute a flow of conversation between two chatbots. </li>


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Jupyter Notebook</b>
- <b>OpenAI (API-based model)</b>

<h2>Environments Used </h2>

- <b>Macbook M2 chip Air</b> (21H2)

<h2> Project 1: LLM-Powered AI Agent Dialogue Conversation Model</h2>
<p> At the start of the project, we heavily focused on wanting to explore how two different chatbots can pragmatically adapt to each other and explore the conversations that could be developed in the process--exploring the capabilities of dynamic conversational agents. Thereby, we utilised 'gpt-4' as our API-based LLM model that would power the chatbots and then set up an environment that could create two different AI chatbot personas and then engage them in turn-taking dialogue. </p>

<p> One of the biggest challenges faced was figuring out how to "naturally" end the conversation and not have the chatbots continue their dialogue forever--which would serve as a long-term fianncial burden. At first, there was exploration of the utilisation of sentiment analysis--where there would be a dataset of "negative" phrases that would be phrases typically said to signify the end of a conversation such as "wow! look at the time, can't believe how much time has passed!" or "well, it was so nice catching with you!". Then, there would be one "negative" phrase that would be randomly selected and another random selection between 1 to 10 that would determine when the random phrase would be inserted in the chatbot dialogue conversation. </p> 

<p> However, later on, we revised the approach where we focused more heavily on prompt engineering to provide a systematic step process to guide the chatbot dialogue conversation as well as utilised a list of "end phrases" that would signify the stop of input to the API system. Within the chatbot prompts, each bot would have their own systematic step process that would guide the direction of the conversation and would be introduced one at a time to mimic a natural conversation dialogue. Then, once the bots had concluded their conversation by saying phrases such as "hope you have a great rest of your day!" "wish you the best!", these would be flagged under the list of "end phrases" and signify the end of the chatbot conversation. </p> 

<p> With this new format, it allowed for a much more natural dialogue of conversation between the two chatbots that micmiced a genuine conversation two people may have--where in this case, it was the situation of Solomon, a tutor helping teach Psychology on the topic of validity within research studies, and Sophia, a college student who needed help clarifying about the material. </p>

<p> Through this project, it provided great insight on the capabilities of prompt engineering as well as exploring the potential of chatbot dialogue conversation. </p> 

<h2> Project 2: Non-LLM Powered Dual AI Agent Dialogue Conversation Model</h2>
<p> After creating a successful model of dual-chatbot dialogue conversation powered by 'gpt-4', there was more exploration in how to create this same type of dynamic without the use of 'gpt-4'. For greater scalability and cost efficiency, this served as an interesting area of exploration in testing out how to create a dual-chatbot conversation without it being an API-based model. The code below is still in the progress of development but serves as an interesting introuction for the development of this new type of model. </p>
