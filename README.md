# Research-Assistant-Crypto
Application for Qodri Hassan

1. FINANCE

a. In economic theory, there are two types of variables namely stock and flow variables. Stock variables refers to those variables that are measured at a point in time, flow variables, on the other hand, refers to variables that are measured over a period of time.
The stock to flow ratio is the amount of a resource held in reserves(stock) divided by the amount of resources produced annually(flow). The stock to flow model is generally applied to natural resources which have an element of scarcity. For instance, in the case of gold, the World Gold Council estimates that around 190,000 tons of gold have ever been mined. This amount is what we can refer to as the stock. Meanwhile, there are about 2,500 – 3,200 tons of gold mined each year. This amount is what we refer to as the flow. Therefore, the stock to flow ratio for this instance would be calculated as 190,000/3,200.
The stock to flow ratio shows how much supply enters the market each year for a given resource relative to the total supply. The higher the stock to flow ratio, the less new supply enters the market relative to the total supply. As such, an asset with a higher stock to flow ratio should, in theory, retain its value well over the long-term.  
The stock to flow ratio treats bitcoins comparably to scarce commodities, like gold or silver. Hence, the bitcoin’s stock to flow model.
Gold and silver are often called store of value resources. They, in theory, should retain their value over the long term due to their relative scarcity and low flow. This is because it’s very difficult to significantly increase their supply within a short period of time.
Bitcoin is a similar resource to Gold and silver. It’s scarce, relatively costly to produce, and its maximum supply is capped at 21 million coins. Also, Bitcoin’s supply issuance follows a protocol which makes the flow completely predictable. According to the proponents of this model, these properties of Bitcoin makes it a scarce digital resource with profoundly compelling characteristics to retain value over the long term. According to model projections, Bitcoin’s price should see a significant increase over time due to its continually reduced stock to flow ratio.
This model however, comes with deficiencies both in theoretical proposition and its empirical foundation. Theoretically, the model assumes that the USD market capitalization of a monetary good is derived directly from their new rate of supply. No evidence or research has been provided to support this idea. This idea is also not applicable when applied to long run analysis or prediction of bitcoin worth.
In conclusion, the stock to flow metric says nothing about how market participants value commodities. Many cryptocurrencies which utilize Bitcoin’s code have the exact same supply schedule as Bitcoin and it is evident that their stock to flow values have nothing to do with their future (or current) valuation.  Therefore, we are left with a hypothesis that applies to no economic assets except bitcoin.

b. YARA INC		
Stock price(Po)=$40 
Strike/Exercise price = $45
Time to expiration= 4 months(4/12)
Volatility = 40% 
Risk free rate = 3%   
Call price ( Vc )= Po Nd1  - (x/ekrf * t)Nd2
 d1 = [ln[Po/x] + (KRF+ .05σ2)t]/ σ√t
 d2 = d1 - σ√t
Therefore,
d1 = (ln(40/45) + [0.03 + 0.5(0.40)2]*4/12)/0.40 * √4/12
    = (0.11778 + [0.03 + 0.08]0.33333)/0.40 * 0.57735
    = (-0.11778 + 0.0366663)/0.23094
    = -0.0811137/0.23094
    = -0.35
d1 = -0.35. 
Checking the corresponding value on the standard normal table:
Nd1= 0.3632

d2 = -0.35123 – 0.40√4/12
    = -0.35123 – 0.23094
    = -0.58
Checking the corresponding value on the standard normal table:
Nd2= 0.2810
To calculate the call price:
Vc = 40(0.3632) – (45/e0.03*4/12)0.2810
     = 14.528 – (45/1.010050)0.2810
     = 14.528 – 12.51918
     = 2.0088
     Therefore, call price is $2.
     

COMPUTER SCIENCE
a. Recursion is a method of solving a problem where the solution depends on solutions to smaller instances of the same problem. It calls itself over and over again until a base condition is met that breaks the loop.  Recursion solves recursive problems by using functions that call themselves from within their own code. 
However, recursion can be inefficient because:
	•	Recursion uses more memory, because the function has to add to the stack with each recursive call and keep the values there until the call is finished, which makes it use more memory as opposed to the iterative process
	•	Recursion can also be slow.











































MATHS

y = sqrt((x+6)^2 + 25) + sqrt((x-6)^2 + 121)
Using chain rule on both terms separately:
The first term can be re-written as follows:
Y = ((x+6)^2 + 25)^1/2
      Let u = (x+6)^2 + 25
              du/dx = d/dx((x+6)^2 + 25)
            y = U^1/2
            dy/du = ½ U^-1/2
                  = 1/2U^1/2
         Therefore, following the rule
	=1/2 ((x+6)^2 +25)^1/2 * d/dx((x+6)^2 + 25)
	=(d/dx((x+6)^2) + d/dx (25))/2√((x+6)^2+25)
	= (2(x+6) + 0)/ 2√((x+6)^2+25)
	Dividing numerator by denominator
	= (x + 6)/ √((x+6)^2+25)
The second term can be re-written as follows:
Y = ((x-6)^2 + 121)^1/2
      Let u = (x-6)^2 +121
              du/dx = d/dx((x-6)^2 +121)
            y = U^1/2
            dy/du = ½ U^-1/2
                  = 1/2U^1/2
         Therefore, following the rule
	=1/2 ((x-6)^2 +121)^1/2 * d/dx((x-6)^2 + 121)
	=(d/dx((x-6)^2) + d/dx (121))/2√((x-6)^2+121)
	= (2(x-6) * d/dx(x-6) + 0)/ 2√((x+6)^2+121)
	Dividing numerator by denominator
	= ((x - 6)*d/dx(x-6))/√((x-6)^2+121)
	= (d/dx(x) – d/dx(6) * (x-6)) / √((x-6)^2+121)
	= ((1-0) * (x -6))/√((x-6)^2+121)
	= x-6/ √((x-6)^2+121).
Therefore, bringing the result of both terms together we have:
dy/dx = (x + 6)/ √((x+6)^2+25) + (x-6)/ √((x-6)^2+121)
To get the minimum value, dy/dx should be set to zero (i.e dy/dx=0):
(x + 6)/ √((x+6)^2+25) + (x-6)/ √((x-6)^2+121) = 0
Rearranging (note the effect of the rearrangement on the rhs):
 (x + 6)/ √((x+6)^2+25) = (6-x)/ √((x-6)^2+121)
Take squares to eliminate roots:
 (x + 6)^2/ ((x+6)^2+25) = (6-x)^2/((x-6)^2+121)
Expanding:
 (x+6)(x+6) / (x+6)(x+6) + 25 = (6-x)(6-x) / (x-6)(x-6) + 121
 x^2 + 6x + 6x + 36 / x^2 + 6x +6x +36 +25 = 36 -6x-6x+x^2/x^2-6x-6x+36+121
x^2+12x+36 / x^2+12x¬+61 = x^2 -12x+36 / x^2-12x+157
Cross Multiplying:
x^2+12x+36(x^2-12x+157) = x^2+12x+61(x^2-12x+36)
x^4-12x^3+157x^2+12x^3-144x^2+1884x+36x^2-432x+5652=x^4-12x^3+36x^2+12x^3-144x^2+432x+61x^2-732x+2196
Simplifying,
x^4+49x^2+1452x+5652 = x^4-47x^2-300x+2196
collect like terms
x^4+49x^2+1452x+5652 – (x^4-47x^2-300x+2196) = 0
x^4+49x^2+1452x+5652-x^4+47x^2+300x-2196=0
Simplify
96x^2+1752x+3456=0
Solving quadratically with the aid of a calculator we have,
24(4x+9) = 0	or 	x+16=0
4x+9=0		x = -16
4x= -9
x = -2.25

Substituting the values for x in the equation for y
y = sqrt((x+6)^2 + 25) + sqrt((x-6)^2 + 121)

When x = -2.25			
y = sqrt ((-2.25+6)^2 + 25) + sqrt ((-2.25-6)^2 + 121)   	    	
   = sqrt ((3.75)^2+25) + sqrt ((-8.25)^2+121)
   = sqrt (39.0625) + sqrt (189.0625)
   = 6.25 + 13.75
   = 20.
or					
when x = -16
y = sqrt ((-16+6)^2 + 25) + sqrt ((-16-6)^2 +121)
   = sqrt ((-10)^2+25) + sqrt ((-22)^2+121)
   = sqrt (125) + sqrt (608)
   = 11.18 + 24.5967
   = 35.78
Therefore, the minimum value of y is 20 and can be achieved when x = -2.25




