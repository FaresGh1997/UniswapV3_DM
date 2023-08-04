# Data Mining of Uniswap Decentralized Exchange platform

This repo is code part of the paper "Data Mining of Uniswap Decentralized Exchange" published in ICBTA 2022 conference | Dec 16, 2022 [link to the paper](https://camps.aptaracorp.com/ACM_PMS/PMS/ACM/ICBTA2022/4/bb7bada9-9e86-11ed-a76e-16bb50361d1f/OUT/icbta2022-4.html).

##### The Task:

collect, store and analyze [UniSwap](https://uniswap.org/) Transactional data.

##### The Solution Process:

- Data Gathering: using The Graph hosting serves API and Sql to extract relevant data for the research.
- Data Storage: using Microsoft SQL-server to store the data acquired in a relational database.
- Data Analysis: perform multiple statistical data analysis on the database using python and seaborn. 

##### The Findings:

- Analysis shows declining in price of WBTC and WETH throughout 2022. WBTC decline follows rising interest rates in the US on 21 of September 2022 and the high inflations in general, which causes the lower demand on WBTC and thus dropping in price. WETH suffered drop in price for the same reasons and because of The Merge of Ethereum and Ethereum 2.0.
- Analysis shows USDC/WETH fee Tier 0.3% pool having the highest trading volume in 2021 on UniSwap. While DAI/USDC fee tier 0.01% is the pool with the highest TVL.
- [Liquidity Distribution](https://github.com/FaresGh1997/UniswapV3_DM/blob/main/Source%20Code/LD.ipynb) was calculated to see the effect of UniSwap centralized liquidity principal.
- Most of the liquidity in the USDC/WETH fee tier 0.3% pool is focused around the 2021 price of USDC per WETH which was 0.0007, remaining of the liquidity is distributed to the right of the 2021 price more, which means that LP were expecting the drop in the price of WETH.
- Most of the liquidity in the WBTC/WETH fee tier 0.3% pool is focused around the price of 17.19 WETH for 1 WBTC or the 2021 price which was 19.74 WETH for 1 WBTC. No huge amount of liquidity distributed elsewhere. This can be explained because both tokens are normally not stable, making them venerable to the price fluctuation.
- predicted decline in the value of the WBTC and WETH at the same time.
- Analysis of the total amount of mints, burns and Swaps did not reveal interesting discoveries.

  
Skills developed: pandas | SQL | BigQuery | Graphql | networkx | APIs | Data Processing | EDA | Statistical Analysis | Data Visualization | DeFi protocols.

