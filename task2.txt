# Basic Chatbot

def chatbot():
    print("Simple Chatbot")
    print("Type 'bye' to exit.\n")

    while True:
        # User input
        user_input = input("You: ").lower()

        # Chatbot replies
        if user_input == "hello":
            print("Bot: Hi!")

        elif user_input == "how are you":
            print("Bot: I'm fine, thanks!")

        elif user_input == "what is your name":
            print("Bot: I am a simple chatbot.")

        elif user_input == "bye":
            print("Bot: Goodbye!")
            break

        else:
            print("Bot: Sorry, I don't understand that.")

# Run chatbot
chatbot()