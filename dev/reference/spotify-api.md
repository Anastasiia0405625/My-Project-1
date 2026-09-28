# Spotify API helpers

Set and retrieve Spotify client information.

## Usage

``` r
get_spotify_access_token()

set_spotify_api_key(id = NULL, secret = NULL)
```

## Arguments

- id:

  A Spotify Client ID.

- secret:

  A Spotify Client Secret.

## Value

- `get_spotify_api_key()` returns a previously stored Client ID and
  Secret.

- `set_spotify_api_key()` is called for side effects only.

## Examples

``` r
if (FALSE) { # taylor_examples()
get_spotify_access_token()
}
```
