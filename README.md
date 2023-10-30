# Tribal Wars
_My personal repository of browser game Tribal Wars._

## RegExp cheatsheet

### Extended labels
```regexp
Taran (\d+\.\d+) o (\d+:\d+:\d+) \[\d+\]( \[[a-z\/]+\])?
```

### Support label
```regexp
.*\((\d{3}\|\d{3})\) K\d+.*\((\d{3}\|\d{3})\) K\d+.*
```

### Villages of player from their profile
```regexp
\n(\d{3}\|\d{3})\s
```
