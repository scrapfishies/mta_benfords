# Does MTA turnstile data follow Benford's Law? 

I recently learned about [**Benford's Law**](https://en.wikipedia.org/wiki/Benford%27s_law) through the [Netflix series, Connected with Latif Nasser](https://www.netflix.com/title/81031737#:~:text=Digits&text=Latif%20explores%20a%20law%20of,and%20perhaps%20the%20entire%20universe.). Episode 4: 'Digits' explores how Benford's Law applies to music, social media, tax fraud, and more. It's a fun show and I'd highly recommend checking it out if you can!

A quick primer on Benford's Law from Wikipedia:

> **Benford's law**, also called the **Newcomb–Benford law**, the **law of anomalous numbers**, or the **first-digit law**, is an observation about the frequency distribution of leading digits in many real-life sets of numerical data. **The law states that in many naturally occurring collections of numbers, the leading digit is likely to be small.** For example, in sets that obey the law, the number 1 appears as the leading significant digit about 30% of the time, while 9 appears as the leading significant digit less than 5% of the time. If the digits were distributed uniformly, they would each occur about 11.1% of the time. Benford's law also makes predictions about the distribution of second digits, third digits, digit combinations, and so on.

You can see Benford's illustrated in the figure below.

![Benford's Law](https://github.com/scrapfishies/mta_benfords/blob/master/images/benfords.png)

Since watching that episode, I'd had it in the back of my mind that I wanted to explore a dataset to check for *Benfordness*. 

I recently started [Metis' Data Science Bootcamp](https://www.thisismetis.com/) and our first project was to conduct some exploratory data analysis on [MTA Turnstile data](http://web.mta.info/developers/turnstile.html).

With the project behind me, I decided to dig a little more into the data and see how well the MTA turnstile data fit Benford's Law.

Check out [my blog post on Medium (coming soon!)]() and dig into my [Jupyter Notebook](https://github.com/scrapfishies/mta_benfords/blob/master/mta_benfords.ipynb) where I explore the data. Feedback welcome!
