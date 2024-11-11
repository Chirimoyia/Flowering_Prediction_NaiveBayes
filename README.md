# Flowering_Prediction_NaiveBayes
Classification problem of flowering type based on plant genotype using Naive Bayes.

This exercise belongs to the course "Machine Learning" from the MSc Bioinformatics and Biostatistics program (Universitat Oberta de Catalunya, UOC).

## Data set
Dataset describes the genotype of 697 plants and their flowering time in days.
- genotype.csv: genotype of each plant (697 x 149) with three posible values: 0 (homozygous dominant), 1 (heterozygous), 2 (heterozygous recessive).
- flowering_time.csv: time to flowering in days (697 x 1).

## Objective
Predict type of flowering (slow or fast) based on genotype.

## Notes
- Fast flowering (flowering time <= 40 days, 0); quick flowering (flowering time > 40, 1).
- Training and test datasets divided from original dataset 2/3 and 1/3 (seed 12345).
- Performance evaluation via confusionMatrix(). Positive cateogory = slow flowering.
- Naive Bayes algorithm (laplace = 0 and 1).
