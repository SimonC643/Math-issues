# Distance of the tips of a diagonally folded, rectangular towel

## Introduction

If you want to fold a rectangular, crumbled up Towel, you most likely take two random corners and pull it along them.  
If you are lucky, you have found the matching corners to fold it nicely and you can continue the process till the towel is neatly folded.  
Sometimes, you are not that lucky and you pick up the diagonal facing corners.  You now face W-shape-folded Towel.  

![Diagaonally Folded Towel](./towel.jepg)

If you are like me, the stupid thought of _"how far are the two remaining tips apart?"_ comes to your mind.
This page will answer this question and will release your mind in peace.

## Theorem

For a given rectangular Towel with a width of $`a > 0`$ and heigth of $`b > 0`$, where $`b>a`$, the distance of the two tips, when folded diagonally, is

```math
\sqrt{a^2+b^2} - 2 \frac{a^2}{\sqrt{a^2+b^2}}
```


## Proof

The geometrical representation of the towel is shown in the followin picture

![Folded Towel represented in Triangles](./folded_towel.png)

To proof the theorem, we want to calculate the length marked as $`x`$ in the diagram.

We already know that the diagonal has a length of $`d=\sqrt{a^2+b^2}`$.  As the folded towel is symmatrical, we observe, that

```math
x = d - 2y
```

With that we can focus on only one triangle:

![One side of the folded Towel represented by one triangle](./triangle.png)


The small and the big triangle both share the same angle $`\alpha`$.  As all triangles are right triangles, it follows

```math
\cos\alpha = \frac{y}{a} = \frac{a}{d}
\implies y = \frac{a^2}{d}
```

Combine all, we get the theorem:

```math
x = d - 2y = d - 2 \frac{a^2}{d} = \sqrt{a^2+b^2} - 2 \frac{a^2}{\sqrt{a^2+b^2}}
```
