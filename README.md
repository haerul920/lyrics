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
    0.12,  
    0.12,   
    0.13,
    0.1,  
    0.1,  
    0.1,  
    0.18,
]

# fungsi animasi ketikan
def typewriter(text, delay=0.2):
    for char in text:
        sys.stdout.write(char)
        sys.stdout.flush()
        time.sleep(delay)
    print()

# tampilkan semua lirik sesuai speed yang diatur
def generate_song():
    for line, speed in zip(verses, speeds):
        typewriter(line, speed)
        time.sleep(0.4)

# jalankan
if __name__ == "__main__":
    generate_song()
```

### Coming soon
