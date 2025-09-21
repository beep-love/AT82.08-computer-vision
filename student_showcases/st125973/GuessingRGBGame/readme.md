# SHOJI SHINOBI
## FIRST OPENCV GAME: GUESSING THE RGB

---

<details>
<summary><strong>About Me & TL;DR</strong></summary>

This script includes not only the game created using concepts from our first week of Computer Vision lectures and lab, but also all the prerequisites and extra learnings I explored during that week.  

I have been working in NukeX (a high-level VFX software) for a year and have immersed myself in the art and techniques of visual effects. You’ll notice this in the creation of the background for the game.  

Feel free to modify the code and make the game your own! I would love to see your projects on our showcase repo. We might be the most populated batch at AIT — let’s show them we’re the best!

Contact me if problem is faced OR good update is made: 099-291-0854 / st125973@ait.ac.th

</details>

---

IF YOU WANT TO JUST START OFF WITH THE GAME: MOVE TO THE SECTION LABELLED: GAME ON 1.1 AND RUN THE TWO SNIPPETS

### Libraries Included:
- cv2
- numpy
- matplotlib
- os
- time
- tkinter

---

### How It’s Played (Prototype 1.1)
After running the final snippet:  

1. The OpenCV interface opens, and a small animation is played.  
2. A ninja (shinobi) hides behind a shoji (Japanese door).  
3. The ninja’s chakra (energy), visible through the door, has a certain Hue value (ranging from 0 to 180).  
4. A pop-up appears asking for your first input — the **lowest predicted Hue value**.  
5. After submitting, another input appears — the **highest predicted Hue value**.  
6. If the actual Hue lies **between your predicted values**, a **WIN!** image is displayed using Matplotlib.  
7. Otherwise, a **LOSE!** image is displayed.  

---

**Quick Start:**  
If you want to jump straight into the game, move to the section labelled **GAME ON 1.1** and run the two snippets.