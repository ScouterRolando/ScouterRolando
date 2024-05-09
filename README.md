# Sample user database
users = {
    "user1": "password1",
    "user2": "password2",
    "user3": "password3"
}

def login():
    username = input("Enter your username: ")
    password = input("Enter your password: ")

    # Check if username exists in the database and if the password matches
    if username in users and users[username] == password:
        print("Login successful!")
    else:
        print("Invalid username or password. Please try again.")

# Main program
def main():
    print("Welcome to the login system!")
    login()

if __name__ == "__main__":
    main()
