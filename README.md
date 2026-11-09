# Market Research — UC3M

Coursework for **Investigación de Mercados** (Market Research), Dual Degree in Computer Science & Business Administration, Universidad Carlos III de Madrid, 2025–26.

Most of the course is one end-to-end study. We asked whether **NVIDIA should launch a "Pure Gaming" GPU line**: graphics cards built only for gaming performance, without the AI features that have pushed prices up in recent generations. We went from framing the problem to designing a survey, collecting data and analysing it in SPSS, and finished with a recommendation to management. Exercises 5 and 6 apply the same multivariate techniques to a larger social-media dataset.

## Contents

| # | File | Topic | Methods |
|---|---|---|---|
| 1 | `Ej.1-Correlacion-Causalidad.pdf` | Correlation vs. causation | Critical reading of evidence |
| 2 | `Ej.2-Problema-Marketing-NVIDIA.pdf` | NVIDIA's shift from gaming to AI: framing the marketing problem | Industry and competitor analysis, SWOT, research objectives |
| 3 | `Ej.3-Cuestionario-Codificacion-SPSS.pdf` | Survey design for PC gamers | Six-block questionnaire, pre-test, SPSS coding |
| 4 | `Ej.4-Analisis-Descriptivo-Bivariante-NVIDIA.pdf` | Who the respondents are and what drives willingness to pay | Univariate statistics, chi-square, ANOVA, correlation |
| 5 | `Ej.5-Regresion-Satisfaccion-Redes-Sociales.pdf` | What drives satisfaction with social networks (n ≈ 700) | Multiple linear regression, collinearity diagnostics, ANOVA |
| 6 | `Ej.6-Analisis-Factorial-Posicionamiento-Facebook.pdf` | Facebook's perceived positioning vs. competitors (n = 569) | Principal component factor analysis, KMO/Bartlett, perceptual map |
| Final | `Ej.7-Informe-Final-NVIDIA-Pure-Gaming.pdf` | Full research report and recommendation to NVIDIA | All of the above, plus price-sensitivity regression |

## Key findings

**NVIDIA "Pure Gaming"**
- Price matters most to this market. 52% of respondents said price is the deciding factor when buying a GPU, and the average maximum they would pay was about €479.
- Our first price model reached R² ≈ 0.9, but that came from overfitting a small sample. We reduced dimensionality (for example, by merging six usage variables into one ordinal "usage profile") to get a model that actually explains something.
- **Recommendation:** go ahead with "Pure Gaming", but in stages. Launch one or two pilot models in the mid / upper-mid range, measure cannibalisation of the premium lines, and adjust pricing before scaling up.

**Social networks**
- The strongest drivers of satisfaction are information credibility, variety of apps and design. Control and security features matter less.
- Facebook's positioning comes down to two factors, *perceived control* and *commercial ecosystem*, which together explain 60% of the variance. Its ad-funded model puts these two in direct conflict. Subscription or marketplace models are ways to reposition it.

## Limitations

The NVIDIA study is a convenience sample of 25 PC gamers in Spain. Its multivariate results are exploratory, not conclusive. The reports discuss this in detail.

## Tools

IBM SPSS · Excel · Microsoft Word

## Team

Alejandro de Santos Lobo · Alejandro Pérez Montes · **Lucas Ruiz Gómez** · Daniel Robles Ruiz · Roberto Sanz Gamero

*Reports are written in Spanish.*
