# MTRN3100

## Converting `md` to `pdf`

To convert `Markdown` files for a particular lab, do:
```
make -s MD=lab02/lab02.md
```

To convert all labs, do:
```
make -s all
```

Running `make` will create both a student and tutor `pdf` version.

**Do not modify anything inside lab-master** as this serves as a template for the format of the documents. Only edit the `md` files and use `make`.
