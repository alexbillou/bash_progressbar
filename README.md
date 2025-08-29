# bash_progressbar

test code

```
!#/bin/bash
source progressbar

for ((i = 0; i <= 100; i++)); do
    draw_progress $((i))
    sleep .01
done
echo
```