---
layout: project
type: project
image: img/BlackJack.png
title: "Black Jack Game"
date: 2022
published: true
labels:
  - Python
  - Jupyter Notebook
summary: "I created a black jack game application."
---



## About the project
This is an apps to play Blackjack by using TKInter module and random module in Python.
random.randint() and random.seed(1), which are ensuring that they are dealt with an equal probability.
It is possible to play a game match against a virtual opponent as a dealer.
This app can be working well when you kill a time!
However, this project has not sufficiently considered user graphics. Therefore, I believe that a more visually appealing version can be created by incorporating more photos and motion, or by using JavaScript React.


## Code Reference
```
import random as R
import tkinter as tk


A = 11
J = 10
Q = 10
K = 10
cards = [A,2,3,4,5,6,7,8,9,10,J,Q,K]
total = 0
```
```
def hit():
    global total
    i = R.randint(1, 12)
    draw = cards[i]
    print(f'{draw}を引きました。')
    if draw == cards[0] and (total + draw) > 21:
        total -= 10
    total += draw
    print(f'合計は{total}です。')
```
```
def stay():
    global total
    print(f'合計は{total}です。')
```
```
def Black_Jack():
    global total
    global count

    for xx in range(2):
        count += 1
        hit()
    
    if total == 21 and count == 2:
        print('ブラックジャック')
    
    while total < 21:
        turn = input('ヒット or ステイ')
        
        if turn == 'ヒット':
            hit()
            
        elif turn == 'ステイ':
            stay()
            if total <= 15:
                print('弱気ですね。')
                
            elif 15 < total and total < 20:
                print('グッジョブ！')
                
            elif 20 <= total and total <= 21:
                print('エクセレント！')
                
            break
            
        else:
            total ==True
            
    if total + cards[0] > 21:
        cards[0] -= 10
    
    if total > 21:
        print('バーストです。残念！')
        
    elif total == 21:
        print('ピッタリです！お見事！')
    return total
```

```
total = 0
count = 0
Black_Jack()
```

```
def _root_():
    Black_Jack()
    root2 = tk.Tk()
    root2.geometry('700x400')
    root2.title('ブラックジャック')

    button_hit = tk.Button(root2, text='ヒット', font=('Helvetica'), command=hit)
    button_hit.place(x=200, y=300, width=80, height=50)

    button_stay = tk.Button(root2, text='ステイ', font=('Helvetica'), command=stay)
    button_stay.place(x=400, y=300, width=80, height=50)

    Total = tk.Label(root2, text=f'合計 {total}', font=('Helvetica', 50))
    Total.place(x=160, y=150, width=380, height=100)
    root2.mainloop()
    
root = tk.Tk()
root.geometry('700x400')
root.title('Click the button to start Black Jack')

button_start = tk.Button(root, text='スタート', font=('Helvetica'), command=_root_)
button_start.place(x=300, y=150, width=100, height=100)

root.mainloop()
```

## What I have learned form the project
In this project, I did not use class methods and wrote the program code considering two players(you and a dealer), which resulted in a long length of the code unnecessarily. For instance, there's an initialization of 'total = 0' in the first block, and also this initialization is repeated before the definition of function called '_root_()'. If I used a class methods, these repetitive lines could be not necessary, which help to sav my time. Consequently, I implemented the UI(User Interface) using Tkinter module.
However, compared with JavaScript's React, it's quite basic as for not instantly resetting the game results.
I found the case which Object-Oriented Programming Language work, which motivated me to learn other languages besides Python or SQL.
