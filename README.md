#import libraries, import from the libraries
import tkinter
from tkinter import *
import webbrowser
from webbrowser import *
#def all functions

def funcion():
    webbrowser.get(
    "C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("https://discord.com/channels/@me"
    )
    print("Discord has been opened")
 
def funcion2():
    print("Youtube has been opened")
    webbrowser.get("C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("https://www.youtube.com/")

def funcion3():
    print("Twitch has been opened")
    webbrowser.get("C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("https://www.twitch.tv/")

def funcion4():
    print("Slimefun has been opened")
    webbrowser.get("C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("https://github.com/Slimefun/Slimefun4/wiki")

def funcion5():
    print("Pablo")
    webbrowser.get("C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("https://www.google.com/search?q=anime+girl&oq=anime+girl&aqs=chrome..69i57j0i131i433i512j0i433i512j0i512l7.3417j1j7&sourceid=chrome&ie=UTF-8")

def funcion6():
    print("Soundcloud")
    webbrowser.get("C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("https://soundcloud.com/discover")

def funcion7():
    print("Twitter has been opened")
    webbrowser.get("C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("https://twitter.com/home")

def funcion8():
    print("Facebook has been opened")
    webbrowser.get("C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("https://www.facebook.com/")

def funcion9():
    print("Classroom has been opened")
    webbrowser.get("C:/Program Files (x86)/Google/Chrome/Application/Chrome.exe %s").open_new("")


def funcion10():
    print("MENU has been opened")
    from cgitb import text
    import cmd
    import time
    from tracemalloc import start
    import turtle
    
#importaciones y pendejadas

    wn = turtle

#funcion k creo y nunca voy a usar

    print("-------------------------------")
    print("--------------MENU-------------")
    print("-------------------------------")
    print("")
    print("for -bank-: type number -1- ")
    print("")
    print("for -shop-: type number -2-")
    print("")
    print("for -shaper-: type number -3-")


    value = input(("SET:"))



    if value == "1":
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("directing you to -bank-")
        print("")
        print("-------------------------------")
        print("-------------Bank--------------")
        print("-------------------------------")
   
                                    #alaverga me pase con los "elifs"
    elif value == "2":
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("directing you to -shop-")
        print("")
        print("-------------------------------")
        print("-------------Shop--------------")
        print("-------------------------------")
    elif value == "3":
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("")
        print("directing you to -shaper-")
        print("")
        print("-------------------------------")
        print("------------Shaper-------------")
        print("-------------------------------")
        print("")
        print("square_code = draw a square")
        print("circle_code = draw a circle")
    shaper = input(("SET:"))
    if shaper == "draw a square":
        print("shaper working...")
        eula = 1
        for eula in range(10):
            print("drawing...")
            wn.bgcolor("black")
            wn.color("blue")
            wn.forward(100)
            wn.left(90)
            wn.forward(100)
            wn.left(90)  
         
    elif shaper == "draw a circle":
        for eula in range(10):
            print("drawing...")
            wn.bgcolor("black")
            wn.color("green")
            wn.circle(100)
#polla galactica con sida y sifilis con heptitis nivel 3 alaverga :
                            #si no pones cosas vien te ba a salir esto asi que pon 1 2 3 pendejo :D
    else:
        print("Sorry this number do not exists in this program, run the program again!")
        sm = Tk()
        sm.title("test")
        sm.geometry("400x400")
        sm.config(bg="Black")
        label = Label(text="WRONG SYNTAXIS, TRY AGAIN!!!")
        label.pack()
        sm.mainloop()
    

#create a window with Tkinter
window = Tk()
window.title("GUI(click a button to open a browser window)")
window.geometry("400x400")
window.config(bg="Black")


boton1 = Button(window, text = "Discord",command = funcion, bg="Blue", fg="white")
boton1.place(x=250, y=60)
boton1.config(font=("Bahnschrift_SemiBold"))

boton2 = Button(window, text = "Youtube",command = funcion2, bg="red", fg="white")
boton2.place(x=170, y=60)
boton2.config(font=("Bahnschrift_SemiBold"))

boton3 = Button(window, text = "Twitch",command = funcion3, bg="magenta", fg="white")
boton3.place(x=100, y=60)
boton3.config(font=("Bahnschrift_SemiBold"))

boton4 = Button(window, text = "Slimefun",command = funcion4, bg="gray", fg="white")
boton4.place(x=90, y=300)
boton4.config(font=("Bahnschrift_SemiBold"))

boton5 = Button(window, text = "RandomVid",command = funcion5, bg="Brown", fg="white")
boton5.place(x=90, y=260)
boton5.config(font=("Bahnschrift_SemiBold"))

boton6 = Button(window, text = "SoundCloud",command = funcion6, bg="orange", fg="white")
boton6.place(x=100, y=100)
boton6.config(font=("Bahnschrift_SemiBold"))

boton7 = Button(window, text = "Twitter", command= funcion7, bg="turquoise", fg="white")
boton7.place(x=210, y=100)
boton7.config(font=("Bahnschrift_SemiBold"))

boton8 = Button(window, text = "Facebook", command = funcion8, bg= "blue", fg= "white")
boton8.place(x=100, y=140)
boton8.config(font=("Bahnschrift_SemiBold"))

boton9 = Button(window, text= "Classroom", command = funcion9, bg= "lime", fg="white")
boton9.place(x=280, y=100)
boton9.config(font=("Bahnschrift_SemiB200"))

boton10 = Button(window, text= "DEBUG", command = funcion9, bg= "black", fg="white")
boton10.place(x=100, y=180)
boton10.config(font=("Bahnschrift_SemiB200"))

boton11 = Button(window, text= "MENU", command = funcion10, bg= "black", fg="white")
boton11.place(x=170, y=180)
boton11.config(font=("Bahnschrift_SemiB200"))

window.mainloop()
