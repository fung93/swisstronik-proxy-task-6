# SWISSTRONIK Technical Task 6

Steps to a deploy proxy

1. Clone repository
```shell
https://github.com/fung93/swisstronik-proxy-task-6.git
```
```shell
cd swisstronik-proxy-task-6
```
2. Install Dependency
```shell
npm install
```
3. Set .env File
Create .env file in root project
```shell
touch .env
```
Add this to .env file
```shell
PRIVATE_KEY="your private key"
```
4. Compile Smart Contract
```shell
npm run compile
```
5. Deploy Smart Contract
```shell
npm run deploy
```
6. Final
   - Copy the address and paste the address to testnet dashboard
   - Copy the transaction hash link to testnet dashboard
   - Push this project to your github and paste the repository link to testnet dashboard
