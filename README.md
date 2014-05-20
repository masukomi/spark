# spark
### sparklines for your shell

See? Here's a graph of your productivity gains after using spark: ▁▂▃▅▇

## install

spark is a [shell script][bin], so drop it somewhere and make sure it's added
to your `$PATH`. It's helpful if you have a super-neat collection of dotfiles,
[like mine][dotfiles].

If you're on OS X, spark is also on [Homebrew][brew]:

    brew install spark

## usage

Just run `spark` and pass it a list of numbers (comma-delimited, spaces,
whatever you'd like). It's designed to be used in conjunction with other
scripts that can output in that format.

    spark 0 30 55 80 33 150
    ▁▂▃▅▂▇

Invoke help with `spark -h`.

## Why this flavor

I just wanted to add some color, so there are 2 new options and a behavior 
change: it will measure size on absolute value, and you can specify if you
want regular green/red for positive/negative value, or inverted colors:

Give it a try

