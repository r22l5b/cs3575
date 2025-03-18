java c
CSIT 5710 Problem Set 1 
Problem 2 (4pts) 
PRF security game. We recall the definition of a secure PRF. Let F:KxX→y be a function with key-space K, input space X and output space y. The PRF security game is played between an adversary A and a challenger C, defined as follow:
1. C picks a bit b  {0,1}
2. If b= 0, then C samples k  K and sets f ← F(k,.). If b=1, C samples a uniformly random function f: X → y.
3. PRFQuery: A chooses z ∈ X and sends z to C, who replies with f(x).
4. A can repeatedly make PRFQueries to the challenger (repeats step 3).
5. A outputs bit b' ∈ {0,1} and wins if b' = b
For a secure PRF, the probability of any probabilistic polynomial-time adversary winning the abovegame is at most 1/2 +e(n), for some negligible function e of security parameter n.
(a) (1pt): Let F: {0,1}n× {0,1}n → {0,1}n be a secure PRF. Let F' : {0,1}n × {0,1}n → {0,1}n be the function

Is F' a secure PRF? If so, provide a proof for its security; otherwise, descr代 写CSIT 5710 Problem Set 1Python
代做程序编程语言ibe an attack that adversary A can use to break its security and explain why the attack works.
(b) (1pt): Let F: {0,1}n x {0,1}n → {0,1}n be a secure PRF. Let F' : {0,1}n× {0,1}n → {0,1}n be the function

Is F' a secure PRF?    If so, provide a proof for its security;    otherwise, describe an attack that adversary A can use to break its security and explain why the attack works.
(c) (2pts): Let F be a secure PRF defined over (K,X,y), where K= X=y= {0,1)".    Let Ki = {0,1}n+1.    Construct a new PRF Fi over (K1,X,y), with the following property: the PRF Fi is secure;    however, if the adversary learns the last bit of the key then the PRF is no longer secure.    This shows that leaking even a single bit of the secret key can destroy the PRF security property.    You need to provide the construction of Fi, prove it is a secure PRF, and show that if the adversary learns the last bit of the key, then the PRF is no longer secure.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
