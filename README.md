## Command Options

| Command                           | Description                              |
| --------------------------------- | ---------------------------------------- |
| `python counting.py`              | Show Warriors,Rocket,Spurs,Okc game once |
| `python counting.py --all`        | Show all NBA games once                  |
| `python counting.py --live`       | Live tracking (Warriors)                 |
| `python counting.py --all --live` | Live tracking (All games)                |
| `python counting.py --live 15`    | Custom refresh (15 sec)                  |
| `python counting.py --p2p`        | Warriors detail                          |

## Requirements

- Python 3.10+
- nba_api
- requests
- Internet connection

## API Source

Based on [nba_api](https://github.com/swar/nba_api) - An API Client package to access NBA.com APIs.

## Tips

- **Before games**: Run once to check start times
- **During live games**: Use `--live 15` for frequent updates
- **Multiple games**: Use `--all` to see everything happening today
- **Network issues**: Script will show error if NBA.com APIs are unreachable
