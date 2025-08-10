# Nutshells
A collection of useful nushell scripts. Requires [nushell](https://www.nushell.sh/).

### 1. bart
Show BART (Bay Area Rapid Transit) departure times from the station and direction configured in the script.
```nu
~> bart
Next Southbound trains from ROCK:
╭─────────┬───────┬────────┬───────╮
│ minutes │ time  │ length │ bikes │
├─────────┼───────┼────────┼───────┤
│ 18      │ 11:18 │ 8      │ Yes   │
│ 38      │ 11:38 │ 8      │ Yes   │
│ 58      │ 11:58 │ 8      │ Yes   │
╰─────────┴───────┴────────┴───────╯
~>
```
