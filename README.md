# Probability-Statistics
### What is a Non-Parametric Test?

A non-parametric test is a type of statistical test that does not assume a specific distribution for the data. These tests are used when you cannot assume that the data follows a normal distribution. They are often used with small sample sizes, ordinal data, or non-continuous data.

### Types of Non-Parametric Tests

Here are some common types of non-parametric tests:

1. **Chi-Square Test**: 
   - Used to compare observed frequencies with expected frequencies.
   - Example: Testing if a die is fair by comparing the frequency of each outcome (1 through 6) with the expected frequency (each should appear about the same number of times).

2. **Mann-Whitney U Test**:
   - Compares differences between two independent groups.
   - Example: Comparing the test scores of two different classes to see if there is a significant difference.

3. **Wilcoxon Signed-Rank Test**:
   - Compares differences between two related groups.
   - Example: Comparing the weights of patients before and after a diet program.

4. **Kruskal-Wallis Test**:
   - Compares differences between three or more independent groups.
   - Example: Comparing customer satisfaction scores across different stores.

5. **Spearman’s Rank Correlation**:
   - Measures the strength and direction of association between two ranked variables.
   - Example: Determining if there is a relationship between the rank of students' math scores and their science scores.

6. **Friedman Test**:
   - Compares differences between three or more related groups.
   - Example: Comparing the performance of students in different subjects over time.

### References

For a better understanding, you can watch the following videos:

1. [Non-Parametric Tests - When and Why to Use Them](https://www.youtube.com/watch?v=faLzK5Vo27M)
2. [Chi-Square Test Explained](https://www.youtube.com/watch?v=WXPBoFDqNVk)
3. [Mann-Whitney U Test Explained](https://www.youtube.com/watch?v=UibcVt8QTIc)
4. [Wilcoxon Signed-Rank Test Explained](https://www.youtube.com/watch?v=lzD5exPJh0c)
5. [Kruskal-Wallis Test Explained](https://www.youtube.com/watch?v=2VR-YMFPQYg)

These resources should help clarify the concepts and applications of non-parametric tests.



---

<img src="2A.jpg" width="100%" alt="Q2 A">

### Given Data
- **Group 1 (Medicine A)**: 43, 39, 49, 62, 42 kg
- **Group 2 (Medicine B)**: 39, 41, 47, 66, 48 kg

### Step-by-Step Process

#### 1. Calculate Means
\[
\bar{X}_1 = \frac{43 + 39 + 49 + 62 + 42}{5} = 47
\]
\[
\bar{X}_2 = \frac{39 + 41 + 47 + 66 + 48}{5} = 48.2
\]

#### 2. Calculate Variances
\[
S_1^2 = \frac{(43-47)^2 + (39-47)^2 + (49-47)^2 + (62-47)^2 + (42-47)^2}{4} = 83.5
\]
\[
S_2^2 = \frac{(39-48.2)^2 + (41-48.2)^2 + (47-48.2)^2 + (66-48.2)^2 + (48-48.2)^2}{4} = 114.05
\]

#### 3. Calculate Standard Deviations
\[
S_1 = \sqrt{83.5} \approx 9.14
\]
\[
S_2 = \sqrt{114.05} \approx 10.68
\]

#### 4. Calculate Standard Error (SE)
\[
SE = \sqrt{\frac{S_1^2}{n_1} + \frac{S_2^2}{n_2}} = \sqrt{\frac{83.5}{5} + \frac{114.05}{5}} = \sqrt{39.51} \approx 6.29
\]

#### 5. Calculate t-statistic
\[
t = \frac{\bar{X}_1 - \bar{X}_2}{SE} = \frac{47 - 48.2}{6.29} \approx \frac{-1.2}{6.29} \approx -0.19
\]

#### 6. Degrees of Freedom
\[
df = n_1 + n_2 - 2 = 5 + 5 - 2 = 8
\]

#### 7. Critical Value
From the given table, the critical value of t at the 5% significance level for \(df = 8\) is \(2.31\).

### Decision
- If \(|t| > t_{\text{critical}}\), reject the null hypothesis.
- Here, \(|-0.19| \approx 0.19\), which is less than \(2.31\).

### Conclusion
Since \(|t| < t_{\text{critical}}\), we do not reject the null hypothesis. This means there is no significant difference between the effects of the two medicines on weight.

### Reference Video Links

- [Khan Academy - Hypothesis Testing](https://www.khanacademy.org/math/statistics-probability)
- [YouTube - T-test Explained](https://www.youtube.com/watch?v=0zZYBALbZgg)

This explanation should clarify the process in simple terms.
