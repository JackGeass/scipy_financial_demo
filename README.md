# scipy fincail functions
https://docs.scipy.org/doc/numpy-1.15.0/reference/routines.financial.html

```
fv(rate, nper, pmt, pv[, when])whenCompute the future value.
pv(rate, nper, pmt[, fv, when])whenCompute the present value.
npv(rate, values)valuesReturns the NPV (Net Present Value) of a cash flow series.
pmt(rate, nper, pv[, fv, when])whenCompute the payment against loan principal plus interest.
ppmt(rate, per, nper, pv[, fv, when])whenCompute the payment against loan principal.
ipmt(rate, per, nper, pv[, fv, when])whenCompute the interest portion of a payment.
irr(values)valuesReturn the Internal Rate of Return (IRR).
mirr(values, finance_rate, reinvest_rate)reinvest_rateModified internal rate of return.
nper(rate, pmt, pv[, fv, when])whenCompute the number of periodic payments.
rate(nper, pmt, pv, fv[, when, guess, tol, …])tolCompute the rate of interest per period.
```

