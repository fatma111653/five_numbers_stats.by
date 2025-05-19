# five_numbers_stats.by
#This program takes five numbers as input, calculates the total, average, maximum, and minimum.
```
five_num = input("enter five numbers separated by space: ")
num = list(map(int, five_num.split()))
total = sum(num)
print(total)
average = total / len(num)
print(average)
maximum = max(num)
print(maximum)
minimum = min(num)
print(minimum)

```