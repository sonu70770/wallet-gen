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

# Quest1 - Send Tokens

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
python cli.py send --to oct5zG3PzB7DBGfwkUbL5fSvFszftEsVTiKNDNK3nhs2LYJ --amount 0.01
```

