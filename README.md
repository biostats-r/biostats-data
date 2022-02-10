
<!-- README.md is generated from README.Rmd. Please edit that file -->

# biostats-data

<!-- badges: start -->
<!-- badges: end -->

This GitHub repository includes datasets for use with the BioCeed
biost@ts books.

## Downloading biostats-data

The easiest way to download biostats-data is to use the `usethis`
package

1.  Open your course RStudio project with RStudio

2.  Install the `usethis` package if you don’t have it already.

``` r
install.packages("usethis")
```

3.  Use `usethis::use_zip()` to download the data into your data
    directory.

``` r
usethis::use_zip("biostats-r/biostats-data", destdir = "data")
```

## Included datasets

### Bergen weather

Monthly mean temperature and precipitation data from Bergen, Norway.

File: bergen_weather.csv

Source: <https://seklima.met.no/>

Data importing, Data manipulation, Data visualisation

| Navn             | Stasjon | Tid(norsk normaltid) | Homogenisert middeltemperatur (mnd) | Nedbør (mnd) |
|:-----------------|:--------|:---------------------|------------------------------------:|:-------------|
| Bergen - Florida | SN50540 | 01.1957              |                                 3.7 | \-           |
| Bergen - Florida | SN50540 | 02.1957              |                                 2.2 | \-           |
| Bergen - Florida | SN50540 | 03.1957              |                                 5.5 | \-           |
