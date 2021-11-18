print("Enter your details")
option = input("Enter your Name = ")
option = input("Enter your E-mail ID = ")
option = input('Enter your Age = ')
print('')
print('Instructions')
print('1-You have to attempt all the question')
print('2-Each question carries 5 mark .')
print('There will be 2 questions')
print('')
print('Now lets start the QUIZ')
score = 0
total_score = 10
print(" Welcome to the quiz")
print("")
print("Q1 - who made the great wall of china")
print("A = Qin shi Huang")
print("B = Yang CHi")
print("C = Chen Yang")
print("D = Liu Huang Zhao")
print("")
option = input("Enter the correct option")

if option == 'A' or option == 'a':
    print("correct")
    score = score + 5
else: 
    print("incorrect")
    print('the correct answer is -Qin shi Huang')
print('------------------------')
print("Q2 - Who is the founder of Samsung")
print("A = Lee Byung-haul")
print("B = Yang CHi")
print("C = Lee Byung-chul")
print("D = Liu Huang Zhao")
print("")
option = input("Enter the correct option")

if option == 'C' or option == 'c':
    print('correct')
    score = score + 5
else:
    print('incorrect')
    print('the correct answer is -Lee Byung-chul')
print('------------------------')
print('')
print(f'YAY, you have completed the Quiz with score -{score}/{total_score}')
print('Thanks for your valuable time ')

