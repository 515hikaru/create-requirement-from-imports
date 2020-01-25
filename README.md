# create-requirement-from-imports
sample project for dephell magic

# How To

```
$ curl -L dephell.org/install | python3
$ pip3 install jupyter
$ jupyter nbconvert --to script notebook/load_data.ipynb
$ dephell deps convert --from imports --to requirements.txt
```

