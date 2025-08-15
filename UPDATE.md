# UPDATE PROCEDURES

```bash
git checkout flakepure
# set to newest yarn version globally (it will install in the .cache directory)
corepack prepare yarn@4.9.2 --activate


# install new quasar version:

yarn create quasar

# checkout our quasar tracker:
git checkout quasar_tracker

# delete everything in parent except .git:
find . -mindepth 1 -maxdepth 1 \( -name .git -o -name quasar-project \) -prune -o -exec rm -rf -- {} +

# move everything inside quasar-project folder to parent dir
mv quasar-project/* .

# check git gui for changes and commit!


# now, while still in quasar_tracker branch reset to vite branch,
# so that we can see all the new changes coming in. We have to 
# decide ourselves now which files to delete and which we stil need
git reset vite

# also make sure to checkout prettierrc and merge/install package.json in order to make sure
# we have all the tools available and standarddized

```

