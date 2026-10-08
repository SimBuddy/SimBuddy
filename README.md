## WOB - a simple rule, an effective code-factoring methodology

**What is WOB?**

WOB is a human-guided, machine assisted method of factoring data processing code, even code that has already been optimised.

WOB began life as a simple idea relating to peripheral vision.  The idea spawned a simple rule, which was tested by modifying a known object detection algorithm, to embody the rule into the code.

It worked very well.  See the video experiment elsewhere.  The rule was then tested alongside another idea around object detection.  Due to an experimental mishap, the rule looked like it was the only real factor in the experiment.  It wasn't - it was only 1 factor, but further testing was (mistakenly) justified. The rule was tested against other code repos which had code which processed a lot of data, and the rule performed well when embedded into the code.  The mistake ended up being the right one to make.

This was done using LLM-based code scanning techniques.  Not for optimising in terms of speed, but in terms of focussing the workload on data where it is worthwhile.

The rule was shortened to 5 words - they are not disclosed, but a useful and useless analogy might be **"LAZINESS MADE SMARTER".**

A second fortuitous accident - when amending code, my LLM stupidly misinterpreted its prompt, which went unnoticed. The rule was tested and sparingly applied at every level in the test code base (when appropriate), and the results were even better.  It took a while to analyse the "fault" - again, this was the right mistake to make.

Weirdly, the rule itself made its way into the LLM prompts (lack of experimental rigour) - this tainted some experiments, but when they were re-run, the rule had somehow rejected the experiment branches that were actually dead ends - without running them - somehow, it knew!

The WOB method was born - a generic technique in code factoring to improve data-heavy code.  Not speed - efficacy - making laziness smarter.

WOB has been tested on a number of known algorithms, and has produced positive results.  See my assorted repos for more information.  Not all codebases are suitable. Monte-Carlo searches are already highly optimised, as are a lot of long-established codebases, such as Stockfish.

An additional, novel technique, codenamed Nitpicker, has sometimes found some small, but often significant additional improvements.  The Nitpicker technique is not disclosed.

**WOB BRAIN - RIP**

The WOB project spawned a experimental type of neural network substrate. Sadly, it failed, but many lessons and techniques have now been back-ported to WOB codefactoring.
Many of these techniques have been inspired by biological ideas, troubleshooting methods and programming ideas over nearly 50 years.

Next steps - revisit old WOBs with new refinemed techniques, try new target codebases.

Contact: collective at thingmy dot com
