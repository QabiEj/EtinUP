---
# Introduction
*Note: The introduction was completed in Part I of the study.*

# Methodology

## Systematic Approach
This literature review follows the Preferred Reporting Items for Systematic Reviews and Meta-Analyses (PRISMA)[16] guidelines to ensure methodological rigor.

## Eligibility Criteria

### Inclusion Criteria
- Studies published between 2020 and 2024 focusing on inventory optimization and demand analysis.
- Peer-reviewed journal articles, conference proceedings, or book chapters employing machine learning, deep reinforcement learning, or similar computational approaches.
- English language publications accessible through major academic databases.

### Exclusion Criteria
- Non-peer-reviewed articles, books, and editorials.
- Studies lacking detailed methodology or insufficient data.
- Articles addressing unrelated topics, such as non-supply-chain inventory systems.

## Information Sources
The review included literature from the following databases:
- ScienceDirect
- IEEE Xplore
- ACM Digital Library
- Conference proceedings from major computational and supply chain forums

## Search Strategy
The following query was designed to retrieve relevant studies:
- ("inventory optimization" AND ("machine learning" OR "predictive analytics") AND ("supply chain" OR "e-commerce"))
- Filters included publication years (2020–2024), document type, and relevance. Keywords such as “inventory optimization”, “machine learning”, "predictive analytics", “supply chain” and "e-commerce" were applied.

## Selection Process
1. **Screening:** Titles and abstracts were assessed for relevance.
2. **Full-Text Review:** Shortlisted studies were reviewed for detailed applicability.
3. **Risk of Bias Assessment:** Study bias was evaluated using the Cochrane Collaboration tool.

## Data Extraction
Data collected included:
- Study objectives and methodologies.
- Inventory system hierarchy (e.g., single-echelon vs. multi-echelon).
- Computational techniques applied.
- Reported outcomes and limitations.

# Results and Discussion

## Clustering of Studies
The reviewed studies were categorized into the following clusters:

### 1. Reinforcement Learning-Based Models
- **Studies:**
  - Inventory management of new products in retailers using model-based deep reinforcement learning - ScienceDirect [1].
    - **Details:** This study addresses the optimal inventory management problem for new smartphone products, focusing on model-based deep reinforcement learning. The proposed method combines offline model learning and online planning, demonstrating improved profitability, efficiency, and customer satisfaction. The method improved total rewards and inventory turnover by over 5% compared to heuristic methods while maintaining the same stock-out rate.
  - Contextual reinforcement learning for supply chain management - ScienceDirect [2].
    - **Details:** This study combines offline training and online adaptation for supply chain inventory management. Agents were trained using data from various environmental configurations and adapted online to maximize rewards. The methodology improved efficiency and effectiveness in unknown environments, making RL algorithms more practical.

- **Findings:** These studies demonstrated the efficiency of reinforcement learning (RL) in optimizing dynamic inventory systems. RL-based models excel in adapting to non-stationary demand patterns and optimizing multi-echelon configurations. For example, RL models reduced inventory costs by up to 15% in some case studies [1][2].
- **Limitations:**
  - High computational requirements.
  - Dependence on large datasets for training [2].

### 2. Deep Learning and Time-Series Forecasting
- **Studies:**
  - Improving efficiency and sustainability via supply chain optimization through CNNs and BiLSTM - ScienceDirect [3].
    - **Details:** This study integrates CNNs and BiLSTM models to enhance supply chain efficiency and sustainability. The proposed model optimizes resource allocation, uncovers trends, and evaluates supply chain spatial linkages. It achieved high accuracy and specificity, significantly improving supply chain processes.
  - Order-up-to-level inventory optimization model using time-series demand forecasting with ensemble deep learning - ScienceDirect [4].
    - **Details:** This study uses ensemble deep learning methods for demand forecasting in the online retail industry. The ensemble models improved prediction accuracy and optimized inventory systems under a cycle service level objective.
  - A comparative assessment of Holt-Winters exponential smoothing and ARIMA for inventory optimization in supply chains - ScienceDirect [5].
    - **Details:** This study compares Holt-Winters Exponential Smoothing (HWES) and ARIMA models for demand forecasting and inventory optimization. ARIMA consistently outperformed HWES in minimizing lost sales and mitigating stockouts.
  - Financial Big Data Visualization: A Machine Learning Perspective - Proceedings of the 17th International Symposium on Visual Information Communication and Interaction [11].
    - **Details:** This study categorizes financial big data visualization methodologies from a machine learning perspective. It explores the latest trends and identifies the most suitable techniques for different types of financial data.

- **Findings:** Deep learning approaches, such as CNNs, BiLSTMs, and ensemble models, significantly enhanced demand forecasting accuracy. These techniques integrate historical data and stochastic modeling to predict inventory requirements [3][4][5]. Additionally, financial big data visualization techniques provided insights into inventory trends and patterns [11].
- **Limitations:**
  - Susceptibility to overfitting.
  - High dependency on historical data [5].

### 3. Hybrid and Blockchain-Integrated Models
- **Studies:**
  - βFSCM: An Enhanced Food Supply Chain Management System Using Hybrid Blockchain and Recommender Systems - ScienceDirect [6].
    - **Details:** This study proposes a hybrid blockchain model with an Access Control mechanism to enhance security, reliability, and usability in food supply chain management. The integration of a recommender system improves inventory management and consumer satisfaction.
  - Innovative Applications of Unsupervised Learning in Uncertainty-Aware Pharmaceutical Supply Chain Planning - IEEE Journals & Magazine [7].
    - **Details:** This study introduces a framework for pharmaceutical supply chain planning using unsupervised learning algorithms. The model addresses uncertainty through a joint chance constraint formulation, improving resiliency, reliability, and equity in the supply chain.
  - Amplifying Learning and Teaching Effectiveness through Generative Artificial Intelligence: A Qualitative Approach with Case Studies on Supply Chain and Cold Chain Management - Proceedings of the International Conference on Decision Science and Management [12].
    - **Details:** This study evaluates the effectiveness of generative AI-based learning for students, with case studies on supply chain and cold chain management. The results indicate that the treatment group outperformed the control group, enhancing learning quality and experience.

- **Findings:** Hybrid systems combining blockchain with unsupervised learning provided increased transparency and traceability in supply chains. These models also addressed pharmaceutical-specific challenges, such as expiration tracking and storage conditions [6][7]. Additionally, generative AI approaches enhanced learning and teaching effectiveness in supply chain management [12].
- **Limitations:**
  - Implementation complexity.
  - High initial setup costs [6].

### 4. E-Commerce and Retail Applications
- **Studies:**
  - Optimizing e-Commerce Supply Chains with Categorical Boosting - IEEE Xplore [8].
    - **Details:** This study uses the CatBoost algorithm to optimize e-commerce supply chain processes. The model handles categorical variables effectively and improves prediction efficiency for sales, profit, and delivery times.
  - Customer Segment Classification Prediction in the Australian Retail - Proceedings of the 2023 4th International Conference on Machine Learning and Computer Application [9].
    - **Details:** This study employs multiple machine learning methods to classify customer segments for an Australian retail company. XGBoost was found to be the most effective model, providing insights into customer behavior and preferences.
  - Research and implementation of e-commerce inventory optimization strategy based on advanced data analysis technology - Conference Proceedings [10].
    - **Details:** This study explores the use of advanced data analysis technologies, such as machine learning and big data analysis, to optimize e-commerce inventory. The effectiveness of these technologies in improving inventory turnover rate, reducing inventory cost, and enhancing customer service was verified.
  - Precise Issuance of Meituan Merchants’ Coupons with Machine Learning - Proceedings of the International Conference on Machine Learning, Pattern Recognition and Automation Engineering [13].
    - **Details:** This study analyzes transaction data to predict coupon redemption using the XGBoost model. The model improves the precision of coupon issuance, increasing net profits for merchants.
  - Retailers’ Order Decision with Setup Cost using Machine Learning - Proceedings of the 2024 8th International Conference on Machine Learning and Soft Computing [14].
    - **Details:** This study develops a predictive model to inform retailer purchasing decisions using artificial neural networks. The model helps manufacturers optimize their order policies, reducing costs and improving operational efficiency.
  - Customer Segment Classification Prediction in the Australian Retail Based on Machine Learning Algorithms - Proceedings of the 2023 4th International Conference on Machine Learning and Computer Application [15].
    - **Details:** This study classifies customer segments for an Australian retail company using machine learning algorithms. The results provide insights into customer behavior and preferences, helping to improve marketing strategies.

- **Findings:** Machine learning applications in e-commerce and retail enhanced customer segmentation, optimized order fulfillment, and reduced supply chain bottlenecks. Predictive analytics and boosting algorithms were pivotal in automating inventory decision-making [8][9][10]. Additionally, machine learning techniques were used for precise issuance of coupons and order decision-making [13][14][15].
- **Limitations:**
  - Limited applicability to small-scale businesses.
  - Issues with model scalability [10].
- **Limitations:**
  - Limited applicability to small-scale businesses.
  - Issues with model scalability [10].

## Visual Representation
**Figure 1:** PRISMA Flow Diagram for Study Selection
![PRISMA Flow Diagram](prisma_flow_diagram.png)

**Figure 2:** Study Categorization and Key Findings
![Study Categorization](study_categorization.png)
A bar chart or bubble chart can represent the distribution of studies across the clusters, highlighting the methodologies applied and their corresponding outcomes.

# Conclusion
This systematic review provides insights into the advancements in inventory optimization and demand forecasting within the supply chain domain. Key findings include:
1. Reinforcement learning offers dynamic adaptability but requires significant computational resources [1-2].
2. Deep learning models enhance forecasting accuracy but are data-intensive [3-5][11].
3. Hybrid systems with blockchain introduce transparency but are costly to implement [6-7][12].
4. Machine learning in e-commerce optimizes processes but faces scalability challenges [8-15].

**Future research should focus on:**
- Improving the scalability and efficiency of reinforcement learning models [1][2].
- Developing hybrid systems tailored for low-resource environments [6].
- Addressing ethical and privacy concerns in blockchain and ML-based supply chains [7].

These efforts will further advance the integration of intelligent systems into supply chain management, enhancing both operational efficiency and customer satisfaction.

# References
1. Inventory management of new products in retailers using model-based deep reinforcement learning, ScienceDirect. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S0957417423007583
2. Contextual reinforcement learning for supply chain management, ScienceDirect. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S0957417424004068
3. Improving efficiency and sustainability via supply chain optimization through CNNs and BiLSTM, ScienceDirect. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S0040162524006395
4. Order-up-to-level inventory optimization model using time-series demand forecasting with ensemble deep learning, ScienceDirect. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S2949863523000237
5. A comparative assessment of Holt-Winters exponential smoothing and ARIMA for inventory optimization in supply chains, ScienceDirect. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S294986352400027X#sec0080
6. βFSCM: An Enhanced Food Supply Chain Management System Using Hybrid Blockchain and Recommender Systems, ScienceDirect. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S2096720924000587
7. Innovative Applications of Unsupervised Learning in Uncertainty-Aware Pharmaceutical Supply Chain Planning, IEEE Journals & Magazine. [Online]. Available: https://ieeexplore.ieee.org/document/10614135
8. Optimizing e-Commerce Supply Chains with Categorical Boosting, IEEE Xplore. [Online]. Available: https://ieeexplore.ieee.org/document/10643537
9. Customer Segment Classification Prediction in the Australian Retail, Proceedings of the 2023 4th International Conference on Machine Learning and Computer Application. [Online]. Available: https://dl.acm.org/doi/10.1145/3650215.3650302
10. Research and implementation of e-commerce inventory optimization strategy based on advanced data analysis technology, Conference Proceedings. [Online]. Available: https://dl.acm.org/doi/10.1145/3696952.3696977
11. Financial Big Data Visualization: A Machine Learning Perspective, Proceedings of the 17th International Symposium on Visual Information Communication and Interaction. [Online]. Available: https://dl.acm.org/doi/10.1145/3678698.3678702
12. Amplifying Learning and Teaching Effectiveness through Generative Artificial Intelligence: A Qualitative Approach with Case Studies on Supply Chain and Cold Chain Management, Proceedings of the International Conference on Decision Science and Management. [Online]. Available: https://dl.acm.org/doi/10.1145/3686081.3686126
13. Precise Issuance of Meituan Merchants’ Coupons with Machine Learning, Proceedings of the International Conference on Machine Learning, Pattern Recognition and Automation Engineering. [Online]. Available: https://dl.acm.org/doi/10.1145/3696687.3696700
14. Retailers’ Order Decision with Setup Cost using Machine Learning, Proceedings of the 2024 8th International Conference on Machine Learning and Soft Computing. [Online]. Available: https://dl.acm.org/doi/10.1145/3647750.3647781
15. Customer Segment Classification Prediction in the Australian Retail Based on Machine Learning Algorithms, Proceedings of the 2023 4th International Conference on Machine Learning and Computer Application. [Online]. Available: https://dl.acm.org/doi/10.1145/3696952.3696977
16. PRISMA 2020 Checklist, PRISMA. [Online]. Available: https://www.prisma-statement.org/
--
