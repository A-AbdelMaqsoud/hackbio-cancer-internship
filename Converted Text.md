**From Data to Predictions\
The Fundamentals of Supervised Learning\ <!--[if !supportLineBreakNewLine]-->\ <!--[endif]-->**

One of the main methods for creating predictive models in machine learning is supervised learning, which is categorized alongside unsupervised and reinforcement learning. With this method, algorithms are trained on labeled datasets, in which every data point has a known correlation with an outcome. Through identifying correlations and patterns between the input data and the labels, the algorithm learns to accurately categorize and forecast newly discovered data. This process is similar to a "teacher-student" dynamic in which the algorithm (student) learns from examples provided by the labeled data (teacher).

Building a model that can correctly predict or classify outcomes based on fresh input data is the main goal of supervised learning. Usually, there are two primary tasks associated with this learning method:

<!--[if !supportLists]-->1-     <!--[endif]-->**Classification:** This is the process of forecasting distinct results or groups.

Classification models, for example, can be used in cancer research to differentiate between various tumor types. These models can accurately identify and classify new tumor samples by being trained on large datasets of labeled tumor images, which can help with diagnosis and treatment planning.

<!--[if !supportLists]-->2-     <!--[endif]-->**Regression:** Predicting continuous values is the purpose of this task.&#x20;

Regression models in cancer research can predict the course of the disease by examining ongoing patient data. Understanding illness trends and developing future treatment plans can both benefit from these forecasts.

 

**Key Steps in Supervised Learning**

1-** Data Preparation: **

Data Splitting: Three subsets of the dataset are separated: Training, Validation, and Testing.

<!--[if !supportLists]-->                 ·          <!--[endif]-->**Training:** is applied to develop and improve the model.&#x20;

<!--[if !supportLists]-->                 ·          <!--[endif]-->**Validation:** Assesses performance on an independent dataset to aid in the selection of the optimal model.&#x20;

<!--[if !supportLists]-->                 ·          <!--[endif]-->**Testing:** Evaluate the performance of the model using fresh, untested data.&#x20;

2-** Selecting the Algorithm:** Regression or Classification, the last one separated into:&#x20;

<!--[if !supportLists]-->                 ·          <!--[endif]-->**Binary classification:** is used to describe outcomes that can be divided into two groups, such as "positive" or "negative".&#x20;

<!--[if !supportLists]-->                 ·          <!--[endif]-->**Multiclass classification:** is used for outcomes that have more than two categories, such as categorizing various cancer types.&#x20;

 

 

In cancer research we can implement supervised learning in the following:

<!--[if !supportLists]-->1-     <!--[endif]-->**Early Diagnosis:** This can identify cancer patterns early by evaluating large datasets that contain genetic data, medical histories, and imaging data.

This results in prompt interventions and individualized treatment regimens for each patient.

<!--[if !supportLists]-->2-     <!--[endif]-->**Tumor Classification:** By training on large datasets of labeled tumor images, supervised learning models can reliably classify various tumor types.&#x20;

Oncologists can use this classification to find the best treatment plans for individual tumor types.

A potent technique that greatly improves predicted accuracy in a variety of domains, including cancer research, is supervised learning. Supervised learning uses sophisticated algorithms and vast datasets to improve patient outcomes and enhance the field of oncology by enabling early diagnosis, accurate tumor categorization, and efficient treatment planning

 

**Reference**

<!--[if !supportLists]-->1-     <!--[endif]-->Alpaydin, E. (2020). _Introduction to machine learning_ (4th ed.). MIT Press.

 

<!--[if !supportLists]-->2-     <!--[endif]-->Le Nguyen Quoc Khanh. Associate Professor, Professional Master Program in Artificial Intelligence in Medicine, Taipei Medical University

 

<!--[if !supportLists]-->3-     <!--[endif]-->Azizi, S., Culp, L., Freyberg, J., Mustafa, B., Baur, S., Kornblith, S., Chen, T., Tomasev, N., Mitrović, J., Strachan, P., Mahdavi, S. S., Wulczyn, E., Babenko, B., Walker, M., Loh, A., Chen, P. C., Liu, Y., Bavishi, P., McKinney, S. M., Winkens, J., … Natarajan, V. (2023). Robust and data-efficient generalization of self-supervised machine learning for diagnostic imaging. _Nature biomedical engineering_, _7_(6), 756–779. <https://doi.org/10.1038/s41551-023-01049-7>
