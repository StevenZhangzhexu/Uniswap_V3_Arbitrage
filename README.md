# Uniswap_V3_Arbitrage

Discover Triangular Arbitrage opportunities in the Cryptocurrency market.

## Limitation & Next Step
Gas fee is not considered in Uniswap V3 Quoter.
"These functions are not gas efficient and should not be called on chain. Instead, optimistically execute the swap and check the amounts in the callback." (https://docs.uniswap.org/contracts/v3/reference/periphery/lens/Quoter)

Arbitrage opportunities would disappear within seconds. Hereby smart contract and trading automatioin is necessary.

for example, the program showed this oppotunity.
<img width="1003" alt="arb_try" src="https://github.com/StevenZhangzhexu/Uniswap_V3_Arbitrage/assets/68343996/548c897a-e3bf-44be-b896-ffc986b68ef0">
However due to other cost (gas fee, web fee, slippage lost etc..), this trade does not make money.<img width="551" alt="Screenshot 2023-08-14 at 12 17 30 PM" src="https://github.com/StevenZhangzhexu/Uniswap_V3_Arbitrage/assets/68343996/47a947a9-a973-4f77-ae9e-fc112e8b0ff3">
<img width="600" alt="Screenshot 2023-08-14 at 12 06 13 PM" src="https://github.com/StevenZhangzhexu/Uniswap_V3_Arbitrage/assets/68343996/c2a6a254-b807-4276-a7a4-e6835d3fdf9e">
<img width="574" alt="Screenshot 2023-08-14 at 12 16 46 PM" src="https://github.com/StevenZhangzhexu/Uniswap_V3_Arbitrage/assets/68343996/bf0fc81f-0bcd-480b-bae3-ee77b82713ad">
