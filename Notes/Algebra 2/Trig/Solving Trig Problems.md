#Trig 
#Solving_Problems

- How can you solve the trigonometric equation
	$6\sin (\theta) \ =\ 3\sin (\theta) \ +\ 2$  for values between $0$ and $2\pi$?

	1. Subtract $3\sin(\theta)$ from both sides of the equation.
		$6\sin (\theta) - 3\sin(\theta) = 3\sin(\theta) = 2$
	2. Divide $3$ from both sides to isolate $\sin(\theta)$.
		$\frac{3sin(\theta)}{3} = \sin(\theta) = \frac{2}{3}$
	3. Invert the $\sin$ function to isolate $\theta$ by using $\arcsin$.
		$\arcsin(\sin(\theta)) = \theta = \arcsin\left( \frac{2}{3} \right)$
	4. Calculate $\arcsin\left( \frac{2}{3} \right)$.
		$\theta = \arcsin\left( \frac{2}{3} \right) \approx 0.73rad$
	5. Find the other angle with the same sine: $(\frac{2}{3})$, by reflecting the angle across the $y$-axis.
		$\pi - 0.73 \approx 2.41rad$

-  What is the $\sin$ of $\theta$ if $\cos \theta =-\frac{3}{5}$ and the angle with measure $\theta$ is in Quadrant three?

	1. Using the [[The Pythagorean Identity]] we know that:
		 $\sin^{2}(\theta) + \left( -\frac{3}{5} \right)^{2} = 1$
	2. Simplify $\left( -\frac{3}{5} \right)^{2}$.
		 $\sin^{2}(\theta) + \frac{9}{25} = 1$
	3. Subtract $\frac{9}{25}$ from both sides.
		 $\sin^{2}(\theta) = \frac{16}{25} = 1 - \frac{9}{25}$
	4. Square both sides to cancel out the power of $2$.
		 $\sqrt{\sin^{2}(\theta)} = \sqrt{\frac{16}{25}}$
	5. Simplify.
		 $\sin(\theta) = \pm \frac{4}{5}$
	6. We know that $\theta$ is in quadrant $3$, so we know that the negative answer is correct.
		 $-\frac{4}{5}$
	* Note that if $\theta$ was in quadrant $1$ or $2$ the answer would be positive

- Solving a triangle with law of sines/cosines. ([[Law of Sines and Cosines]])
 ![[solve_triangle_with_cosines.png]]
	1. replace the known variables in the law of cosines. ($a^{2} + b^{2} - 2ab\cos(C) = c^{2}$)
		$8^{2}+11^{2}-2(8)(11)\cos(37\degree) = c^{2}$
	2. Simplify the exponents and multiplication.
		$64 + 121 - 176\cos(37\degree) = c^{2}$
	3. Calculate the cosine of $37$.
		$64 + 121 - 176(0.798) = c^{2}$
	4. Multiply, and finish adding/subtracting.
		$64 + 121 - 176(0.798) = 44.44... = c^{2}$
	5. Find the Square root of $44.44$ to approximate $c$.
		$\sqrt{44.44} \approx 6.67 \approx c$
	6. Since we have side $c$ we can use the law of sines to find $A$ and $B$.
		$\frac{\sin(37)}{6.67}=\frac{\sin(B)}{11}$
	7. Multiply both sides by $11$ to get $sin(B)$ by itself.
		$11\left( \sin\left( \frac{37}{6.67} \right) \right) = \sin(B)$
	8. Calculate the left side of the equation.
		$11\left( sin\left( \frac{37}{6.67} \right) \right) = .99$
	9.  Take the $.99$ of the answer to find the value of $B$.
		$\arcsin(.99)\approx82.98\degree$
	10. Add together the two angles we have, then subtract from $180$ to find the final angle.
		$180\degree-(37\degree+82.98\degree)= 60.02\degree$

