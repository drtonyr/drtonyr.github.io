# Dr Tony Robinson on Github

My main site is [tonyRobinson.com](https://tonyRobinson.com). Here lies random odds-and-sods I've worked on over the years:

## [shorten](https://github.com/drtonyr/shorten)

Perhaps the first dedicated losseless audio compressor.  First released in 1993 [Wikipedia](https://en.wikipedia.org/wiki/Shorten_(codec)).

## [pis-third-asm-emu](https://github.com/drtonyr/pis-third-asm-emu)

I've wanted to build a very simple educational computer for decades, this is the archive of part of those dreams up to 2017.
My current plans use a simpler instruction set and are at [The Blinking Computer](https://blinkingcomputer.org).

## [MSF-60 decoder](https://drtonyr.github.io/MSF60decoder)

A simple software decoder for the 60kHz NPL time signal (aka MSF) accurate to a few tens of milliseconds.

The UK radio time signal is broadcast on 60kHz from Anthorn, Cumbria, UK (see [Time from NPL](https://en.wikipedia.org/wiki/Time_from_NPL_(MSF)))

There are many ways to decode this signal already out there but all seem to involve significant hardware (e.g. [current search](https://www.google.com/search?q=msf+decoder)).  This project uses just a bit of wire into a soundcard and does all the hard work in software.   I'm about 250 miles away from the transmitter and I put about 4 meters of wire out of an upstairs window and attached it to a tree.  Others suggest that a small loop antenna or a few turns around a ferrite rod would do the trick as well.  Whatever antenna is used, there is no radio frequency hardware (e.g. demodulator), everything is done by sampling and software.
  
## [carbonTaxBackstop](https://drtonyr.github.io/carbonTaxBackstop)

A 2019 analyis of UK consumer spending to estimate the effect of a carbon tax which achieved net zero.  The main conclusion is that it's not what we buy, just how much we spend.  Net zero is achievable if (a) those that consume most spend less and (b) we implement soemthing like a universal basic income to make the carbon tax affordable to all.

## [wasp-os](https://github.com/wasp-os/wasp-os)

You too can write micropython and run it on your watch - it's great fun, give it a go.

## [UK and Ireland tide time model (with predictions)](https://drtonyr.github.io/tide)

Tide clocks assume that high tide is spaced every 12 hours and 25 minutes.  They look good, but on average they have about 38 minutes of error (one standard deviation), however a little modelling can get this down to 9 minutes of error.  The deviation from uniform spacing is modelled as a sum of sinusoids and parameters fitted with least-mean-squared error.  Python/micropython code is provided to read the model and compute predictions for any year.
