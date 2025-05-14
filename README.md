#simple chatbot program
def chatbot():    
  print("Chatbot: Hi!, I'm your simple chatbot. Ask me anything or type 'exit' to end the chat.")

  #predefined responses
  responses ={
    "hello":"Hello! How can I help you today?",
    "how area you": "I"m just a bot,but I"m doing fine.Thanks for asking !"
    "what is your name": "I am a chatbot,your virtual assistant."
    "bye": "Goodbye!Have a great day!"
    "help:"Sure,I'm here to help!What do you need?"


while True:
    user_input = input("You:").strip().lower() # Get user input and make it lowercase

     if user_input == "exit":
         print("chatbot: Goodbye!")
         break

     #Respond based on predefined responses or use a default message
     response = responses.get(user_input,i don't understand that.GN)
