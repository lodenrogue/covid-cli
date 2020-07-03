# covid-cli

- Command line interface for Covid-19 data
- Service provides data by **state** or **county**
- Data is pulled from a NY Times database which is updated daily
- All calls are case-insensitive

#### Basic Usage

```
# All states
$ covid
```

```
# Specific state
$ covid -s "New York"
```

```
# All counties
$ covid -t all
```

```
# Specific county
$ covid -t Broward
```

#### State
```
# All data for state
$ covid -s Florida
```

```
# Daily cases for state
$ covid -s Florida -c daily
```

```
# Cumulative cases for state
$ covid -s Florida -c cumul
```

```
# Daily deaths for state
$ covid -s Florida -d daily
```

```
# Cumulative deaths for state
$ covid -s Florida -d cumul
```

#### County

```
# All data for county
$ covid -t Miami-Dade
```

```
# Daily cases for county
$ covid -t Miami-Dade -c daily
```

```
# Cumulative cases for county
$ covid -t Miami-Dade -c cumul
```

```
# Daily deaths for county
$ covid -t Miami-Dade -d daily
```

```
# Cumulative deaths for county
$ covid -t Miami-Dade -d cumul
```
