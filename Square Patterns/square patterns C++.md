# Can you Code these Square patterns with C++


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

Solution by : [@code-withAshish](https://github.com/code-withAshish)

```C++
#include <stdio.h>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 5; i++) //loop for number of rows
    {
        for (j = 0; j < 5; j++) //loop for number of columns
        {
            cout<<"* "; //printing character
        }
        cout<<"\n"; //newline for every new row
    }
}
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

Solution by : [@code-withAshish](https://github.com/code-withAshish)

```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 5; i++) //loop for number of rows
    {
        for (j = 0; j < 5; j++) //loop for number of columns
        {
            if (j == i)  //condition for printing * character or blank space
            {
                cout<<"* ";
            }
            else
            {
                cout<<" ";
            }
        }
        cout<<"\n"; //newline for every row
    }
}
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

Solution by : [@code-withAshish](https://github.com/code-withAshish)


```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 5; i++)
    {
        for (j = 0; j < 5; j++)
        {
            if (i + j == 4)
            {
                cout << "* ";
            }
            else
            {
                cout << " ";
            }
        }
        cout << "\n";
    }
}
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

Solution by : [@code-withAshish](https://github.com/code-withAshish)

```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 5; i++)
    {
        for (j = 0; j < 5; j++)
        {
            if (i + j == 4 || i == j)
            {
                cout << "*";
            }
            else
            {
                cout << " ";
            }
        }
        cout << "\n";
    }
}
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

Solution by : [@code-withAshish](https://github.com/code-withAshish)


```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 6; i++)
    {
        for (j = 0; j < 6; j++)
        {
            if (i == 0 || i == 5 || j == 0 || j == 5)
            {
                cout << "* ";
            }
            else
            {
                cout << "  ";
            }
        }
        cout << "\n";
    }
}

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

Solution by : [@code-withAshish](https://github.com/code-withAshish)


```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 7; i++)
    {
        for (j = 0; j < 7; j++)
        {
            if (i == 0 || i == 6 || j == 0 || j == 6 || i + j == 6 || i == j)
            {
                cout << " * ";
            }
            else
            {
                cout << "   ";
            }
        }
        cout << "\n";
    }
}
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

Solution by : [@code-withAshish](https://github.com/code-withAshish)

```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 5; i++)
    {
        for (j = 0; j < 5; j++)
        {
            if (i == j)
            {
                cout << " * ";
            }
            else
            {
                cout << " @ ";
            }
        }
        cout << "\n";
    }
}
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

Solution by : [@code-withAshish](https://github.com/code-withAshish)

```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 5; i++)
    {
        for (j = 0; j < 5; j++)
        {
            if (i + j <= 4)
            {
                cout << " * ";
            }
            else
            {
                cout << " @ ";
            }
        }
        cout << "\n";
    }
}
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

Solution by : [@code-withAshish](https://github.com/code-withAshish)

```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 5; i++)
    {
        for (j = 0; j < 5; j++)
        {
            if (i == 0 || i == 4 || j == 0 || j == 4 || i == 2 && j == 2)
            {
                cout << " * ";
            }
            else
            {
                cout << "   ";
            }
        }
        cout << "\n";
    }
}
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

```C++
// your solution here
```
</details>

---
