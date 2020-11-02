# Modular Arithmetic

Two numbers, a and b are congruent modulo n if they have the same remainder when divided by n. Mathematically, 

$$
a \equiv b \ (mod\ n)
$$

Equivalently, 

$$
a \equiv b\ (mod\ n) \ \  iff \ \  (a - b) \ \%\ n = 0
$$

### Congruence Relations / Properties

#### A\) Addition of Constants

If we add a constant 'c' on both sides of the modulo relation then the equivalency still holds true.

$$
a+c \ \equiv \ b+ c\ (mod\ n)
$$

$$
Also, \ if\ a\equiv b\ (mod\ n) \ and  \ c \equiv d\ (mod\ n)\\ then, \ a+c \equiv b+d\ (mod\ n)
$$

#### Q. What is the remainder of 10 + 19 + 21 + 31 + 26 when divided by 4?

This problem can easily be solved by first evaluating the sum and then find the remainder on dividing by 4. But in situations where a very large number of big numbers are involved this approach becomes computationally unfeasible. Using the above property, 

$$
10+19+21+31+26\ (mod\ 4) =2+3+1+3+2\ (mod\ 4)\\\ \ \ \ \ \ \ \ \ \ \ \ = 3
$$

#### B\) Multiplication by a Constant

$$
if\ a\equiv b\ (mod\ n)\\then,\ a\times c \equiv b\times c\ (mod\ n)
$$

$$
if\ a\equiv b\ (mod\ n)\ and\ c\equiv d\ (mod\ n)\ then,\\a\times c \equiv b\times d\ (mod\ n)
$$

#### Q. What is the remainder of $$24\times 81\times 91\times 101\times 26$$ when divided by $$5$$ ?

A quick evaluation of the expesssion gives us $$465449904$$ which on division by $$5$$ gives $$4$$ as a remainder. Again using the above property this expression can be solved very elegantly as follows:  
  
 $$24\times 81\times 91\times 101\times 26\ (mod\ 5)=4\times1\times 1\times 1\times 1\ (mod\ 5)\\=4$$ 

#### Q. Find the remainder $$17\times (12\times 19 +5)-23$$ of when divided by $$3$$ ?

Applying both relation A and relation B simultaneously,  
  
  $$17\times (12\times 19 +5)-23\ (mod\ 3)=2\times(0\times1+2)-2\ (mod\ 3)\\=2.$$ 

{% hint style="info" %}
2 modulo 3 can also be expressed as -1 so remainders r modulo 3 set is {0, 1, -1} which in many cases can further simplify the calculation. 
{% endhint %}

#### 

