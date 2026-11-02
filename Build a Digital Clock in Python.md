**Build a Digital Clock in Python**



import tkinter as tk

from time import strftime 



root = tk.Tk()

root.title("Digital Clock")



def time():

&#x20;string = srftime('%H:%M:%S %p \\n %D')

&#x20;label.config(text=string)

&#x20;label.after(1000,time)





label = tk.Label(root, font=('calibri', 50, 'bold'), background= 'Yellow', foreground='black')

label.pack(anchor='center')



time()

root.mainloop()



