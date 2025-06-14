This repository contains all of my lecture notes of the course CSE340: Computer Architecture. </br>
-------------------------------------------------------------------------
**Table of Contents**
- [Lecture 0](#lecture-0)
  - [Brief History of Computer Architectures](#brief-history-of-computer-architectures)
- [Lecture 1](#lecture-1)

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


<br/>

# Lecture 1

