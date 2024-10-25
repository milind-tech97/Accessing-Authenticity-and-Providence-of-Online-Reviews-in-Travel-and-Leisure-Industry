# Overview:
During my Master's Thesis I have conducted study to investigate the ability to detect fake reviews generated using OpenAI’s ChatGPT 4.0, compared to authentic reviews in the travel and leisure sector, focusing on data from TripAdvisor. With the rise of AI-generated content, there is a growing concern over misleading information that can damage consumer trust and affect business reputation.

# Methodology and Key Findings:

# 1. Data Collection:
**Authentic reviews (380) were collected manually from TripAdvisor for Red Dragon Holidays.**
**AI-generated reviews (380) were created using ChatGPT 4.0, ensuring diversity and avoiding duplication.**

# 2. Sentiment Analysis and NLP:
**Tools like VADER and TextBlob were applied to evaluate emotional content in both authentic and AI-generated reviews.**
**Statistical analysis, including t-tests, showed significant differences in sentiment patterns between authentic and fake reviews.**

# 3. Machine Learning Models:
**Supervised algorithms, including Logistic Regression, Decision Tree, SVM, and Naive Bayes, were employed.**
**The Decision Tree model outperformed others, achieving an accuracy of 92%.**

# 4. Deployment:
**A prototype interface using Gradio was developed, allowing users to input reviews and receive predictions on their authenticity.**

# Conclusions:
The study demonstrates that machine learning algorithms can effectively distinguish AI-generated reviews from genuine ones. The project highlights the importance of integrating such systems into online platforms to maintain authenticity. Despite the small dataset, results are promising, and future work may include scaling the dataset and refining models to improve reliability further.

# Ethical Considerations:
All collected data was used exclusively for research, with no personal data being compromised. AI-generated reviews were not posted publicly to ensure compliance with ethical standards.
