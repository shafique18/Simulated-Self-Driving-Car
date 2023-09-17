# Simulated-Self-Driving-Car

here we are using

1 - pytorch (Python library) - open source machine learning library for Python

2 - kivy - Python library for rapid development of applications
            that make use of innovative user interfaces, such as multi-touch application.
            
            
# first install Anaconda in your system

# How to install PyTorch

  conda install pytorch-cpu -c pytorch 

  for gpu please follow the pytorch documentation
  
  pip3 install torchvision
  
  or you can visit - https://pytorch.org
  
  
# How to install kivy

 - first install dependencies required for Kivy
 
 - second install proper cython version
 
 - now install kivy in your system
 
 - you can visit - https://kivy.org
 
 
 # How to run
 
   - download or clone repository in your system and save the files inside a self driving car folder
   
   - now start spyder IDE which is automaically installed at the time of anaconda installation using Anaconda navigator or you can type
        
        - spyder (In terminal)
        
   - go to you project directory and restart kernel so your current directory should become your working directory.
   
   - now run map.py file
   
        - try with multiple option like
            
            - first try with setting T=0 at the line no 63 (probs = F.softmax(self.model(Variable(state, volatile = True)) * T ) in ai.py so artificial Intelligence will not work on the system.The system work randomly for random paths.
            - now increase the T value so AI will start working on the system it will start predicting the path from source to destination.In given system lower right corner of the window is source and upper left corner of the window is destination.for more certainty increase T value.
            - now try to draw the path in window and observe the car behaviour in system.For simple paths it will work properly but for complex paths you have to customize the code.
        
