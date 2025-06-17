# 🛢️ Case Study: Oil, AI, Geopolitics & The Future of Energy Security

[![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge\&logo=r\&logoColor=white)]()
[![ggplot2](https://img.shields.io/badge/ggplot2-darkgreen?style=for-the-badge)]()
[![dplyr](https://img.shields.io/badge/dplyr-1E90FF?style=for-the-badge)]()
[![showtext](https://img.shields.io/badge/showtext-grey?style=for-the-badge)]()
[![tidyr](https://img.shields.io/badge/tidyr-steelblue?style=for-the-badge)]()

## 🔍 [Executive Summary](#executive-summary)

This case study synthesizes ExxonMobil CEO Darren Woods’ forecast that oil and gas demand will rise through 2050—with analysis of the EU’s Due Diligence Directive, the Israel-Iran conflict, and U.S. foreign policy.

## 🌐 [Why Oil Demand Will Continue to Grow](#why-oil-demand-will-continue-to-grow)

### 1. 🌍 Global Energy Demand Is Still Rising

* Emerging markets (India, Africa, Southeast Asia) are driving growth.
* Industrialization needs dense energy—renewables can’t yet scale to meet this.
* IEA: Over 70% of energy demand growth through 2040 will come from developing economies.

> 💡 Even with renewables, fossil fuels remain indispensable in the near term.

### 2. 🏗️ Infrastructure & Transport Still Favor Oil

* Aviation, freight, shipping, and agriculture remain oil-dominant.
* Petrochemicals (plastics, fertilizer) still lack scalable clean alternatives.
* Over 600M fossil-fuel vehicles remain in use in developing nations.

### 3. ⚡ Renewables Aren’t Fully Base-Load Ready

* Intermittency and storage limitations still require natural gas backups.
* Grid-scale batteries and smart grids are advancing, but deployment lags.

### 4. 🌍 Middle East Conflict & Geopolitical Risk

* Israel-Iran escalation threatens Strait of Hormuz oil flows.
* NATO countries, including the U.S., have energy security guarantees.
* Instability incentivizes local production and fossil stockpiling.

### 5. 🏛️ Due Diligence Directive Pushback

* Woods criticized the EU’s Directive requiring firms to manage environmental and human rights risks in their global supply chains.
* He argues it causes unlimited liability, deters investment, and penalizes U.S. producers.
* Critics call it “protectionist lawfare” reshaping trade via ESG compliance.

> 💡 The Directive could turn climate goals into trade barriers, distorting global markets.

## 📉 [Strategic Insights Table](#strategic-insights-table)

| Factor                    | Implication for Oil  |
| ------------------------- | -------------------- |
| Emerging Market Growth    | Expanding demand     |
| Israel-Iran Conflict      | Supply disruption    |
| Due Diligence Legislation | Reduced investment   |
| Grid & Renewable Lag      | Fossil fuel reliance |
| ESG Lawfare & Compliance  | Market fragmentation |

## ⚔️ [Will the U.S. Get Involved in a Middle East Conflict?](#will-the-us-get-involved-in-a-middle-east-conflict)

**Short answer: Possibly.**

* The U.S. Navy already escorts oil tankers through the Strait of Hormuz.
* Escalation with Iran could jeopardize over 30% of global seaborne oil.
* U.S. alliances with Israel, UAE, and Saudi Arabia may push Washington into a defensive role.

> 💬 Energy has always been strategic. Tensions and restrictive legislation may deepen U.S. involvement.

## 🇺🇸 [What the U.S. Stands to Gain or Lose](#what-the-us-stands-to-gain-or-lose)

### 🟢 Strategic Gains

* **Energy Route Control:** Stability for \~30% of global seaborne oil.
* **Alliance Credibility:** Strengthened ties with Israel, UAE, and Saudi Arabia.
* **Domestic Oil Leverage:** Boosted U.S. shale and Gulf Coast production.
* **AI & Defense Innovation:** Accelerated military logistics and drone systems.

### 🔴 Risks & Losses

* **Escalation Costs:** Regional war and rising defense spending.
* **Economic Shock:** Oil price spikes may worsen inflation.
* **Reputational Blowback:** Anti-American sentiment in the region.
* **Green Energy Delay:** Diverts attention and funds from clean energy.

> 🧠 **Net Impact**: Likely U.S. involvement under energy security—but with major tradeoffs.

## ❗ [Why This Matters](#why-this-matters)

Understanding the entanglement of energy policy, military alliances, AI investments, and global governance (e.g., ESG laws) is critical for:

* Policymakers managing energy transitions
* Companies navigating global compliance risks
* Investors predicting geopolitical volatility

## 📊 [Visualizations](#visualizations)

### 📈 Graph 1: Global Oil Demand Forecast

```r
library(ggplot2)
demand <- data.frame(Year = seq(2025, 2050, 5), Demand = c(98, 101, 104, 107, 109, 110))
ggplot(demand, aes(x = Year, y = Demand)) +
  geom_line(color = "#556B2F", size = 1.5) +
  theme_minimal() +
  labs(title = "Global Oil Demand Forecast (2025-2050)", x = "Year", y = "Million Barrels per Day")
```

### 📈 Graph 2: Investment Drop due to Due Diligence Directive

```r
investment <- data.frame(Region = c("US", "EU", "China", "India"), Impact = c(-20, -10, 5, 10))
ggplot(investment, aes(x = Region, y = Impact, fill = Impact)) +
  geom_col() +
  scale_fill_gradient2(low = "darkred", mid = "khaki", high = "darkgreen", midpoint = 0) +
  theme_minimal() +
  labs(title = "Projected Investment Shifts under Due Diligence Directive", y = "% Change")
```

### 📈 Graph 3: Strategic Oil Route Risk Map

```r
routes <- data.frame(Route = c("Strait of Hormuz", "Suez Canal", "Panama Canal"), Risk = c(0.9, 0.7, 0.4))
ggplot(routes, aes(x = reorder(Route, Risk), y = Risk)) +
  geom_bar(stat = "identity", fill = "#808000") +
  coord_flip() +
  theme_minimal() +
  labs(title = "Risk Ratings for Global Oil Routes", x = NULL, y = "Risk Level (0-1)")
```

## 🛠 [Summary](#summary)

* Oil demand is shifting, not shrinking.
* The EU’s Due Diligence Directive may hurt U.S. energy exports.
* Iran-Israel conflict may catalyze U.S. action to defend oil routes.

> Fossil fuels, ESG lawfare, and global instability are shaping the future of energy.

## 📁 [Suggested Repo Title](#suggested-repo-title)

**`geoenergy-ai-2025`**
*Modeling the geopolitical and legislative feedback loops shaping the future of oil and gas.*

