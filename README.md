<!--

author: André Dietrich

email:  LiaScript@web.de

edit:   https://liascript.github.io/LiveEditor/?/show/file/https://raw.githubusercontent.com/LiaScript/Hello-LiaScript/refs/heads/main/README.md

comment: LiaScript introduces itself in an interactive way.

version: 0.0.1

mode:   Slides

import: https://raw.githubusercontent.com/liaTemplates/ABCjs/main/README.md

@style
@keyframes burn {
  0% { text-shadow: 0 0 5px #ff0, 0 0 10px #ff0, 0 0 15px #f00, 0 0 20px #f00, 0 0 25px #f00, 0 0 30px #f00, 0 0 35px #f00;
  }
  50% { text-shadow: 0 0 10px #ff0, 0 0 15px #ff0, 0 0 20px #ff0, 0 0 25px #f00, 0 0 30px #f00, 0 0 35px #f00, 0 0 40px #f00;
  }
  100% { text-shadow: 0 0 5px #ff0, 0 0 10px #ff0, 0 0 15px #f00, 0 0 20px #f00, 0 0 25px #f00, 0 0 30px #f00, 0 0 35px #f00;
  }
}

.burning-text {
  font-weight: bold;
  color: #fff;
  animation: burn 1.5s infinite alternate;
}
@end

@burn: <span class="burning-text">@0</span>

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/liascript/hello-liascript/refs/heads/main/README.md)
[![LiveEdit](https://raw.githubusercontent.com/LiaScript/LiaScript/refs/heads/development/badges/editor.svg)](https://liascript.github.io/LiveEditor/?/show/file/https://raw.githubusercontent.com/liascript/hello-liascript/refs/heads/main/README.md)

# Hello LiaScript

    --{{0}}--
Hello, my name is LiaScript, I am a Markdown-based language that has been specially developed to create educational materials. The advantage of Markdown is that it is already widely used, easy to write and read, and supported by many platforms. The biggest drawback, however, is that it is @burn(static as hell) and offers no interactivity.
!?[⏯](media/liascript_0.webm)



    --{{1}}--
So my creators set out to rethink Markdown from the ground up...
!?[⏯](media/liascript_1.webm)

     {{1-2}}
> <marquee>... Once you free your mind about a concept of Harmony and of music being "correct" you can do whatever you want ...</marquee>
>
> -- Giorgio Moroder (inventor of disco music)



    --{{2}}--
Actually, tables in Markdown are simple to create and, as mentioned, are quite @burn(static). However, a table can also represent a dataset that strives for its ideal visualization.
!?[⏯](media/liascript_2.webm)

      {{2}}
| Animal          | Weight in kg | Lifespan (years) | Mitogen |
| --------------- | -----------: | ---------------: | ------: |
| Mouse           |        0.028 |               02 |      95 |
| Flying Squirrel |        0.085 |               15 |      50 |
| Brown Bat       |        0.020 |               30 |      10 |
| Sheep           |           90 |               12 |      95 |
| Human           |           68 |               70 |      10 |



    --{{3}}--
Another tabular structure can produce a different visualization that can be fine-tuned by the creator. In total, I support 10 different types of visualizations.
!?[⏯](media/liascript_3.webm)

      {{3}}
<!--
data-type="heatmap"
data-title="Seattle Average Temperature in Fahrenheit"
data-show
-->
| Seattle |  Jan |  Feb |  Mar |  Apr |  May |  Jun |  Jul |  Aug |  Sep |  Oct |  Nov |  Dec |
| -------:| ----:| ----:| ----:| ----:| ----:| ----:| ----:| ----:| ----:| ----:| ----:| ----:|
|       0 | 40.7 | 41.5 | 43.6 | 46.6 | 51.4 | 56.0 | 60.5 | 61.2 | 57.0 | 50.1 | 44.1 | 39.6 |
|       2 | 40.2 | 40.7 | 42.7 | 45.3 | 50.0 | 54.4 | 58.5 | 59.2 | 55.4 | 49.2 | 43.5 | 39.3 |
|       4 | 39.7 | 40.0 | 41.9 | 44.4 | 48.9 | 53.2 | 57.0 | 57.7 | 54.2 | 48.6 | 43.1 | 38.9 |
|       6 | 39.6 | 39.5 | 41.3 | 44.2 | 49.5 | 54.2 | 57.8 | 57.4 | 53.6 | 48.2 | 42.8 | 38.7 |
|       8 | 39.6 | 39.9 | 42.9 | 47.1 | 52.7 | 57.3 | 61.3 | 61.1 | 56.7 | 49.5 | 43.1 | 38.7 |
|      10 | 41.3 | 42.7 | 46.4 | 50.7 | 56.4 | 60.9 | 65.2 | 65.4 | 60.9 | 52.8 | 45.5 | 40.4 |
|      12 | 43.8 | 46.0 | 49.5 | 53.8 | 59.6 | 64.3 | 69.4 | 69.8 | 65.1 | 56.0 | 47.8 | 42.6 |
|      14 | 45.1 | 47.7 | 51.3 | 55.9 | 61.9 | 66.9 | 72.6 | 73.2 | 67.7 | 57.8 | 48.8 | 43.6 |
|      16 | 44.5 | 47.5 | 51.4 | 55.9 | 62.3 | 67.5 | 73.9 | 74.3 | 68.2 | 57.4 | 47.8 | 42.6 |
|      18 | 42.6 | 44.7 | 48.7 | 53.8 | 60.3 | 65.9 | 72.3 | 72.2 | 64.6 | 53.9 | 46.0 | 41.2 |
|      20 | 42.0 | 43.3 | 46.4 | 50.2 | 56.0 | 61.4 | 66.9 | 66.6 | 60.7 | 52.3 | 45.2 | 40.7 |
|      22 | 41.4 | 42.5 | 45.0 | 48.3 | 53.5 | 58.2 | 63.2 | 63.5 | 58.7 | 51.1 | 44.5 | 40.1 |



    --{{4}}--
What Markdown has always lacked was the embedding of multimedia content ...
!?[⏯](media/liascript_4.webm)



    --{{5}}--
I support audio content ...
!?[⏯](media/liascript_5.webm)

     {{5-6}}
?[a horse](https://www.w3schools.com/html/horse.mp3 "hear a horse")



    --{{6}}--
I can handle video as well, and of course, I work on feature phones even if they are offline.
!?[⏯](media/liascript_6.webm)

     {{6-7}}
!?[LiaScript on Nokia](https://www.youtube.com/watch?v=U_UW69w0uHE)



    --{{7}}--
I can also try to embed other types of content that do not fall into either of the two categories
!?[⏯](media/liascript_7.webm)

      {{7}}
??[Esther’s scroll in a cover](https://sketchfab.com/3d-models/esthers-scroll-in-a-cover-21a13eba33cb4343bab56f0c0f982876 "Historical Museum of the City of Kraków")



    --{{8}}--
And much, much more... We will soon show you how everything works.
!?[⏯](media/liascript_8.webm)

      {{8}}
```abc
X: 1
M: 4/4
L: 1/8
K: Emin
|:D2|"Em"EBBA B2 EB|~B2 AB dBAG|"D"FDAD BDAD|FDAD dAFD|
"Em"EBBA B2 EB|B2 AB defg|"D"afe^c dBAF|"Em"DEFD E2:|
```
@ABCJS.eval



    --{{9}}--
You might have noticed that this document is being used like a PowerPoint presentation. However, our intention was to utilize LiaScript in various contexts. With LiaScript, you can create presentations, enable self-study through browser-based text-to-speech output, or read the content as a simple yet interactive textbook, without animations.
!?[⏯](media/liascript_9.webm)

    {{9}}
> ## Quiz?
>
> __Will you use LiaScript in the future?__
>
> - [(X)] Yes of course
> - [( )] not sure ...
> - [( )] No, I prefer to use a classical LMS



## More Information

- __Website:__ https://LiaScript.github.io
- __Documentation:__
  https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md
- __YouTube:__ https://www.youtube.com/@liascript4180
- __Blog:__ https://LiaScript.github.io/blog
- __LiveEditor:__ 
  
  - https://liascript.github.io/LiveEditor
  - https://liascript.github.io/LiveEditor/examples.html

- __GitHub:__

  - Project: https://github.com/^superscript^
  - Courses: https://github.com/topics/liascript-course
  - Templates: https://github.com/topics/liascript-template
