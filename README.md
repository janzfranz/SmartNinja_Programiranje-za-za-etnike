# SmartNinja_Programiranje-za-zacetnike

# Homework 1.1: The mood checker

print("Kako si?")

mood = "Dobro"

if mood == "Odlicno":
    print("Lepo te je videti srečnega.")

elif mood == "Slabo":
    print("Ne sekiraj se.")

elif mood == "Žalostno":
    print("Bo že.")

elif mood == "Vznemirjeno":
    print("Kaj te čaka?")

elif mood == "Na izi":
    print("Kava ali pivo?")

else:
    print("Ne štekam.")


# Homework 1.2: Guess the secret number

secret = int("5")

guess = int(input("The secret number is: "))

if secret == guess:
    print("Congrats, your guess is correct!")

else:
    print("That is not the secret number. You can try again.")
    guess = int(input("The secret number is: "))

#(Poskušal sem narediti zanko ponavljanja, dokler ne bi ugotovili pravilne skrivne številke. Ni mi uspelo. Kako bi jo naredil?)


#Homework 1.3: Calculator

stevilo1 = int(input("Vnesite željeno naravno število: "))
stevilo2 = int(input("Vnesite drugo naravno število: "))
operacija = input("Vnesite računsko operacijo: ")

if operacija == "+":
    print(int(stevilo1 + stevilo2))

elif operacija == "-":
    print(stevilo1-stevilo2)

elif operacija == "/":
    print(stevilo1/stevilo2)

elif operacija == "*":
    print(stevilo1*stevilo2)

else:
    print("Prišlo je do napake. Poskusite ponovno. Vnesite po dve naravni števili in nato računsko operacijo: +, -, / in *.")


