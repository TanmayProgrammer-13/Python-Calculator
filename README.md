sum = 0
while(True):
    userInput = input("Enter The Item Price Or Press q To Quit:\n")
    if(userInput!='q'):
        sum = sum + int(userInput)
        print(f"Your Order Total Is:{sum}")
    else:
        print(f"Your Bill Total Is {sum}. Thanks For Shopping With Us")
        break
