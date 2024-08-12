출처 : https://github.com/visionNoob/CS231N_17_KOR_SUB
출처 : https://duemoo.github.io/ai/2022/01/11/studying_AI-CS231n/

# GDSC AI PART SYLLABUS
Translation project of [CS231n 2017 lecture video](https://www.youtube.com/playlist?list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)  
Also see [CS231n Website](http://cs231n.stanford.edu/)

### 왜 cs231n?
<pre>
CS231n은 스탠포드 대학에서 학부 고학년생 및 대학원생을 대상으로(!) 개설된 인공 신경망 및 컴퓨터 비전 강의이다. 이 강의가 워낙 명강의로 잘 알려졌기 때문에, 이제는 한국에서도 AI를 공부하고자 할 때 추천하는 강의로 자주 등장하곤 한다. 하지만 강의의 대상이 대상인 만큼, 입문자에게 자주 추천되는 것에 비해 AI를 처음 시작해보려는 사람이 준비 없이 바로 듣기에는 살짝 난이도가 있는 편이다.

물론 스탠포드 재학생이 아니라면, 해당 강의를 정식으로 수강하며 여러 지원(채점, 질의응답, 프로젝트를 위한 하드웨어 지원 등)을 받는 것이 불가능하다. 하지만 감사하게도 유튜브에 2017년도 강의 영상이 업로드되어 있어, 전 세계의 누구나 무료로 CS231n 강의를 들으며 공부할 수 있다! 필자는 위의 영상을 보며 공부했지만, 영어가 익숙하지 않은 경우 Kyoseok Song님의 한국어 해설 영상을 함께 본다면 큰 도움이 될 수 있을 것 같다. 또한, 강의를 듣다 보면 과제에 대한 이야기가 나오는데, 과제는 총 3개로 구성되어 있으며 이곳에서 다운로드해서 직접 풀어볼 수 있다.
</pre>
[2017년도 강의 영상](https://youtu.be/vT1JzLTH4G4)<br>
[한국어 해설 영상](https://youtu.be/vT1JzLTH4G4)<br>
[과제 링크](https://cs231n.github.io/)


## Usage

1. You should download lectures from youtube
    - You need a video downloader like [4k video downloader](https://www.4kdownload.com/ko/products/product-videodownloader) (maybe support most of platforms like Windows, Linux(Ubuntu), MacOS)
    - Download this [Youtube Playlist](https://www.youtube.com/playlist?list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk) with downloader
    - If you take "4k video downloader", you can download whole lectures "at once" not "each", with Playlist.      
    
2. and Enjoy videos with Subtitles  

        root
        └── eng
            └── Subtitles in English.
        └── kor 
            └── Subtitles in Korean.

----------

## Update Note
    Welcome to Pull Request

    1. Update News
    ...
    2018.05.23 - Complete Lecture 6(draft)
    2018.06.14 - Complete Lecture 7(draft)
    2018 06 26 - Complete Lecture 8(draft) 
    2018 07 27 - Complete Lecture 1(1st Revision) 
    2018 07 09 - Complete Lecture 9(draft) 
    2018 07 16 - Complete Lecture 2(1st Revision) 
    2018 07 30 - Complete Lecture 10(draft) 
    2018 08 13 - Complete Lecture 11(draft) 
    2018 09 24 - Complete Lecture 12(draft)
    2018 10 06 - Complete Lecture 13(draft)
    2018 12 31 - Complete Lecture 14(draft)

    1. Milestone
    Lecture 01 : Complete(draft + 1st Revision) 
    Lecture 02 : Complete(draft + 1st Revision)
    Lecture 03 : Complete(draft)
    Lecture 04 : Complete(draft)
    Lecture 05 : Complete(draft)
    Lecture 06 : Complete(draft)
    Lecture 07 : Complete(draft)
    Lecture 08 : Complete(draft)
    Lecture 09 : Complete(draft)
    Lecture 10 : Complete(draft)
    Lecture 11 : Complete(draft)
    Lecture 12 : Complete(draft)
    Lecture 13 : Complete(draft)
    Lecture 14 : Complete(draft)
    Invited Talk 1 : not yet :(
    Invited Talk 2 : not yet :(
----------
## Table of Contents (CS231n 2017)


 Please see also
1. Detailed syllabus 
 [[2016]](http://cs231n.stanford.edu/2016/syllabus.html)
 [[2017]](http://cs231n.stanford.edu/2017/syllabus.html)
 [[2018]](http://cs231n.stanford.edu/syllabus.html)

2. Lecture Vodeos Playlist
[[2016]](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC)
[[2017]](https://www.youtube.com/playlist?list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk) 
[2018 is not in public] 


#### Status info
| *Status info* | Symbol  |*Status info*   |Symbol                           |
|:-------------:|:-------:|:--------------:|:-------------------------------:|
|**Draft**      |:pencil2:|**1st_revision**|:pencil2: :scissors:             |
|**not yet**    |:no_bell:|**2nd_revision**|:pencil2: :scissors: :scissors:  |


----

| Event Type  | Description       |Videos(youtube)      |Slides      | Subtitles| Status |
|:--------:|:-----------------:|:-----------:|:--------:|:--------:|:----:|
|Lecture 1        |Introduction to Convolutional Neural Networks for Visual Recognition|[video](https://www.youtube.com/watch?v=vT1JzLTH4G4&t=0s&index=1&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture1.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%201%20_%20Introduction%20to%20Convolutional%20Neural%20Networks%20for%20Visual%20Recognition.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%201%20%20%20Introduction%20to%20Convolutional%20Neural%20Networks%20for%20Visual%20Recognition.ko.srt)|:pencil2: :scissors:|
| Lecture 2        |Image Classification|[video](https://www.youtube.com/watch?v=OoUX-nOEjG0&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=1)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture2.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%202%20_%20Image%20Classification.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%202%20%20%20Image%20Classification.ko.srt)|:pencil2: :scissors:|
| Lecture 3        |Loss Functions and Optimization|[video](https://www.youtube.com/watch?v=h7iBpEHGVNc&index=2&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture3.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%203%20_%20Loss%20Functions%20and%20Optimization.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%203%20%20%20Loss%20Functions%20and%20Optimization.ko.srt)|:pencil2: |
| Lecture 4        |Introduction to Neural Networks|[video](https://www.youtube.com/watch?v=d14TUNcbn1k&index=3&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture4.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%204%20_%20Introduction%20to%20Neural%20Networks.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%204%20%20%20Introduction%20to%20Neural%20Networks.ko.srt)|:pencil2: |
| Lecture 5        |Convolutional Neural Networks|[video](https://www.youtube.com/watch?v=bNb2fEVKeEo&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=4)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture5.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%205%20_%20Convolutional%20Neural%20Networks.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%205%20%20%20Convolutional%20Neural%20Networks.ko.srt)|:pencil2: |
| Lecture 6        |Training Neural Networks I|[video](https://www.youtube.com/watch?v=wEoyxE0GP2M&index=5&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture6.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%206%20_%20Training%20Neural%20Networks%20I.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%206%20%20%20Training%20Neural%20Networks%20I.ko.srt)|:pencil2: |
| Lecture 7        |Training Neural Networks II|[video](https://www.youtube.com/watch?v=_JB0AO7QxSA&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=6)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture7.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%207%20_%20Training%20Neural%20Networks%20II.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%207%20%20%20Training%20Neural%20Networks%20II.ko.srt)|:pencil2: |
| Lecture 8        |Deep Learning Software|[video](https://www.youtube.com/watch?v=6SlgtELqOWc&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=7)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture8.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%208%20_%20Deep%20Learning%20Software.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%208%20%20%20Deep%20Learning%20Software.ko.srt)|:pencil2: |
| Lecture 9        |CNN Architectures|[video](https://www.youtube.com/watch?v=DAOcjicFr1Y&index=8&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture9.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%209%20_%20CNN%20Architectures.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%209%20%20%20CNN%20Architectures.ko.srt)|:pencil2: |
| Lecture 10       |Recurrent Neural Networks|[video](https://www.youtube.com/watch?v=6niqTuYFZLQ&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk&index=9)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture10.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2010%20_%20Recurrent%20Neural%20Networks.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%2010%20%20%20Recurrent%20Neural%20Networks.ko.srt)|:pencil2: |
| Lecture 11       |Detection and Segmentation|[video](https://www.youtube.com/watch?v=nDPWywWRIRo&index=10&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture11.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2011%20_%20Detection%20and%20Segmentation.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%2011%20%20%20Detection%20and%20Segmentation.ko.srt)|:pencil2: |
| Lecture 12       | Visualizing and Understanding|[video](https://www.youtube.com/watch?v=6wcs6szJWMY&index=11&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)|[slide](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture12.pdf)|[english](https://github.com/insurgent92/cs231n_spring_2017/blob/master/eng/Lecture%2012%20_%20Visualizing%20and%20Understanding.srt)<p>[korean](https://github.com/insurgent92/CS231N_17_KOR_SUB/blob/master/kor/Lecture%2012%20%20%20Visualizing%20and%20Understanding.ko.srt)|:pencil2: |
