import pyautogui
import time 
time.sleep(5)
count=1                                                 #start with Hi 01 and end in Hi 100
while count<=100:                                       #How many time to auto type hi
    pyautogui.typewrite("Hi"+str(count), interval=0.05) #auto typing in your mouse location with 0.05 sec deley for security security reasons
    pyautogui.press("enter")                            #auto key press after typing 
    count=count+1                                       #count=count+1 is use for example:Hi 01,Hi 02,Hi 03....
