---
layout: page
title: Matrix Mystics
order: 5
permalink: /matrixmystics/
---

* TOC
{:toc}
# Module 1

0. Ram and Lakshman were two brothers, Ram's pocket money was twice as much as Lakshman. The good boy that Ram and Lakshman were, they did not spend their pocket money on anything. They instead saved the same in their piggy bank. Every week, they would check their savings so far. Assume the first week's savings was $$(R_1,L_1)$$ and second week's $$(R_2,L_2)$$ and so on. They try plotting their weekly savings on a graph sheet. How will the points look like?

0. Atul's house is centered at origin $$(0,0)$$ he walks straight (along the x-axis) for 2 units and then takes a left and walks 1 unit to reach Bala's house, after that he takes a right turn and walks for one unit and then a left turn and walks for one unit and reaches Chetan's house. He continues in a similar style, takes a right turn 1 unit and then left turn one unit and reaches Divya's house. Are the houses of Bala, Chetan and Divya on a straight line? What is the equation of this line? Plot this on Geogebra



1. Plot the lines $$y=x$$, $$y=2x$$, $$y=10x$$.

2. Observe that they all pass through the origin. Why?

3. Plot $$y=2x+1$$. Why doesn't it pass through the origin?

4. Plot $$y=ax+b$$, with $$a$$ and $$b$$ as parameters which you should be able to varry. What do youaa observe?

5. Consider the following simultaneous equation:

   2x+3y=7 <br>
   3x+4y=10 <br>

   Do you see a 2x2 matrix here? What is the importance of seeing a matrix in this problem? Why study matrices in general?<br>Do you observe that this problem can be retold as: <br>$$ \left( \begin{matrix} 2 & 3 \\3 & 4 \\\end{matrix}\right) $$
   $$\left(
   \begin{matrix}
   x\\
   y\\
   \end{matrix}
   \right)$$
   =$$\left(
   \begin{matrix}
   7\\
   10\\
   \end{matrix}
   \right)$$
5. Consider a simple function $$f(x) = 3x+2$$. This function is invertible right? Can you tell us what is $$\alpha$$ such that $$f(\alpha)=17$$? Is such an $$\alpha$$ unique? How did you find such an $$\alpha?$$. Is this always possible?

5. Consider the function $$f(x)=x^2-10$$, what is f(5)?

6. Consider the function $$f(x)=x^2-10$$, if $$f(\alpha)=54$$, what is $$\alpha$$?

7. Consider the function $$g(x)=x^3-x^2-10x+2$$, if $$g(x)=-22$$ what is $$x$$?


6. Do you know what is $$\mathbb{R}, \mathbb{R}^2 and \mathbb{R}^3$$ ? 


8. Consider the function $$\phi : \mathbb{R}^2\rightarrow \mathbb{R}^2$$ defined by $$\phi (x,y)=(2x+3y,3x+4y)$$. What has this to do with the previous question?

9. Is the function $$\phi$$ invertible? In the question above on matrices, we see that it is of the form $$Ax=b$$. Note that we can invert the matrix, using the method that was taught to us in our high school to find out the value for the variables x and y. This is one of the many applications of matrices.

10. We will now see matrices as functions. Instead of $$\phi$$ we will write the matrix itself: <br>$$\left( \begin{matrix} 2 & 3 \\3 & 4 \\\end{matrix}\right) : \mathbb{R}^2 \rightarrow \mathbb{R}^2$$. 

11. Consider the function $$\left( \begin{matrix} 1 & 2 \\2 & 4 \\\end{matrix}\right) : \mathbb{R}^2 \rightarrow \mathbb{R}^2$$. This matrix takes a few elements to the origin. What are those elements? Plot this using Geogebra.



# Module 2

---

1. A is assigned 0, B:1, C:2, and so on up to Z:25<br>
Assume you denoted every letter with a number, as given in the table above.<br> You need to encrypt the word "SUDARSHANA" which stands for the numbers: $$18, 20, 3, 0, 17, 18, 7, 0, 13,0$$. <br>
You encrypt this using a matrix given by : $$ \left( \begin{matrix} 2 & 3 \\3 & 4 \\\end{matrix}\right) $$. <br>
So "SUDARSHANA" will end up becoming: $$96, 134, 6, 9, 88, 123, 14, 21, 26, 39$$. <br>
Given these numbers, how will you decrypt the message and get back "SUDARSHANA"?<br>. This is a well known cryptographic protocol called the Hill Cipher. You can read more online.
1. We encounter equations very often in our lives. Consider for example, the following situation at ___Baker's Cafe___. The manager has a very important estimate to make. Mostly, visitors at his cafe happen to be families and they are often comprised of Children and/or Adults. He observes that there are 3 adults and 1 child at a table and their bill turns out to be Rs.1200/-. There is yet another table with 2 children and 1 adult and their bill comes out to be Rs.1000/-. Can the manager estimate the consumption of a Child/Adult? This is popularly called the _Simultaneous Equations_ and we all remember from our school days, multiple ways in which these can be solved.<br>
   $$ 3A + 1C = 1200 $$   
   $$ 1A + 2C = 1000 $$

2. While we were taught the so called two variables and two unknowns, what if there were more equations than unknowns?<br>
   $$ 3A + 1C = 1200 $$   
   $$ 1A + 2C = 1000 $$    
   $$ 1A + 1C =  900 $$

3. Note that the previous question can be modelled as a matrix:

   $$ 3A + 1C = 1200 $$   
   $$ 1A + 2C = 1000 $$    
   $$ 1A + 1C =  900 $$

   <u>Observe</u> this is same as :

   $$ \left( \begin{matrix} 3 & 1 \\1 & 2 \\1 & 1 \\\end{matrix}\right) $$
   $$\left(
   \begin{matrix}
   A\\
   C\\
   \end{matrix}
   \right)$$
   =
$$
\left(
	\begin{matrix}
	1200\\
	1000\\
	900\\
	\end{matrix}
   \right)
$$



4. One obvious way to solve this, is to guess the values :-). Can you get closer to the solution by guessing? Note that there is no solution to this question. You can just reduce the error. Do you see why?

