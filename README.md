# 📦 Inventory Service-Level Modeling Across Stores

## 💼 Business use case

Retail planners need to decide how much inventory to position across a network when demand is uncertain. Excess stock ties up working capital, while insufficient stock increases service failures. A probability model makes that trade-off explicit by linking inventory levels to expected service probability.

## 🎯 Principal objective

Model store demand as independent Normal random variables with mean 800 units and standard deviation 250 units, then calculate the probability that aggregate demand stays below available supply and the inventory needed to reach specific service targets.

## 🔎 Summary of takeaways

For two stores with 2,000 units of combined inventory, the stored probability of covering aggregate demand is **87.11%**, and the 95th-percentile requirement is about **2,182 units**. For 12 stores, the modeled 95th-percentile aggregate demand is approximately **11,024 units**, compared with mean demand of 9,600 units.

The exercise illustrates risk pooling: under independence, expected demand grows linearly with the number of stores while aggregate uncertainty grows with the square root of that count. The main caveat is that real store demand is often correlated during promotions, weather events, or holidays, which would make the current independence-based estimates optimistic.

## 🧭 Explore the code

The [notebook](https://github.com/saels/warehouse-fulfillment-probability/blob/e0316935e3bfadeb15c0e22df9c0e2164c3e6849/Warehouse_fulfillment_probability.ipynb) walks through aggregation of Normal demand, CDF-based service probabilities, inverse-CDF inventory targets, and visualizations of the supply-service trade-off. Check the code for the formulas behind each planning scenario.
