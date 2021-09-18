# my_first_code
import time

username = 'mungai'
password = 'sijui'
username_input = input("username: ")
password_input = input("password: ")


if username_input == username and password_input == password:
    print('please wait...')
    time.sleep(2)
    print('.....loading........')
    time.sleep(5)
    print('Access Granted')

elif username_input != username and password_input == password:
    print('please wait...')
    time.sleep(2)
    print('.....loading........')
    time.sleep(5)
    print('Access denied check username ')
elif password_input!= password and username_input == username:
    print('...checking details..')
    time.sleep(3)
    print('wrong password')

else:
    time.sleep(3)
    print('   ......   ')
    time.sleep(2)
    print('wrong username and password')
    time.sleep(1)
    print('please check signIn details...')



