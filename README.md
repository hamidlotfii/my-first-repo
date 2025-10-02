def greet(name: str) -> str:
    """
    Returns a friendly greeting message.
    
    Args:
        name (str): The name of the person to greet 

    Returns:
        str: Greeting message.
    """
    return f"Hello, {name}! Welcome to my GitHub repository."

if __name__ == "__main__":
    user_name = input("Enter your name: "
    print(greet(user_name))
