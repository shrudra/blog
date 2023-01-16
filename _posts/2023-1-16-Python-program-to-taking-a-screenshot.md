---
layout: post
title: Python program to taking a screenshot
---
In this article, We will create a program in Python that will take screenshots on our computer.So don’t waste your time, open your computer quickly.

In order to take screenshots we need to install a module that can control the mouse and keyboard of our computer, one such module is PyAutoGUI.

To install PyAutoGUI type the below command in the terminal.

```bash
pip install pyautogui
```

Now we need to install the pillow package.To install Pillow type the below command in the terminal.

```bash
pip install Pillow
```

It’s will take few seconds to install. After installed, we now need to write a program that will take screenshot after 5 seconds.

Below is the implementation.

```python
#Python Program to taking a screenshot
 
#To import pyautogui module
import pyautogui 
 
#To import time module
import time 
 
#To take screenshot after 5 seconds
time.sleep(5) 
 
#To take screenshot 
screenshot = pyautogui.screenshot() 
 
#To save the screenshot
#This image will be saved inside this directory
screenshot.save('image.png')  
 
#Will print a message in terminal, after taken the screenshot
print('screenshot taken.') 
```
