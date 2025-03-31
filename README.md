# Introduction to databases

This repo introduces databases for big data and how to interact with them.

## Set up

- Open this repository in a GitHub Codespace or clone it to your local machine.

- Install required R packages:

```r
install.packages("renv")
renv::restore()
```

- Download the [NYC yellow taxi dataset](https://catalog.data.gov/dataset/2020-yellow-taxi-trip-data-january-june/resource/c3ec101d-e6c7-4084-85f3-3930defd8140):

```bash
wget -O nyctaxi.csv "https://data.cityofnewyork.us/api/views/kxp8-n2sj/rows.csv?accessType=DOWNLOAD"
```

- Sign up for a free account at [motherduck.com](https://auth.motherduck.com/login?state=hKFo2SBsenc1X0ZTTXQtMXl1RTNOVHdaSHQ0QW14T0toSUtqZ6FupWxvZ2luo3RpZNkgR2k1VlFXT1JjcWhnSTBlRlJ1a3hLaUhiSUp3eG9GbU2jY2lk2SBiemEzS1dRcHhSQUZsVGxSRlhVbzI5QU9nOXhEN3pjcA&client=bza3KWQpxRAFlTlRFXUo29AOg9xD7zcp&protocol=oauth2&scope=openid%20profile%20email&app_source=web&auth_flow=signup&redirect_uri=https%3A%2F%2Fapp.motherduck.com&response_type=code&response_mode=query&nonce=MkxXNGZMV1RjLXhhdTJyNFpZUWxucjhEfmJsQkY2VGRuSkxaLm5ZUy5OQw%3D%3D&code_challenge=5D-6lu9UqJdiIxWi5WyFF-MoJFA1s4wKSx8W4FmWlmI&code_challenge_method=S256&auth0Client=eyJuYW1lIjoiYXV0aDAtcmVhY3QiLCJ2ZXJzaW9uIjoiMi4yLjQifQ%3D%3D)

## Learning

Run through the quarto notebooks `dplyr.qmd` and `motherduck.qmd`.
