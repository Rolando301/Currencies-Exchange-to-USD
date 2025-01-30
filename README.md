# Currencies
GEL = 0.35
RMB = 0.14
EUR = 1.04
TRY = 0.28

# loop
while True:
    
    # pick a currency
    Pick_Currency = input('Pick a currency: ')
    
    # RMB
    if Pick_Currency == 'RMB':
        number1 = input('Pick a number: ')
        print(float(RMB * float(number1)))

    # GEL    
    elif Pick_Currency == 'GEL':
        number2 = input('Pick a number: ')
        print(float(GEL * float(number2)))

    # EUR        
    elif Pick_Currency == 'EUR':
        number3 = input('Pick a number: ')
        print(float(EUR * float(number3)))

    # TRY            
    elif Pick_Currency == 'TRY':
        number4 = input('Pick a number: ')
        print(float(TRY * float(number4)))
