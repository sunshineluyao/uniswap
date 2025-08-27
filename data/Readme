# Uniswap Data Repository

## 📊 Overview

This repository contains comprehensive data about Uniswap, a decentralized cryptocurrency exchange protocol. The data covers multiple blockchain networks and includes various metrics that measure trading activity, market concentration, and decentralization levels.

## 🌐 Supported Networks

The data is organized by blockchain network:

- **Ethereum** (`ethereum/`) - The main Ethereum network (mainnet)
- **Polygon** (`Polygon/`) - A Layer 2 scaling solution for Ethereum
- **Arbitrum** (`Arbitrum/`) - Another Layer 2 scaling solution
- **Optimism** (`Optimism/`) - A Layer 2 optimistic rollup solution

## 📁 Data Structure

Each network folder contains the following CSV files:

```
[Network_Name]/
├── [Network]_volume.csv      # Trading volume statistics
├── [Network]_HHI.csv         # Herfindahl-Hirschman Index (market concentration)
├── [Network]_gini.csv        # Gini coefficient (inequality measure)
├── [Network]_nakamoto.csv    # Nakamoto coefficient (decentralization)
└── [Network]_Entropy.csv     # Entropy measure (diversity)
```

## 📋 Data Dictionary

### 1. Volume Data (`*_volume.csv`)

**Purpose**: Tracks daily trading volume statistics across all trading pairs on each network.

| Column | Description | Data Type | Example |
|--------|-------------|-----------|---------|
| `date` | Date of the data point | Date (YYYY-MM-DD) | 2021-06-01 |
| `min` | Minimum daily volume for any trading pair | Float | 0.0 |
| `max` | Maximum daily volume for any trading pair | Float | 8007651.52 |
| `sum` | Total daily volume across all pairs | Float | 1751659615.91 |
| `std` | Standard deviation of daily volumes | Float | 141649.60 |
| `var` | Variance of daily volumes | Float | 20064608101.60 |
| `mean` | Average daily volume per trading pair | Float | 35075.28 |
| `median` | Median daily volume per trading pair | Float | 1564.16 |
| `percentile_75` | 75th percentile of daily volumes | Float | 8914.14 |
| `percentile_25` | 25th percentile of daily volumes | Float | 269.67 |
| `count` | Number of trading pairs active that day | Integer | 49940 |

**What This Tells Us**: 
- **High volume days** indicate increased trading activity and market interest
- **Large gaps between mean and median** suggest some pairs are much more popular than others
- **High standard deviation** indicates significant variation in trading pair popularity

### 2. HHI Data (`*_HHI.csv`)

**Purpose**: Measures market concentration using the Herfindahl-Hirschman Index.

| Column | Description | Data Type | Example |
|--------|-------------|-----------|---------|
| `date` | Date of the data point | Date (YYYY-MM-DD) | 2021-06-01 |
| `val` | HHI value (0-100 scale) | Float | 3.47 |

**HHI Interpretation**:
- **0-10**: Highly competitive market (many small players)
- **10-25**: Moderately concentrated market
- **25-50**: Concentrated market
- **50+**: Highly concentrated market (few dominant players)

**What This Tells Us**: 
- **Lower HHI** = More decentralized, competitive market
- **Higher HHI** = Market dominated by few large players
- **Trends over time** show whether markets are becoming more or less concentrated

### 3. Gini Data (`*_gini.csv`)

**Purpose**: Measures inequality in trading volume distribution across pairs.

| Column | Description | Data Type | Example |
|--------|-------------|-----------|---------|
| `date` | Date of the data point | Date (YYYY-MM-DD) | 2021-06-01 |
| `val` | Gini coefficient (0-1 scale) | Float | 0.887 |

**Gini Interpretation**:
- **0**: Perfect equality (all pairs have equal volume)
- **0.3-0.4**: Low inequality
- **0.4-0.6**: Moderate inequality
- **0.6+**: High inequality
- **1**: Perfect inequality (one pair has all volume)

**What This Tells Us**:
- **High Gini** = Most trading activity concentrated in few pairs
- **Low Gini** = Trading activity more evenly distributed
- **Trends** show whether the platform is becoming more or less inclusive

### 4. Nakamoto Data (`*_nakamoto.csv`)

**Purpose**: Measures decentralization by counting the minimum number of entities needed to control 51% of the network.

| Column | Description | Data Type | Example |
|--------|-------------|-----------|---------|
| `date` | Date of the data point | Date (YYYY-MM-DD) | 2021-06-01 |
| `val` | Nakamoto coefficient | Integer | 1457 |

**Nakamoto Interpretation**:
- **Higher numbers** = More decentralized (harder to control)
- **Lower numbers** = Less decentralized (easier to control)
- **1000+** = Highly decentralized
- **100-1000** = Moderately decentralized
- **<100** = Centralized

**What This Tells Us**:
- **High Nakamoto** = Network is resistant to attacks and manipulation
- **Low Nakamoto** = Network vulnerable to concentration of power
- **Trends** show whether decentralization is improving or declining

### 5. Entropy Data (`*_entropy.csv`)

**Purpose**: Measures diversity and randomness in trading volume distribution.

| Column | Description | Data Type | Example |
|--------|-------------|-----------|---------|
| `date` | Date of the data point | Date (YYYY-MM-DD) | 2021-06-01 |
| `val` | Entropy value (higher = more diverse) | Float | 6740.35 |

**Entropy Interpretation**:
- **Higher values** = More diverse, unpredictable trading patterns
- **Lower values** = More concentrated, predictable patterns
- **Trends** show whether markets are becoming more or less diverse

**What This Tells Us**:
- **High entropy** = Healthy, diverse ecosystem with many active pairs
- **Low entropy** = Ecosystem dominated by few pairs
- **Changes over time** indicate shifts in market dynamics

## 📊 Data Coverage

| Network | Date Range | Records | Trading Pairs |
|---------|------------|---------|---------------|
| Ethereum | 2021-06-01 to 2021-09-07 | 581 days | ~30,000-90,000 daily |
| Polygon | 2021-06-01 to 2021-09-07 | 379 days | ~20,000-60,000 daily |
| Arbitrum | 2021-06-01 to 2021-09-07 | 490 days | ~25,000-70,000 daily |
| Optimism | 2021-06-01 to 2021-09-07 | 418 days | ~20,000-50,000 daily |

## 🔍 Key Insights

### Market Health Indicators
- **Volume trends** show overall platform adoption and usage
- **HHI trends** indicate whether markets are becoming more competitive
- **Gini trends** show whether trading is becoming more inclusive
- **Nakamoto trends** measure decentralization progress
- **Entropy trends** indicate ecosystem diversity

### Cross-Network Comparison
- **Ethereum** typically has highest volumes and most pairs
- **Layer 2 solutions** (Polygon, Arbitrum, Optimism) show different adoption patterns
- **Network effects** can be observed across all metrics

## 📈 How to Use This Data

### For Researchers
- **Academic studies** on DeFi market dynamics
- **Economic analysis** of decentralized exchanges
- **Network effect research** across blockchain layers

### For Analysts
- **Market trend analysis** and forecasting
- **Risk assessment** of different networks
- **Investment decision support**

### For Developers
- **Protocol optimization** based on usage patterns
- **Feature prioritization** based on user behavior
- **Performance benchmarking** across networks

## 🛠️ Data Processing

### Data Sources
- **On-chain data** from blockchain networks
- **Real-time aggregation** of trading pair statistics
- **Daily snapshots** for consistent time series analysis

### Quality Assurance
- **Automated validation** of data integrity
- **Outlier detection** and flagging
- **Consistency checks** across networks

## 📚 Additional Resources

- **Uniswap Documentation**: [docs.uniswap.org](https://docs.uniswap.org)
- **Protocol Analytics**: [info.uniswap.org](https://info.uniswap.org)
- **Developer Resources**: [github.com/Uniswap](https://github.com/Uniswap)

## 🤝 Contributing

This data is maintained as part of ongoing research into DeFi market dynamics. For questions, suggestions, or collaboration opportunities, please reach out to the research team.

---

*Last Updated: September 2021*  
*Data Version: 1.0*  
*Maintained by: Uniswap Research Team*

