# Mythological Chatbot
A Chatbot for asking spiritual questions

AI-powered chatbots offer a promising new approach to exploring and disseminating the wisdom of the Bhagavad Gita. By providing a personalized, interactive, and immersive learning experience, chatbots can help individuals to deepen their understanding of this timeless scripture and apply its insights to their own lives.

This chatbot allows you to ask questeions related to the holy scriptures of Bhagawad Gita and answers them taking that as the context, and answers in a spiritual manner.

# Dataset Description
The dataset used in this research comprises the entire **Bhagavad Gita**, translated into English. The text is organized into 18 chapters, each containing verses, or 'shlokas,' totaling approximately 700 shlokas. To equip our AI chatbot with the profound wisdom encapsulated within this ancient scripture, we embarked on a meticulous process. A **question-answer dataset** was carefully built from the verses of the Bhagavad Gita to aid in the training of our AI chatbot. This dataset encompasses a comprehensive array of queries that span diverse philosophical and spiritual topics explored within the scripture. By fine-tuning the AI chatbot using this meticulously curated dataset, we equipped it with the requisite knowledge and semantic understanding to yield precise and contextually relevant responses to user queries.

# Methodology
The methodology employed in this research involves fine-tuning the T5 transformer model on the Bhagavad Gita question-answer dataset. One of the key features of T5 is its use of relative scalar embeddings. These embeddings allow T5 to encode the relationship between words in a sentence, rather than just their individual meanings. This enables T5 to better understand the context of a question and provide more accurate and informative responses.
Along with our Mythological Chatbot development, the creation of a user-friendly and responsive interface is paramount. Leveraging a lightweight and efficient technology stack, our choice of **Svelte** for the frontend, **FastAPI** for the backend, and **Uvicorn** for server deployment is guided by a commitment to optimal performance and streamlined development.

# Future Work
- One potential future direction is to extend the chatbot's knowledge base to include other religious scriptures, such as the Ramayana and the Quran. This would allow the chatbot to engage in conversations about a wider range of religious and spiritual topics, appealing to a broader audience.

- Another potential area for future work is to train the chatbot on a larger dataset of Bhagavad Gita questions and answers. This would help the chatbot to learn more complex patterns and relationships, resulting in more accurate and insightful responses. Additionally, training on a larger dataset would help to reduce the number of incorrect or incomplete responses.

- Finally, future work could explore the use of more powerful computational resources to train larger and more sophisticated T5 models. This would enable the chatbot to achieve even better performance on a variety of tasks


