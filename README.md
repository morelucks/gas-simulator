# Gas Simulator

This project implements a **gas simulator** for Ethereum transactions using **Reth** in Rust. It allows you to estimate gas costs for transactions **without broadcasting them** to the network by simulating execution in a local EVM environment.

##  Features  
- Simulates Ethereum transactions **before sending**  
- Estimates **gas usage** and detects potential reverts  
-  Supports **ETH transfers** and **smart contract calls**  
- Works with **dummy state** or **real blockchain data**  
- Can be extended for **mempool monitoring**  

---

##  Installation  

### **Clone the Repository**  
```sh
git clone https://github.com/your-username/gas-simulator.git
cd gas-simulator
