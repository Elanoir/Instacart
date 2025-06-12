# 📊 Instacart

## 🗃️ Dataset 
- Source: https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis

## 🔍 Objetive 1
- Analyze the itemset/rules generation procedure
- Make a performance analysis up to a threshold level of support
- Identify a good candidate method
- Define a good support threshold for analysis according to your computational capabilities

## 🔍 Objetive 2
- Identify the most relevant rules
- From your predefined support level generate all available itemsets and generate rules
- Identify a set of relevant rules and comment them
- Identify the Maximal and Closed Itemsets for the same level of support
- Generate the most relevant rules for closed and maximal itemsets with adequate statistics
  
## 🛠️ Tools
- Python (Pickle, Pandas, NumPy, Matplotlib, pyeclat, apriori, association_rules, fpgrowth, TransactionEncoder)
- Jupyter Notebook

## 📈 Metodologia
1. **Data Acquisition and Transformation**
2. **Association Rules Models: Apriori, FP-growth,	ECLAT,	PD**
3. **Performance Evaluation**
4. **Discussion**

## 💡 Findings
- All algorithms indicate the same itemsets (using the same minimum support level)
- Consider: time complexity and computacional requirements
- Exponential growth in time complexity for Apriori 
- Model chosen: Eclat at a minimum support level of 0.01
- Trend found: People who buy fruits, tend to buy bananas
- Example: People who get Organic Fuji Apple are 2.576 times more likely to get a Banana
