## Linear Classifier

Before we defining multilayer perceptrons we need to understand the linear classifier. Lets say that we had a binary classification problem: our data is $$ (x^1, y^1) ... (x^n, y^n) $$ where $$ x^i $$ is the input and $$ y^i $$ is the output where $$ x \in R$$ and $$ y \in \{0, 1\} $$. Then with the data the aim is to find a function:

$$  f(x) = \sigma\left( \sum_{i=1}^{n} w_i x_i + b \right) = \sigma\left(\mathbf{w}^T\mathbf{x} + \mathbf{b}\right)
 $$ 

1. item 1
2. item 2
3. item 3
1. item 4
1. item 5


| Name |  Prime |
| ---- | ------ |
| John |  No    |
| Adam |  Yes   |
| Mary |  Yes   |
| Mark |  No    |


The following is a Python code block:
```python
  def hello():
      print("Hello world")
```

And this is a C code block:
```c
#include <stdio.h>
int main()
{
    printf("Hello, World!");
    return 0;
}
```
