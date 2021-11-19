![waves23](https://user-images.githubusercontent.com/78451795/142639920-b54ab12d-dbd1-4d76-9a81-0006b50c81b0.png)



Note: When fund performance is measured in absolute gain, this also incentivizes fund managers to spread the word about their fund and increase the liquidity of the fund.

<br/>
Note: There is some complexity to consider in the fact that funds can increase or decrease in value based upon how much is invested in the fund, which can make it more difficult to know the fund performance measured by absolute gain for each fund. This could potentially make it possible to game the system by adding funds before the end of the week and then withdrawing funds at the beginning of the week. 

Here are some ways that come to mind about how we can solve this:
<br/>
<br/>

1. Fees could be set high enough that this strategy wouldn’t make sense. For example, if there is a 1% fee to withdraw from the fund then that may be sufficient to discourage this kind of gaming behavior. This can also be a revenue generator for CETF.
<br/>

2. The whitelisting process could play a role in selecting managers who will play the game with ‘good intentions’, but if it’s not well-defined then it could get kind of messy, opinionated, and create drama.
<br/>

3. We can measure fund performance on an equal amount of play money for each fund, similar to how the Bullish trading competition started each participant with $500k of play money. Each trade could be accounted for according to the percentage allocation of each fund. This could work well but adds more complexity and abstraction. I’m not sure if this would be simple to explain or how this would account for slippage on exchanges like defibox etc. It also could make it more difficult to keep track of all the data. 

<br/>
<br/>

4. There could be residual disincentives for losing funding. This could be helpful to reduce gaming behavior but might be messy. 
<br/>
<br/>

5. This can work itself out fairly naturally because if someone reduced their funding at the beginning of one week to try to game the system for the previous week then that would likely preclude them from good fund performance in the next week. 

<br/>

<br/>


6. There could be a multiplier for money that is added or removed from the fund. For example, we could account for changes in liquidity with a 0.2x multiplier. This could be relatively simple to account for by importing the CVC file for each fund from bloks.io and calculating the total amount of liquidity added or removed in that week for each fund in the excel spreadsheet. Then there could be a simple multiplier like 0.2x that is applied to all additions/reductions of liquidity. 

  This would provide some incentives for managers to increase the liquidity in the funds, while also reducing the incentive to game the system by adding or reducing liquidity. If we measure fund performance by percentage gains rather than absolute gains and we include this kind of multiplier to reduce the effect of adding or reducing the liquidity, then the majority of CETF rewards would go to fund performance that is agnostic to the amount of liquidity in each fund. 

  There might be more edge cases to consider but overall I think this could be a simple solution to make the system less gameable and more inclusive so everyone can participate on a more even playing field regardless of capital, while still providing incentives for fund managers to attract more capital to their funds.

<br/>
<br/>
<br/>

Overall this is the part of the system that I’m the least sure about right now, but I think that we can probably make it work very well with a simple solution including solutions #1, #5, and #6. Either way I think it’s worth exploring more. 
<br/>
Thoughts?

<br/>

![waves1](https://user-images.githubusercontent.com/78451795/142640168-8e74a1f5-fa53-441d-94dd-076d934582f1.png)
