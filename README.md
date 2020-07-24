# jokeR

Forked from [Jeff Hollister's dadjoke R package](https://github.com/jhollist/dadjoke), this fork removes the sting and adds a similar function for Chuck Norris jokes. I'm planning to use this package in R/Shiny apps as "loading screen entertainment" and the sting starts to wear after a while!

## Credits

Jeff Hollister (for the original R package!), [Brett Langdon](https://brett.is/) (for the <https://icanhazdadjoke.com> API), and [Mathias Schilling](https://matchilling.com) (for the <https://chucknorris.io> API)


## Installation

You can install jokeR from GitHub with:

``` r
# install.packages("devtools") OR install.packages("remotes") ## remotes is a subpackage of devtools
remotes::install_github("tanho63/joker")
```

## Examples

This is a basic example which shows you how to solve a common problem - the problem of not laughing enough!

``` r
joker::dadjoke()
[1] "Can a kangaroo jump higher than the Empire State Building? Of course. The Empire State Building can't jump."

joker::chuckjoke()
[1] "There is no Esc key on Chuck Norris' keyboard, because no one escapes Chuck Norris."

joker::randomjoke()
[1] "Chuck Norris makes onions cry."
```

