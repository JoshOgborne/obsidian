# Chapter 1 - Intro to Vectors
```
Test
```


## Example Vectors
$$
v = 
\begin{bmatrix}
	v_{1}\\ v_{2}\\
\end{bmatrix} \ \
w = 
\begin{bmatrix}
	w_{1}\\ w_{2}\\
\end{bmatrix}
$$


When doing calculations with vectors you use the components of the vectors. Where the first vector is v, the components are v$_1$ and v$_2$ and for vector w, the components are w$_1$ and w$_2$ .

When multiplying vectors we use a scalar __c__.
$$
cv = 
\begin{bmatrix}
cv_{1} \\
cv_{2}
\end{bmatrix}
$$
The sum of -v and v is the zero vector. The zero vector is represented by 0 but it is different from the number 0. The zero vector has components of 0 and 0.


## Linear Combinations

Combining addition and scalar multiplication gives linear combinations of v and w. Eg: Multiple v by c, multiply w by d and then add them, cv + dw.

The main linear combinations are: **Sum, Difference, zero vector and scalar multiplication**.

Vector addition provides the diagonal of a parallelogram.

Example of scalar multiplication on a graph will show 2v as double the length of the arrow and -v will be the reversed vector, essentially mirrored.

## Three Dimensions

$$ v =
\begin{bmatrix}
v_{1} \\
v_{2} \\
v_{3}
\end{bmatrix} \
w = 
\begin{bmatrix}
w_{1} \\
w_{2} \\
w_{3}
\end{bmatrix}
$$


Usually arrows for vectors starts at 0,0,0 which is where the axis meet. The arrow ends at the point with coordinates v$_1$, v$_2$, v$_3$ . 

Vectors can be written such as v = (v$_1$ , v$_2$, v$_3$).

### Linear Combinations of three dimensional vectors

Using the vectors u, v, w the combination cu fills a line. The combination cu + dv fills a plane. And the combination cu + dv + ew fills a three dimensional space.

## Lengths and Dot Products

Dot product representation:
$v.w = v_{1}v_{2} + w_{1}w_{2}$

For example:
$$
v = (1,2)
\
w = (3, 1)
$$
The dot product of v and w is $v_{1}.v_{2} + w_{1}w_{2}$ is v.w
Substituted that gives is 1 * 2 + 3 * 1 = 2 + 3 = 5


The dot product is the multiplication of the components of vectors and then adding them together. 
If the dot product is zero, the two vectors are perpendicular and the angle between them is $90^o$

To compute v.w multiply each v$_{i}$ times w$_{i}$ then add $\sum_{}$v$_{i}$w$_{i}$

## Lengths and unit vectors

You can calculate dot products of a vector with itself. Eg: vector v = (1,2,3), the dot producty of itself is v.v = ||v||$^2$ = 14. ||v||$^2$  = $$
\begin{bmatrix}
1 \\
2 \\
3
\end{bmatrix} \\
.
{\begin{bmatrix}
1 \\
2 \\
3
\end{bmatrix}}
$$
1.1 + 2.2 + 3.3 = 1 + 4 + 9 = 14

This gives us an angle of $0^0$ . The answer can't be zero since the lines aren't perpendicular. The dot product of v.v is the length of v squared.
The length ||v|| of a vector v is the square root of v.v
Length = norm      Length = ||v|| = $\sqrt{ v.v }$

In two dimensions the length is $\sqrt{ v_{1}^2 + v_{2}^2 }$ . In three dimensions it's $\sqrt{ v_{1}^2 + v_{2} ^2 + v_{3}^2 }$
Therefore the length of v = (1,2,3) is ||v|| = $\sqrt{ 14 }$ 
||v|| = $\sqrt{ v.v }$ which is the ordinary length of the arrow that represents the vector.
In two dimensions the arrow is on a plane. If the components are 1 and 2, the arrow is the third side of a right triangle. The pythag formula $1^2 + 2^2 = ||v||^2$ . 
For the length of v = (1,2,3), we sue the pythag formula twice. 
The vector (1,2,0) in the base has length $\sqrt{ 1^2 + 2^2 + 0^2 }$ = $\sqrt{ 5 }$ . This base vector is perpendicular to (0,0,3) that goes straight up and has a length of $\sqrt{ 0^2 + 0^2 + 3^2 } = \sqrt{ 9 }$ Therefore the diagonal of the box has length $||v|| = \sqrt{ 5 + 9 } = \sqrt{ 14 }$

The length of a four dimensional vector would be $\sqrt{ v_{1}^2 + v_{2}^2  + v_{3}^2 + v_{4}^2}$
If the vector was (1,1,1,1) the length would be $\sqrt{ 1^2 + 1^2 + 1^2 + 1^2 }$ = 2. This is the diagonal through a unit cube in four-dimensional space.
The diagonal in n dimensions has length $\sqrt{ n }$.
The word "unit" is always indicating some measurement equal to "one".

A Unit Vector is a vector whose length equals one u.u = 1.
An example in four dimensions is $\frac{1}{2}.\frac{1}{2}.\frac{1}{2}.\frac{1}{2}$. Then u.u is $\frac{1}{4}.\frac{1}{4}.\frac{1}{4}.\frac{1}{4} = 1$
We divided v = (1,2,3,4) by its length $||v||$ = 2 to get this unit vector.

Standard unit vectors along the x and y axis are written i and j. In the x y plane the unit vector that makes angle *theta* with the x axis is ($\frac{\cos \theta}{\sin \theta}$)