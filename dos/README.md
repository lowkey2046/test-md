# README

normal.c

```
00000000  23 69 6e 63 6c 75 64 65  20 3c 73 74 64 69 6f 2e  |#include <stdio.|
00000010  68 3e 0d 0a 0d 0a 69 6e  74 20 6d 61 69 6e 28 29  |h>....int main()|
00000020  0d 0a 7b 0d 0a 20 20 72  65 74 75 72 6e 20 30 3b  |..{..  return 0;|
00000030  0d 0a 7d 0d 0a                                    |..}..|
00000035
```

no-line.c

```
00000000  23 69 6e 63 6c 75 64 65  20 3c 73 74 64 69 6f 2e  |#include <stdio.|
00000010  68 3e 0d 0a 0d 0a 69 6e  74 20 6d 61 69 6e 28 29  |h>....int main()|
00000020  0d 0a 7b 0d 0a 20 20 72  65 74 75 72 6e 20 30 3b  |..{..  return 0;|
00000030  0d 0a 7d                                          |..}|
00000033
```

line.c

```
00000000  23 69 6e 63 6c 75 64 65  20 3c 73 74 64 69 6f 2e  |#include <stdio.|
00000010  68 3e 0d 0a 0d 0a 0d 0a  0d 0a 69 6e 74 20 6d 61  |h>........int ma|
00000020  69 6e 28 29 0d 0a 7b 0d  0a 20 20 72 65 74 75 72  |in()..{..  retur|
00000030  6e 20 30 3b 0d 0a 7d 0d  0a 0d 0a 0d 0a 0d 0a 0d  |n 0;..}.........|
00000040  0a                                                |.|
00000041
```