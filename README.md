# api-contract-linter

Review an API contract for ambiguous fields and missing error cases.

## Run

Requires Python 3.10+.

```sh
python3 app.py examples/input.txt
```

The tool reads its development gateway settings from `config/staging.env`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.
