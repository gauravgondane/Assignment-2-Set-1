# Descriptive Statistics and Probability Assignment

## 	Look at the data given below. Plot the data, find the outliers and find out  μ,σ,σ^2

| Company         | Measure X |
|-----------------|------------|
| Allied Signal   | 24.23%     |
| Bankers Trust   | 25.53%     |
| General Mills   | 25.41%     |
| ITT Industries  | 24.14%     |
| J.P. Morgan & Co. | 29.62%  |
| Lehman Brothers | 28.25%     |
| Marriott        | 25.81%     |
| MCI             | 24.39%     |
| Merrill Lynch   | 40.26%     |
| Microsoft       | 32.95%     |
| Morgan Stanley  | 91.36%     |
| Sun Microsystems | 25.99%    |
| Travelers       | 39.42%     |
| US Airways      | 26.71%     |
| Warner-Lambert  | 35.00%     |

### Analysis

1. **Look at the data given below. Plot the data, find the outliers and find out μ, σ, σ²**
   - Mean (μ)
   - Standard Deviation (σ)
   - Variance (σ²)

### Box-Plot Analysis

Answer the following three questions based on the box-plot above:

1. **What is the inter-quartile range of this dataset? (please approximate the numbers) In one line, explain what this value implies.**
   - Approximately (First Quantile Range) Q1 = 5
   - (Third Quantile Range) Q3 = 12
   - Median (Second Quartile Range) = 7
   - Inter-Quartile Range (IQR) = Q3 – Q1 = 12 – 5 = 7
   - **Interpretation**: The IQR indicates the range within which the central 50% of the data lies.

2. **What can we say about the skewness of this dataset?**
   - The dataset is right-skewed (median is towards the left side).

3. **If it was found that the data point with the value 25 is actually 2.5, how would the new box-plot be affected?**
   - Changing the value 25 to 2.5 removes the outliers and reduces the positive skewness, leading to a more normally distributed dataset.

### Histogram Analysis

Answer the following three questions based on the histogram above:

1. **Where would the mode of this dataset lie?**
   - The mode lies between 5 to 10 (approximately between 4 to 8).

2. **Comment on the skewness of the dataset.**
   - The dataset is right-skewed (Mean > Median > Mode).

3. **Suppose that the above histogram and the box-plot in question 2 are plotted for the same dataset. Explain how these graphs complement each other in providing information about any dataset.**
   - The box-plot and histogram together show the right-skewness and outliers, with the median easily visualized in the box-plot and the mode in the histogram.

### Probability Analysis

**Scenario**: Probability of Misdirected Calls

4. **AT&T was running commercials in 1990 aimed at luring back customers who had switched to one of the other long-distance phone service providers. One such commercial shows a businessman trying to reach Phoenix and mistakenly getting Fiji, where a half-naked native on a beach responds incomprehensibly in Polynesian. When asked about this advertisement, AT&T admitted that the portrayed incident did not actually take place but added that this was an enactment of something that “could happen.” Suppose that one in 200 long-distance telephone calls is misdirected. What is the probability that at least one in five attempted telephone calls reaches the wrong number? (Assume independence of attempts.**

- Probability of a call being misdirected = 1/200
- Probability of a call not being misdirected = 199/200
- Number of calls (n) = 5

\[ P(x) = \binom{n}{x} p^x q^{n-x} \]

For at least one misdirected call:

\[ P(1) = \binom{5}{1} \left(\frac{1}{200}\right)^1 \left(\frac{199}{200}\right)^4 \approx 0.0245 \]

5. **5.	Returns on a certain business venture, to the nearest $1,000, are known to follow the following probability distribution.**
| Return (x) | Probability (P(x)) |
|------------|---------------------|
| -2000      | 0.1                 |
| -1000      | 0.1                 |
| 0          | 0.2                 |
| 1000       | 0.2                 |
| 2000       | 0.3                 |
| 3000       | 0.1                 |

1. **Expected Return (E(X))**

\[ E(X) = (-2000 \times 0.1) + (-1000 \times 0.1) + (0 \times 0.2) + (1000 \times 0.2) + (2000 \times 0.3) + (3000 \times 0.1) = 600$ \]

   **Interpretation**: The expected return on the business venture is $600.

2. **What is the most likely monetary outcome of the business venture?**
   - The most likely outcome is $2000, with the highest probability of 0.3.

3. **Is the venture likely to be successful? Explain**
   - Probability of making a profit (P(x > 0)): \(0.2 + 0.2 + 0.3 + 0.1 = 0.8\)
   - There is an 80% chance of making a profit, indicating a high likelihood of success.

4. **What is the long-term average earning of business ventures of this kind? Explain**
   - The long-term average is the expected value, which is $600.

5. **What is the good measure of the risk involved in a venture of this kind? Compute this measure**
   - Variance (Var(X)) = \(E(X^2) - (E(X))^2 = 2800000 - 600^2 = 2160000\)
   - Higher variance indicates higher risk.

## Conclusion

This assignment demonstrates the application of descriptive statistics and probability in analyzing datasets and making informed predictions about business ventures. The combined use of box-plots, histograms, and probability calculations provides a comprehensive understanding of data distribution, skewness, and risk.
