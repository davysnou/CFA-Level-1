# Detailed Notes for CFA Level 1

## I. Economics

### A. Time Value of Money
1. Interested Rate  
(1) Interest rate = nominal risk-free rate + risk premium  
(2) nominal risk-free rate = real risk-free rate (t-bill rate) + inflation rate  
(3) risk premium = default risk premium + liquidity risk premium + maturity risk premium  

2. Effective Annual Rate
lim(1+1/n)^n = e
Continuous compounding EAR = e^r - 1

3. Annuity  
(1) Ordinary annuity  
(2) Annuity due  
(3) Perpetuity P = A/r  
(4) Geometric Sequence Formula  
<img src="https://i.ytimg.com/vi/XjdDt2xU-tw/maxresdefault.jpg" width="200" height="150">  

### B. Statistics

1. Measurement scale (Weak -->> strong)  
(1) Nominal scale  
(2) Ordinal scale: sort data into categories  
(3) Interval scale: equal difference between scale values. Additive and subtractive  
(4) Ratio scale: true zero point, additive, subtractive, mutiplitive, dividitive  

2. Frequency Distribution  
(1) Absolute Frequency  
(2) Cumulative Absolute Frequency  
(3) Relative Frequencies  
(4) Cumulative Relative Frequencies

3. Quant Description of Distribution  
(1) Central tendency (return centered)  
(2) Dispersion (standard deviation)  
(3) Skewness  
(4) Kurtosis  
(5) Moment E(x-Ex)^k *Central tendency: Ex = 0

4. Mean  
    (1) Arithmetic Mean  
    (2) Weighted Mean: sum(Wi) = 1, Wi can be negative(short) or greater than 1(leverage)  
    (3) Geometric Mean: G = n_rt(X1X2...Xn)  
    (4) Geometric Periodic Return: R = n_rt[(1+r1)(1+r2)...(1+rn)]-1  
    (5) Harmonic Mean: N/(sum(1/Xi)) use when absolute spent amount are the same, eg. $100 to buy three stocks, $10/share, $20/share, $30/share  
    (6) Harmonic Mean <= Geometric Mean <= Rithmetic Mean  
    (7) Equal sign only happens when all data are the same  
    (8) Dispersion: Greater variability, the more the discrapancies between different means

### C. Cost of Capital
1. Weighted average cost of capital = debt*(1-marginal tax rate) + preferred stock + equity  

    (1) Calculation
    * Market value instead of book value
    * D/E = n, D + E = 1
    * %

### D. Demand
1. Definition: Willingness and ability to consume a good or service at a given price  

    (1) Price determines quantity Q = f(P)  
    * Normally, P up, Q down  
    * Exceptions: Giffen goods, Veblen goods  

    (2) Demand function: Qx = f(Px, I, Py ...)
    * Px: price of good X
    * I: income
    * Py: stustitute good Y
    * Assumption: I and Py constant
    * Q = a + b*Px

    (3) Demand curve P = m + n*Q  
    * Moment: Px change or point change  
    * Shift: constants (I and Py) change or curve shift  
    * Consumer surplus: the different between the highest price that the consumer willing to pay and the actual paid price  
    <img src = 'https://marketbusinessnews.com/wp-content/uploads/2017/02/Economic-Surplus-Consumer-and-Producer-Surplus.jpg' width = 250 height = 250>

2. Price elasticity of demand  
> (1) Formula  

$$E^d_Px = \frac{\%\Delta Qx}{\%\Delta Px} = \frac{\Delta Q/Q}{\Delta P/P} = \frac{\Delta Q}{\Delta P}*\frac{P}{Q}$$  
* Elastic: $$|E^d_Px| > 1$$   
* Unit elastic: $$|E^d_Px| = 1$$  
* Inelastics: $$|E^d_Px| <> 1$$  

> (2) Interpretation  
>> * **The price elasticity**: the tangent between quantity and price.
>> * Elastic: the price won't raise too much, because a small price rise can cause a large quantity dip. The selling strategy would be sell more with lower price.  
>> * Inelastic: life necessities, the price change won't impact as much as elastic goods for the quantity.
>> * There is one and only one unit elastic point, where the total return also reachs its maximum. 
>> * Before unitary elastic point: **elastic**
>> * After unitary elastic point: **inelastic** 
> <img src = "https://shellg.files.wordpress.com/2012/12/elastic.gif">
>> * When elastic, the price and total expenditure moves in opposite direction.
>> * When inelastic, the price and total expenditure moves in the same direction.

> (3) Interpretation derivation  
>> 1. Break down the formula
>> $$R = P * Q_P$$
>> $$= \frac{dR}{dP} = Q + P * \frac{\Delta Q}{\Delta P}$$
>> $$= Q + E^d_P * Q = (1+Q) * E^d_P$$

>> 2. How is the change of revenue determined?
>> $$\frac{\Delta R}{R} = \frac{(P + \Delta P) * (Q + \Delta Q) - P * Q}{P * Q}$$
>> $$= \frac{\Delta P * Q + \Delta Q * P + \Delta Q * \Delta P + P * Q  - P * Q}{P * Q}$$
>> As $\Delta Q * \Delta P$ is differential factor, we can consider it as 0.  
>> Thus,  
>> $$\frac{\Delta R}{R}= \frac{\Delta P}{P} + \frac{\Delta Q}{Q}$$
>> or,   
>> the change of revenue is determined by both the change of price and quantity.

>> 3. Why is the function for TR prarabolic?  
>> From demand curve:   
>> $$R = Q * P(Q) = Q * (a + b*Q) = bQ^2 + aQ$$
>> Must be a prarabolic with the center at $$Q = -\frac{a}{2b}$$ which is the unit elastic point.

> (4) Perfect elastic and perfect inelastic
>> Perfect elastic  
>> <img src = 'https://www.writework.com/uploads/0/9700/perfectly-elastic-demand.png' width = 200 >  
>> Elasticity is infinite  
>> Perfect inelastic  
>> <img src = 'https://fthmb.tqn.com/-0l1usnAdhxRmYmR5Z5M6RG3A8Y=/1517x1128/filters:fill(auto,1)/Perfectly-Inelastic-5845801c5f9b5851e546a619.jpg' width = 200>  
>> Elasticity is zero

3. Income elasticity of demand > 0
> (1) Definition: the responsiveness of quantity demanded to a change in income.

> (2) Formula
>> $$E^d_I = \frac{\%\Delta Q^d_x}{\%\Delta I} = \frac{\Delta Q^d_x/Q^d_x}{\Delta I/I} = \frac{\Delta Q^d_x}{\Delta I}*\frac{I}{Q^d_x}$$

> (3) Interpretation
>> * **The income elasticity:** the tangent between quantity and income.
>> Normal luxuries goods: high positive
>> Normal necessities: low positive
>> Inferior goods: negative (because you have normal goods as substitute)

4. Cross-price Elasticity of demand
> (1) Definition
>> The responsiveness of the quantity demanded to a change in the price of substitutes or complements.

> (2) Formula
>> $$E^d_{Py} = \frac{\%\Delta Q^d_x}{\%\Delta P_y} = \frac{\frac{\Delta Q^d_x}{Q^d_x}}{\frac{\Delta P_y}{P_y}} = \frac{\Delta Q^d_x}{\Delta P_y} * \frac{P_y}{Q^d_x}$$  

> (3) Interpretation
>> * Substitutes: positive
>> * Complements: negative
>> * The cross-price can be 0 when X and Y has no relation.


5. Substitution effect and income effect 
> (1) Definition
>> 1. **Substitution effect:** the **relative price** of the good against substitute decreases, then the quantity demanded for the good increases
>> 2. **Income effect:** the **real purchasing power** increase when the price of good decreases, which leads to the change in demand of the good

If Price Down (-)| Substitution Effect (Quantity) | Income Effect (Quantity)| Total Effect (Quatity) | Demand Curve  
:---:|:---:|:---:|:---:|:---:  
Normal Goods|+|+|+|Downward
Inferior Not Giffen|++|-|+|Downward
Inferior Giffen|+|--|-|Upward
Veblen Goods|+|--|-|Upward

>> Giffen goods: 1845 Scottish potato and pork
>> Veblen goods: conspicuous consumption (Ferrari)

### E. Supply analysis
1. Basic concepts  
> (1) Production **non-liner** function (Capital, labor, land and material)  
>> Formula Q = f(K, L) for capital and labor. In Short term, capital is assumed to be fixed, Q = f(L).

> (2) Product
>> * Total product
>> * Average product: TP/ Qty of input
>> * Marginal product: additional product using one more unit of input $\frac{\Delta Q}{\Delta L}$
>> * Per capita: per individual

> (3) Law of diminishing returns
>> * Definition: As more and more resources such as labor are devoted to the production process, the total product increases at a decreasing rate. 
<img src = 'https://forestrypedia.com/wp-content/uploads/2018/05/DiminishingReturns1.jpg'>

>> * How to draw TP, MP, AP? 
>> <img src = 'https://www.myassignmentservices.com.au/wp-content/uploads/2018/08/marginal-product.jpg'>
>> Using derivatives and second derivatives  
>> **Do a derivation yourself!**

> (4) Profits
>> * Explicit cost: accounting costs that are paid to non-owner  
>> * Implicit cost: opportunity costs that are promised for the owner to have, the cost is when you take a project, the highest opprtunity cost (highest potential return) of all other projects.  
>> * Total Econ cost = explicit cost + implicit cost (explicit cost & implicit cost are both opportunity costs)
>> * Accounting profit = total revenue - accounting cost 
>> * $$Economic\ profit$$  
>> $$= total\ revenue - economic\ cost$$  
>> $$= total\ revenue - accounting\ cost - implicit\ cost$$  
>> $$= accounting\ profit - implicit\ cost$$  
>> <img src = 'https://image.slidesharecdn.com/costsproduction-150722183205-lva1-app6892/95/the-costs-of-production-11-638.jpg?cb=1437590044'>
>> * **Normal Profit**: is the accounting profit that makes economic profit zero (in a complete competitive market)  

>> $$Normal\ Profit = Implicit\ Profit$$
>> Normal profit is making profit but not making an extra profit so it has economic profit. It only covers the implicit costs.

> (5) Revenue
>> * Revenue = Price * Quantity
>> * $$Marginal\ revenue\ product $$ 
>> $$= MP * MR$$
>> $$= \frac{\Delta Q}{\Delta L} * \frac{\Delta TR}{\Delta Q}$$
>> $$= \frac{\Delta TR}{\Delta L}$$

Term | Definition | Formula
:---:|:---:|:---:|
Total Revenue | Sum products of price and quantity | TR = P * Q
Average Revenue | TR / Q | AR = TR / Q = P
Marginal Revenue | Change in TR against change in Q | $MR = \frac{\Delta TR}{\Delta Q}$ 
>>  The relationship between MR and price elasticity: 
$$MR = P[1 + \frac{1}{E_p}] = P[1 - \frac{1}{|\epsilon|}]$$

> (6) Cost

2. Perfect Competition and imperfect competition
3. Profit maximization
4. Shutdown and breakeven point
5. Economies of scale