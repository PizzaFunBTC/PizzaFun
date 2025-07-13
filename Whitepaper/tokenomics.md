---
hidden: true
---

# Tokenomics

## $PIZZA Token Basic Information

* Token Name: PIZZA
* Total Supply: 210,000,000 $PIZZA (Fixed Supply)
* Decimals: 18
* Deflationary Mechanism: Cross-protocol operations system auto-burn

The $PIZZA token is the core utility token of the PizzaFun ecosystem, designed to empower the platform's decentralized Bitcoin token trading functionality. The total supply is set at 210 million tokens, paying tribute to Bitcoin's 21 million maximum supply but expanded 10-fold to support broader distribution and use cases.

## Economic Model Overview

PizzaFun's tokenomics model aims to create a self-sustaining ecosystem where $PIZZA token circulation generates network effects while maintaining long-term value through multiple mechanisms. The model is based on three core pillars:

1. **Utility Value**: $PIZZA serves as an access credential for platform features, used for fee discounts, liquidity mining, advanced feature unlocks, etc.
2. **Governance Rights**: Token holders participate in platform decision-making, influencing system parameters, feature upgrades, and fund allocation
3. **Value Capture**: Through transaction fee sharing, staking rewards, and deflationary mechanisms, platform success is translated into token value

This multi-dimensional value model ensures the token economy maintains resilience and sustainability across different market environments.

## Token Distribution

The $PIZZA token distribution has been carefully designed to balance initial liquidity needs, long-term development resources, community incentives, and decentralized governance requirements.

| Distribution Category  | Amount            | Percentage | Initial Unlock             | Vesting Period                             | Primary Purpose                                            |
| ---------------------- | ----------------- | ---------- | -------------------------- | ------------------------------------------ | ---------------------------------------------------------- |
| Trading Mining         | 31,500,000 $PIZZA | 15%        | Released by trading volume | Ongoing                                    | Incentivize platform trading activity                      |
| Private Rounds         | 21,000,000 $PIZZA | 10%        | None                       | 6-month lock + 18-month linear release     | Early development funding                                  |
| Founding Team          | 29,400,000 $PIZZA | 14%        | None                       | 12-month lock + 36-month linear release    | Team incentives, expert compensation                       |
| Ecosystem Development  | 63,000,000 $PIZZA | 30%        | None                       | 10% permanent lock + 8-year linear release | Developer grants, cross-chain tools, marketing             |
| Liquidity Pool         | 21,000,000 $PIZZA | 10%        | Phased release             | Milestone-based                            | Protocol-owned liquidity                                   |
| Community Airdrop      | 10,500,000 $PIZZA | 5%         | 100% at TGE                | Immediate                                  | Initial community building, user acquisition               |
| Baking Mining          | 12,600,000 $PIZZA | 6%         | None                       | Activity-based release                     | Baking phase liquidity incentives                          |
| Strategic Partnerships | 10,500,000 $PIZZA | 5%         | None                       | 3-year linear release                      | Key partners, exchange listings                            |
| DAO Treasury           | 10,500,000 $PIZZA | 5%         | None                       | DAO managed                                | Security reserves, market operations, community incentives |

## Deflationary Mechanisms

PizzaFun implements multi-layered token deflationary mechanisms designed to gradually reduce $PIZZA circulating supply as platform usage increases:

1. **Transaction Fee Burn**: 20% of the base fee from each platform transaction is directly burned. Based on transaction volume prediction models, this will burn approximately 5% of total supply within 5 years.
2. **Token Buyback**: 15% of platform revenue will be used for open market $PIZZA token buybacks, with community voting guidance on whether to burn or add to DAO treasury.
3. **Feature Activation Burn**: Certain advanced features (such as creating professional trading bots, accessing premium market data, or setting custom trading rules) require burning small amounts of $PIZZA for activation.
4. **Name Registration Burn**: Registering unique trader names or token symbols on the platform requires burning $PIZZA, with amounts depending on name length and rarity.

The deflationary algorithm follows this mathematical pattern:

$$B_t = B_{t-1} + \alpha \cdot TV_t - \beta \cdot TV_t$$

Where:

* $B\_t$ is cumulative burn amount at time t
* $TV\_t$ is trading volume at time t
* $\alpha$ is transaction fee burn rate (0.2 × transaction fee rate)
* $\beta$ is buyback burn rate

Long-term deflationary models predict that upon reaching platform maturity, circulating supply will show approximately 2-3% annual negative growth rate.

## Utility and Value Capture

The $PIZZA token has multiple utilities within the PizzaFun ecosystem, ensuring sustained demand and translating platform success into token value:

### Trading Advantages

*   **Fee Discounts**: Holding and staking $PIZZA provides up to 50% trading fee discounts, with discount rates calculated according to staking amount using the following formula:

    $$D(s) = D_{max} \cdot (1 - e^{-\lambda \cdot s})$$

    Where $s$ is the amount of staked $PIZZA, $D\_{max}$ is maximum discount rate (50%), $\lambda$ is scaling parameter
* **Priority Trading**: During peak periods, users staking $PIZZA receive trading priority, reducing latency
* **Slippage Protection**: Staking sufficient $PIZZA activates slippage protection features, limiting trade execution price deviation

### Mining and Liquidity Incentives

*   **Trading Mining**: Users receive $PIZZA rewards for each completed trade, with reward formula:

    $$R_i = \frac{V_i}{\sum_{j=1}^n V_j} \cdot R_{total}$$

    Where $V\_i$ is user i's trading volume, $R\_{total}$ is total reward amount for the period
* **Liquidity Mining**: Users providing liquidity in the serving phase receive additional $PIZZA rewards proportional to their liquidity provision ratio
* **Referral Mining**: Users referring new users receive $PIZZA rewards based on referred users' trading volume, building sustainable user acquisition mechanisms

### Advanced Feature Unlocks

* **Professional Trading Tools**: Staking $PIZZA unlocks advanced trading analysis tools, automated trading strategies, and risk management features
* **API Access**: Staking sufficient $PIZZA provides higher-level API access permissions, suitable for professional traders and institutions
* **Token Issuance Rights**: Creating new Bitcoin tokens requires staking $PIZZA, with staking amount proportional to initial liquidity

## Governance Rights

$PIZZA holders can participate in platform governance, influencing PizzaFun's development direction. Governance weight is proportional to token staking duration and amount, calculated using a quadratic voting formula:

$$VotingPower = \sqrt{s \cdot t}$$

Where $s$ is the amount of staked tokens, $t$ is staking duration (in months, calculated up to maximum 36 months).

Governance permissions are divided into four levels based on holding and staking amounts:

1. **Basic Participants** (≥1,000 $PIZZA): Can vote on proposals
2. **Active Contributors** (≥10,000 $PIZZA): Can submit improvement suggestions and participate in discussions
3. **Core Governors** (≥100,000 $PIZZA): Can formally submit governance proposals and receive proposal funding
4. **Strategic Decision Makers** (≥1,000,000 $PIZZA): Can participate in emergency decision committees and long-term strategic planning

All holders, regardless of token amount, can participate in community discussions and non-binding votes, ensuring inclusivity and broad participation.

## Circulation and Unlock Schedule

$PIZZA token unlocking follows a carefully designed timeline that balances short-term liquidity needs with long-term price stability:

### First Year Unlock

* TGE (Token Generation Event): 5% of total supply (mainly from community airdrop)
* Months 1-3: Additional 1% monthly, cumulative 8% released
* Months 4-6: Additional 1.5% monthly, cumulative 12.5% released
* Months 7-12: Additional 2% monthly, cumulative 24.5% released

### Long-term Unlock Plan

* Year 2: Release 25%, cumulative 49.5%
* Year 3: Release 20%, cumulative 69.5%
* Year 4: Release 15%, cumulative 84.5%
* Years 5-8: Release remaining 15.5%

The long-term unlock plan ensures $PIZZA token supply growth remains balanced with platform adoption growth, avoiding early over-dilution or supply shocks.

## Sustainable Incentive Loop

PizzaFun's tokenomics design creates a self-reinforcing positive loop:

1. User trading → generates fees → portion used for buyback and burn → reduces supply → enhances token value
2. Token value increase → attracts more users and liquidity providers → increases platform activity and utility
3. Increased platform activity → ecosystem expansion → more token use cases → enhanced demand

This loop design ensures PizzaFun's growth directly translates into value for token holders while maintaining long-term tokenomic sustainability. The token model is specifically designed to demonstrate resilience across different market cycles, ensuring project long-term success and alignment of user interests.
