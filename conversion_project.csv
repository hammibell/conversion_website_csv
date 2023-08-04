from tkinter import *
from tkinter import filedialog

root = Tk()
root.title("Converting Customary Units of Lengths")
root.configure(background = "light blue")
root.geometry("500x500")

title = Label(root)
title["text"] = "Converting Customary Units of Lengths"
title.config(font = ('Helvatical bold', 18))
title.place(relx = 0.5, rely = 0.1, anchor = CENTER)

con1 = Label(root)
con1["text"] = "INCHES TO FEET"
con1.config(font = ('Helvatical bold', 13))
con1.place(relx = 0.5, rely = 0.2, anchor = CENTER)

inches_entry = Entry(root)
inches_entry.place(relx = 0.3, rely = 0.3, anchor = CENTER)

inches_label = Label(root)
inches_label["text"] = "Inches"
inches_label.place(relx = 0.4, rely = 0.3, anchor = CENTER)

equal = Label(root)
equal["text"] = "="
equal.place(relx = 0.5, rely = 0.3, anchor = CENTER)

feet = Label(root)
feet["text"] = "0"
feet.place(relx = 0.6, rely = 0.3, anchor = CENTER)

feet_label = Label(root)
feet_label["text"] = "Feet"
feet_label.place(relx = 0.7, rely = 0.3, anchor = CENTER)

def inches_to_feet(event):
    if len(inches_entry.get()) == 0:
        feet["text"] = "0"
        
        
    if not feet_entry1.get() == 0:
        feet["text"] = float(inches_entry.get()) / 12
        

inches_entry.bind("<KeyRelease>", inches_to_feet)


con2 = Label(root)
con2["text"] = "FEET TO INCHES"
con2.config(font = ('Helvatical bold', 13))
con2.place(relx = 0.5, rely = 0.4, anchor = CENTER)

feet_entry = Entry(root)
feet_entry.place(relx = 0.3, rely = 0.5, anchor = CENTER)

feet_label1 = Label(root)
feet_label1["text"] = "Feet"
feet_label1.place(relx = 0.4, rely = 0.5, anchor = CENTER)

equal1 = Label(root)
equal1["text"] = "="
equal1.place(relx = 0.5, rely = 0.5, anchor = CENTER)

inches = Label(root)
inches["text"] = "0"
inches.place(relx = 0.6, rely = 0.5, anchor = CENTER)

inches_label1 = Label(root)
inches_label1["text"] = "Inches"
inches_label1.place(relx = 0.7, rely = 0.5, anchor = CENTER)

def feet_to_inches(event):
    if len(feet_entry.get()) == 0:
        inches["text"] = "0"
    
    if not feet_entry1.get() == 0:
        inches["text"] = float(feet_entry.get()) * 12

feet_entry.bind("<KeyRelease>", feet_to_inches)

con3 = Label(root)
con3["text"] = "FEET TO YARDS"
con3.config(font = ('Helvatical bold', 13))
con3.place(relx = 0.5, rely = 0.6, anchor = CENTER)

feet_entry1 = Entry(root)
feet_entry1.place(relx = 0.3, rely = 0.7, anchor = CENTER)

feet_label2 = Label(root)
feet_label2["text"] = "Feet"
feet_label2.place(relx = 0.4, rely = 0.7, anchor = CENTER)

equal2 = Label(root)
equal2["text"] = "="
equal2.place(relx = 0.5, rely = 0.7, anchor = CENTER)

yard = Label(root)
yard["text"] = "0"
yard.place(relx = 0.6, rely = 0.7, anchor = CENTER)

yard_label = Label(root)
yard_label["text"] = "Yards"
yard_label.place(relx = 0.7, rely = 0.7, anchor = CENTER)

def feet_to_yard(event):
    if len(feet_entry1.get()) == 0:
        yard["text"] = "0"
        
    if not feet_entry1.get() == 0:
        yard["text"] = float(feet_entry1.get()) / 3
    
feet_entry1.bind("<KeyRelease>", feet_to_yard)

con4 = Label(root)
con4["text"] = "YARDS TO FEET"
con4.config(font = ('Helvatical bold', 13))
con4.place(relx = 0.5, rely = 0.8, anchor = CENTER)

yard_entry = Entry(root)
yard_entry.place(relx = 0.3, rely = 0.9, anchor = CENTER)

yard_label1 = Label(root)
yard_label1["text"] = "Yards"
yard_label1.place(relx = 0.4, rely = 0.9, anchor = CENTER)

equal3 = Label(root)
equal3["text"] = "="
equal3.place(relx = 0.5, rely = 0.9, anchor = CENTER)

feet1 = Label(root)
feet1["text"] = "0"
feet1.place(relx = 0.6, rely = 0.9, anchor = CENTER)

feet_label3 = Label(root)
feet_label3["text"] = "Feet"
feet_label3.place(relx = 0.7, rely = 0.9, anchor = CENTER)

def yard_to_feet(event):
    if len(yard_entry.get()) == 0:
        feet1["text"] = "0"
        
    if not yard_entry.get() == 0:
        feet1["text"] = float(yard_entry.get()) * 3
    
yard_entry.bind("<KeyRelease>", yard_to_feet)


def openNewWindow():
    newWindow = Toplevel(root)
    newWindow.title("Converting Metric Units for Length")
    newWindow.geometry("500x500")
    newWindow.config(background = "light green")
    
    title1 = Label(newWindow)
    title1["text"] = "Converting Metric Units for Length"
    title1.config(font = ('Helvatical bold', 18))
    title1.place(relx = 0.5, rely = 0.1, anchor = CENTER)
    
    note = Label(newWindow)
    note["text"] = "NOTE: At the top navigate through the tabs to go back to other conversions"
    note.config(font = ('Helvatical bold', 15))
    note.place(relx = 0.5, rely = 0.15, anchor = CENTER)
    
    newcon1 = Label(newWindow)
    newcon1["text"] = "MILIMETERS (mm) TO CENTIMETERS (cm)"
    newcon1.config(font = ('Helvatical bold', 13))
    newcon1.place(relx = 0.5, rely = 0.2, anchor = CENTER)
    
    mm_entry = Entry(newWindow)
    mm_entry.place(relx = 0.3, rely = 0.3, anchor = CENTER)
    
    mm_label = Label(newWindow)
    mm_label["text"] = "mm"
    mm_label.place(relx = 0.4, rely = 0.3, anchor = CENTER)
    
    newequal = Label(newWindow)
    newequal["text"] = "="
    newequal.place(relx = 0.5, rely = 0.3, anchor = CENTER)
    
    cm = Label(newWindow)
    cm["text"] = "0"
    cm.place(relx = 0.6, rely = 0.3, anchor = CENTER)
    
    cm_label = Label(newWindow)
    cm_label["text"] = "cm"
    cm_label.place(relx = 0.7, rely = 0.3, anchor = CENTER)
    
    def mm_to_cm(event):
        if len(mm_entry.get()) == 0:
            cm["text"] = "0"
            
        if not mm_entry.get() == 0:
            cm["text"] = float(mm_entry.get()) / 10
        
    mm_entry.bind("<KeyRelease>", mm_to_cm)
    
    newcon2 = Label(newWindow)
    newcon2["text"] = "FAHRENHEIGHT (f) TO CELSIUS (c)"
    newcon2.config('Helvatical bold', 13)
    newcon2.place(relx = 0.5, rely = 0.4, anchor = CENTER)
    
    f_entry = Entry(newWindow)
    f_entry.place(relx = 0.3, rely = 0.5, anchor = CENTER)
    
    f = Label(newWindow)
    f["text"] = "F "
    
    
btn = Button(root, text = "Navigate to metric units", command = openNewWindow)
btn.place(relx = 0.5, rely = 0.97, anchor = CENTER)

root.mainloop()

