# Monero Mining

Step 1: Crete a VM  and connect via ssh.
Create a VM on a cloud of your choice or you can mine anywhere you want Cloud, Home PC, Raspberry pi

Step 2: Install the Crypto Mining Software

1. Update your VM and essential repositories
    
    sudo apt update
    
    sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y
    
2. Clone XMRig repository from GITHUB and open the folder
    
    git clone https://github.com/xmrig/xmrig.git
    cd xmrig
    
3. Create a new directory and cd into it
    
    mkdir build
    cd build
    
4. Install XMRig which you downloaded 
    
    cmake ..
    make
    
Note: it is cmake [space] [dot] [dot]

STEP 3 - Get a Monero Crypto Wallet
  https://www.getmonero.org

STEP 4 - Start Mining 
To start mining enter the following code with your wallet address and label for VM

./xmrig -o gulf.moneroocean.stream:10128 -u yourwalletaddress -p lableforvm

Press the following key to check the status

 H - hash rate speed of mining

 S - to check result 

 C- current connection mining 

STEP 5 - Check the accepted share in the mining pool

To check accepted share goto website moneroocean. stream
