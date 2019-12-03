# Проект готов!
Можете копировать код и смотреть как работает. До выходных выложу инструкцию по работе с Free Basic
<pre><code>
SUB Star
DIM I AS INTEGER 
DIM J AS INTEGER 
DIM x AS INTEGER 
DIM y AS INTEGER 
DIM c AS INTEGER 
RANDOMIZE TIMER 
FOR j= 1 TO 500 
x = INT(RND * 639) + 1 
y = INT(RND * 479) + 1 
c = INT(RND * 15) + 1 
PSET (x, y), c 
NEXT j 
End SUB
SCREEN 12 
Star
SLEEP(300) 
DIM I AS INTEGER 
FOR I=1 TO 8 
 LINE(20+60*I,80)-(100+60*I,80),15 
 LINE(20+60*I,130)-(100+60*I,130),15 
 LINE(20+60*I,80)-(20+60*I,130),15 
 LINE(100+60*I,80)-(100+60*I,130),15 
 LINE(100+60*I,80)-(120+60*I,105),15 
 LINE(100+60*I,130)-(120+60*I,105),15 
 LINE(5+60*I,60)-(20+60*I,80),15 
 LINE(5+60*I,150)-(20+60*I,130),15 
 LINE(5+60*I,60)-(5+60*I,150),15 
 CIRCLE(80+60*I,105),10,15 
 SLEEP(300) 
 CLS 
STAR
NEXT I 
SLEEP
</code></pre>
