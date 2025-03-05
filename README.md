``` 
sudo apt-get install virtualbox-guest-x11
sudo apt install wget unzip xxd -y
```

``` 
wget "https://drive.usercontent.google.com/u/0/uc?id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut&export=download" -O tutorials.zip
```
```
mkdir artists_who_can_sing
cd artists_who_can_sing
```
```
mv tutorials.zip artists_who_can_sing/
```

```
mkdir singing_tutorials
unzip tutorial.zip -d singing_tutorials
```
```
ls -la
```
```
grep -ril "opera" | xargs grep -i "NBAYoungboy" | xargs grep -o "FLAG{.*}" > ../flag.txt
```
```
cd ..
wget -O plsrunmeiamnotmalwarefr "$(cat flag.txt)"
```
```
chmod +x plsrunmeiamnotmalwarefr
./plsrunmeiamnotmalwarefr
```

