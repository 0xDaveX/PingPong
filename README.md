![image](https://github.com/0xDaveX/PingPong/assets/172975959/747763a0-ee2c-48f2-a1f7-19baba16e603)

<h1 align="center"> PingPong Point Reward Program </h1>

> Running a PingPong Mining Node can grant you points/tokens in their upcomping AIRDROP

> You need an Lunux server for this Node.

> The stronger server/system spec, the more you farm

# MorphL2 x PingPong Campaign

Prior to starting the mining node, We have the opportunity to join the Ping Pong x MorphL2 campaign by simply claiming and staking tokens as below, without the need to operate a node.

1- Connect with your wallet with this link [here](https://app.pingpong.build/points?invite_code=Z382XVhy)

2- Claim your daily mLPT & mGRT token on <b>Holesky</b> Network in `Points` tab

3- Do tasks on `Boost Your Rewards` to increase your daily limit

4- Bridge Claimed tokens From `Holesky` to `MorphL2` via: https://app.pingpong.build/bridge

5- Stake on MorphL2 via: https://app.pingpong.build/markets

<b>Now you are farming PingPong + Morph points Together </b>
Repeat daily to increase your points

if you are already done with above tasks, head below for the 

# PingPong Node Mining Program

## 1- Register
Connect via your Email in [dashboard](https://harvester.pingpong.build/)

## 2- Install with the commands below 

```console
wget https://pingpong-build.s3.ap-southeast-1.amazonaws.com/linux/latest/PINGPONG
```

```console
# Install and update your linux packages
sudo apt-get update
sudo apt-get install apt-transport-https ca-certificates curl software-properties-common screen

# Downlaod Docker packages
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

# Add docker to your packages
sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"

# Update packages
sudo apt-get update

# Install Docker
sudo apt-get install docker-ce

# Start Docker
sudo systemctl enable docker

sudo systemctl start docker

# Give Permissions to Docker
sudo usermod -aG docker $USER

# Test Docker
docker run hello-world
```

## 3- Run
Add device in [dashboard](https://harvester.pingpong.build/devices) and Copy Device ID

![image](https://github.com/0xDaveX/PingPong/assets/172975959/639ffd63-4565-4094-95bc-cc39f6cf670a)


```console
# Start a screen
screen -S pingpong
```

```console
# Replace YOUR_DEVICE_ID_HERE with your ID you copied
chmod +x ./PINGPONG && ./PINGPONG --key YOUR_DEVICE_ID_HERE
```

Ctrl+A+D to minimze the pingpong screen and keep it ruuning in the background

Check the results [Here](https://harvester.pingpong.build/devices) to see if it's running, it might take a minute or two to show uptime
![image](https://github.com/0xDaveX/PingPong/assets/172975959/33f91a3f-4d2c-4802-8110-6f3ef5f692f7)

<B>Now you are farming AIOZ, MASQ and TITAN tokens Beside PPP points</b>

Follow [0xDaveX](https://x.com/0xDaveX) for more Alpha Airdrops



> `Thanks Rues for the detailed guide - Written by 0xMoei ` Follow here [0xMoei](https://x.com/0xMoei)
