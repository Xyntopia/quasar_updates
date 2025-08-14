# UPDATE PROCEDURES

```bash
git checkout flakepure
# set to newest yarn version globally (it will install in the .cache directory)
corepack prepare yarn@4.9.2 --activate


# install new quasar version:

yarn create quasar

# checkout our quasar tracker:
git checkout quasar_tracker

# move everything inside quasar-project folder to parent dir
mv quasar-project/* .

# check git gui for changes and commit!
```

