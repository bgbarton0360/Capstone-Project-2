# Capstone-Project-2

Natural Language Processing  
Chatbot  

File Descriptions:  
All_seasons.csv - dataset used for processing  
Capstone 2 Slides.pptx - Presentation of project  
Report.pdf - Detailed findings and reasonings  
Project2.ipynb - Coding for project  
  Figures  
    Bigram - most common two word phrases used  
    Trigram - most common three word phrases used  
    BoW - Bag of Words   
    TFIDF - Term Frequency Inverse Document Frequency  
    Wordcloud - most common single words  
    
This project is using the scripts from the television South Park to create chatbots that are able to talk to the user input with the most appropriate response.
The chatbots will also be to communicate with each other to create a loop of dialogue between each other.
With some television shows having been on the air for hundreds of episodes sometimes its hard to come up with fresh new dialogue that hasn't been done before in the show.
This project is seeking to solve the problem of creating new dialogue and interactions of established characters solely based on their previous data.

By taking the existing the data, the aim of this project works by implementing an NLP language model we can access work that abides by the parameters of the characters that have 
previously been determined.  Our client would be the creators and producers of the show, and our job is to convince them that using our model can work by checking that new 
dialogue created would match the personality of the character.
Using Bag of Words Model and TF-IDF Model this project will compare which model works best for the implementation of these chatbots.

Final Results show that the models perform identically when given a single word input.  We see a difference when we have a question with multiple words that need to be compared 
against.  Bag of Words will match its response with the line that matches the most words while TF-IDF will match the single word with the highest score and give a line based on 
that one word. 
