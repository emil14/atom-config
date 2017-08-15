# atom-config
My settings and packages list for Atom editor. Inspired by [this issue](https://stackoverflow.com/questions/30006827/how-to-save-atom-editor-config-and-list-of-packages-installed) ⚛️

``` bash
# retrieve settings
git clone https://github.com/emil14/atom-config ~/.atom
cd ~/.atom
apm install --packages-file ~/.atom/package.list

# update packages list
cd ~/.atom/
apm list --installed --bare > ~/.atom/package.list
git commit -am "Update package-list"
```
