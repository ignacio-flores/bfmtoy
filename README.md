# bfmtoy: Simulating Biased Income Distributions in Stata

## Description
`bfmtoy` is a Stata package designed to simulate income distributions and draw biased samples. This tool is tailored for researchers and analysts working in economic and social sciences, providing a way to analyze the impact of bias in survey data. It integrates seamlessly with Stata commands like `bfmcorr` and `postbfm` for advanced analyses.

## Installation
To install `bfmtoy`, you can download the `.ado` and `.sthlp` files from this repository and place them in your Stata ado directory. 

```
sysdir set PERSONAL "path_in_your_computer/bfmtoy_ado/."
```

For detailed syntax and options, refer to the `bfmtoy.sthlp` file or type `help bfmtoy` in Stata.


## Usage
To use `bfmtoy`, invoke the command with the desired parameters in Stata. Here is a basic example:

```
bfmtoy, obs(1000) theta(0.5) misreporting(1 2) true(1) sample(0.01)
```

This command will simulate an income distribution with specified parameters.


