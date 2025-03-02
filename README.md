# Python-Dapp

web3-inex based dapp

#### Preinstallation

```bash
git clone https://github.com/INEX-EX/web3-inex.git
cd web3-inex
python setup.py
```

#### Steps:

1. Deploy your contract on your preferred network(update `RPC_URL` accordingly) and get the contract address.

2. Create `.env` file in the root directory with below parameters:

```
PRIVATE_KEY=
RPC_URL=
CONTRACT_ADDRESS=
```

3. Install dependencies and run app:

```bash
pip install -r requirements.txt

python app.py # open http://localhost:8000

```
