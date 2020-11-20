[Chatbot](https://github.com/t-arf/Portfolio/images/cbot)

 Start by exploring the MultiWoz dataset. The dataset you are about to use has more than 10,000 human annotated dialogues and spans multiple domains and topics. 
 Some dialogues include multiple domains and others include single domains. 
 In this section, you will load and explore this dataset, as well as develop a function to extract the dialogues.
 Here you are going to use the Reformer, also known as the efficient Transformer, to generate a dialogue between two bots.
 You will feed conversations to your model and it will learn how to understand the context of each one. Not only will it learn
 how to answer questions but it will also know how to ask questions if it needs more info. For example, after a customer asks for
 a train ticket, the chatbot can ask what time the said customer wants to leave. You can use this concept to automate call centers, 
 hotel receptions, personal trainers, or any type of customer service. By completing this assignment, you will:

Understand how the Reformer works
Explore the MultiWoz dataset
Process the data to feed it into the model
Train your model
Generate a dialogue by feeding a question to the model
