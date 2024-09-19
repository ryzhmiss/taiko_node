# taiko_node

## Describe the feature request
A simple tutorial is good, but the step by step on https://taiko.xyz/docs/guides/run-a-taiko-node is too simple. With about 3 lines of code a user could install all prerequisites (docker, git, etc).
Also, I used a burner wallet. Should I do something about that if I want to receive the famous airdrop?

## Describe alternatives you've considered
Better step by step setup node
Execute each command sequentially by copying and pasting them one-by-one. Make sure to wait for completion before proceeding to the next!

sudo apt-get update sudo apt-get install ca-certificates curl apt install gnupg apt install lsb-release

sudo mkdir -p /etc/apt/keyrings curl -fsSL https://download.docker.com/linux/ubuntu/gpg… | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt-get update

sudo apt-get install docker-ce docker-ce-cli http://containerd.io docker-compose-plugin

## Additional context
Additional context here
