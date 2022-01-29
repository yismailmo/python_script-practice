# python_script-practice 2
# build a game to start, stop and quit with your car 
#  with DRY method (Don't repeat yourself)
command = " "
while command.lower() != "quit":
    command = input(">")
    if command.lower() == "start":
        print("Start your car")
    elif command.lower() == "stop":
        print("stop your car")
    elif command.lower() == "help":
        print("""
        start - to start your car
        stop - to stop your car
        quit - to quit
        """)
    else:
        print("Sorry, I don't understand that")
        
