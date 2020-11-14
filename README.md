

#project on chrome dinosaur game









import pyautogui
pyautogui.keydown('h')
from PIL import Image,ImageGrab
           # from numpy import asarray
from numpy 
import timemodule 
def hit
def draw():
   for i in range(34,45):
    for j in range(45,67):
    
def iscollide(data):
   for i in range(300,415):
    for j in range(600,650):
                 data[i,j]<100
                 return true
             return false


def takescreenshot():
 image=Imagegrab.grab().convert('L')
 image.show()
 return image 
 
 if _name_=="main":
   time.sleep(1)
   while True:
  image=takescreenshot()
  data=image.load()
  if iscollide(data):
  hit("up")
  #print (asarray(image))  
  for i in range(300,415):
    for j in range(600,650):
                 data[i,j]=0
                 
                 #image.show()
   
   

