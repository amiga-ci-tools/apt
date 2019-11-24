This is an APT repository that contains various tools from around here. It is served via GitHub Pages.

To access packages, add the APT repository to your list of Apt sources:

```
sudo echo "deb https://amiga-ci-tools.github.io/apt/ stable main" | sudo tee /etc/apt/sources.list.d/amiga-ci-tools.list
wget http://amiga-ci-tools.github.io/apt/PUBLIC.KEY -O - | sudo apt-key add -
```

Then install packages as per usual:
```
sudo apt-get update && apt-get install <packagename>
```

Packages available:

[vasmm68k](https://github.com/amiga-ci-tools/vasmm68k)
