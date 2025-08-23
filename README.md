# 🚀 Lyrics

Lirik lagu dengan animasi ketikan sesuai timing, dm ig untuk req bro..

### 🎬 Ours to Keep (Python)
```python
import time
import sys

verses = [
"do you ever feel the need to",
"get away from me?",
"do i bore you?",
"or do you want to take me from this crowded place",
"to somewhere we can find some peace",
"and the world",
"is ours to keep....."
]

speeds = [
15 0.12,

16 0.12,

17 0.13,

18 0.1,

>

19 0.1,

>

20 0.1,

21 0.18,

22 ]

23

24 #fungsi animasi ketikan

25 def typewriter(text, delay=0.2):

26 for char in text:

27

28

sys.stdout.write(char)

sys.stdout.flush()

29 time.sleep(delay)

30 print()

31

32 #tampilkan semua lirik sesuat speed yang diatur

33 def generate_song():

34

for line, speed in zip(verses, speeds):

35

typewriter(line, speed) #gunakan kecepatan sesuai list

speeds

36

time.sleep(0.4)
```
