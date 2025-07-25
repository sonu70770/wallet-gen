# Octra

# Wallet generation Guide

---

## 🔹 Step 1:

```bash
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
````

---

## 🔹 Step 2:

```bash
bun install
```

---

## 🔹 Step 3:

```bash
bun run build
```

---

## 🔹 Step 4:

```bash
bun start
```

> click the **“PORTS”** tab open link under forwarded address in browser

---

**Wallet Generated, Back up private key**

Go to https://faucet.octra.network/

Paste Wallet address & claim faucet

Join Discord - https://discord.gg/vnp9QsPW

---

# Task 1 - Token Transfer

### Step 1

```bash
pip install -r requirements.txt
````

---

### Step 2

```bash
cp wallet.json.example wallet.json
```

### Step 3 
Then open the file: wallet.json

Paste your test wallet details 


```
{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

---

### 🔹 Step 4 : Send a test transaction

Replace address with any address from explorer - https://octrascan.io/

```bash
python cli.py send --to oct5ziFzQJkiJFPfcQeuAmp4vhfQgjwb8gyx2W2TZdGhzJm --amount 0.01
```

#  TASK 2 : ENCRYPT / DECRYPT BALANCE

###  STEP 1: Follow Task 1 Steps & Open Wallet UI

---

###  STEP 2: 
![image alt](https://github.com/sonu70770/wallet-gen/blob/1f9a60dbcb856fcc76f38fa48aa721cd1977a924/Screenshot%202025-07-12%20003821.png) 

• Use Command `4` For Encrypt  
• Use Command `5` For Decrypt  

Keep doing transactions, you can also use other commands like `6` & `7` for private Transfer & Claim , Use Address From Explorer:(https://octrascan.io/)
