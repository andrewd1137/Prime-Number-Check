#Andrew DeMarco
num1 = input("Enter a Number to Check if it's Prime: ")
temp_num = num1 - 1


def check_prime_number(number, temp_number):
    if temp_number == 1 or temp_number == 2:
        number = str(number)
        print("The number " + number + " is Prime")
    else:
        temp_number2 = num1 % temp_number
        if temp_number2 == 0:
            number = str(number)
            print("The number " + number + " is not Prime")
        else:
            temp_number = temp_number - 1
            return check_prime_number(number, temp_number)


check_prime_number(num1, temp_num)
