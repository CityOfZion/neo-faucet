# neo-faucet
A faucet for a neo private test network

Install:

1. clone and install [neo python](https://github.com/CityOfZion/neo-python)
2. in a neighboring directory, clone this repo
3. `cd neo-faucet`
4. `python3 -m venv venv`
5. `source venv/bin/activate`
6. install neo-python locally to this project: `pip install -e ../neo-python`
7. install rest of requirements `pip install -r requirements.txt`
8. get a wallet of your private net with a lot of stuff in it
9. export the wallet path and password as ENV vars
```
export FAUCET_WALLET_PASSWORD=yourpass
export FAUCET_WALLET_PATH=yourwallet.db3
```

10. optionally, configure host and port
```
export FAUCET_PORT=80
export FAUCET_HOST=127.0.0.1
```

11. start the faucet `python faucet.py`

12. fun
