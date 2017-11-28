### Introduction to Enumerative Combinatorics, quiz 3

#### Question 1

$$(-2, -2) -> (0, 0)$$

$$$
\binom{2+2}{2} = 6
$$$

$$(0, 0) -> (3, 3)$$
$$$
\binom{3+3}{3} = 20
$$$

$$$
6 * 20 = 120
$$$

because we have to pass through the point $$(0, 0)$$

#### Question 2

$$$
\frac{6!}{3!} = 120
$$$


#### Question 3

This formula is taken from Concrete Mathematics: A Foundation for Computer Science (2nd Edition), page 139:

$$$
N(10, 2) = \frac{1}{10}\sum_{d|10} 2^{d} \phi(\frac{10}{d}) = \frac{1}{10}(2^{1} * \phi(10) + 2^{2}*\phi(5) + 2^{5}*\phi(2) + 2^{10}*\phi(1)) = \frac{1}{10}(8 + 16 + 32 + 1024) = 108
$$$

#### Question 4

$$$
300 - (300 * \frac{1}{2} + 300 * \frac{1}{3} + 300 * \frac{1}{5} - 300 * \frac{1}{6} - 300 * \frac{1}{10} - 300 * \frac{1}{15} + 300 * \frac{1}{30}) = 300 - (150 + 100 + 60 - 50 - 30 - 20 + 10) = 80
$$$
