# READING 35. EXECUTION OF PORTFOLIO DECISIONS

The candidate should be able to:

## a compare market orders with limit orders, including the price and execution uncertainty of each;

## b calculate and interpret the effective spread of a market order and contrast it to the quoted bid–ask spread as a measure of trading cost;

## c compare alternative market structures and their relative advantages;
- Quote-driven: dealer markets dealer=market maker
   - Many markets that trade illiquid securities (e.g., bond markets) are organized as dealer markets 
   - Dealers also provide liquidity for securities whose terms are negotiated
   - the dealer that offers the best price is not always the one to get a trader’s business because of credit risk

- Order-driven
   - electronic crossing networks
     - the typical trader is an institution. 
     - Orders are batched together and crossed (matched) at fixed points in time during the day at the average of the bid and ask quotes.
     - The costs of trading are low because commissions are low and traders do not pay a dealer’s bid-ask spread. 
     - A trade may not be filled or may be only partially filled if there is insufficient trading activity.
     - The trader usually does not know the identity of the counterparty or the counterparty’s trade size in an electronic crossing network. 
     - no price discovery
- auction
     - periodic/batch, or continous auction
     - price discovery
- automated auctions (electronic limit-order markets)
     - identity not known
     - price discovery 
- Brokered market
    - A broker can place the order without revealing his client’s identity. 
    - He can discreetly shop the stock and find the necessary liquidity.
    - He may even take a position in the stock with his own capital.
    - important in countries where public capital markets are not well developed
- hybrid market

## d explain the criteria of market quality and evaluate the quality of a market when given a description of its characteristics;
 - liquidity
   - If a market has small spreads, traders are apt to trade more often. 
   - Market depth allows larger orders to trade without affecting security prices much.
   - A market is resilient if asset prices stay close to their intrinsic values, and any deviations from intrinsic value are minimized quickly
   
   - An abundance of buyers and sellers, so traders know they can quickly reverse their trade if necessary.
   - Investor characteristics are diverse. If every investor had the same information, valuations, and liquidity needs, there would be little trading.
   - A convenient location or trading platform which lends itself to increased investor activity and liquidity.
   - Integrity as reflected in its participants and regulation, so that all investors receive fair treatment.
 - transparency
   -  investors can, without significant expense or delay, obtain both pre-trade information (regarding quotes and spreads) and post-trade information(regarding completed trades)
 - assurity of completion
   - nvestors can be confident that the counterparty will uphold its side of the trade agreement.
 
 evaluate the quality of a market
 - transparency and assurity of completion require a qualitative assessment
 - liquidity can be measured by the quoted spread, effective spread, and ask and bid sizes. 
 
## e explain the components of execution costs, including explicit and implicit costs, and evaluate a trade in terms of these costs;

The explicit costs of trade execution are directly observable and include 
- commissions,
- taxes, 
- stamp duties, 
- fees. 
Implicit costs are harder to measure, but they are real. They include 
- the bid-ask spread,
- market or price impact costs,
- opportunity costs, and
- delay costs (i.e., slippage costs).
 They must be inferred by measuring the results of the trade versus a reference point.
 
 Volume weighted average price shortcomings:
  1. not useful if trader is significant part of the volume
  2. "game" the comparison. wait until later to decide which trade to execute
  3. not consider missed trades
  

## f calculate and discuss implementation shortfall as a measure of transaction costs;

Implementation shortfall is the difference between the actual portfolio’s return and a paper portfolio’s return.
For a purchase:
- An increase in price is a cost.
- A decrease in price is an account benefit (a negative cost).

For a sale:
- An increase in price is an account benefit (a negative cost).
- A decrease in price is a cost.

Total IS can be computed as the difference in the value of the hypothetical portfolio if the trade was fully executed at the DP (with no costs) and the value of the actual portfolio.

- Missed trade (also called opportunity, or unrealized profit/loss) is the difference in the initial DP and CP applied to the number of shares in the order not filled. It can generally be calculated as:

|CP − DP| × # of shares canceled

- Explicit costs (sometimes just referred to as commissions or fees) can be computed as:

cost per share × # of shares executed

- Delay (also called slippage) is the difference in the initial DP and revised benchmark price (BP*) if the order is not filled in a timely manner applied to the number of shares in the order subsequently filled. It can generally be calculated as:

|BP* − DP| × # of shares later executed

- Market impact (also called price impact or realized profit/loss) is the difference in EP (or EPs if there are multiple partial executions) and the initial DP (or BP* if there is delay) and the number of shares filled at the EP. It can generally be calculated as:

|EP − DP or BP*| × # of shares executed

====================Calculate===============================

EXAMPLE: Of implementation shortfall and decomposition
- On Wednesday, the stock price for Megabites closes at $20 a share.
- On Thursday morning before market open, the portfolio manager decides to buy Megabites and submits a limit order for 1,000 shares at $19.95. The price never falls to $19.95 during the day, so the order expires unfilled. The stock closes at $20.05.
- On Friday, the order is revised to a limit of $20.06. The order is partially filled that day as 800 shares are bought at $20.06. The commission is $18. The stock closes at $20.09 and the order for the remaining 200 shares is canceled.

Answer:
The DP is $20.00. There was a delay, in this case due to the use of a limit order to buy below the market price.

The BP* is $20.05. The increase of $0.05 is a cost in a buy order. The order is partially filled at an EP of $20.06 and there is missed trade cost. 200 shares were not filled and the CP is 20.09. Commissions were $18.00.
 
The gain or loss on the paper portfolio versus the actual portfolio gain or loss is the total implementation shortfall. 

The paper portfolio would have purchased all the shares at the decision price with no costs.

The investment made by the paper portfolio is 1,000 × $20.00 = $20,000.

The terminal value of the paper portfolio is 1,000 × $20.09 = $20,090. This is based on the price when the trade is completed, which in this case is when it is canceled.

The gain on the paper portfolio is $20,090 − $20,000 = $90.

The gain or loss on the real portfolio is the actual ending value of the portfolio versus the actual expenditures, including costs.

The investment made by the real portfolio is (800 × $20.06) + $18 = $16,066.

The terminal value of the real portfolio is 800 × $20.09 = $16,072.

The gain on the real portfolio is $16,072 − $16,066 = $6.

Total implementation shortfall is the difference in results of the hypothetical and actual portfolio of $84.00.

The smaller actual gain is a cost.

On a per share basis, this is allocated to the full order of 1,000 shares:

$84 / 1,000 = $0.084 per share

As percentage and bp, this is allocated to the hypothetical portfolio cost of $20,000 (= 1,000 × $20.00):

$84 / $20,000 = 0.42% = 42 bp

The IS components are:

- Missed trade is the CP versus DP on 200 shares. The price increased, which is a cost on a purchase:

|$20.09 − 20.00| × 200 = $18.00

$18 / 1,000 = $0.018 per share

$18 / $20,000 = 0.09% = 9 bp


- Explicit costs are $18 and are a cost:

$18 / 1,000 = $0.018 per share

$18 / $20,000 = 0.09% = 9 bp

- Delay is BP* versus DP on 800 shares. The price increased, which is a cost on a purchase:

|$20.05 − 20.00| × 800 = $40.00

$40 / 1,000 = $0.04 per share

$40 / $20,000 = 0.20% = 20 bp

- Price impact is EP versus DP or in this case versus BP* because there was a delay on 800 shares. The price increased, which is a cost on a purchase:

|$20.06 − 20.05| × 800 = $8.00

$8 / 1,000 = $0.008 per share

$8 / $20,000 = 0.04% = 4 bp


- Verification of total versus components:
$84 = $18 + 18 + 40 + 8

$0.084 = $0.018 + 0.018 + 0.040 + 0.008

0.42% = 0.09% + 0.09 + 0.20 + 0.04

42bp = 9bp + 9 + 20 + 4


===================================================

Market adjusted IS = IS - β * E(Rm)
<0: Negative trading cost: => Benefit: Negative cost means a benefit to the portfolio. The purchase was executed above the original benchmark price (DP) but, when the general increase in market prices is considered, the execution was more favorable than expected


====================IS % ===============================

Use the following information to calculate the implementation shortfall and its components as a percentage.
- On Wednesday, the stock price closes at $50 a share.
- On Thursday morning before market open, the portfolio manager decides to buy Megawidgets and transfers a limit order for 1,000 shares at $49.95. The order expires unfilled. The stock closes at $50.05.
- On Friday, the order is revised to a limit of $50.07. The order is partially filled that day as 700 shares are bought at $50.07. The commission is $23. The stock closes at $50.09 and the order is canceled.

Answer:
First, organize the information.
- The trade decision was made while the market was closed, making DP the previous close of 50.00.
- There was a one-day delay in execution making BP* 50.05. 
- There was an unexecuted trade portion and a CP of 50.09. EP was 50.07.
- Total explicit costs are given as $23. 
- (Note that a limit price is not a direct part of IS calculations, though it may affect EP and create delays.)

- Explicit cost—the commission as a percentage of the paper portfolio investment is $23 / $50,000 = 0.05%.
- Realized profit and loss is EP – DP (or BP*). This is divided by the DP and weighted by proportion of the order filled. It is (700 / 1,000) × ($50.07 – $50.05) / $50.00 = 0.03%.
- Delay cost is BP\* – DP and then divided by the DP. It is weighted by the portion of the order filled. It is (700 / 1,000) × ($50.05 – $50.00) / $50.00 =0.07%.

===================================================

## g contrast volume weighted average price (VWAP) and implementation shortfall as measures of transaction costs;
Advantages of VWAP:
- Easily understood.
- Computationally simple.
- Can be applied quickly to enhance trading decisions.
- Most appropriate for comparing small trades in nontrending markets (where a market adjustment is not needed).

Disadvantages of VWAP:
- Not informative for trades that dominate trading volume (as described earlier).
- Can be gamed by traders (as described earlier).
- Does not evaluate delayed or unfilled orders.
- Does not account for market movements or trade volume.

Advantages of Implementation Shortfall:
- Portfolio managers can see the cost of implementing their ideas.
- Demonstrates the tradeoff between quick execution and market impact.
- Decomposes and identifies costs.
- Can be used in an optimizer to minimize trading costs and maximize performance.
- Not subject to gaming.

Disadvantages of Implementation Shortfall:
- May be unfamiliar to traders.
- Requires considerable data and analysis


## h explain the use of econometric methods in pretrade analysis to estimate implicit transaction costs;

Econometric models can be used to forecast transaction costs. Using market microstructure theory, it has been shown that trading costs are nonlinearly related to:
- Security liquidity: trading volume, market cap, spread, price.
- Size of the trade relative to liquidity.
- Trading style: more aggressive trading results in higher costs.
- Momentum: trades that require liquidity [e.g., buying (selling) when the market is trending upward (downward)].
- Risk.

The analyst uses these variables and a regression equation to forecast the estimated cost of a trade.
The usefulness of econometric models is twofold. 
- First, trading effectiveness can be assessed by comparing actual trading costs to forecasted trading costs from the model.
- Second, it can assist portfolio managers in determining the size of the trade.

## i discuss the major types of traders, based on their motivation to trade, time versus price preferences, and preferred order types;
- Information-motivated traders trade based on time-sensitive information; thus, they prefer market orders because their trades must take place quickly. Their trades demand liquidity, and they are willing to bear higher trading costs.
- Value-motivated traders use investment research to uncover misvalued securities. They will use limit orders because price, not speed, is their main objective.
- Liquidity-motivated traders transact to convert their securities to cash or reallocate their portfolio from cash. They utilize market orders and trades on crossing networks and electronic communication networks (ECNs). Liquidity-motivated traders prefer to execute their order within a day.
- Passive traders trade for index funds and other passive investors. They favor limit orders and trades on crossing networks. This allows for low commissions, low market impact, price certainty, and possible elimination of the bid-ask spread

## j describe the suitable uses of major trading tactics, evaluate their relative costs, advantages, and weaknesses, and recommend a trading tactic when given a description of the investor’s motivation to trade, the size of the trade, and key market characteristics;

- In a liquidity-at-any-cost trading focus, the trader must transact a large block of shares quickly. The typical trader in this case is an information trader but can also be a mutual fund that must liquidate its shares quickly to satisfy redemptions in its fund. This trader must be ready to pay a high price for trading in the form of market impact, commissions, or both.

- In a costs-are-not-important trading focus, the trader believes that exchange markets will operate fairly and efficiently such that the execution price they transact at is at best execution. The trader thus uses market orders.

- In a need-trustworthy-agent trading focus, the trader employs a broker to skillfully execute a large trade in a security, which may be thinly traded. The weakness of this strategy is that commissions may be high and the trader may reveal his trade intentions to the broker.

- In an advertise-to-draw-liquidity trading focus, the trade is publicized in advance to draw counterparties to the trade. The weakness of this strategy is that another trader may front run the trade, buying in advance of a buy order.

- In a low-cost-whatever-the-liquidity trading focus, the trader places a limit order outside of the current bid-ask quotes in order to minimize trading costs. Passive and value motivated traders will often pursue this strategy

## k explain the motivation for algorithmic trading and discuss the basic classes of algorithmic trading strategies;

Algorithmic trading is the use of automated, quantitative systems that utilize trading rules, benchmarks, and constraints to execute orders with minimal risk and costs.

Algorithmic trading strategies are classified into logical participation strategies (simple logical and implementation shortfall strategies), opportunistic strategies, and specialized strategies.

- Simple logical participation strategies seek to trade with market flow so as to not become overly noticeable to the market and to minimize market impact.
  - Volume-weighted average price strategy involves breaking up an order over time according to a pre-specified volume profiles;
  - Time-weighted average price strategy is a particularly simple variant that assumes a flat volume profile and trades in proportion to time;
  - Percentage-of-volume strategy takes place in proportion to overall market volume until the order is completed.

- Implementation shortfall strategies, or arrival price strategies, minimize trading costs as defined by the implementation shortfall measure or total execution costs.

- Opportunistic participation strategies trade passively over time but increase trading when liquidity is present.

- Specialized strategies include passive strategies and other miscellaneous strategies

    - hunter strategies, where the size of the order or portion seeking execution is adjusted to take advantage of changing market liquidity;
    - market-on-close, which targets the closing price as execution price; and 
    - smart routing, which monitors multiple markets and routes the order to the most liquid market

## l discuss the factors that typically determine the selection of a specific algorithmic trading strategy, including order size, average daily trading volume, bid–ask spread, and the urgency of the order;

The choice of strategy will be primarily driven by three factors:
- Size of the order as a percentage of average daily trading volume.
- Bid-asked spread.
- Urgency of the trade.

Examples:

- The trade for stock ABCD is also relatively small, and in both cases the spreads are fairly low.
- The ABCD trade is of low urgency and can be traded over time. 
- It is thus suitable for a simple participation strategy based on VWAP or another benchmark.

- The WXYZ trade is of high urgency,
- however, and should be traded more quickly using an implementation shortfall strategy.

- The LMNO trade is of relatively large size and has a large spread. 
- Because of these characteristics, it should be traded through a skilled broker or through a crossing system to minimize the spread.


Consider the order size as a percentage of daily trading volume, size of spread, and urgency of the trade:
- Algorithmic strategies when all three are low (e.g., VWAP strategy).
- Implementation shortfall for low size and spread but with high urgency.
- A broker or crossing network when size and spread are high but urgency is low.

Questions:

Q: A market observer notices that a particular trading firm tends to execute its trades early in the day, with volume falling off later in the day. What type of algorithmic trading system is the firm likely using?

A: The firm is likely using an implementation shortfall strategy. These strategies trade heavier early in the day to ensure order completion, reduce opportunity costs, and minimize the volatility of trading costs. 

Q: What is the primary indication that a trader should not use algorithmic trading and instead use a broker or a crossing network?

A: When a trade is of relatively large size and has a large spread, it should be traded through a broker or a crossing system in order to minimize the spread. 

## m explain the meaning and criteria of best execution;

The Institute compares best execution to prudence. Prudence refers to selecting the securities most appropriate for an investor, whereas best execution refers to the best means to buy or sell those securities. They are similar in that they both attempt to improve portfolio performance and meet fiduciary responsibilities.

Four characteristics of best execution:

1. It depends on the value added of the trade versus cost.
2. Best execution and value added cannot be known ex ante.
3. Best execution and cost can only be calculated ex post. Assessing value added may take even longer to evaluate if the idea works out.
4. Relationships and practices are integral to best execution. Best execution is ongoing and requires diligence and dedication to the process

## n evaluate a firm’s investment and trading procedures, including processes, disclosures, and record keeping, with respect to best execution;

[Trade Management Guidelines](https://cfainstitute.org/ethics/codes) are split into three parts:
1. Processes: Firms should have policies/procedures that have the intent of maximizing portfolio value using best execution. These should help firms determine and manage best execution.

2. Disclosures: Investment management firms should provide disclosure to their clients and potential clients regarding 
   - (1) general information on their trading techniques, markets, and brokers and 
   - (2) their conflicts of interest related to trading. This information should be provided periodically to clients.

3. Record Keeping: Investment management firms should maintain the documentation supporting 
   - (1) the firm’s compliance and 
   - (2) disclosures made to its clients. In doing so, the firm also provides evidence to regulators as to how the firm pursues best execution for its clients.

## o discuss the role of ethics in trading.

Trading is based on word of honor. Buy-side and sell-side traders must honor their verbal agreements or they will quickly find that no one wants to take the opposite side of their trade. 

The development of 
- complex trading techniques and
- the decline in explicit commissions 

have increased the opportunity and temptation to act unethically.

Regardless of these developments, buy-side traders should always act in the best interests of their clients. Buy-side traders and portfolio managers have a fiduciary duty to maximize the value of their client’s portfolio. The buy-side trader’s relationships with sell-side traders must never come before the interests of the trader’s clients
