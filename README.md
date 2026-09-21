# Adjusted net income — the figure three UK cliffs key off

Adjusted net income is your total taxable income from every source, minus a
short list of deductions. It is **not** your salary, and three of the sharpest
thresholds in UK tax are assessed on it.

**Live:** <https://uk-adjusted-net-income.onrender.com/>

One static page. No framework, no dependencies, no tracking, no build step.

## The three thresholds

| Threshold | What happens | Shape |
| --- | --- | --- |
| **£100,000** | Personal allowance withdrawn £1 for every £2, gone by £125,140. Marginal rate 60%, or 62% with NI | Taper |
| **£60,000** | High Income Child Benefit Charge begins, reaching 100% at £80,000. Assessed on the *higher earner*, not the household | Taper |
| **£100,000** | Tax-Free Childcare and the funded hours are lost **entirely** | **Cliff** |

## Why the cliff matters more than the taper

A taper takes a share of the extra pound. A cliff takes the whole benefit the
moment you cross. Stacked with the 60% band, a family crossing £100,000 can be
materially worse off than before the raise — the one case where a pension
contribution is better than free.

## The two facts people miss

**ISA income never counts.** Interest and dividends inside an ISA are not
taxable income, so they never appear in adjusted net income. The same money
outside one can push you over a cliff.

**Gift Aid is deducted, grossed up.** £80 given is £100 off your adjusted net
income — the same mechanism as a pension contribution, and far more often
forgotten.

## Deploying

`render.yaml` is a Render Blueprint. Connect the repo on Render and it
configures itself: static site, no build command, published from the repo
root.

## Related

[Adjusted net income calculator](https://truetakehome.co.uk/adjusted-net-income-calculator/) ·
[100k tax trap calculator](https://truetakehome.co.uk/100k-tax-trap-calculator/) ·
[Childcare cliff calculator](https://truetakehome.co.uk/childcare-cliff-calculator/) ·
[Pension sweet spot calculator](https://truetakehome.co.uk/pension-sweet-spot-calculator/)
on [True Take-Home](https://truetakehome.co.uk/)

**Not tax advice.** gov.uk and an accountant are the authorities on your own
circumstances.
