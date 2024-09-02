import random
import time

# Define the playful message
message = "Hey, do you still love me?"

# Define possible playful responses
responses = [
    "Of course, I do! 💖",
    "Maybe... 😉",
    "Always and forever! 💘",
    "You're the only one! 😘",
    "Hmm, let me think... Just kidding, YES! 😍"
]

# Display the message
print(message)

# Add a slight delay for dramatic effect
time.sleep(2)

# Print a random playful response
print(random.choice(responses))
