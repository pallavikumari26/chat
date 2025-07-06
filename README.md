# chat
# Rule-based Chatbot in Python

def chatbot():
    print("🤖 Hello! I'm ChatBot. Type 'bye' to exit.")
    
    while True:
        user_input = input("You: ").lower()

        if user_input in ['hi', 'hello', 'hey']:
            print("Bot: Hello! How can I help you today?")
        elif "your name" in user_input:
            print("Bot: I'm a simple rule-based chatbot.")
        elif "how are you" in user_input:
            print("Bot: I'm doing well! Thanks for asking.")
        elif "help" in user_input:
            print("Bot: Sure! I'm here to answer your basic questions.")
        elif "bye" in user_input:
            print("Bot: Goodbye! Have a great day 😊")
            break
        else:
            print("Bot: Sorry, I didn't understand that.")

# Run the chatbot
if __name__ == "__main__":
    chatbot()
