import time 
def countdown (time_sec):
    while time _sec:
        mins,secs = divmod(time_sec,60)
        timeformat = '{:02d} : {:02d}'.format(mins,secs)
        print (timeformat,end='\r')
        time.sleep(1)
        time_sec -= 1
   Print("stop")
Countdown (5)
