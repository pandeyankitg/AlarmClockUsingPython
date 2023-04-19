# AlarmClockUsingPython
The code begins by importing the necessary libraries - time for time-related functions, playsound to play the alarm sound, and tkinter to create the GUI window.

Next, a GUI window is created using the Tk() method from tkinter. The title and dimensions of the window are set using the title() and geometry() methods.

A label widget is created using the Label() method to prompt the user to set the alarm. An entry widget is also created using the Entry() method to allow the user to input the alarm time.

The set_alarm() function is defined to set the alarm based on the user input. The alarm time is obtained from the entry widget using the get() method, converted to seconds, and time.sleep() is used to pause the program for the specified alarm time. The alarm sound is played using playsound.playsound(). Finally, a message box is displayed using the messagebox.showinfo() method to notify the user that the alarm has gone off.

A button widget is created using the Button() method to allow the user to set the alarm. The command parameter is set to the set_alarm() function.

Finally, the GUI window is run using the mainloop() method.
