

#project on chrome dinosaur game



import pyautogui # pip install pyautogui
from PIL import Image, ImageGrab # pip install pillow
# from numpy import asarray
import time

def hit(key):
    pyautogui.keyDown(key)
    return

def isCollide(data):
    # Draw the rectangle for birds
    for i in range(300, 415):
        for j in range(410, 563):
            if data[i, j] < 100:
                hit("down")
                return

    for i in range(300, 415):
        for j in range(563, 650):
            if data[i, j] < 100:
                hit("up")
                return
    return

if __name__ == "__main__":
    print("Hey.. Dino game about to start in 3 seconds")
    time.sleep(2)
    # hit('up') 

    while True:
        image = ImageGrab.grab().convert('L')  
        data = image.load()
        isCollide(data)
            
        # print(asarray(image))
        '''
        # Draw the rectangle for cactus
        for i in range(275, 325):
            for j in range(563, 650):
                data[i, j] = 0
        
        # Draw the rectangle for birds
        for i in range(250, 300):
            for j in range(410, 563):
                data[i, j] = 171

        image.show()
        break
      '''







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
   
   
   
   /*
   PACKAGES TO BE INSTALL PIP INSTALL PYAUTOGUI(USED FOR AUTOMATING THE KEYBOARD)
   main.py(filename)
   import pyautogui              //we can use our keyboard keys and also mouse 
   from PIL import image,ImageGrab
   from numpy as array
   import time
   def hit(key)
      pyautogui.keyDown()
   def draw()
       for i in range()
            for j in range()
             data
  def isCollide(data)
    for i in range():
          for j in range():
            if data[i,j]<100:
             return True
  return false;
   
    if __name__=="__main__":
       //it will take the screenshot of the current window 
       print("Hey dinogame is gonna start")
        time.sleep(3)
        hit('up')
     while True:
        image=ImageGrab.grab().convert('L')
        data=image.load()
        iscollide(data):
        hit("up")
       # print(data)
        #print(asarray(image))
        for i in range():
          for j in range():
               data[i,j]=0                                 #greyscale image vs coloured image black =0   white =255    
               # to see if the rectangle is black or not
        # image.show()
               
          
        
        
  /* while True:
   pytogui.keyDown('s')
   pytogui.keyDown('o')
   pytogui.keyDown('u')
   pytogui.keyDown('m')//soum will be written automatically
   the do pip install pillow 
   import using PIL
   */
   
  
   
   
   
    
   
   
   
   
   
   
   
   
   

