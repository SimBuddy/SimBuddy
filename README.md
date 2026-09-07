## WOB - a simple 5-word rule, and a 1-word implementation method.

**What is WOB?**

WOB began life as a simple idea relating to peripheral vision.  The idea spawned a simple rule, which was tested by modifying a known object detection algorithm, to embody the rule into the code.

It worked very well.  See the video experiment elsewhere.  The rule was then tested alongside another idea around object detection.  Due to an experimental mishap, the rule looked like it was the only real factor in the experiment.  It wasn't - it was only 1 factor, but further testing was (mistakenly) justified. The rule was tested against other code repos which had code which processed a lot of data, and the rule performed well when embedded into the code.  The mistake ended up being the right one to make.

This was done using LLM-based code scanning techniques.  Not for optimising in terms of speed, but in terms of focussing the workload on data where it is worthwhile.

The rule was shortened to 5 words - they are not disclosed, but a useful and useless analogy might be **"LAZINESS MADE SMARTER".**

A second fortuitous accident - when amending code, my LLM stupidly misinterpreted its prompt, which went unnoticed. The rule was applied at every suitable point in the test code base, and the results were even better.  It took a while to analyse the "fault" - again, this was the right mistake to make.

The WOB method was born - a generic technique in code factoring to improve data-heavy code.  Not speed, efficacy - making laziness smarter.











