## Best program for producing economics graphs on Linux?

- posted by: [shapr](https://stackexchange.com/users/-1/784-shapr) on 2012-03-13
- tagged: `software`, `linux`
- score: 1

I'd like to produce economics graphs (Elasticity of Demand, Supply and Demand curves, etc) on Ubuntu.
I've looked at gnuplot and Gnu Octave, but haven't found any complete examples.

I'd like to be able to produce output from both equations and tables of numbers.

What's the best option?

Edit: I'm a poor college student, what's the best solution that uses an open source solution?


## Answer 1111

- posted by: [Peteris](https://stackexchange.com/users/-1/486-peteris) on 2012-03-13
- score: 5

[Mathematica](http://wolfram.com/mathematica) is very rich in both computation and visualization, but also very simple to learn and use. If you can afford it, I would strongly suggest using Mathematica. There is even a dedicated economics package [here](http://www.wolfram.com/solutions/industry/economics/).

As a free alternative, there is indeed GNU Octave, but there is also a more ambitious project called [Sage](http://www.sagemath.org/) that you might want to look into.

For quantitative analysis, I would recommend [R](http://www.r-project.org/) even though I haven't used it personally. It is both free and mature.


## Answer 1135

- posted by: [mzuba](https://stackexchange.com/users/-1/219-mzuba) on 2012-03-21
- score: 4

The already mentioned [R Project](http://www.r-project.org/) is the reference software package for your purpose. IMHO, you shouldn’t bother with commercial packages, as those are not better than R. 

[This page](http://addictedtor.free.fr/graphiques/thumbs.php) demonstrates the plotting/graphing capabilities of R. It also provides the code used for creating these graphs, which makes it easy to adopt them to your requirements.

For example, plotting functions can be done with the $curve()$ command.

    curve(30-3*x, 0, 10)
    curve(0.5*x, 0, 10, add=TRUE, col="blue")


## Answer 1110

- posted by: [EnergyNumbers](https://stackexchange.com/users/-1/104-energynumbers) on 2012-03-13
- score: 0

<p>The best sledgehammer for this particular nut would be Matlab for Linux.</p>

<p>It's an all-singing, all-dancing matrix laboratory, with a squillion features, one of which is drawing graphs from equations and tables of numbers. If you're serious about doing a lot of quantitative analysis, MatLab is <strong>the</strong> tool.</p>

<p>Some courses use Matlab for supply-demand curves and the like - <a href="http://cs.wellesley.edu/~cs112/assignments/assign5/assign5.html" rel="nofollow">see sample course notes here</a>.</p>

<p>You may be able to coerce the samples from those course notes into GNU Octave - I gather that Octave tries to mimic MatLab syntax, but without the ultra-comprehensive help documentation or the performance. YMMV</p>

<p>If you like Python, you could try <a href="http://matplotlib.sourceforge.net/index.html" rel="nofollow">Matplotlib</a> - free Python software to produce a wide variety of plots. You may find that performance and documentation are, once again, less than ideal.</p>

<p>If you'll be doing a lot of statistical analysis too, you could look at the <a href="http://www.r-project.org/" rel="nofollow">R Project</a>, which has charting capabilities. It's also had some lot of attention paid to performance, and there's a large support community.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
