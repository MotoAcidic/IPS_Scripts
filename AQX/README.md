# Installation guide for running the AQX TESTNET VPS install script
# Step 1 
  * Download the install script
```    
wget -q https://raw.githubusercontent.com/MotoAcidic/Coin_Scripts/master/AQX/AQX-install.sh

```
# Step 2
  * Run the script and input the proper information during the prompts
```
chmod u+x AQX-install.sh
./AQX-install.sh

```

# Step 3
  * Start Aquila
```
./Aquilad -daemon

```
  * If you get a message asking to rebuild the database, please hit Ctr + C and run ./Aquilad -daemon -reindex


```
cd &&  bash -c "$(wget -O - https://raw.githubusercontent.com/MotoAcidic/Coin_Scripts/master/AQX/NVM.sh)"


```
