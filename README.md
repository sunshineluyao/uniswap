# Uniswap Transaction Analysis Repository


Welcome to the Uniswap Transaction Analysis Repository! This repository provides data and code for replicability, allowing you to analyze transactions on Uniswap, a decentralized exchange protocol built on Ethereum. Gain insights into Uniswap's transaction history and its impact on the decentralized finance (DeFi) ecosystem.

## Table of Contents
- [Introduction](#Introduction)
- [Illustrations](#Illustrations)
- [Key Concepts](#Key-concepts)
- [Measures](#Measures)
- [Repository Structure](#Repository-structure)


## Introduction

Uniswap is a leading decentralized exchange (DEX) protocol built on the Ethereum blockchain. It enables users to swap various ERC-20 tokens without the need for a traditional order book, providing liquidity and facilitating DeFi transactions.

## Illustrations

### comparison
[![](https://mermaid.ink/img/pako:eNptUctOwzAQ_BVrz3FlO6kb-4YUOFFAPA6gXExiUquNHbmuSqj67zi1EK1gtYfV7Mw-D9C4VoOETtkQaouiBRM2Gj2vNLrTYe_8GrkP9GLNdq8GiSoVFHpUttOJ3aqgb5zvVUDoNRpeLnFV1TZlt7oJxll0q0btMU3gdVhpr3c9QlLRDDHCKCYckxQzTBnO6f8VWAIf3GbsIvirjxpGLvUT8erdBB87nTUqY_Iv8X4Ipjfbcyad_JIJGfQ67mraeLLDpKwhLtPrGmQMW-XXNdT2GHlqF9zTaBuQcQCdwW6YLlUZ1XnV_4CDsiAP8Alyns_YgjNOclHmZSmKDEaQeVHMCiEWcQQuBOPlMYMv56KezMRciHxOuCBlQfmCn6q9nZKpuG5NcH6Z_nt68_EbE--MKw?type=png)](https://mermaid.live/edit#pako:eNptUctOwzAQ_BVrz3FlO6kb-4YUOFFAPA6gXExiUquNHbmuSqj67zi1EK1gtYfV7Mw-D9C4VoOETtkQaouiBRM2Gj2vNLrTYe_8GrkP9GLNdq8GiSoVFHpUttOJ3aqgb5zvVUDoNRpeLnFV1TZlt7oJxll0q0btMU3gdVhpr3c9QlLRDDHCKCYckxQzTBnO6f8VWAIf3GbsIvirjxpGLvUT8erdBB87nTUqY_Iv8X4Ipjfbcyad_JIJGfQ67mraeLLDpKwhLtPrGmQMW-XXNdT2GHlqF9zTaBuQcQCdwW6YLlUZ1XnV_4CDsiAP8Alyns_YgjNOclHmZSmKDEaQeVHMCiEWcQQuBOPlMYMv56KezMRciHxOuCBlQfmCn6q9nZKpuG5NcH6Z_nt68_EbE--MKw)

#### trend
<table>
    <tr>
        <td>
            <img src="./figures/ethereum/uniswap_Eth_transaction_trend.png" alt="Ethereum Transaction Trend">
        </td>
        <td>
            <img src="./figures/Polygon/uniswap_polygon_transaction_trend.png" alt="uniswap_Polygon_transaction_trend">
        </td>
    </tr>
    <tr>
        <td>
            <img src="./figures/Arbitrum/uniswap_Arb_transaction_trend.png" alt="uniswap_Arb_transaction_trend">
        </td>
        <td>
            <img src="./figures/Optimism/uniswap_Opt_transaction_trend.png" alt="uniswap_Opt_transaction_trend">
        </td>
    </tr>
</table>

#### volume

<table>
    <tr>
        <td>
            <img src="./figures/ethereum/uniswap_Eth_volume.png" alt="Ethereum Volume">
        </td>
        <td>
            <img src="./figures/Polygon/uniswap_polygon_volume.png" alt="uniswap_Polygon_volume">
        </td>
    </tr>
    <tr>
        <td>
            <img src="./figures/Arbitrum/uniswap_Arb_volume.png" alt="uniswap_Arb_volume">
        </td>
        <td>
            <img src="./figures/Optimism/uniswap_Opt_volume.png" alt="uniswap_Opt_volume">
        </td>
    </tr>
</table>

#### Entropy

<table>
    <tr>
        <td>
            <img src="./figures/ethereum/uniswap_Eth_entropy.png" alt="Ethereum Entropy">
        </td>
        <td>
            <img src="./figures/Polygon/uniswap_polygon_entropy.png" alt="uniswap_Polygon_entropy">
        </td>
    </tr>
    <tr>
        <td>
            <img src="./figures/Arbitrum/uniswap_Arb_entropy.png" alt="uniswap_Arb_entropy">
        </td>
        <td>
            <img src="./figures/Optimism/uniswap_Opt_entropy.png" alt="uniswap_Opt_entropy">
        </td>
    </tr>
</table>


#### Gini

<table>
    <tr>
        <td>
            <img src="./figures/ethereum/uniswap_Eth_gini.png" alt="Ethereum Gini">
        </td>
        <td>
            <img src="./figures/Polygon/uniswap_polygon_gini.png" alt="uniswap_Polygon_gini">
        </td>
    </tr>
    <tr>
        <td>
            <img src="./figures/Arbitrum/uniswap_Arb_gini.png" alt="uniswap_Arb_gini">
        </td>
        <td>
            <img src="./figures/Optimism/uniswap_Opt_gini.png" alt="uniswap_Opt_gini">
        </td>
    </tr>
</table>


#### HHI
<table>
    <tr>
        <td>
            <img src="./figures/ethereum/uniswap_Eth_HHI.png" alt="Ethereum HHI">
        </td>
        <td>
            <img src="./figures/Polygon/uniswap_polygon_HHI.png" alt="uniswap_Polygon_HHI">
        </td>
    </tr>
    <tr>
        <td>
            <img src="./figures/Arbitrum/uniswap_Arb_HHI.png" alt="uniswap_Arb_HHI">
        </td>
        <td>
            <img src="./figures/Optimism/uniswap_Opt_HHI.png" alt="uniswap_Opt_HHI">
        </td>
    </tr>
</table>

#### Nakamoto
<table>
    <tr>
        <td>
            <img src="./figures/ethereum/uniswap_Eth_nakamoto.png" alt="Ethereum Nakamoto">
        </td>
        <td>
            <img src="./figures/Polygon/uniswap_polygon_nakamoto.png" alt="uniswap_Polygon_nakamoto">
        </td>
    </tr>
    <tr>
        <td>
            <img src="./figures/Arbitrum/uniswap_Arb_nakamoto.png" alt="uniswap_Arb_nakamoto">
        </td>
        <td>
            <img src="./figures/Optimism/uniswap_Opt_nakamoto.png" alt="uniswap_Opt_nakamoto">
        </td>
    </tr>
</table>


### Ethereum
<table>
    <tr>
        <td><img src="./figures/ethereum/uniswap_Eth_entropy.png" alt="uniswap_Eth_entropy"></td>
        <td><img src="./figures/ethereum/uniswap_Eth_gini.png" alt="uniswap_Eth_gini"></td>
    </tr>
    <tr>
        <td><img src="./figures/ethereum/uniswap_Eth_HHI.png" alt="uniswap_Eth_HHI"></td>
        <td><img src="./figures/ethereum/uniswap_Eth_nakamoto.png" alt="uniswap_Eth_nakamoto"></td>
    </tr>
    <tr>
        <td><img src="./figures/ethereum/uniswap_Eth_transaction_trend.png" alt="uniswap_Eth_transaction_trend"></td>
        <td><img src="./figures/ethereum/uniswap_Eth_volume.png" alt="uniswap_Eth_volume"></td>
    </tr>
</table>

### Polygon
<table>
    <tr>
        <td><img src="./figures/Polygon/uniswap_polygon_entropy.png" alt="uniswap_polygon_entropy"></td>
        <td><img src="./figures/Polygon/uniswap_polygon_gini.png" alt="uniswap_polygon_gini"></td>
    </tr>
    <tr>
        <td><img src="./figures/Polygon/uniswap_polygon_HHI.png" alt="uniswap_polygon_HHI"></td>
        <td><img src="./figures/Polygon/uniswap_polygon_nakamoto.png" alt="uniswap_polygon_nakamoto"></td>
    </tr>
    <tr>
        <td><img src="./figures/Polygon/uniswap_polygon_transaction_trend.png" alt="uniswap_polygon_transaction_trend"></td>
        <td><img src="./figures/Polygon/uniswap_polygon_volume.png" alt="uniswap_polygon_volume"></td>
    </tr>
</table>

### Arbitrum
<table>
    <tr>
        <td><img src="./figures/Arbitrum/uniswap_Arb_entropy.png" alt="uniswap_Arb_entropy"></td>
        <td><img src="./figures/Arbitrum/uniswap_Arb_gini.png" alt="uniswap_Arb_gini"></td>
    </tr>
    <tr>
        <td><img src="./figures/Arbitrum/uniswap_Arb_HHI.png" alt="uniswap_Arb_HHI"></td>
        <td><img src="./figures/Arbitrum/uniswap_Arb_nakamoto.png" alt="uniswap_Arb_nakamoto"></td>
    </tr>
    <tr>
        <td><img src="./figures/Arbitrum/uniswap_Arb_transaction_trend.png" alt="uniswap_Arb_transaction_trend"></td>
        <td><img src="./figures/Arbitrum/uniswap_Arb_volume.png" alt="uniswap_Arb_volume"></td>
    </tr>
</table>


### Optimism


<table>
    <tr>
        <td><img src="./figures/Optimism/uniswap_Opt_entropy.png" alt="uniswap_Opt_entropy"></td>
        <td><img src="./figures/Optimism/uniswap_Opt_gini.png" alt="uniswap_Opt_gini"></td>
    </tr>
    <tr>
        <td><img src="./figures/Optimism/uniswap_Opt_HHI.png" alt="uniswap_Opt_HHI"></td>
        <td><img src="./figures/Optimism/uniswap_Opt_nakamoto.png" alt="uniswap_Opt_nakamoto"></td>
    </tr>
    <tr>
        <td><img src="./figures/Optimism/uniswap_Opt_transaction_trend.png" alt="uniswap_Opt_transaction_trend"></td>
        <td><img src="./figures/Optimism/uniswap_Opt_volume.png" alt="uniswap_Opt_volume"></td>
    </tr>
</table>


## Key Concepts

### Uniswap

Uniswap is a decentralized exchange protocol known for its automated market maker (AMM) model. It allows users to trade tokens directly from their wallets, providing liquidity and earning fees in the process.

### Ethereum
Ethereum is a blockchain platform that enables the execution of smart contracts and the development of decentralized applications (DApps). Transactions on Ethereum involve the execution of these smart contracts and the transfer of Ether (ETH) and other tokens.

### Layer-2 Solutions
Layer-2 solutions are protocols or technologies that are built on top of Layer-1 blockchains like Ethereum to improve scalability and reduce transaction costs. Optimism, Arbitrum, and Polygon are examples of Layer-2 solutions that aim to enhance Ethereum's performance.


#### Optimism

**Introduction:**
Optimism is a Layer-2 scaling solution for Ethereum, employing Optimistic Rollup technology to increase transaction throughput while reducing gas fees. It's EVM-compatible, making it easy for Ethereum developers to migrate their projects.

**Advantages:**
- Scalability: Optimism significantly boosts Ethereum's TPS, ideal for high-demand applications.
- Reduced Fees: Transaction costs are lowered, benefiting DeFi and other Ethereum-based activities.

**Use Cases:**
- DeFi: DeFi platforms leverage Optimism for high transaction volumes and cost-efficiency.
- Gaming: Online games and applications with quick, low-cost transactions find Optimism beneficial.

#### Arbitrum

**Introduction:**
Arbitrum is a Layer-2 Ethereum scaling solution using Optimistic Rollup. It enhances throughput and reduces latency, ensuring EVM compatibility for seamless project migration.

**Advantages:**
- High Throughput: Arbitrum increases Ethereum's transaction capacity significantly.
- Low Latency: Fast transaction confirmations enhance the user experience.

**Use Cases:**
- DEXs: Decentralized exchanges leverage Arbitrum for smoother and cheaper trading.
- NFT Marketplaces: Quick and efficient NFT transactions benefit from Arbitrum.

#### Polygon

**Introduction:**
Polygon offers multiple sidechains and PoS consensus to scale Ethereum. It fosters interoperability and accommodates various dApps, attracting developers and users alike.

**Advantages:**
- Scalability Options: Polygon provides sidechains with flexible decentralization, balancing performance and security.
- Ecosystem Growth: A vibrant ecosystem with diverse projects and DApps makes Polygon appealing.

**Use Cases:**
- DeFi: Many DeFi projects utilize Polygon for low costs and faster confirmations.
- Gaming and NFTs: Scalability and cost-efficiency make Polygon popular in these domains.

## Measures

Understood. Here's the updated section that includes a discussion of the range for Shannon Entropy and the adjustment to the HHI Index range:

---

## Measures

In this section, we'll introduce various measures used to analyze daily transaction values on different Layer-2 scaling solutions, including Optimism, Arbitrum, and Polygon.

### Transaction Volume: Daily Total Transaction Value in USD

**Definition:** Transaction volume refers to the total daily transaction value conducted on a platform, typically measured in USD. It provides insights into the economic activity within a network.

**Example:** Suppose we want to calculate the daily transaction volume for Optimism. In a single day, the platform records transactions with values of $10, $20, $30, and so on. The daily total transaction volume would be calculated as follows:

```
Daily Transaction Volume (USD) = Sum of Transaction Values
                             = $10 + $20 + $30 + ...
```

### Transaction Decentralization Measured in Shannon Entropy

**Definition:** Shannon Entropy is a measure of the degree of randomness or uncertainty in a dataset. In the context of daily transaction decentralization, it can be used to assess the distribution of daily transaction values among various entities. Higher entropy values indicate greater decentralization.

**Example:** Let's consider an example with three entities (Entity A, Entity B, and Entity C) and their daily transaction values on a Layer-2 network:

- Entity A: $5,000 daily transaction value
- Entity B: $3,000 daily transaction value
- Entity C: $2,000 daily transaction value

To calculate Shannon Entropy:

1. Calculate the proportion of daily transaction values for each entity:
   - Proportion A = (5,000 / Total Daily Transaction Value) * 100
   - Proportion B = (3,000 / Total Daily Transaction Value) * 100
   - Proportion C = (2,000 / Total Daily Transaction Value) * 100

2. Calculate Shannon Entropy using the formula:

   ```
   H(X) = - Sum of (Proportion * Log2(Proportion))
   ```

   Calculate H(X) and then transform it as 2^H to get the Shannon Entropy value.

**Range:** The range for Shannon Entropy is between 1 (when there's a single entity with 100% of the transaction value) and infinity (maximum entropy when values are evenly distributed among entities). The exact maximum value depends on the number of entities.

### Transaction Decentralization Measured in Gini Index

**Definition:** The Gini Index is a measure of income or wealth inequality, and it can be adapted to assess the distribution of daily transaction values. It ranges from 0 to 1, where 0 indicates perfect equality (every entity has the same share), and 1 indicates perfect inequality (one entity has all the daily transaction values).

**Example:** Consider the same three entities from the previous example:

- Entity A: $5,000 daily transaction value
- Entity B: $3,000 daily transaction value
- Entity C: $2,000 daily transaction value

To calculate the Gini Index:

1. Arrange the daily transaction values in ascending order: [$2,000, $3,000, $5,000].

2. Calculate the Lorenz Curve, which represents the cumulative distribution of daily transaction values.

3. Calculate the area between the Lorenz Curve and the line of perfect equality.

4. Normalize the area to obtain the Gini Index.

**Range:** The Gini Index ranges from 0 (perfect equality) to 1 (perfect inequality).

### Transaction Decentralization Measured in HHI Index

**Definition:** The Herfindahl-Hirschman Index (HHI) is a measure of market concentration, but it can also be applied to assess the concentration of daily transaction values among entities in a network. It ranges from 0 to 10,000, where 0 indicates perfect decentralization, and 10,000 indicates perfect centralization (one entity controls all the daily transaction values).

**Example:** Let's use the same entities:

- Entity A: $5,000 daily transaction value
- Entity B: $3,000 daily transaction value
- Entity C: $2,000 daily transaction value

To calculate the HHI Index:

1. Calculate the market share of each entity (the proportion of daily transaction values they have):

   - Market Share A = (5,000 / Total Daily Transaction Value) * 100
   - Market Share B = (3,000 / Total Daily Transaction Value) * 100
   - Market Share C = (2,000 / Total Daily Transaction Value) * 100

2. Square each market share and sum the squared values:

   ```
   $$HHI = (Market Share A^2) + (Market Share B^2) + (Market Share C^2)$$
   ```

   Calculate HHI and then transform it as $2^HHI$ to get the HHI Index.

**Range:** The HHI Index ranges from 0 (perfect decentralization) to 10,000 (perfect centralization).

### Transaction Decentralization Measured in Nakamoto Index

**Definition:** The Nakamoto Index is a measure of decentralization that considers the distribution of daily transaction values among entities in a network. It assesses how many entities are needed to control a significant portion of the daily transaction values.

**Example:** Consider a Layer-2 network with five entities. The Nakamoto Index would measure how many of these entities are needed to control 51% or more of the daily transaction values.

- Entity A: $6,000 daily transaction value
- Entity B: $4,000 daily transaction value
- Entity C: $2,000 daily transaction value
- Entity D: $1,000 daily transaction value
- Entity E: $500 daily transaction value

To calculate the Nakamoto Index:

1. Arrange the entities in descending order of daily transaction values.

2. Calculate the cumulative percentage of daily transaction values:

   - Cumulative % A = (6,000 / Total Daily Transaction Value) * 100
   - Cumulative % A+B = (Cumulative % A + Cumulative % B)
   - And so on...

3. Determine how many entities are needed to reach a cumulative percentage of 51% or more. The Nakamoto Index is the minimum number of entities needed to control the majority of daily transaction values.

**Range:** The Nakamoto Index does not have a predefined range. It depends on the specific data and threshold you set for control (e.g., 51%). The Nakamoto Index is not inherently limited to a specific numerical range.


## Repository Structure

This repository is organized as follows:

- `/data`: Contains datasets related to Uniswap transactions and liquidity pools.
- `/code`: Includes code for data collection, analysis, and visualization.
- `/figures`: Figures files, including diagrams and visualizations

