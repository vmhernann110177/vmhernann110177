# <u>Applied AI & Data Science</u>

## Victor Miguel Hernández Maldonado

**From Research to Real-World Solutions**  
*De la investigación a las soluciones del mundo real*

**Scientific Research · Interpretable Machine Learning · Computer Vision · Statistical Analytics · Software Development**

**Investigación científica · Aprendizaje automático interpretable · Visión por computadora · Análisis estadístico · Desarrollo de software**

---

Welcome to my professional portfolio, featuring applied research and projects in Data Science, Artificial Intelligence, Machine Learning, and Software Development.

My work connects scientific methodology, statistical analysis, predictive modeling, and practical solutions to real-world problems.

**Bienvenido a mi portafolio profesional**, donde presento investigaciones y proyectos aplicados en Ciencia de Datos, Inteligencia Artificial, Aprendizaje Automático y Desarrollo de Software.

Mi trabajo integra la metodología científica, el análisis estadístico, el modelado predictivo y el desarrollo de soluciones prácticas para abordar problemas del mundo real.

---

## <u>Explore My Work | Explora mis proyectos</u>

[Scientific Research](#scientific-research--investigación-científica) ·
[Computer Vision](#computer-vision--visión-por-computadora) ·
[Deep Learning](#deep-learning--aprendizaje-profundo) ·
[Applied Data Science](#applied-data-science--ciencia-de-datos-aplicada) ·
[Business Statistics](#business-statistics--estadística-empresarial) ·
[Software Development](#software-development--desarrollo-de-software)

---

## Featured Projects | Proyectos destacados

| Project / Proyecto | Focus / Especialidad | Highlight / Resultado destacado |
|---|---|---|
| **Hospitalization Risk Stratification** | Interpretable Machine Learning · Scientific Research | Peer-reviewed publication (2026). Random Forest: 79.5% accuracy; 71.9% recall. [Publication](https://doi.org/10.35429/JOHS.2026.13.32.1.1.11) |
| **NutriScan — Food Recognition** | Computer Vision · MobileNetV2 · Transfer Learning | 17 food categories; approximately 65% validation accuracy in recorded fine-tuning experiments. |
| **Video Game Market Analysis** | Data Analytics · Statistical Testing · Business Intelligence | Regional market analysis and evidence-based recommendations for advertising strategy. |
| **Interactive Used-Vehicle Dashboard** | Python · Streamlit · Plotly · Software Development | Functional web application deployed on Render. [Live Demo](https://tripleten-s7-c7-vehicles-dashboard.onrender.com) |

---

## Projects & Scientific Publications | Proyectos y publicaciones científicas

### <u>Scientific Research | Investigación científica</u>

#### Hospitalization Risk Stratification in Mexican Respiratory Surveillance Data

**Applied Research · Interpretable Machine Learning · Public Health Analytics**

**Research objective | Objetivo:** Identify factors associated with hospitalization in Mexican respiratory surveillance data and evaluate interpretable machine learning models.

**Methodology | Metodología:** Exploratory data analysis, statistical testing, logistic regression, classification-threshold optimization, and Random Forest.

**Key results | Resultados principales:**
- Analyzed 219,023 surveillance records; 218,557 were retained after preprocessing.
- Logistic regression recall increased from 55.3% to 71.1% after threshold adjustment.
- Random Forest achieved 79.5% accuracy, 71.9% recall, and a 76.9% F1-score.
- Pneumonia showed the strongest association with hospitalization among the selected predictors.

**Scientific publication | Publicación científica:**

Hernández-Maldonado, V. M. (2026). *Hospitalization risk stratification in Mexican respiratory surveillance data: a retrospective analysis with interpretable machine learning*. Journal of Health Sciences, 13(32), 1–11.

**DOI:** https://doi.org/10.35429/JOHS.2026.13.32.1.1.11

**Source code and reproducibility | Código y reproducibilidad:**

https://github.com/vmhernann110177/interpretable-machine-learning-hospitalization-risk-mexico

---

**EXPLORE / EXPLORAR:**  
[Scientific Research](#scientific-research--investigación-científica) · [Computer Vision](#computer-vision--visión-por-computadora) · [Deep Learning](#deep-learning--aprendizaje-profundo) · [Applied Data Science](#applied-data-science--ciencia-de-datos-aplicada) · [Business Statistics](#business-statistics--estadística-empresarial) · [Software Development](#software-development--desarrollo-de-software)  

[↑ Index / Índice](#explore-my-work--explora-mis-proyectos) · [⌂ Start / Inicio](#applied-ai--data-science)

### <u>Computer Vision | Visión por computadora</u>

#### NutriScan — Food Recognition Using MobileNetV2

**Computer Vision · Deep Learning · Transfer Learning · TensorFlow/Keras · OpenCV**

**Objective | Objetivo:** Develop an AI-based food image classification pipeline using a pretrained convolutional neural network.

**Methodology | Metodología:**
- Explored and preprocessed 16,256 food images across 17 categories.
- Applied image processing and heuristic cropping to prepare food regions for classification.
- Implemented MobileNetV2 with ImageNet pretrained weights and a custom classification head.
- Evaluated progressive fine-tuning strategies and inspected model predictions.

**Key results | Resultados principales:**
- Training dataset: 13,004 images.
- Evaluation dataset: 3,252 images.
- Validation accuracy reached approximately 65% during fine-tuning.
- Identified classification challenges involving visually similar food categories.

**Scope | Alcance:** Experimental food image classification prototype. Nutritional estimation, personalized recommendations, and production deployment remain future development objectives.

**Project notebook | Notebook del proyecto:** [View NutriScan on GitHub](https://github.com/vmhernann110177/nutriscan-food-recognition-mobilenetv2)


#### Cats vs Dogs — Convolutional Neural Network

**Computer Vision · Deep Learning · CNN Architecture · TensorFlow/Keras · Experimental Evaluation**

**Objective | Objetivo:** Design, train, and evaluate a convolutional neural network for binary image classification, distinguishing cats from dogs.

**Methodology | Metodología:**
- Worked with 697 labeled images across two classes.
- Built a custom CNN with three convolutional layers, pooling, global average pooling, dropout, and softmax classification.
- Applied image resizing, normalization, and training-data augmentation.
- Conducted comparative experiments involving batch size, image resolution, training epochs, activation functions, dropout, optimizers, and loss functions.

**Key results | Resultados principales:**
- Baseline CNN: 93,506 trainable parameters.
- Baseline validation accuracy: 59.71% after five epochs.
- Increasing dropout from 0.25 to 0.50 produced 62.50% validation accuracy in the recorded experiment.
- Experimental comparisons highlighted the sensitivity of model performance to regularization, input resolution, and optimization settings.

**Limitations | Limitaciones:** Results come from a small educational dataset. The validation/test partitioning requires additional verification before making stronger generalization claims.

**Project notebook | Notebook del proyecto:** [View Cats vs Dogs on GitHub](https://github.com/vmhernann110177/cats-vs-dogs-cnn)

---

**EXPLORE / EXPLORAR:**  
[Scientific Research](#scientific-research--investigación-científica) · [Computer Vision](#computer-vision--visión-por-computadora) · [Deep Learning](#deep-learning--aprendizaje-profundo) · [Applied Data Science](#applied-data-science--ciencia-de-datos-aplicada) · [Business Statistics](#business-statistics--estadística-empresarial) · [Software Development](#software-development--desarrollo-de-software)  

[↑ Index / Índice](#explore-my-work--explora-mis-proyectos) · [⌂ Start / Inicio](#applied-ai--data-science)

### <u>Deep Learning | Aprendizaje profundo</u>

#### Deep Learning Fundamentals — Heart Disease Prediction

**Neural Networks · NumPy · TensorFlow/Keras · Backpropagation · Hyperparameter Optimization**

**Objective | Objetivo:** Implement and compare neural networks for binary classification using a heart disease dataset, examining the mathematical foundations of deep learning and the impact of optimization strategies.

**Methodology | Metodología:**
- Explored 1,025 records containing clinical and demographic variables.
- Performed exploratory data analysis, categorical encoding, and feature scaling.
- Created stratified training, validation, and test partitions (60/20/20).
- Implemented a feed-forward neural network from scratch using NumPy, including forward propagation, binary cross-entropy, backpropagation, and gradient descent.
- Recreated the baseline architecture using TensorFlow/Keras.
- Compared four hyperparameter configurations using ReLU activation and the Adam optimizer.

**Key results | Resultados principales:**
- NumPy baseline validation accuracy: 86.83%.
- Equivalent Keras baseline validation accuracy: 86.83%.
- Best recorded validation AUC: 0.9827 (20 hidden neurons; learning rate 0.01).
- Demonstrated the effects of activation functions, optimization algorithms, and learning rates on model performance.

**Limitations | Limitaciones:** Educational case study. Potential duplicate-record effects and generalization performance require additional verification. Results should not be interpreted as evidence of clinical readiness.

**Project notebook | Notebook del proyecto:** [View Deep Learning Fundamentals on GitHub](https://github.com/vmhernann110177/deep-learning-fundamentals)

---

**EXPLORE / EXPLORAR:**  
[Scientific Research](#scientific-research--investigación-científica) · [Computer Vision](#computer-vision--visión-por-computadora) · [Deep Learning](#deep-learning--aprendizaje-profundo) · [Applied Data Science](#applied-data-science--ciencia-de-datos-aplicada) · [Business Statistics](#business-statistics--estadística-empresarial) · [Software Development](#software-development--desarrollo-de-software)  

[↑ Index / Índice](#explore-my-work--explora-mis-proyectos) · [⌂ Start / Inicio](#applied-ai--data-science)

### <u>Applied Data Science | Ciencia de datos aplicada</u>

#### Video Game Market Analysis — Ice | Tripleten Sprint 6

**Data Analytics · Python · pandas · NumPy · Matplotlib · SciPy · Statistical Hypothesis Testing**

**Objective | Objetivo:** Analyze historical video game sales to identify commercially promising platforms, genres, and regional markets for an online retailer's 2017 advertising strategy.

**Methodology | Metodología:**
- Explored and cleaned an original dataset of 16,715 video game records.
- Examined missing values, data types, release years, regional sales, user scores, critic reviews, and ESRB ratings.
- Selected 2011–2016 as the relevant market-analysis period.
- Analyzed platform life cycles, global sales distributions, genres, and regional market profiles.
- Evaluated correlations between reviews and sales.
- Applied Welch's two-sample t-tests to compare user ratings across platforms and genres.

**Key findings | Hallazgos principales:**
- Identified PS4 as the strongest platform candidate for the 2017 campaign, with Xbox One as another relevant option.
- Found substantial regional differences: Action and Shooter led sales in North America and Europe, while Role-Playing ranked first in Japan.
- The five leading platforms represented 81.89% of North American sales, 80.51% of European sales, and 86.25% of Japanese sales during 2011–2016.
- For PS4, critic scores showed a moderate positive correlation with sales (Pearson r ≈ 0.41), while user scores showed almost no linear correlation (r ≈ -0.03).
- Welch's t-test identified a statistically significant difference in average user ratings between Xbox One and PC (p ≈ 4.54e-6).
- No statistically significant difference was established between Action and Sports user ratings at the 5% significance level (p ≈ 0.0737).

**Business outcome | Resultado empresarial:** Developed evidence-based recommendations for platform prioritization and region-specific advertising, emphasizing the importance of the game itself rather than relying exclusively on platform popularity.

**Limitations | Limitaciones:** Historical observational analysis; 2016 records may be incomplete. Statistical associations do not establish causality. Hypothesis tests used the broader cleaned dataset.

**Project notebook | Notebook del proyecto:** [View Video Game Market Analysis on GitHub](https://github.com/vmhernann110177/videogames-market-analysis)

#### Megaline — Telecom Revenue Optimization | Tripleten Sprint 5

**Business Analytics · Python · pandas · NumPy · Matplotlib · SciPy · Statistical Hypothesis Testing**

**Objective | Objetivo:** Compare the revenue performance of Megaline's Surf and Ultimate prepaid mobile plans to inform advertising budget allocation.

**Methodology | Metodología:**
- Analyzed 2018 usage data covering 500 telecom customers.
- Integrated customer profiles, calls, text messages, internet sessions, and pricing plans.
- Cleaned and transformed records, applying the company's billing and rounding rules.
- Aggregated usage and calculated monthly revenue for each customer.
- Compared calling behavior, messaging activity, internet consumption, and revenue distributions.
- Applied two-sided Welch's t-tests to compare average monthly revenue between plans and geographic regions.
- Used one average monthly revenue observation per customer in hypothesis testing to avoid pseudoreplication.

**Key findings | Hallazgos principales:**
- The statistical analysis included 490 customers with recorded usage: 333 on Surf and 157 on Ultimate.
- Average monthly revenue per customer was $71.82 for Ultimate and $58.19 for Surf, a difference of $13.63 USD.
- The revenue difference between plans was statistically significant (p ≈ 5.72e-8).
- No statistically significant revenue difference was established between New York–New Jersey customers and customers in other regions (p ≈ 0.4410).
- Internet usage exceeded the plan allowance in 57.91% of Surf user-month records, compared with 5.69% for Ultimate.

**Business outcome | Resultado empresarial:** Identified Ultimate as the higher-revenue plan on a per-customer monthly basis, providing evidence for marketing decisions while highlighting the importance of overage charges in Surf's revenue structure.

**Limitations | Limitaciones:** Observational analysis of 2018 customer records. Higher revenue does not necessarily imply higher profitability because operating, acquisition, and retention costs were unavailable. Statistical results do not establish causality.

**Project notebook | Notebook del proyecto:** [View Megaline on GitHub](https://github.com/vmhernann110177/megaline-telecom-revenue-analysis)

#### Instacart — Grocery Shopping Behavior & Data Cleaning | Tripleten Sprint 4

**Data Cleaning · Data Wrangling · Python · pandas · Matplotlib · Exploratory Data Analysis · Consumer Analytics**

**Objective | Objetivo:** Clean and analyze grocery-order data to identify purchasing patterns, product popularity, reorder behavior, and opportunities for customer segmentation.

**Methodology | Metodología:**
- Examined five related datasets covering orders, products, aisles, departments, and order-product relationships.
- Analyzed 478,967 original order records and 4,545,007 order-product records.
- Identified duplicate records, missing values, data-type inconsistencies, and potential data-integrity issues.
- Removed 15 exact duplicate order records and addressed 1,258 missing product names.
- Investigated 836 missing cart-position values and documented the preprocessing decisions.
- Explored order frequency by hour and weekday, reorder intervals, basket sizes, and popular products.
- Calculated product-level reorder rates and customer-level repeat-purchasing indicators.

**Key findings | Hallazgos principales:**
- Order activity was concentrated between 10:00 and 16:00, with Sundays and Mondays showing particularly high activity.
- The typical order contained 8 products (median), compared with an average of approximately 10.1.
- Weekly purchasing patterns were visible, including a pronounced reorder interval around seven days.
- Bananas and other fresh grocery products ranked prominently among frequently purchased and reordered items.
- Banana was the first item added to the cart in 15,562 recorded orders.
- Reorder rates must be interpreted alongside purchase volume to avoid overstating customer loyalty based on small samples.

**Analytical outcome | Resultado analítico:** Developed interpretable purchasing-behavior indicators that could support inventory planning, product discovery, and customer segmentation.

**Limitations | Limitaciones:** Educational dataset modified from original Instacart records. Findings are descriptive; proposed business applications were not experimentally validated or deployed.

**Project notebook | Notebook del proyecto:** [View Instacart on GitHub](https://github.com/vmhernann110177/instacart-data-cleaning-analysis)

---

**EXPLORE / EXPLORAR:**  
[Scientific Research](#scientific-research--investigación-científica) · [Computer Vision](#computer-vision--visión-por-computadora) · [Deep Learning](#deep-learning--aprendizaje-profundo) · [Applied Data Science](#applied-data-science--ciencia-de-datos-aplicada) · [Business Statistics](#business-statistics--estadística-empresarial) · [Software Development](#software-development--desarrollo-de-software)  

[↑ Index / Índice](#explore-my-work--explora-mis-proyectos) · [⌂ Start / Inicio](#applied-ai--data-science)

### <u>Business Statistics | Estadística empresarial</u>

#### Business Statistics — Probability Distributions & Statistical Foundations

**Probability Theory · Binomial Distribution · Normal Distribution · Statistical Standardization · Python · NumPy · SciPy · Matplotlib**

**Objective | Objetivo:** Apply fundamental probability and statistical concepts to practical scenarios involving customer purchases, standardized examination scores, and probability-based decision-making.

**Methodology | Metodología:**
- Modeled customer purchasing outcomes using the binomial distribution.
- Calculated exact and cumulative probabilities using probability mass and cumulative distribution functions.
- Explored the effects of changing success probabilities on distribution shapes.
- Analyzed a sample of 1,000 SAT examination scores through descriptive statistics and a fitted normal distribution.
- Computed probability thresholds, percentiles, and standardized Z-scores.
- Visualized probability distributions and cumulative probability regions using Python.

**Selected results | Resultados seleccionados:**
- Under a binomial model with 10 visitors and an 80% purchase probability, the probability of all 10 purchasing was 10.74%.
- The probability of at most 7 purchases was 32.22%.
- The SAT exercise produced a mean score of 1,007.46 and a standard deviation of 204.43.
- Demonstrated percentile-based calculations and standardized comparisons between SAT and ACT scores.

**Learning outcome | Resultado académico:** Strengthened practical understanding of probability modeling, distribution functions, statistical visualization, and standardized comparisons.

**Scope | Alcance:** Guided educational exercises illustrating statistical concepts rather than an independently conducted research study.

**Project notebook | Notebook del proyecto:** [View Business Statistics on GitHub](https://github.com/vmhernann110177/business-statistics-foundations)

---

**EXPLORE / EXPLORAR:**  
[Scientific Research](#scientific-research--investigación-científica) · [Computer Vision](#computer-vision--visión-por-computadora) · [Deep Learning](#deep-learning--aprendizaje-profundo) · [Applied Data Science](#applied-data-science--ciencia-de-datos-aplicada) · [Business Statistics](#business-statistics--estadística-empresarial) · [Software Development](#software-development--desarrollo-de-software)  

[↑ Index / Índice](#explore-my-work--explora-mis-proyectos) · [⌂ Start / Inicio](#applied-ai--data-science)

### <u>Software Development | Desarrollo de software</u>

#### Interactive Used-Vehicle Dashboard | Panel interactivo de vehículos usados

**Python · pandas · Plotly · Streamlit · GitHub · Render**

**Objective | Objetivo:** Develop and deploy an interactive web application for exploring used-vehicle advertisements and supporting consumer searches.

**Key features | Funcionalidades:**
- Interactive histogram of vehicle mileage.
- Scatter plot comparing mileage and advertised prices.
- Stacked bar chart of vehicle types by manufacturer.
- Interactive price-distribution comparisons between manufacturers.
- Vehicle search with customizable price and mileage limits, plus ranking preferences.

**Outcome | Resultado:** Developed and deployed a functional web application, successfully reviewed and approved as the Tripleten Sprint 7 project.

**Live application | Aplicación web:**

https://tripleten-s7-c7-vehicles-dashboard.onrender.com

**Source code | Código fuente:**

https://github.com/vmhernann110177/tripleten-s7-c7-vehicles-dashboard

---

**EXPLORE / EXPLORAR:**  
[Scientific Research](#scientific-research--investigación-científica) · [Computer Vision](#computer-vision--visión-por-computadora) · [Deep Learning](#deep-learning--aprendizaje-profundo) · [Applied Data Science](#applied-data-science--ciencia-de-datos-aplicada) · [Business Statistics](#business-statistics--estadística-empresarial) · [Software Development](#software-development--desarrollo-de-software)  

[↑ Index / Índice](#explore-my-work--explora-mis-proyectos) · [⌂ Start / Inicio](#applied-ai--data-science)

