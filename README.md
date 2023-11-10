
# Assignment 2 - rbpack

<!-- badges: start -->
<!-- badges: end -->

The goal of Assignment 2 - rbpack is to create a package of functions.

The rbpack was created by Raveen Badyal for STAT545B Assignment 2. It is
a package that includes an lb_to_kg function. To use this function, you
will have to install the package. The package can be installed using
install_github(“stat545ubc-2023/rbpack”). The package can then be loaded
using the library() function.

``` r
library(rbpack)
```

The lb_to_kg function can be used to convert pounds to kilograms to 2
decimal places. A numeric input is required for the lb_to_kg function.
Numbers less than 0.02 can not be inputted into this function as the
outut is limited to two decimal places. A different function must be
used for that purpose, or divide by 2.20462. There are some examples
below. Error messages will be outputted if an invalid input is made.

``` r
lb_to_kg(0.02)
#> [1] 0.01
lb_to_kg(0.01)
#> [1] "Your input for lb is too small for this function"
lb_to_kg(10)
#> [1] 4.54
lb_to_kg("hi")
#> [1] "This function only works for numeric input."
```

\`\`\`
