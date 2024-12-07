# RepoSh
Shell script to manage your Cydia &amp; Sileo repositories 

Please consider customizing it as by default it is dummy values.

## How to use it?

1. cd /path/to/your/repo. In VScode just open terminal.

2. chmod +x update-repo.sh <-- to make it executable

3. Your directory should look something like this

```debs/```
  main/
    tweak1.deb
    tweak2.deb
  testing/
    beta-tweak1.deb
  other/
    misc-tweak1.deb

4. mkdir -p debs/main debs/testing debs/other

5. Move to this directories 

## Upload everything 

After just run the shell script. By default it will allow you to customize the info before zipping the tweaks into packages archive.




