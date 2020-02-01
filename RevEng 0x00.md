---


---

<h1 id="reverse-engineering--exploit-development-training-0x00--prolog">Reverse Engineering / Exploit Development Training 0x00 ; Prolog</h1>
<h2 id="what-is-reverse-engineering">What is Reverse Engineering?</h2>
<p>In the world of CyberSecurity and Software Engineering, Reverse Engineering is the practice of analyzing execution patterns of executable files in order to copy a program back into it’s original form, thereby gaining an understanding of how said program is structured.</p>
<p>The present participle verb form of Reverse Engineering is called <strong>Reversing</strong>.</p>
<h2 id="why-practice-reversing">Why Practice Reversing?</h2>
<p>A few examples of the use cases for reverse engineering would be:</p>
<ul>
<li><strong>Finding exploits and vulnerabilities within a program. Exploit Development.</strong></li>
<li>Retrieval of lost source code for a project.</li>
<li>Gain a greater understaning of how compilers translate human readable code into machine-readable code.</li>
<li>Gain a greater understanding of Instruction-Set Architectures for CPU’s.</li>
<li>Gain a greater understanding of your own compiled code when debugging.</li>
</ul>
<h2 id="what-is-exploit-development">What is Exploit Development?</h2>
<p>Exploit Development is the practice of utilizing core concepts that tie closely with Reverse Engineering to find vulnerabilities within a program.</p>
<p>These core concepts are Behavior Analysis and Behavior Modification.</p>
<p>Sometimes a particularly challenging program can require the “full picture”, and thus a full Reversing of the program is necessary to find potential attack vectors that can be used.</p>
<p>Exploit Development does not always require Reversing, however a full understanding of Reverse Engineering makes Exploit Development <strong>much</strong> easier.</p>
<h2 id="why-develop-exploits">Why Develop Exploits?</h2>
<p>Exploit Developers utilize the core concepts of Reverse Engineering to find exploits in programs in order to better protect those programs.</p>
<p>The skill is essential for the security of programs, and covers the occupations of Malware Analysis, Vulnerability Researchers, and  is the basis of the SANS SSEC710 &amp; SEC760 certifications for penetration testing.</p>
<p>It is a multidisciplinary skill involving a combination of Computer Science and Cybersecurity fundamentals.</p>
<p>If you enjoy puzzles, and making things do what they are not supposed to do, you will enjoy exploit development.</p>
<p>Also, <a href="https://www.youtube.com/watch?v=ON-7v4qnHP8">https://www.youtube.com/watch?v=ON-7v4qnHP8</a></p>
<h2 id="how-does-one-begin-reversing-and-by-extension-developing-exploits">How does one begin Reversing, and by extension, developing Exploits?</h2>
<p>For us, a simple understanding of Programming Concepts &amp; Python is enough.</p>
<p>We will start off with simple C, and x86 Assembly. We will then build from there into more advanced concepts.</p>
<p><em><strong>If you do not know C, I would recommend looking up “Derek Banas” on YouTube, he has a wonderful C Programming Language tutorial  with included source code &amp; comments that will get you where you need to be, the link will follow for those of you who download these notes.</strong></em><br>
<a href="https://www.youtube.com/watch?v=nXvy5900m3M">https://www.youtube.com/watch?v=nXvy5900m3M</a></p>
<h3 id="the-resources-we-will-be-using-are-as-follows">The Resources we will be using are as follows:</h3>
<p><strong>Book</strong>: <em><strong>Reverse Engineering for Beginners, by Dennis Yurichev.</strong></em><br>
It can be found as a pdf at <a href="https://beginners.re">https://beginners.re</a></p>
<p><em><strong>The reason we are using this book is not only because it is the best resource for learning Reverse Engineering, but it is additionally licensed under the Creative Commons license (CC BY-SA 4.0). We are legally allowed to print this book, and I am legally allowed to use it for teaching.</strong></em></p>
<p><strong>Exercises</strong>: We will be using the books’ exercises located here: <a href="https://challenges.re/">https://challenges.re/</a></p>
<ul>
<li>Do keep in mind these challenges are not numbered in order of difficulty, but in order of when they were written. For example, our first challenges will be #48 and #49</li>
</ul>
<p><strong>In addition,</strong> we will be using custom written binaries and labs, or sometimes we will borrow from individuals or sites such as :</p>
<ul>
<li>
<p>LiveOverflow’s  [Binary Exploitation / Memory Corruption] playlist: <a href="https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN">https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN</a></p>
</li>
<li>
<p>Andrew Griffith’s Exploit Education Virtual Machines: <a href="http://exploit.education/">http://exploit.education/</a></p>
</li>
<li>
<p>Pwn, Crackme, and Reversing Challenges from a handful of sites:</p>
<ul>
<li><a href="http://pwnable.xyz/">http://pwnable.xyz/</a></li>
<li><a href="https://crackmes.one/">https://crackmes.one/</a></li>
<li><a href="https://www.hackthebox.eu/">https://www.hackthebox.eu/</a></li>
</ul>
</li>
</ul>
<h1 id="schedule">Schedule</h1>
<p>We will be using laptops provided by Pensacola State College with a Kali Linux image downloaded on them.</p>
<p>On this Kali Linux image we will have GDB with GEF installed, GCC, a few IDE’s, Ghidra, and Radare2 with the Cutter GUI Frontend.</p>
<ul>
<li>Next Week: Pages 1-29 of book, <strong>ONLY X86 EXAMPLES NEED TO BE READ</strong>, exercise #48, #49, a lab example.</li>
</ul>

