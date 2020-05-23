# Algo1

## Задача "Разворот строки"

[Ссылка на задачу](https://leetcode.com/problems/reverse-string/)

## Решение

```java
class Solution {
    public void reverseString(char[] s) {
        int left = 0, right = s.length - 1;
        while (left < right) {
            char tmp = s[left];
            s[left++] = s[right];
            s[right--] = tmp;
        }
    }
}
```

## Решения участников

### Go

#### @iBubnov

![go](results/photo_2020-05-15_16-16-17.jpg)

#### @vF1sher

![go](results/photo_2020-05-22_10-04-49.jpg)

### CSharp

#### @vvilliamblake

![csharp](results/photo_2020-05-23.png)

#### @vF1sher

![charp](results/photo_2020-05-22_09-52-40.jpg)

### C

#### @vasssad

![c](results/photo_2020-05-15_16-21-22.jpg)

### JS

#### @vvilliamblake

![js](results/photo_2020-05-23_2.png)
