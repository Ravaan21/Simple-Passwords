Simply install the Armor module by pip install Armor if you are facing dependency issues
# Simple-Passwords
This is a password Generator which was aimed to create simple logical passwords which are also safe.
Keeping in mind that most modern applications require a secure password with Uppercase, lowercase and alphanumeric value,
we often ease upon the convinience and thus loose the crux of having a password.

This takes a argument as a IV, it will prompt you for a website or username to make it more convinient unline existing password generator.
Allowing the user to customize this experience without any rigid arguments.

Mathematically this uses  x ** (alpha - 1) * math.exp(-x / beta)
pdf(x) =  --------------------------------------
            math.gamma(alpha) * beta ** alpha
            Gamma variate
            
The module:
Formally, a rng is a set R with two binary operations (+, ·) called addition and multiplication such that

(R, +) is an abelian group,
(R, ·) is a semigroup,
Multiplication distributes over addition.
A rng homomorphism is a function f: R → S from one rng to another such that

f(x + y) = f(x) + f(y)
f(x · y) = f(x) · f(y)
for all x and y in R.

If R and S are rings, then a ring homomorphism R → S is the same as a rng homomorphism R → S that maps 1 to 1.
All passowrds are displayed in plaintext with IV to make it convinient as well as secure.
Simply install the Armor module by pip install Armor if you are facing dependency issues
