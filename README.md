# backwards

Returns the @field'th field from the end

## Usage

Passing the field number as an argument:

```
❯ echo "1 2 3 4" | bw -v field=2
2
```

Defaults to the last column:

```
❯ echo "1 2 3 4" | bw
4
```

