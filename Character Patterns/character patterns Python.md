# Can you code these Square patterns with python


### Pattern 1

input : 5
```
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
```

<details> <summary>Show Solution</summary>

Solution by : [@Muntaqim Ahmed](https://github.com/ahmed51raj)

```python
n = 5
for i in range(n):
  for j in range(n):
    print('*', end=' ')
  print()
```
</details>

---

### Pattern 2

input : 5
```
*
  *
    *
      *
        *
```

<details> <summary>Show Solution</summary>  

Solution by : [@Muntaqim Ahmed](https://github.com/ahmed51raj)

```python
n = 5
flag = 0
for i in range(n):
  for j in range(n):
    if flag == j:
      print('*', end=" ")
    else:
      print(" ", end= " ")
  flag += 1
  print()
```
</details>

---

### Pattern 3

input : 5
```
        *
      *
    *
  *
*
```

<details> <summary>Show Solution</summary>  

Solution by : [@Muntaqim Ahmed](https://github.com/ahmed51raj)

```python
n = 5
flag = 4
for i in range(n):
  for j in range(n):
    if flag == j:
      print('*', end=" ")
    else:
      print(" ", end= " ")
  flag -= 1
  print()
```
</details>

---

### Pattern 4

input : 5
```
*       *
  *   *
    * 
  *   *
*       *
```

<details> <summary>Show Solution</summary>  

Solution by : [@Muntaqim Ahmed](https://github.com/ahmed51raj)

```python
n = 5
low = 0
high = n-1
for i in range(n):
    for j in range(n):
      if j == low or j == high:
        print("*", end = " ")
      else:
        print(" ", end = " ")
    print()
    low += 1
    high -= 1
```
</details>

---

### Pattern 5

input : 6
```
* * * * * *
*         *
*         *
*         *
*         *
* * * * * *
```

<details> <summary>Show Solution</summary>  

Solution by : [@Muntaqim Ahmed](https://github.com/ahmed51raj)

```python


n = 6
for i in range(n):
    for j in range(n):
      if i == 0 or i == (n-1):
        print("*", end=" ")
      else:
        if j == 0 or j == (n-1):
          print("*", end=" ")
        else:
          print(" ", end=" ")
    print()
      
```
</details>

---

### Pattern 6

input : 7
```
* * * * * * *
* *       * *
*   *   *   *
*     *     *
*   *   *   *
* *       * *
* * * * * * *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```python
# your solution here
```
</details>

---

### Pattern 7

input : 5
```
* @ @ @ @
@ * @ @ @
@ @ * @ @
@ @ @ * @
@ @ @ @ *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```python
# your solution here
```
</details>

---

### Pattern 8

input : 5
```
* * * * *
* * * @ @
* * @ @ @
* @ @ @ @
@ @ @ @ @
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```python
# your solution here
```
</details>

---

### Pattern 9

input : 5
```
* * * * *
*       *
*   *   *
*       *
* * * * *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```python
# your solution here
```
</details>

---

### Pattern 10

input : 11
```
* * * * * * * * * * *
*                   *
*   * * * * * * *   *
*   *           *   *
*   *   * * *   *   *
*   *   *   *   *   *
*   *   * * *   *   *
*   *           *   *
*   *  *  *  *  *   *
*                   *
* * * * * * * * * * *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```python
# your solution here
```
</details>

---
