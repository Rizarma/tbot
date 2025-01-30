# tbot


## Pre-requirements

1. update first

    ```
    $ sudo apt update && sudo apt install -y screen
    ```

## How To

1. clone repo

    ```
    $ git clone https://github.com/Rizarma/tbot.git
    ```

2. install requirements

    ```
    $ pip install -r requirements.txt
    ```

3. update hex

    ```
    $ nano data_bridge.py
    ```

4. update private key & address

    ```
    $ nano keys_and_addresses.py
    ```

5. run script

    ```
    $ screen -S t3rn
    $ python3 t3rn-bot.py
    ```

## Credit

original by [sipalingnode](https://github.com/sipalingnode)