# checkout-fetch-all
Uses `actions/checkout@v3` to fetch all history, branches, and tags which require Personal Access Token.

## Usage
```yml
uses: mnrendra/checkout-fetch-all@v1
with:
  token: ${{ secrets.TOKEN }}
  # @description: Personal Access Token.
  # @type: string
  # @required: true
```

## Author
[@mnrendra](https://github.com/mnrendra)
