import tkinter
from tkinter import*

root=Tk()
root.title("Grade Calcualtor")
root.geometry("500x400")

def Calculation():
    electrical=int(electricalentry.get())
    maths=int(mathsentry.get())
    physics=int(physicsentry.get())
    mechanical=int(mechanicalentry.get())
    python=int(pythonentry.get())
    total=(electrical+maths+physics+mechanical+python)
    Label(text=f"{total}",fon="arial 15 bold").place(x=250,y=270)
    
    average=int(total/5)
    Label(text=f"{average}",fon="arial 15 bold").place(x=250,y=320)
    
    if (average>50):
        grade="PASS"
    else:
        grade="FAIL"
    Label(text=f"{grade}",fon="arial 15 bold",fg="blue").place(x=250,y=370)
title=Label(root,text="Enter marks out of 100",font="arial 10")

sub1=Label(root,text="Physics:",font="arial 10")
sub2=Label(root,text="Maths:",font="arial 10")
sub3=Label(root,text="Electrical:",font="arial 10")
sub4=Label(root,text="Mechanical:",font="arial 10")
sub5=Label(root,text="Python:",font="arial 10")
total=Label(root,text="Total:",font="arial 10")
avg=Label(root,text="Average:",font="arail 10")
grade=Label(root,text="Grade:",font="arial 10")

title.place(x=50,y=10)

sub1.place(x=50,y=20)
sub2.place(x=50,y=70)
sub3.place(x=50,y=120)
sub4.place(x=50,y=170)
sub5.place(x=50,y=220)
total.place(x=50,y=270)
avg.place(x=50,y=320)
grade.place(x=50,y=370)

electricalvalue=StringVar()
mathsvalue=StringVar()
physicsvalue=StringVar()
mechanicalvalue=StringVar()
pythonvalue=StringVar()

electricalentry=Entry(root,textvariable=electricalvalue,font="arial 15",width=15)
mathsentry=Entry(root,textvariable=mathsvalue,font="arial 15",width=15)
physicsentry=Entry(root,textvariable=physicsvalue,font="arial 15",width=15)
mechanicalentry=Entry(root,textvariable=mechanicalvalue,font="arial 15",width=15)
pythonentry=Entry(root,textvariable=pythonvalue,font="arial 15",width=15)

electricalentry.place(x=250,y=20)
mathsentry.place(x=250,y=70)
physicsentry.place(x=250,y=120)
mechanicalentry.place(x=250,y=170)
pythonentry.place(x=250,y=220)

Button(text="Calculate",font="arial 15",bg="white",bd=10,command=Calculation).place(x=50,y=420)
Button(text="Exit",font="arial 15",bg="white",bd=10,width=8,command=lambda:exit()).place(x=350,y=420)


root.mainloop()
