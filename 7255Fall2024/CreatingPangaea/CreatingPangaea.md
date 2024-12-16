
Learning and Creating Pangaea <br>
---
<br>

<img src="Images/C++.png"/>
---

---

## Getting Started <br>

---
<img height="80%" src="Images/UnrealStartUp.png" width="80%"/><br>
---

<br>

* Open Unreal Engine.<br>
* Choose Games. <br>
* Choose the "Top Down" game option.<br>
* Change "Blueprint" to "C++" option.<br>

<br>
<br>

---
### Setting Up a New C++ Class

---
<img height="70%" src="Images/AddingNewC++Class.png" width="70%"/><br>
---
<br>

* First thing that was covered was setting up a "New C++ Class". <br>
* C++ Classes allow you to create a new base that is tailored to your exact need that can be used then in blueprints.<br>
* The 1st new c++ class I created in Pangaea was a defense tower.
    * right-click in the Pangaea C++ folder and choose New C++ Class
    * Next choose Actor under the common classes, select next.
    * Leave the Public and Private buttons unselected
    * Name field type: DefenseTower
    * Spelling is important, if you misspell something in this step you are stuck with it.
    * Hit create.
        * You should now be able to find your new class in the Pangaea C++ Folder,
          if you don't save and quit and reload the game. This is where I had difficulties
          as I often forgot to check.

<br>
<br>

### Coding DefenseTower in Ryder

---
<img height="70%" src="Images/DefenseHeader.png" width="70%"/><br>
---
<br>

* When coding we always start with the header file. It will contain the "name of your file" followed by ".h" <br>
* 1st thing that should always be added to this file is "#pragma once", it helps the compiler not freakout if there are redundancies.<br>
* Here you can take a look at the code I used for the header file:

> Defense tower header file: [DefenseTower.h](Files/DefenseTower.h) <br>
> 
* For now we leave the Source file or ".cpp" file alone.

<br>
<br>


## Having Build Issues <br>
---

### Switching Tactics <br>
---
<br>

So, I am having difficulties with getting my build to work in unreal. <br>
I also am having difficulties trying to get videos in here. <br>
So, I am going to go over how far I got before the project went to a mangled mess, <br>
and some key things in each blueprint/lesson that I felt was useful knowledge for me.<br>


##  DefenseTower <br>
---



---
<img height="70%" src="Images/DefenseTower.png" width="70%"/><br>
---
<br>

* For almost every new class that you are adding into the game you will need to files. 
A header file also known as ".h" file, and a constructor file also known as ".ccp" file. 
I will share both of them here as text files. <br>
I made it to about page 205 in the book before the game just refused to compile and I gave up on trying to sort out what was broken. <br>

> Defense tower header file where I stopped at: [Defense Header File](Files/ADefenseTower.h.txt) <br>
> Defense tower constructor file: [Defense Constructor File](Files/DefenseTower.cpp.txt) <br>
> 
---
<img src="Images/RadiusDTC.png" height="60%" width="60"/><br>
---
  <br>
  <br>

## Title

---
<img height="70%" src="Images/" width="70%"/><br>
---
<br>

* 1 <br>
  <br>
  <br>


## Title

---
<img height="70%" src="Images/" width="70%"/><br>
---
<br>

* 1 <br>
* 2 <br>
* 3 <br>
  <br>
  <br>

---
## Title <br>




---
>Previous: [Beginning](/7255Fall2024/README.md) |
>Next: [PowerUps](PowerUps/PowerUps.md)
---