## install PPA
```bash
curl -s --compressed "https://antrobotics-de.github.io/ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/antrobotics_ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://antrobotics-de.github.io/ppa/antrobotics.list"
sudo apt update
```
