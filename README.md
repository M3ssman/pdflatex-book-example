# Examples using LaTeX 
Although getting started with LaTex can be really hard, once you climbed the first hill you'll be amazed
how fast things can be done you probably didn't even belive to be possible - thanks to the incredible LaTeX-Community
that goes around now for about 30 years.  

Here you 'll find a Collection of MWEs (Minimum Working Examples) along with short Explanations.

## Place a line-number beside every nth-Line
Just declare to use the <a href="https://www.ctan.org/pkg/lineno">lineno-Package</a>, then add the "modulo"-Option, which defaults to "5" and issue the
"linenumbers"-Command:
```
\usepackage[switch, modulo]{lineno}
\linenumbers
```
And that's it!

If you'd like to change the line-numbering to a different value, ex. "4", just add the following line:
```
\modulolinenumbers[4]
```


