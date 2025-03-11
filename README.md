def classify_age(age):
    while True:
        a = int(input("Classifying age"))
        if a >= 0 and a <= 12:
            print("your age is classified as a child")
        elif a >= 13 and a <= 19:
            print("your age is classified as a teen")
        elif a >= 20 and a <= 64:
            print("your age is classified as an adult")
        elif a >= 65:
            print("your age is classified as a senior")
        else:
            print("Invalid! Input your age.")

classify_age(1)
