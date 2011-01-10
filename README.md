# gc

This is an extremely simple interface to the Google Calculator. Just pass it the query on the command line.

    $ gc 2 + 2
    4

    $ gc -v 2 + 2
    2 + 2 = 4

    $ gc once in a blue moon
    1.16699016 * 10^-8 hertz

    $ gc "(4 * pi * epsilon_0 * hbar * c) / elementary charge^2"
    137.035984

    $ gc "sqrt((c * 8 minutes)^3 / (G * m_sun)) * 2 pi in years" 
    0.943428231 years     

The big difference between this and other projects such as [uj-gcalc](http://code.google.com/p/uj-gcalc/) is that it doesn't try and parse the results from the Google HTML results page, it extracts them directly from the Calculator API at <http://www.google.com/ig/calculator>, thus hopefully making it more resilient to the whims of Google's engineers.

If you come across any bugs, please [open an issue](https://github.com/nickstenning/gc/issues).