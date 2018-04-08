[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> REPLACE THIS TEXT WITH YOUR RESPONSE

# Solution goes here
sample = np.random.random(1000)
sample_pmf = thinkstats2.Pmf(sample)
thinkplot.Pmf(sample_pmf)

the pmf graph is really impossible to read whereas the cdf more clearly tells us that the distribution of our data is uniform since the probability (intuitively) that any random pt p equals a random percentile nbr q --> f(p)=q

# Solution goes here
sample = np.random.random(1000)
sample_cdf = thinkstats2.Cdf(sample)
thinkplot.Cdf(sample_cdf)
