## Objective challenge:

### Classify the run times of each of the following scenarios:

**A.** You are searching for a specific name in a phone book (that is sorted alphabetically).

**B.** You meet someone, and they give you their phone number. You realize later that you forgot their name! To match their number with a name, you look through a phone book until you find their phone number.


### Classify the runtimes of each of the following functions:

**A. Problem One**
```
def foo(n):
    sq_root = int(math.sqrt(n))
    for i in range(0, sq_root):
        print(i)
```

**B. Problem Two**
```
def bar(x):
    sum = 0
    for i in range(0, 1463):
        i += 1
        for j in range(0, x):
                for k in range(x, x + 15):
                    sum += 1
```

**C. Problem Three**
```
def baz(array):
    print(array[1])
    midpoint = len(array) // 2
    for i in range(0, midpoint):
        print(array[i])
    for _ in range(1000):
        print('hi')
```

### Do both of these functions have the same runtime? (Notice the difference between their inputs)

**A.**
```
def make_num_pairs(n):
    for num_one in range(n):
        for num_two in range(n):
            print(num_one, num_two)
```

**B.**
```
def make_item_pairs(items):
    for item_one in items:
        for item_two in items:
            print(item_one, item_two)
```

## Objective challenge:

Suppose your app has 16,384 users that are stored in a database (the users are sorted alphabetically). Your app needs to search for a specific user and you use binary search.
- What’s the maximum number of steps it would take? (Hint: using the logarithm operation is key.)
- Time passes and now your app has exactly double the number of users. What’s the maximum number of steps now?
- Try writing a Python function to perform a linear search on a set of data.
- Try writing your own Python function to perform a binary search on a set of data. This will help you remember and internalize this algorithm much better if you do not refer to our example above in the process of writing your own. Make sure to use UPER as you approach this problem.
- Can you rewrite your binary search function so it uses recursion?


## Objective challenge:
What will the contents of the array that is shown below look like after each pass of the Selection Sort algorithm?

![](https://tk-assets.lambdaschool.com/37acef2d-38c3-4479-a7db-582fa68943e1_Resources23.png)

**Define your own function that sorts the data “out-of-place” and mirrors the process we used for our “out-of-place” book sorting example. Compare this “out-of-place” selection sort to the “in-place” function that we defined together.**
- What is different about it?
- Which version do you think is better and why?
- What will the contents of the same array look like after each pass of the Insertion Sort algorithm?

![](https://tk-assets.lambdaschool.com/37acef2d-38c3-4479-a7db-582fa68943e1_Resources23.png)


**You have the cards 2, 7, 3, 4, and 6.**
- Write an algorithm in pseudo-code that arranges the cards in ascending order.
- What will the contents of the array below look like after each pass of the Bubble Sort algorithm?

![](https://tk-assets.lambdaschool.com/37acef2d-38c3-4479-a7db-582fa68943e1_Resources23.png)


**What would the following array look like after one iteration of Bubble Sort?**

```my_arr = [3,6,4,12,11,15,1,2]```
