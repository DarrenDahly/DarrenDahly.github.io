+++
date = "2017-02-03T12:00:00"
draft = false
tags = ["academic"]
title = "The perils of exploratory data analysis"
math = true
summary = """
Is it ever ok to conduct an exploratory data analysis, for the purpose of "generating hypotheses"?
"""
+++


Is it ever ok to conduct an exploratory data analysis, for the purpose of "generating hypotheses"? 

This question was motivated by a new Retraction Watch piece, [Backlash prompts prominent nutrition researcher to reanalyze multiple papers](http://retractionwatch.com/2017/02/02/backlash-prompts-prominent-nutrition-researcher-reanalyze-multiple-papers/). It covers the backlash to an earlier blog post by [Brian Wansink](https://twitter.com/BrianWansink), who wrote about two early career researchers, one of whom took on several "extra" projects, vs. another who refused ([The Grad student who never said no](http://www.brianwansink.com/phd-advice/the-grad-student-who-never-said-no)). The former managed to turn the "opportunity" into a small handful of publications, and Wansink's thesis was that this is how you get ahead in academia. However, in writing the blog post, its author revealed a concerning approach to statistical inference, not to mention a cavalier attitude to the exploitation of early career scientists, both of which were quickly noted on twitter and in the blog's comments. 

[You can find the relevant tweets here.](https://twitter.com/statsepi/status/809479929435979776)

I am not here to pile on, but in the RW article, there was a quote from Professor Wansink that I couldn't believe. 

> P-hacking shouldn’t be confused with deep data dives – with figuring out why our results don’t look as perfect as we want.
> 
> With field studies, hypotheses usually don’t “come out” on the first data run.  But instead of dropping the study, a person contributes more to science by figuring out when the hypo worked and when it didn’t.  This is Plan B.  Perhaps your hypo worked during lunches but not dinners, or with small groups but not large groups. You don’t change your hypothesis, but you figure out where it worked and where it didn’t.

[I of course turned to twitter to express my outrage](https://twitter.com/statsepi/status/827456005084704769), and was suprised to find people supporting the idea that exploratory analyses were perfectly acceptable for "generating hypotheses". 

I immediately thought of this great paper by Philip Cole, titled [The Hypothesis Generating Machine](http://journals.lww.com/epidem/Citation/1993/05000/The_Hypothesis_Generating_Machine_.12.aspx), in which he humourously claims to have compiled a list that contains every possible "X is associated with Y" hypothesis, making it pointless to try and identify any new ones.  It's a short and entertaining read, and I encourage you to have a look for yourself.

People also seemed to think that exploratory analyses are ok in principle, but only if your explorations, regardless of their outcome, are reported. Obviously we can’t selectively report our "successful" explorations, and hide away the others (see the Texas sharpshooter fallacy; the garden of forking paths; file-dawer effects; and publication bias).  However,  I think people are missing the point that there aren't enough hours in the day to actually do this. Even if you were just sharing summaries of your explorations, the time it would take to write them up would take up more time than the analyses themselves. Given that most of these analyses would lead nowhere, this would be a remarkable waste of researcher time, which is often publicly funded. So sure, exploratory analyses aren’t the end of the world - unless you take the point about selective reporting seriously. 

I want to be clear about one last thing. I agree with [Frank Harell's](https://twitter.com/f2harrell) point that ["Using the data to guide the analysis is almost as dangerous as not doing so."](https://twitter.com/robertstats/status/774112526489440256). We should certainly use the data in front of us to guide modelling decisions, but this is *within the context of the scientific question at hand* (unless I am misunderstanding Harell's point). However, it is completely unscientific to suggest that you should look for subgroups for which you your "hypothesis works" if it didn't work in the full sample. It's exactly the logic that practitioners of so called alternative medicine use, when they point out that the treatment didn't work, except in the people that it worked in. 

These problems aren’t trivial. This kind of thinking is damaging science. It has contributed to a bloated, garbage heap of published research. Most importantly, these problems are no longer just fodder for scientists to discuss over cocktails at international conferences. There are plenty of actors with a vested interest in eliminating the role science **must** play in public decision making, and those people are now actively using our methodological errors against us.   

[First draft,  Feb 03, 2017]

[Second draft, Feb 05, 2017]