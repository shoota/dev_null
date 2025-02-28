# Add Hooks

========

```
　　殺　伐　と　し　た　リ　ポ　ジ　ト　リ　に　ゾ　ウ　リ　ム　シ　が　！　！  
  
＿/＼／＼/＼／|＿  
＼　　　　　　　　　 ／  
＜ 　　ｱﾒｰﾊﾞ!!!　　＞  
／　　　　　　　　　 ＼  
￣|／＼/＼/＼/￣  
　　　　　　　　＿＿＿__/ ●｀丶 、  
　　　　　==ニ───- 、　　　,,lll,｀ 、  
　　　　　　　　　　　　／　 ,,,,,,,,llllllllll 丶 　　　  
　　　　　　　　　　　/　　iiiilllllllllllllllll!! │  
　　　　　　　　　　/　　　llllllllllllllllll´　 │  
　　　　　　　　　 │　　 llllllllllllllllllllli　 │  
　　　　　　　　　 │　　 llllllllllllllllllllll　 │  
　　　　　　　　　 │　　　llllllllllllllllll´　 /  
　　　　　　　　　 丶　ﾐｶﾂﾞｷﾓ´´｀ll 　/  
　　　　　　　　　　丶　　　　　　iillll　 /  
　　　　　　　　　　　丶　　　!!!!iiill!´　/  
　　　　　　　　　　　　 ｀丶───__│  
　　　　　　　　　　　　　　　　　　　　＼  
　　　　　　　　　　　　　　　　　　　　　 ＼  
  
┏━━━┓　　　　 ┏┓　 ┏━━┓┏┓　　　┏┳┓┏━━┓  
┗┓┏┓┃┏━━┛┗┓┗━━┛┃┃　　　┃┃┃┃┏┓┃  
　 ┃┣┛┃┗━┓　 ┏┛┏━━┓┃┗━┓┗┻┛┃┃┃┃  
　 ┃┣━┛　 ┏┛┃┃　 ┗━━┛┃┏━┛　 　 　 ┃┃┃┃  
　 ┃┃　 　 ┏┛┏┫┃　 ┏━━┓┃┃　　　　 　 　 ┃┗┛┃  
　 ┗┛　 　 ┗━┛┗┛　 ┗━━┛┗┛　　　　 　 　 ┗━━┛  

```

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
pie title NETFLIX
         "Time spent looking for movie" : 90
         "Time spent watching it" : 10
```
```mermaid
---
title: Animal example
---
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }

```
