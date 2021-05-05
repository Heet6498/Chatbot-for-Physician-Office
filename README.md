# Chatbot-for-Physician-Office

### Introduction
When facing any unfamiliar medical issue, many people wish to be able to consult a medical professional as soon as possible. Seeking help from a medical professional can take a long time due to the lack of available physicians. The use of a chatbot can help to receive medical information quickly and without the need for a physician.

### Task and Purpose
The job of the chatbot will be to help answer any pressing questions a patient may have regarding a particular medical condition. Chatbot can be used online on a physician website to help quickly provide answers to any questions a person has. The goal of the chatbot is to limit the amount of unnecessary appointments made to a physician office, and to help answer patient’s questions as quickly as possible.

### Knowledge Sources and Acquisition
The chatbot will obtain information from various pages on the Mayo Clinic website. Mayo Clinic has a variety of webpages discussing virtually any type of medical condition a person may have. The Mayo Clinic website highlights what the medical condition is, along with the symptoms, causes, cures, and risks of the condition
https://www.mayoclinic.org/diseases-conditions

### User Interface
- The user will use the chatbot similar to how one would message a person on their phone or computer.
- The user will type a question into the text area and press send. Once the chatbot has come up with an answer, it will provide the answer underneath the question asked.
- The user will then be prompted to ask another question or close the chatbot.

### Implementation
This chatbot was made using Python along with various Python libraries:
- NLTK (Natural Language Toolkit) was used for the language processing required
- The Requests, Article, and BeautifulSoup packages were used for scraping articles from the web for data collection
- CountVectorizer was used for the conversion of scraped text into vectors as part of the language processing
- The cosine_similarity package was used for comparing the similarities of the vectors converted using CountVectorizer.

### Additional Thoughts
- More extensive data processing is required in order to improve accuracy of responses.
- More data from various countries could be collected in order better understand the various local diseases and medical conditions.
- This application could be further deployed onto a mobile app for more accessibility.
- Although this chatbot can greatly help patients get accurate answers to their questions, this application should not replace physicians entirely.













