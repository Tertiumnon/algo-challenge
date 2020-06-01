# Algo2

## Задача "Удаление дубликатов из отсортированного массива"

[Ссылка на задачу](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)

## Решение

```java
public int removeDuplicates(int[] nums) {
    if (nums.length == 0) return 0;
    int i = 0;
    for (int j = 1; j < nums.length; j++) {
        if (nums[j] != nums[i]) {
            i++;
            nums[i] = nums[j];
        }
    }
    return i + 1;
}
```

## Решения участников

### Go

![go](results/photo_2020-05-25_14-32-55.jpg)

![go](results/photo_2020-05-27_14-17-57.jpg)

### CSharp

![csharp](results/photo_2020-05-22_21-04-16.jpg)

![csharp](results/photo_2020-05-25_00-00-00.jpg)

### C++

![c](results/photo_2020-05-22_23-08-20.jpg)
