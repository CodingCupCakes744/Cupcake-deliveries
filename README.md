# def cupcake_order():

#Just an update to my progress....
    name = input("Hello, may I know your name? ")
    no = int(input("How many cupcakes do you want? "))

    if no < 10:
        print(f"Hi {name}, we really appreciate you dropping by! Just a heads-up: if you grab 10 or more cupcakes, we’ll throw in 5 extra—for free!")

    if no >= 10:
        print(f"Awesome choice, {name}! Since you ordered {no} cupcakes, you qualify for our sweet deal—5 bonus cupcakes! Your total: {no + 5} cupcakes. Enjoy!")
        for i in range(1, no + 6):
            print(f"Cupcake #{i} delivered!")
            
cupcake_order()Cupcake-deliveries
