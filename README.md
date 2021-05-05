# Charts repo

## Installation

In order to add this github repo as helm registry, run:

```
helm repo add \
    --username <github username> \
    --password <github api key> \
    szymonrychu \
    'https://raw.githubusercontent.com/szymonrychu/charts/master/'
```

or:

```
helm repo add \
    szymonrychu \
    'https://<github api key>@raw.githubusercontent.com/szymonrychu/charts/master/'
```

then in order to search for newest version of the chart run:

```
helm repo update 
helm repo search szymonrychu
```