# Termux-minecraft-server-port-forwarding-comands

you can use this command if you are running a Minecraft server on termux if you want to connect it to the public the comannd for the port forwarding is

```pkg install rust 
pkg install git
git clone https://github.com/playit-cloud/playit-agent.git 
cd playit-agent  
# Build the binary 
cargo build --release  
# Run Playit 
./target/release/playit cargo fix --bin "playit-cli"  cargo build --release
./target/release/playit-cli
```

then it will give you a link and you can register a user or just log in as a anynomus user
the link will be like ```https://playit.gg/claim/xxxxx```

then after registering it will ask you to add a new agent and press continue on the website 
and then press add agent

after that it will ask you what kind of server you are running 

if you are running java then select java or if you are using bedrock then click bedrock 
and then it will give you the public ip and your friends can finally join your minecraft server
