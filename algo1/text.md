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

![go](results/photo_2020-05-15_16-16-17.jpg)

![go](results/photo_2020-05-22_10-04-49.jpg)

### CSharp

![csharp](results/photo_2020-05-23.png)

![charp](results/photo_2020-05-22_09-52-40.jpg)

### C

![c](results/photo_2020-05-15_16-21-22.jpg)

### JS

![js](results/photo_2020-05-23_2.png)
