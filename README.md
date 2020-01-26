This is an APT repository that contains various tools from around here. It is served via GitHub Pages.

To access packages, add the APT repository to your list of Apt sources:

```
sudo echo "deb https://prebuilt-amiga-dev-tools.github.io/apt-prebuilt-amiga-dev-tools/ stable main" | sudo tee /etc/apt/sources.list.d/apt-prebuilt-amiga-dev-tools.list
wget https://prebuilt-amiga-dev-tools.github.io/apt-prebuilt-amiga-dev-tools/PUBLIC.KEY -O - | sudo apt-key add -
```

Then install packages as per usual:
```
sudo apt-get update && apt-get install <packagename>
```
