# fun_traffic_light
#traffic signal
#write a program that simulates a traffic light.
#the program should consists of the fallowing:
#here 2 condition s
#function 1 traffic light
#function 2 light
#colours red  green and yellow


def trafficlight():
    signal=input("enter the colour of the traffic signal light:")
    if (signal not in ("RED" ,"YELLOW","GREEN" )):
        print("enetr a valid traffic ligth colour in capitals")
    else:
        value=light (signal)
        if value==0:
            print("stop,your life fis precious")
        elif value==1:
            print("plese go slow")
        else:
            print("go thankou for being patient")
def light(colour):
    if colour=="RED":
        return 0
    elif colour =="YELLOW":
        return 1
    else:
        return (2)
#function end here
#function calling
trafficlight()
print("speed thrills but kills")

#input
    # RED
#output
    #stop,your life fis precious
     #speed thrills but kills
    
