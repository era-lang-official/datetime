# Era DateTime (`github.com/era-lang-official/datetime`)

Date, time, ISO 8601 string formatting, and duration arithmetic for Era.

## Features
- **Unix Timestamp Conversion**: Convert between Unix milliseconds and UTC calendar dates.
- **ISO 8601 Formatting**: Standard `YYYY-MM-DDTHH:MM:SS.mmmZ` representation.
- **Duration Arithmetic**: `add_seconds`, leap year calculations.

## Usage
```era
import "github.com/era-lang-official/datetime";

fn main() {
    let now = DateTime::now();
    println(now.to_iso8601());
    let later = now.add_seconds(3600);
}
```

