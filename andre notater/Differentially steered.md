# differentially steered vehicle

## path to achieve the formula of angular speed from differentce in speed vectors spaced apart

$\dot{\theta} = \frac{V_L}{R_L} = \frac{V_R}{R_R}$, if we specify that $R_R = R_L + W$ we can say $\dot{\theta} = \frac{V_L}{R_L} = \frac{V_R}{R_L + W}$

with this we can start to calculate:

we start with:  
$\dot{\theta} = \frac{V_L}{R_L} = \frac{V_R}{R_L + W}$

focusing it down we start with:  
$\dot{\theta} = \frac{V_R}{R_L + W}$

multiplying up the $(R_L + W)$:  
$(R_L + W)\dot{\theta} = V_R$

opening the brachets we get:  
$R_L\dot{\theta} + W\dot{\theta} = V_R$

using $\dot{\theta} = \frac{V_L}{R_L}$ property to  
substitute for $\dot{\theta}$ we get:  
$R_L\frac{V_L}{R_L} + W\dot{\theta} = V_R$

this cancels out $R_L$ with $\frac{1}{R_L}$ to get:  
$V_L + W\dot{\theta} = V_R$

substracting to isolate $W\dot{\theta}$ we get:  
$W\dot{\theta} = V_R-V_L$

dividing down the $W$ to isolate for $\dot{theta}$ we get:  
$\dot{\theta} = \frac{V_R-V_L}{W}$
