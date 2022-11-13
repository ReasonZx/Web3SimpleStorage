# Install modules
```
$pip install py-solc-x
$pip install web3
```

# Public and Private key management:

```
$pip install python3-dotenv
$export PRIVATE_KEY="your_private_key"
$export PUBLIC_KEY="your_public_key"
```

# Network to deploy
Get a network endpoint from infura.io and corresponding chain id and edit the following part of the code:

```
w3 = Web3(Web3.HTTPProvider("HTTP://MY_PROVIDER")) 
chain_id = 5 
```

# Run
```
python deploy.py
```