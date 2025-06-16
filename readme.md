This repository contains my lecture notes of the course CSE340: Computer Architecture. </br>
-------------------------------------------------------------------------
**Table of Contents**
- [Course Outline](#course-outline)
    - [🎯 Attendance](#-attendance)
    - [📚 Research-Based Assessment](#-research-based-assessment)
    - [📘 Quizzes](#-quizzes)
    - [📑 Assignments](#-assignments)
    - [✒️ Midterm Exam](#️-midterm-exam)
    - [📝 Final Exam](#-final-exam)
- [Lecture 0](#lecture-0)
  - [Brief History of Computer Architectures](#brief-history-of-computer-architectures)
  - [Why study Computer Architecture?](#why-study-computer-architecture)
- [Lecture 1](#lecture-1)

# Course Outline

| **Assessment Type**            | **Marks** |
|---------------------------|-------|
| Attendance                | 5     |
| Research-based Assessment | 5     |
| Quizzes                   | 15    |
| Assignments               | 10    |
| Midterm Exam              | 25    |
| Final Exam                | 40    |
| Total                 | 100 |

### 🎯 Attendance

- **70% attendance** is mandatory to be eligible for the final exam.
- If you miss any class due to a valid reason (e.g., **sickness, contest participation, Umrah**, etc.), you **must email** me at  
  📧 [ext.monirul.haque@bracu.ac.bd](mailto:ext.monirul.haque@bracu.ac.bd)  
  within **one week** of your absence along with **proper proof**.

---

### 📚 Research-Based Assessment

- This will be a **short research-oriented assessment**.
- You will likely submit a **report on a research topic or scenario**.
- Detailed instructions and topics will be shared **after the midterm**.

---

### 📘 Quizzes

We plan to take **four quizzes** this semester — **two before** the midterm and **two after**.

| Quiz     | Chapter      |
|----------|--------------|
| Quiz 1   | Chapter 1    |
| Quiz 2   | Chapter 2    |
| Quiz 3   | Chapter 4    |
| Quiz 4   | Chapter 5    |

---

### 📑 Assignments

There will be a total of **4 assignments**. Each assignment will have a **5 to 7-day deadline**.  
Late submissions are allowed up to **1 week after the deadline**, but with a **penalty applied accordingly**.

| Assignment    | Chapter     |
|---------------|-------------|
| Assignment 1  | Chapter 1   |
| Assignment 2  | Chapter 2   |
| Assignment 3  | Chapter 3   |
| Assignment 4  | Chapter 4   |

---

### ✒️ Midterm Exam

- **Syllabus:** Chapter **1**, **2**, and **3**  
  _(Covers everything taught before the midterm)_

---

### 📝 Final Exam

- **Syllabus:** Chapter **2**, **3**, **4**, **5**, and **6**
- Note: The final exam **includes topics from the midterm** (except Chapter 1).
- Chapter 6 may be included depending on whether we can cover it or not.

---

# Lecture 0
## Brief History of Computer Architectures

In 1822, Charles Babbage, an English Mathematician and Mechanical Engieer, saw punchcards used in textile industries and got an idea to create a machine that can compute; Computer. These punch cards were used in machines to create intricate designs on fabrics like rugs and blankets by dictating where to place thread, enabling complex patterns much faster than manual methods. 

<p align="center">
    <img src="Media\Lecture0\textile_punchcards.jpg" width="300" />
    <img src="Media\Lecture0\punchcard_textile_product.jpg" width="400" /> <br/>
    <em>Punch cards used in textile machines</em>
</p>

In 1832, Charles Babbage created a small portion of the Difference Engine to create his visionary mechanical computer. But his idea was ahead of his time, so other scientiests would often call him a madman. In the same year the British government suspended funding for his work.

<p align="center">
    <img src="Media\Lecture0\difference_machine.jpg" width="250" /> <br/>
    <em>Charles Babbage's Difference Machine</em>
</p>

But Charles did not stop there. In 1833, he hired a painter from his own salary and started designing the Analytical Engine, a far more ambitious project intended as a general-purpose programmable computer.
In the same year, Charles Babbage met Ada Lovelace by their mutual friend. As soon as Lovelace learnt about his work, Lovelace became obsessed with his work. <br>

Babbage also sought support abroad after becoming disillusioned with the lack of backing from the British scientific establishment. In 1840, he traveled to Turin, Italy, to present lectures on his design for the Analytical Engine to a group of Italian scientists, hoping to generate international interest. Luigi Federico Menabrea, an Italian mathematician and engineer, attended these lectures, took detailed notes, and subsequently published a research paper in 1842 based on Babbage’s presentation. {Fun fact: Menabrea later in 1963 became the Prime Minister of Italy} 

<p align="center">
    <img src="Media\Lecture0\Charles_Babbage.jpg" width="200" />
    <img src="Media\Lecture0\Luigi_Menabrea.jpg" width="155" />
    <img src="Media\Lecture0\Ada_Lovelace.jpg" width="185" /> <br/>
    <em>Charles Babbage, Luigi Menabrea and Ada Lovelace</em>
</p>


Ada Lovelace, in 1843, translated Menabrea’s paper into English and, crucially, added extensive notes of her own; three times longer than the original article. In these notes, Lovelace included what is now recognized as the first computer algorithm intended for machine processing: a step-by-step method for calculating Bernoulli numbers using the Analytical Engine. Because of this she is called the **First Computer Programmer**. She did not actually write codes or punchcards for the computer; a lot of people still has misconception about that. <br>

<p align="center">
    <img src="Media\Lecture0\Lovelaces_algorithm.jpg" width="" /> <br/>
    <em>Ada Lovelace's first computer algorithm</em>
</p>

In 1956, Charles Babbage finished working on the design of Analytical Engine. But during his lifetime due to technological limitations and lack of sustained funding he could not build it. He died in 1871. Just a reminder that electricity was first used to light up the streets in 1878. So, his computer design was powered by steam like the old trains. <br>

After Babbage's death, his son, Henry Prevost Babbage, continued efforts to realize his father's vision. Between 1880 and 1910, Henry constructed a working section of the Analytical Engine's mill and a printing apparatus. In 1910, this device was able to calculate a list of multiples of pi, but it was faulty and it was only a small fragment of the full machine and was not programmable. It didn't even have any storage. A complete Analytical Engine was never constructed but Charles Babbage is still considered **The Fater of Computer**. <br>

<p align="center">
    <img src="Media\Lecture0\Analytical_engine_part.jpg" width="400" /> <br/>
    <em>A small fragment of the Analytical Engine that was built</em>
</p>

Meanwhile, Herman Hollerith, a German-American Statistician, liked the idea of Charles Babbage's "punch cards as input" idea. He worked as a statistician during the 1880 U.S. Census and saw firsthand how slow and error-prone manual tabulation was. He invented Tabulating Machine in 1890 to make the Census faster. Basically, reducing 8 years of census counting process to just 2 years. <br>

Hollerith’s system used punched cards where the presence or absence of a hole in a specific position represented a data value (for example, marital status or geographic location). His tabulating machine used electrical contacts: when a card was inserted, pins would pass through the holes, complete an electric circuit, and increment mechanical counters—effectively automating the counting and sorting of census data. This was the **first coding** system ever created. <br>

Hollerith continued to work on the machine and in 1906 he innovated a control panel. This control panel allowed the machine to be rewired for different jobs without having to be physically rebuilt, making it much more flexible and efficient for a variety of data processing tasks. Hollerith's company merged with different companies and by 1924 it was renamed IBM. 

<p align="center">
    <img src="Media\Lecture0\Hollerith.jpg" width=180" />
    <img src="Media\Lecture0\Tabulating Machine.jpg" width="300" /> <br/>
    <em>Herman Hollerith and his Tabulating Machine</em>
</p>

After the first World War, the world was in an early space race era. Hundreds of human computers, mostly women, were calculating trajectory and other values of physics formulas to get people to space (To know the fascinating history I would recomment watching the movie [Hidden Figures](https://www.imdb.com/title/tt4846340/)). Alan Turing did not like the idea of brilliant mathematicians and physicists minds wasting their times doing this mundane task whole day. <br>

Inspired by the human computers, in 1936, Alan Turing theorized the idea of a magical problem-solving robot that walks on a tape of infinite length of binary numbers and following the given set of instructions it can solve any problems. If you want to know more in details I recommend watching this [video](https://www.youtube.com/watch?v=PLVCscCY4xI). Basically, the infinite length's tape was the **first idea of a Memory/RAM** and the magical problem-solving walking robot was the **first idea of a Processor/CPU**. <br>

During the World War II, in 1943, Alan Turing created the first prototype of his famous machine The Bombe to to decipher German encoded messages from the Enigma machine. This would be crucial for winning the war. The Bombe later influenced the first electronic digital Computer, Colossus. The real story is very dramatic and I highly recommend watching the movie [The Imitation Game](https://www.imdb.com/title/tt2084970/); it's one of the best movies I have ever watched.

<p align="center">
    <img src="Media\Lecture0\Alan_Turing.jpg" width=180" />
    <img src="Media\Lecture0\Enigma.jpg" width="350" /> <br/>
    <em>Alan Turing and his The Bombe Machine</em>
</p>

<p align="center">
    <img src="Media\Lecture0\Colossus.jpg" width="" /> <br>
    <em>Colossus, the first electronic digital Computer inspired from Turing's work</em>
</p>

After the World War II, a lot of electronic digital computers were being built but those computers had issues. Some of the noteworthy issues were, <br>
- Very large and took up a lot of space
- Used thousands of vacuum tubes (valves), which generated a lot of heat and often burned out, requiring frequent replacement {These vacuum tubes were basically transistors}
- Consumed a huge amount of electrical power
- Expensive to build and operate
- Only one calculation or program could run at a time; users had to reserve time slots to use the computer
- Programming was difficult and frustrating, as it was hard to describe tasks in a way the computer could understand
- Mainly used for complex math problems; most people saw them as giant calculators
- Market was very small and specialized, mostly limited to government, military, and large businesses 

In the 1960's Integrated Circuits (IC) were developed and it was possible because NASA was pouring money for space race. Because of their funding the concept of real-time computing was also developed. Processing inputs and responding instantly was necessary for Apollo 11 moonlanding. <br>

During 1970s, companies started making home computers and Apple released their first home computer Apple 1. But most of these computers were very expensive. It was The 1981's IBM Model 5150 that popularized home computers. Almost every offices started buying IBM PCs because it was affordable and enough functions for official works than other PCs that time. It had Intel 4.77MHz processor and Microsoft's MS-DOS operating system. 

<p align="center">
    <img src="Media\Lecture0\IBM.jpg" width="" /> <br>
    <em>IBM Model 5150</em>
</p>

Then the transistors kept getting smaller and the computers became faster, now almost everyone has a very advanceed computer in their pockets.
<br/>

## Why study Computer Architecture?
- Just like F1 drivers understand their engines to win races, knowing computer architecture helps you build faster, better, and more efficient software and hardware.
- You get troubleshooting superpowers. When your laptop slows down or your phone overheats, understanding architecture lets you pinpoint the problem instead of running towards tech support shops instantly.

Some examples of how knowing the computer architecture can help: <br>
- **Space Invaders Game (1978):** It was released in 1978 on Atari game console. At the beginning of the game, when there were many enemies on screen, the console had to spend more processing power to animate them all. This caused the game to run slower, resulting in enemies moving at a sluggish pace. <br>
However, as players destroyed more invaders, the number of objects the system needed to render decreased. With fewer enemies to process, the hardware could animate them much faster. So ironically, as the player advanced, the game sped up, making it more challenging. <br>
What’s brilliant is that the developers saw this performance limitation and embraced it. Instead of trying to “fix” the speed increase, they turned it into a game feature, increasing difficulty as the player succeeded.
<p align="center">
    <img src="Media\Lecture0\space_invaders.gif" width="300" />
    <img src="Media\Lecture0\space-invaders_speedup.gif" width="400" /> <br>
    <em>Space Invaders Game becomes faster as more enemies are killed</em>
</p>

**Doom Game (1993):** It is is often remembered as one of the first 3D shooter games but it's not not actually 3D. At the time, personal computers lacked the power and graphics cards needed for real-time 3D rendering. So the developers at id Software used clever programming techniques to simulate a 3D environment using 2D technology. <br>
The game world was built using a 2D map (top-down layout), and the player’s view was calculated from that map. Instead of full 3D models, Doom used 2D sprites (flat images) for enemies and objects, which rotated to always face the player—creating a 3D illusion. The rendering engine used a technique called ray casting, where rays were traced from the player’s position to walls and objects to determine what to draw—similar to how light works, but simplified for performance. <br>
So even though the game looked 3D, it was technically a very smart use of 2D rendering with perspective and mathematical tricks.
<p align="center">
    <img src="Media\Lecture0\doom.gif" width="400" /> <br>
    <em>Space Invaders Game becomes faster as more enemies are killed</em>
</p>

**Photoshop (1990):** Memory was expensive and limited, especially for undo operations on large image files. Instead of storing every pixel version for undo, Photoshop stored delta information (only what changed), allowing selective undo using the History Brush. It was so creative that git uses the same idea (even though it released on 2005). <br>

**Instagram Filters (2010):**
Early smartphones had poor camera quality and limited GPU power. Instead of trying to make the photos look better with high-end corrections, Instagram embraced the limitations by introducing retro filters that made photos look intentionally old or “artsy.” Remember candycam? It was so trendy that everyone was using it, but it actually made photos look worse. <br>

**Steam on Macbook (2025):** This game storefront DRM eats up 1.5GB of ram in macbook but takes around 100-200MB on windows when idle. Because, the developers of the software did not optimize it for ARM-based system like M1 to M4. <br>

There are plenty of softwares and video games that are unoptimized or buggy. Making them optimized requires knowledge of the hardware.

# Lecture 1
To be Added
