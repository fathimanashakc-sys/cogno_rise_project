# cogno_rise_project
# 📊 CognoRise InfoTech | Data Analytics Internship Projects

This repository contains three data analytics projects completed during my internship at **CognoRise InfoTech**. Each project has an interactive **Power BI** dashboard, with key insights, recommendations and limitations.

---

## 📚 Projects at a Glance

| Project | Domain | Dataset Size | Dashboard Pages | Headline Result |
|---|---|---|---|---|
| [🛒 Retail Sales Analysis](#-1-retail-sales-analysis) | Retail | ~1K transactions | 2 | 456K sales, with a May peak and a September low |
| [📦 E-Commerce Sales Analytics](#-2-e-commerce-sales-analytics) | E-Commerce | ~1M records | 3 | 879.30M net revenue, evenly spread across categories |
| [📣 Marketing Campaign Performance](#-3-marketing-campaign-performance) | Marketing | ~200K campaigns | 6 | 2.50bn spend, CPA of about 284 |

---

## 🛠️ Tools & Skills

| Area | What I used |
|---|---|
| **Visualization** | Power BI: multi-page dashboards, KPI cards, page navigation, slicers, maps, combo charts, scatter plots |
| **Calculations** | DAX measures such as Net Revenue, Estimated Profit, Profit Margin %, AOV, CTR, CPC and CPA |
| **Analysis** | KPI analysis, category and segment comparison, trend analysis |
| **Communication** | Key insights, recommendations and limitations |

---

## 🛒 1. Retail Sales Analysis

### Objective
Analyze retail transactions to understand sales over time and by product category and gender.


<!-- Data cleaning: add the steps you actually did -->

### Key Metrics
| Total Sales | Transactions | Units Sold | Avg Order Value |
|---|---|---|---|
| ~456K | ~1K | ~3K | 456 |

### Dashboard (2 pages)
| Page | What it shows |
|---|---|
| **Retail Sales Dashboard** | KPI cards, monthly sales trend, sales and average order value by category, sales by gender |
| **Insights & Recommendations** | Findings, actions and limitations |


### Key Insights
- **Category sales are close.** Electronics (~157K) and Clothing (~155K) lead, while Beauty is lowest (~143K).
- **Beauty has the highest average order value** even though its total sales are the lowest.
- **May 2023 was the strongest month** (~53K) and **September 2023 the weakest** (~24K).
- **Gender split is close.** Female customers spend slightly more than male customers.

### Recommendations
1. **Grow Beauty order volume** by testing targeted promotions.
2. **Raise Clothing order value** by testing multi-item offers.
3. **Investigate the September dip** and test a campaign for that period.
4. **Keep campaigns mainly gender-neutral.**

### ⚠️ Limitations
- Only about one year of data, so seasonality cannot be confirmed. January 2024 appears to be partial.
- No cost data, so profit cannot be calculated.

---

## 📦 2. E-Commerce Sales Analytics

### Objective
Measure revenue and estimated profit, and see how categories, products, discounts and returns compare.

### Dataset
Diversified e-commerce data with about 1M records, covering products, categories, prices, discounts, shipping, returns, customer location and gender.



### Key Metrics
| Net Revenue | Estimated Profit | Profit Margin | AOV | Avg Discount | Avg Return Rate | Shipping Cost |
|---|---|---|---|---|---|---|
| 879.30M | 762.07M | ~87% | 879.30 | 12.52 | 10.49 | 24.99M |

### Dashboard (3 pages)
| Page | What it shows |
|---|---|
| **Overview** | KPI cards, revenue map by customer location, revenue and profit by category, revenue by gender, slicers for category, location, shipping method and seasonality |
| **Product Level Analysis** | Return rate by category, product revenue vs profit margin, profit margin by discount, product table |
| **Insights & Recommendations** | Findings, actions and limitation |



### Key Insights
- **Categories are evenly balanced.** Each of the 5 categories (Books, Electronics, Footwear, Home Appliances, Apparel) brings in about 175M.
- **Returns cost more than shipping.** Estimated return loss is about 92M, compared with about 25M of shipping cost.
- **Higher discounts slightly reduce margin,** from about 87.0% at 0% discount to 86.2% at 25%.
- **Return rate is about 10.5% in every category.**

### Recommendations
1. **Reduce returns** with better product descriptions, size guides and quality checks.
2. **Test lower discount levels** and measure the effect on both sales and margin.
3. **Review shipping costs** with carriers.
4. **Keep a balanced category mix.**

### ⚠️ Limitations
- No product cost, so profit is an estimate (revenue minus shipping and return loss). The margin is likely overstated.
- No order date or customer ID, so time trends and new vs repeat customers cannot be analyzed.
- Each row is treated as one order.

---

## 📣 3. Marketing Campaign Performance

### Objective
Compare campaigns by campaign type, channel, target audience and time, and recommend where to improve.


<!-- Data cleaning: add the steps you actually did -->

### Key Metrics
| Total Spend | Campaigns | Conversions | Clicks | CTR | CPC | CPA | Avg ROI |
|---|---|---|---|---|---|---|---|
| 2.50bn | ~200K | ~8.8M | ~110M | 9.98% | 22.74 | ~284 | 5.00 |

### Dashboard (6 pages)
| Page | What it shows |
|---|---|
| **Executive Summary** | KPI cards, conversions by quarter, ROI and cost by campaign type, campaigns by target audience |
| **Campaign Analysis** | ROI, CPA, CTR, engagement and campaign count by campaign type |
| **Channel Analysis** | Campaign count, ROI, CPA, CTR and engagement by channel |
| **Audience Analysis** | Campaign count, CTR, CPA, clicks, engagement and ROI by target audience |
| **Time Analysis** | Monthly spend and conversions, quarterly ROI, clicks and CPA |
| **Insights & Recommendations** | Spend vs conversions, CPA comparison, findings and actions |



### Key Insights
- **No standout channel.** All 6 channels show very similar CPA, CTR and ROI.
- **No standout campaign type.** Each of the 5 types spent about 500M and delivered about 1.75M conversions.
- **Audiences perform similarly** on CTR, CPA and ROI.
- **February was the lowest month** for spend and conversions. It is also the shortest month.
- **Click-to-conversion gap.** CTR is close to 10%, while each conversion costs about 284.

### Recommendations
1. **Set a cost cap** for campaigns whose CPA is far above average (for example, 1.5 times).
2. **A/B test** creatives, landing pages and targeting.
3. **Keep the current channel and audience mix** until a test shows a clear winner.
4. **Track CPA and ROI monthly.**

### ⚠️ Limitations
- Differences between segments are very small, so rankings should be treated with caution.
- The data covers 2021 only.

---

## 📁 Repository Files

```
CognoRise-Info-Tech-Project/
├── retail_sales_dataset.csv.pbix
├── ecommerce analysis.pbix
├── Marketing Campaign Performance.pbix
└── README.md
```

---

## 🚀 How to Explore

1. Clone or download this repository.
2. Open any `.pbix` file in **Power BI Desktop**.
3. Use the page navigation buttons and slicers to explore each dashboard.

---

## 👤 Author

**Fathima Nasha kc**
**Aspiring Data Analyst**
[GitHub](https://github.com/fathimanashakc-sys)
[linkedIn](www.linkedin.com/in/fathima-nasha-kc-027507417)
