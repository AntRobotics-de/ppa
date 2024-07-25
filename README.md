## Install PPA
```bash
curl -s --compressed "https://antrobotics-de.github.io/ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/antrobotics_ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/antrobotics.list "https://antrobotics-de.github.io/ppa/antrobotics.list"
sudo apt update
```


## Add Antrobotics repository to rosdep
```bash
echo "yaml https://antrobotics-de.github.io/ppa/rosdep/antrobotics.yaml" | sudo tee /etc/ros/rosdep/sources.list.d/antrobotics.list
```