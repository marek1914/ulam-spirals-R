Here is some hack R code to build Ulam Spirals. As the story goes in 1963 Stanislaw Ulam was bored at conference and started scribbling numbers in a spiral. What he discovered was a strange diaginal pattern of Prime Numbers. I was a little bored as well so i decided to write up some R to plot these patterns.

IsPrime() and associated functions are borrowed from http://librestats.wordpress.com/2011/08/20/prime-testing-function-in-r/ librestats.

Many Thanks for a useful set of code and saving me some coding time.  

Currently Ulam.Spiral() only accepts odd integers. This parameter is the dimentions of the matrix that will hold the Ulam Spiral.


Prime.Marker() accepts one parameter the name of the spiral created by Ulam.Spiral()


![Ulam Spiral](https://github.com/jofusa/ulam-spirals-R/blob/master/Ulam201.png)
