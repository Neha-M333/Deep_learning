# 📈 Marketing Analytics: Market Basket Analysis

![Market Basket Analysis](https://images.unsplash.com/photo-1563013544-824ae1b704d3?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80)
<sub>Photo by [Dave Goudreau](https://unsplash.com/@davegoudreau) on Unsplash</sub>

Welcome to the **Marketing Analytics** tutorial series. This repository kicks off with **Market Basket Analysis (MBA)** — a powerful technique for uncovering associations between items in transactional data. These techniques can help you make smarter, data-driven decisions for product promotions and recommendations.

---

## 📚 What You'll Learn

After completing this tutorial, you will be able to:

- ✅ Understand what Market Basket Analysis is
- ✅ Prepare and preprocess transactional data for MBA
- ✅ Calculate key MBA metrics such as support, confidence, and lift
- ✅ Perform MBA using the **Apriori algorithm**
- ✅ Visualize item associations and rules

---

## 🧰 Tools Used

This tutorial primarily uses Python and the [`mlxtend`](http://rasbt.github.io/mlxtend/) library, which provides:

- `TransactionEncoder` (for preprocessing)
- `apriori()` (for generating frequent itemsets)
- `association_rules()` (for mining association rules)

Install required packages:

```bash
pip install -r time_series_requirements.txt
