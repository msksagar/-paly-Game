import win32com.client as wincon
import time
speak = wincon.Dispatch("SAPI.SpVoice")
mayank = " Hello beautifull people. ,  my self mayank kumar ,  I am from bangloru , \
and my wrok job app developer. wroking for last five year tech company"
speak.speak(mayank)
time.sleep(1)
Enterview = 'whih company mayank'
speak.speak(Enterview)
time.sleep(1)
mayank1 = "sir this company name is wipro"
speak.speak(mayank1)
time.sleep(1)
Enterview = "that's godd"
speak.speak(Enterview)
