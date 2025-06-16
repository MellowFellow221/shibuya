---
alias:
  - Depreciation
date created: Tuesday, March 11th 2025, 12:36:06 pm
date modified: Friday, June 13th 2025, 7:30:52 pm
---

# Compound Interest and Depreciation
Interest: $Fv=Pv(1+\dfrac{r}{n})^{nt}$
Depreciation: $Fv=Pv(1-\dfrac{r}{n})^{nt}$
$Fv$ = future value, the final amount you have (includes interest).
$Pv$ = principle value, the starting balance.
$r$ = rate, the interest rate as a decimal.
$n$ = number of cycles, how many times interest occurs per year.
$t$ = time in years.

> [!NOTE] Depreciation
> Depreciation functions in the same way but with $1-\dfrac{r}{n}$ instead which takes away the value instead of adding it. All interest formulas work the exact same with depreciation with the small substitution.

## Derivation
By rearranging the original formula we can derive other variables.
- Find the **Future Value** when we know a Principle Value, the Interest Rate and number of Periods.
$$
\Large
Fv=Pv\left( 1+\frac{r}{n} \right)^{nt}
$$
- Find the **Principle Value** when we know a Final Value, the Interest Rate and number of Periods.
$$
\Large
Pv=\frac{Fv}{\left( 1+\frac{r}{n} \right)^{nt} }
$$
- Find the **Interest Rate** when we know the Principle Value, Future Value and number of Periods.
$$
\Large
r=n\left[ \left( \frac{Fv}{Pv} \right) ^\frac{1}{nt} -1 \right]
$$
- Find the number of **Periods** when we know the Principle Value, Future Value and Interest Rate
$$
\Large
n=\frac{\ln\left( \frac{Fv}{Pv} \right)}{\ln \left( 1+r \right)}
$$
# Example Questions
1. Luke puts $\$1,000$ in an account that pays an annual interest of $9\%$. What will be the value of the account after (a) 10 years? (b) 20 years?
   a.
$$
\begin{aligned}
Fv = Pv(1+\frac{r}{n})^{nt} \\
Fv = $1000(1+\frac{0.09}{1})^{1(10)} \\
Fv = $1000(1.09)^{10} \\
Fv = $2367.37
\end{aligned}
$$

   b.

$$
\begin{aligned}
Fv = Pv(1+\frac{r}{n})^{nt} \\
Fv = $1000(1+\frac{0.09}{1})^{1(20)} \\
Fv = $1000(1.09)^{20} \\
Fv = $5604.41
\end{aligned}
$$
2. Sam invests $\$5,000$ in an account that pays annual interest of $10\%$. The funds are invested for 20 years. What will be the value of the account if interest is credited to the account on (a) quarterly basis? (b) monthly basis?
   a.
$$
\begin{aligned}
Fv = Pv(1+\frac{r}{n})^{nt} \\
Fv = $5,000(1+\frac{0.10}{4})^{4(20)} \\
Fv = $5,000(1.025)^{80} \\
Fv = $36,047.84
\end{aligned}
$$
   b.

$$
\begin{aligned}
Fv = Pv(1+\frac{r}{n})^{nt} \\
Fv = $5,000(1+\frac{0.10}{12})^{12(20)} \\
Fv = $5,000(1.008\overline{3})^{240} \\
Fv = $36,640.37
\end{aligned}
$$

[[Simple interest]]