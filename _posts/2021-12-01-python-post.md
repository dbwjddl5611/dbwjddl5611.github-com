---
layout: post
title: "Fan Class"
date: 2021-12-01
excerpt: "A ton of text to test readability with image feature."
tags: [sample post, readability, test, image, feature]
feature: http://i.imgur.com/Ds6S7lJ.png
comments: true
---


## Class Fan 


<pre><code>
class Button:
  def __init__ (self):
    self.상태 = False
  def press(self):
    if self.상태:
      return False
    else:
      self.상태 = True
      return True

class Motor:
  def __init__(self):
    self.상태=False
  def powerUp(self):
    if self.상태:
      return False
    else:
      self.상태 = True
      return True
    def work(self):
      pass

class Blade:
  def move(self):
    pass

class Fan:
  def __init__ (self):
    self.button = Button()
    self.motor = Motor()
    self.blade = Blade()
  def 누르다(self):
    self.button.press()
  def 작동하다(self):
    if (self.button.press()):
      while self.motor.work():
        self.blade.move()

a=Fan()
a.누르다()
a.작동하다()


</code></pre>


