# Codealpha-Task-4
internship purpose
CODE
def chatbot():
    print("Chatbot: Hello! Type something to chat. Type 'bye' to exit.")
    
    while True:
        user_input = input("You: ").lower()
        
        if user_input == "hello":
            print("Chatbot: Hi!")
        elif user_input == "how are you":
            print("Chatbot: I'm fine, thanks!")
        elif user_input == "bye":
            print("Chatbot: Goodbye!")
            break
        else:
            print("Chatbot: Sorry, I don't understand that.")

# Run the chatbot
chatbot()

RESULT
![TASK 4](https://github.com/user-attachments/assets/3923e269-6347-41cf-aeec-1d3de110a4b8)
