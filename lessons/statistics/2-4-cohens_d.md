[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)
firsts = live[live.birthord == 1]
others = live[live.birthord != 1]
if (firsts.totalwgt_lb.mean())>(others.totalwgt_lb.mean()):
    print('First born babies are heavier')
else:
    print('First born babies are lighter')
if (firsts.prglngth.mean())>(others.prglngth.mean()):
    print('Length of first pregnancy is longer')
else:
    print('Length of first pregnancy is shorter')
