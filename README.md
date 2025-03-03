# Python-Dapp-Test

web3-inex based dapp for Test

#### Preinstallation


```bash
git clone https://github.com/INEX-EX/web3-inex.git
cd web3-inex
python setup.py install
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

#### Goal

Improve this repository as much as you can within 24 hours.
