***Introduction*** to Aggreagate Output

National income accounts 
- accounting system
- used to measure AD/AS economic activity 


Key measures of AD/AS stuff
- GDP 
- GDI 
- By construction, GDP = GDI

These are all flow variables (varies... not stock!)

GDP:
- measure by total value of final goods and services produced (see: not intermediate!) 
- value-added approach (start from intermediate good, then subtract final good - intermediate good, then add the two)
	- e.g: steel $100, car $210, so $210 - $100 = 110, so value added: $100 + 110 = $210

GDI
- total income (wages and profits/losses) 

These are all merely a representation of economic activity, nothing more! Housework is considered an economic activity but it is very hard to put a figure on it! 

Nominal and Real GDP
nominal: Sum of quantity * current price  

real: sum of quantitiy * constant inflation adjusted price 

base year:= nominal gdp = real gdp (as the 'current' price is the base year price lol) 

Inflation: GDP deflator and consumer price index (CPI)

GDP deflator: $\$Y_{t}$ is nominal GDP in period t 
$Y_{t}$ is real GDP at period t 
$P_{t} \equiv \frac{\$Y_{t}}{Y_{t}}$*100 where $P_{t}$ is the GDP deflator - a price index. In base year should equal to 100 (or 1).
Measures average price of aggregate output 

CPI is a consumption basket - average price of certain goods. CPI and GDP deflator move together over time.

Inflation rate: $$\pi_{t}\equiv \frac{P_{t} - P_{t-1}}{P_{t-1}}$$


Unemployment: 
L = N + U, where L is the labour force, N = employed, U = unemployed

employment rate: u = U/L 
participation rate: L/working age population (16+, able to work physically)

Note: u = U / (U + E) = U / L 

<h1>lecture 2</h1>
<h3>GDP components</h3>

Consumption: $C$ purchase of goods and services by households

Investment: $I$, purchase of capital goods by firms and businesses (PPE + residential investment) 

Government: $G$, purchase of goods and services through the government (DOES NOT INCLUDE TRANSFER PAYMENTS, but they enter GDP when spent by $C$ or $I$. 

Net exports: $X - IM$, exports minus imports 

LeEquation: $$Y = C + I + G + NX = C + I + G + X - M$$

Closed economy: $X = IM = 0$, so $Z \equiv C + I + G$

<h3>Consumption function</h3>

Disposable income: income - net taxes, or $Y_{D} = Y - T$. 
Key assumption in short-run: $C = C(Y_{D}) = c_{0} + c_{1}Y_{D}$. In other words, C is a function of some $Y_{D}$. $c_{0}, c_{1} > 0$ and $c_{1} < 1$. 
$c_{1}$ is the marginal propensity to consume. How much would a consumer spend if they had an extra dollar. 

<h3>Other parts of demand</h3> 

I, G, and T are <b>exogenous</b>. This means we take the value as given.
G and T are fiscal policy. 

<h3>Equilibrium in the goods market</h3> 

Short term: demand for goods $Z$ determines production of $Y$ (output)
Production $Y$ is equal to aggregate income Y (since GDP = GDI usually...)
Equation: $$Z = c_{0} + c_{1}(Y -T) + I + G$$  
Solve for $Y$. Remember $Y = Z$ in the short run. 

Solving for $Y$ yields:
$$Y = \frac{1}{1 - c_{1}}(c_{0} - c_{1}T + I + G)$$, for some $0 < c_{1} < 1$.

Multiplier: $\frac{1}{1 - c_{1}}$ 
Autonomous spending: $c_{0} - c_{1}T + I + G$

The more sensitive consumption is to income, the larger the multiplier.

<h3>Investment/savings approach to goods market</h3> 

Private savings is disposable income - consumption, or $$S \equiv Y_{D} - C$$ 
Then, $$S \equiv Y - T - C $$ as dispoable income is income - net taxes 
With closed economy: $$Y = C + I + G$$ 

Then, $$I = S + T - G$$ 
Investment is private savings S + public savings $T - G$. 

If $T > G$ then government is running at a surplus, public saving positive
If $T < G$ then government is running at a deficit, public saving negative 

Two ways to state equilibrium: output = demand, or investment = savings (public + private) 

Consumption and savings decisions are the same - no leakages/injections from outside (remember this is a c l o s e d economy!) 
This is also why its called the *IS curve* for equilibrium in the goods market - investment = savings! 

<h3>Fiscal policy</h3> 

With $$Y = \frac{1}{1 - c_{1}}(c_{0} - c_{1}T + I + G)$$ government can set Y by changing G or T. But this is often hard to do (estimating multipliers is difficult and even controversial amongst policymakers) 
- Is G and T changes temporary or permanent 
- Overstimulating economy may cause inflation
- Any existing debts/deficits could be excaerbated  

<h3>Endogenous investment demand</h3> 

Let investment depend on aggregate income $Y$, and some interest rate $i$. Then:
$$I = I(Y,i) = b_{0} + b_{1}Y - b_{2}i$$, for $b_{0}, b_{1}, b_{2} > 0$.
$b_{1} < 1$ 

$I$ depends positively on $Y$ but negatively on $i$. This makes sense - as $i$ increases, $I$ (private investment) will decrease as cost of borrowing ($i$) increases.

Let's review the two functions we learnt:
1. Consumer function: $C = c_{0} +c_{1}(Y-T)$ 
2. Investment function: $I = b_{0} + b_{1}Y - b_{2}i$. Subbing these into $Y = C + I +G$ yields:

$$Y = \frac{1}{1 - c_{1} - b_{1}}(c_{0} - c_{1}T + b_{0} - b_{2}i +G)$$
where $c_{1} + b_{1} <1$
Here Y is negatively related with $i$. 
Hence: 
- IS curve represent combinations of ${Y, i}$ consistent with goods market equilibrium 
- changes in fiscal policy (G, T) shift the curve in or out 
- part of the IS-LM model 

<h3>example problem</h3> 

If a closed economy has the follow consumption function: $C = 100 +0.5Y_{D}$, with exogenous investment $I = 50$, and $G = 20, T =20$. What is $Y$ and $C$?

1. Start with $Y = C + I  G$ (closed economy) 
2. Sub in the values. $Y = 100 + 0.5Y_{D} +50 + 20$
3. Recall that $Y_{D} = Y - T$. Sub this: $Y = 100 + 0.5(Y - 20) + 70$.
4. Solve for Y: $Y = 320$
5. Solve for C: $C = 100 + 0.5(320 - 20) = 260$.
6. Bonus: $\frac{C}{Y} = \frac{260}{320} \approx 78\%$. This is consumption / GDP ratio. How much consumption makes up total GDP. Tends to high for developed nations. 