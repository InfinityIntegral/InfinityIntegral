![image of Singapore flag emoji](./flagemoji.png)

什么是勇气 (What is courage?) <br>
手握着手　形成世界新领域 (Hand in hand, we build a Singaporean dimension in this world) <br>
就凭一颗心可以　打造奇迹 (With just one heart, we can create miracles) <br>
再高的天　也触手可及 (Even the highest sky is within our reach) <br>
(晴空万里, NDP 2008 Chinese / 华文 version) <br>
("Singaporean dimension": [SGEXTN](https://github.com/InfinityIntegral/SGEXTN))

# My Profile

Hi, I am Tianle, a student from Singapore. On my GitHub is my projects typically using SGEXTN (my own extension layer over Qt Quick) and written in C++. Currently, I am still building SGEXTN v4 which is required for my future projects.

## languages and tools

❤️ SGEXTN<br>
💚 Qt framework<br>
💚 Qt Quick<br>
💚 QSB with GLSL<br>
💙 C++

## 05524F.sg

You may have noticed this organisation name in my applications. This is my "organisation name" when I am coding my own projects. The mission of 05524F is to build free and open source software for everyone in Singapore and beyond.

05524F.sg projects include:<br>
- [ ] SGEXTN - Qt Quick wrapper for easier software development<br>
- [x] SingScript.sg - font to display Math and Science symbols<br>
- [ ] SingNote.sg - note taking application<br>

### [SGEXTN](https://github.com/InfinityIntegral/SGEXTN) (active)

SGEXTN, short for "SG Extension" or "The Singaporean Extension", is my project to add a wrapper layer over Qt Quick to eliminate the need for declarative UI, QML, and JavaScript. Using SGEXTN feels like QWidget, but less powerful because I only included parts that I will use in my projects. For the things that I did not include, you can always add custom components in your applications. SGEXTN allows you to use imperative UI and code everything in C++, because J@v@scr!pt is exceptionally blur (literally, it has no clarity of types).

Development for SGEXTN is active since I am building SGEXTN v4. This is expected to be the final major version of SGEXTN, but since originally I only planned 1 version, so that can change. I just completed SingScript v2 which is a dependency of SGEXTN v4 and is back to working on SGEXTN.

### [SingScript.sg](https://github.com/InfinityIntegral/SingScript.sg) (completed)

SingScript is NOT a scripting language. It is just a font that is supposed to display Math and Science symbols. The font is split into modules with each module covering a certain use case, such as Math symbols or Optical Answer Sheet stuff. Unfortunately, this does not work at all with Qt, so there is also a "everything" module with all supported characters in the same font file. If you need only certain modules, you can make your own SingScript subsets using the "merge font" functionality in FontForge. SingScript v2 has been completed already.

### [SingNote.sg](https://github.com/InfinityIntegral/SingNote.sg) (paused)

SingNote is supposed to be a note taking app. I actually have a prototype called "MathNote.sg", but it is built using Unity C# which is not C++, and it is not the most efficient, so I would not link to it. Currently, you see SingNote as a half built project that seem to be abandoned. This is because what you see now is based on QWidget, I want to work on SGEXTN first and then later rebuild it from SGEXTN.

SingNote is a paused project, the code inside is considered below 05524F standards and unsuitable for usage due to it using QWidget and that is not efficient enough.

## Am I blur

no
