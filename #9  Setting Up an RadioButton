#Importing Tkinter Moduele
from tkinter import *
from PIL  import ImageTk,Image
#Building Up the screen
window = Tk()
window.title("Programming TT 2.0")
window.iconbitmap('logo.ico')

#List Of String to be added in RadiButtons
data_list = [
	"Male",
	"Female",
	"Rather Not to say"
	]

def Radio_get(value):
	lb.config(text=f"Option Selected : {value}")
  
#RadioButton Variable
r = StringVar()
r.set(data_list[0])

for rec in data_list:
	Radiobutton(window, text=rec, variable=r, value=rec).pack(anchor=W,pady=20)

Bt = Button(window, text="Enter", command=lambda:Radio_get(r.get()))
Bt.pack()
lb = Label(window, text="", font=("Arial Bold",20))
lb.pack()

window.mainloop()
