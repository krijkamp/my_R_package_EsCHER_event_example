# eschereventpackage

`eschereventpackage` is an R package designed to demonstrate how to create a package. The functions facilitate temperature conversion between Fahrenheit and Celsius. 

## Installation

You can install `eschereventpackage` from GitHub:

```R
# if you don't have the devtools package installed, install it first
if (!requireNamespace("devtools", quietly = TRUE))
    install.packages("devtools")

devtools::install_github("krijkamp/my_R_package_EsCHER_event_example")
```

## Usage

To use `eschereventpackage`, load it into your R environment:

```R
library(eschereventpackage)
```

### Example

Here is a simple example using `eschereventpackage`:

```R
#
convert_Fahrenheid_to_Celsius(45)
```

## Contributing

Contributions to `eschereventpackage` are welcome via pull requests and issues on the GitHub repository.

## License

`eschereventpackage` is free for reuse use

## Acknowledgement
Inspired by the tutorial published by Brad Duthie (see [here](https://ourcodingclub.github.io/tutorials/writing-r-package/#github)), which is part of the Coding Club.


---