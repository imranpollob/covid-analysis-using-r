## COVID data analysis using R

We will use kaggle dataset to analyze

- Whether or not COVID has more effect on older people
- Whether or not COVID has more effect on specific gender.

### Install packages

In terminal run

```bash
install.packages("Hmisc")
```

### Working process

- Collect data
- Clear data
- Analyze age hypothesis
- Analyze gender hypothesis

### Result

#### Age hypothesis

Idealy, f p-value < 0.05, we reject null hypothesis. Here, p-value ~ 0, so, we reject the null hypothesis and conclude that this is statistically significant.

#### Gender hypothesis

Here we found that, men have from 0.8% to 8.8% higher chance of dying. `p-value = 0.002 < 0.05`, so this is statistically significant
