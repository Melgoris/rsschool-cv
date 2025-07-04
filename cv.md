# Anatoliy Kolobok
>### About myself:
>
>Since childhood, I wanted to become a programmer, but I was very disappointed when I entered university because the education turned out to be very different from what I had imagined. I thought they would teach us to code like in the movies and books, but in reality, the curriculum was not much different from what we had in school. So I quickly gave it up and started drifting from one field to another, far from programming.
>
>Later on, I launched several of my own websites, downloading free templates and customizing them to my liking using the F12 tools in Google Chrome and by editing the style files. I enjoyed it and became somewhat interested in web development. Of course, it was more of a hobby—whenever I had some free time, I would try to learn a bit. I liked JavaScript and everything related to it. I mainly chose it because it’s closely tied to the web, and it was interesting. Besides, when you build something, you can immediately see the result in the browser: _I changed the color of a button, cool!_ — instant dopamine.
>
>Most of my attention was on ***JavaScript*** itself, and I usually looked for layouts online and modified them for my needs. I partially completed a couple of small courses on ***Udemy*** and also did self-learning through documentation and ***YouTube***. After I got a bit familiar with ***JavaScript***, I moved on to ***React***.
>
>All my self-learning was stretched over years: I would code for a few weeks, then take breaks due to different circumstances, then come back again, and so on in cycles. Now I’ve decided that I want to take this more seriously and approach the learning process in a more structured way. ***RS School*** seems very appealing in this regard.
<hr style="height:0.5px;">
>#### Contact information:
>- **Location:** Ukraine
>- **Phone:** +38 068 0000000
>- **E-mail:** web.vasilisa@gmail.com
>- **Git-Hub:** [Melgoris](https://github.com/Melgoris)
<hr style="height:0.5px;">
>### Skills
>- HTML
>- CSS (Basic)
>- JavaScript (Basic)
>- Git (Basic)
>- React (Basic)
<hr style="height:0.5px;">
>#### Code example:
In this kata you are required to, given a string, replace every letter with its position in the alphabet.
If anything in the text isn't a letter, ignore it and don't return it.
"a" = 1, "b" = 2, etc.
>##### Example:
>```
> Input = "The sunset sets at twelve o' clock." 
> Output = "20 8 5 19 21 14 19 5 20 19 5 20 19 1 20 20 23 5 12 22 5 15 3 12 15 3 11"
>```
> ```javascript
> function alphabetPosition(text) {
>    return text
>     .toLowerCase()
>     .split('')
>     .map(e => {
>       return 'abcdefghijklmnopqrstuvwxyz'.indexOf(e) + 1
>     })
>     .filter(e => e > 0)
>     .join(' ')
> }
> ```
<hr style="height:0.5px;">
>#### Languages:
>- Ukrainian - Native
>- Russian - Intermediate
>- English - `technical English
<hr style="height:0.5px;">
>#### Courses:
>- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
>- self-study 