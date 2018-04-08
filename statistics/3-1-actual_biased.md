[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>> REPLACE THIS TEXT WITH YOUR RESPONSE

resp = nsfg.ReadFemResp()

# Solution goes here

hist = thinkstats2.Pmf(resp.numkdhh)
thinkplot.Pmf(hist, label='actual')
thinkplot.Config(xlabel="Nbr of children living in household under 18", ylabel="PMF")
hist.Mean()

# Solution goes here
biased_pmf = BiasPmf(hist, label='biased')
thinkplot.Pmfs([biased_pmf, hist])
thinkplot.Config(xlabel="Nbr of children living in household under 18", ylabel="PMF")
biased_pmf.Mean()
