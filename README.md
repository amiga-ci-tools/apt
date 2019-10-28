This is an APT repository that contains various tools from around here. It is served via GitHub Pages.

How to fetch vasmm68k:

```
sudo echo "deb [trusted=yes] https://amiga-ci-tools.github.io/apt/ stable main" | sudo tee /etc/apt/sources.list.d/amiga-ci-tools.list
sudo apt-get update && apt-get install vasmm68k
```
