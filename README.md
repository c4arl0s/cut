# cut

cheatsheet of cut

# Use cut to get strings between double quotes

```console
echo "this is a \"what we really want\" string"
```

```console
this is a "what we really want" string
```

```bash
echo "this is a \"what we really want\" string" | cut -d '"' -f 2
```

Output

```console
what we really want
```
