## Artificial Intelligence <h2>

Team 10
Lina Li,  Xuanzuo Liu,  Jinyu Tian, Santhosh Ranganathan, Zhi Lu
 
### Introduction <h3>

  *	Overview

    Developing minesweeper and implementing AI in minesweeper solver which play the game with Probability method and CSP search algorithm. In additional task is to make the AI be able to compete with other players.

  *	Main Idea
    
    Minesweeper is a classic game with simple rules, it is interesting and challenging, even for searching algorithms. 
    1.	Write the minesweeper game 
    2.	Design an AI solver for the minesweeper with Probability method search algorithm. The minesweeper solver finds the best spot of next movement. 
    3.	Build the GUI with Tkinter packages.
    4.	Add another AI solver for the minesweeper with another search Algorithm (Constraint Satisfaction Problem). The minesweeper solver finds the best spot of next movement.
    5.	(Optional) The minesweeper solver will be able to play with multiple players. (different flags for the mines they found, the number of flags decides who is winner)

### Components of Minesweeper Solver <h3>
    
    Tkinter: it is a Python binding to the Tk GUI toolkit. It is the standard Python interface to the Tk GUI toolkit and is Python's defacto standard GUI. Tkinter is included with standard Linux, Microsoft Windows and Mac OS X installs of Python. The name Tkinter comes from Tk interface. We use Tkinter to create the frame interface of the game. Including the drop-down menu, restart button. and listener to the event when the status of square is changed. 


 ![The window of small size Minesweeper](/image.png)
 
### Environment Setup: <h3>
  
  1. Install pyCharm IDE
  2. Install Python Interpreter
    All the packages can be version as given below with python interpreter.
  #### Python version 3 <h4>

### Dependencies: <h3>

* Minesweeper Solver depends on the following libraries:
* cycler==0.10.0
* decorator==4.4.1
* imageio==2.6.1
* joblib==0.14.0
* kiwisolver==1.1.0
* matplotlib==3.1.1
* networkx==2.4
* numpy==1.17.3
* Pillow==6.2.1
* pyparsing==2.4.4
* python-constraint==1.4.0
* python-dateutil==2.8.1
* PyWavelets==1.1.1
* scikit-image==0.16.2
* scikit-learn==0.21.3
* scipy==1.3.1
* six==1.13.0



### Demo: <h3>
  
* Open the minesweeperSolver.py which have GUI demo with the Probability method algorithm. Choose your custom or prefer size of number of mines and cells. When you click restart. The search algorithm will start to calculate and update the window in the end
* It will compile through all the functions and install the packages. 
* Open the minesweeper.py which have the both CSP Algorithm and Probability Method. Change the calling method inside the last line of auto_play function. You will see how the two algorithm’s performance with 10*10 with 30 mines after 100 trails.

### References: <h3>
  1. A Minesweeper Solver Using Logic Inference, CSP and Sampling. ( https://arxiv.org/pdf/1810.03151v1.pdf )
  1. Minesweeper Solver - Using Deep Reinforcement Learning. ( https://github.com/jakejhansen/minesweeper_solver )
  1. A Minesweeper Solver Using Logic Inference, CSP and Sampling. ( https://arxiv.org/pdf/1810.03151v1.pdf )
  1. Magnus Hoff, Solving Minesweeper: https://magnushoff.com/minesweeper/
  1. Becerra, David J. 2015. Algorithmic Approaches to Playing Minesweeper. Bachelor's thesis, Harvard College. (http://nrs.harvard.edu/urn-3:HUL.InstRepos:14398552 )
  1. Stanford Minesweeper CSP: https://www.google.com/url?sa=t&source=web&rct=j&url=http://web.stanford.edu/class/archive/cs/cs221/cs221.1192/2018/restricted/posters/thowarth/poster.pdf&ved=2ahUKEwiphKWEiKLmAhVuUd8KHSC3BoAQFjAAegQIBxAB&usg=AOvVaw0zbWSbdlhORl_80quF0bTL

