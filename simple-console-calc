#importing maty module to carry out complex math problems
from math import *
# importing time module to cause CPU delay during execution
from time import *

# function to get user input
def calculator():
    #making varibles global 
   global num1, operator, num2
   print('loading, pleasewait...')
   #time delay by stopping CPU action for 1 second
   sleep(1)
   
   print('_' * 60, ' ' *20, 'CALCULATOR', '\n', '_' * 58)
   #getting user input, user pmust press enter to record his values 
   num1 = float((input('\nnum1: ')))
   operator = input('\nsign: ')
   num2 = float(input('\nnum2: '))

#function to determine operator used by user using if...elif statements   
def op_determine():
     if operator == '+':
         ans = num1 + num2
         print('=', ans)
     elif operator == '-':
         ans = num1 - num2
         print('=', ans)
     elif operator == '*':
         ans = num1 * num2
         print('=', ans)               
     elif operator == '/':
         ans = num1 / num2
         print('=', ans)
     else:
         print('invalid operator')
       
#fuction to perform trigonometric  calculations
def trigonometry():
    trig_func = input('calculate sin, cos or tan: ')
    if trig_func == 'sin':
        sin_op = sin(int(input('sin(')))
        sleep(1)
        print(sin_op)
    elif trig_func == 'cos':
        cos_op = cos(int(input('cos(')))
        sleep(1)
        print(cos_op)
    elif trig_func == 'tan':
        tan_op = tan(int(input('tan(')))
        sleep(1)
        print(tan_op)
                  
# calling the functions
calculator()
op_determine()
trigonometry()
                                      
# calculating factorial
num_factorial= factorial(int(input(('enter number whose factorial you want to find: '))))
print(num_factorial)
