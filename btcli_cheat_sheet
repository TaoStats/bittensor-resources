# Bittensor CLI Cheat Sheet

This guide serves as a cheat sheet for the new strucutre of the Bittensor CLI after the Revolution update.
The main key change is that commands are grouped and to perform a command you must first enter the parent group name (or alias).

An example of how commands have changed would be:

Overview (was)
`btcli overview`

Overview (now)
`btcli wallet overview`
`btcli wallets overview`
`btcli w overview`

It will be optimum to use the shorthand aliases for the group names which is who we will be referring to commands in all tutorials and assistance.


## subnets (`s`, `subnet`) 	
Commands for managing and viewing subnetworks.

- `list`				List all subnets on the network
- `metagraph`           View a subnet metagraph information.
- `lock_cost`           Return the lock cost to register a subnet
- `create`              Create a new bittensor subnetwork on this chain.
- `register`           	Register a wallet to a network.
- `recycle_register`    Register a wallet to a network.
- `hyperparameters`     View subnet hyperparameters


## root (`r`, `roots`)			
Commands for managing and viewing the root network.

- `list`                List the root network
- `weights`             Set weights for root network.
- `senate_vote`         Vote on an active proposal by hash.
- `register`            Register a wallet to the root network.
- `proposals`           View active triumvirate proposals and their status
- `delegate`            Delegate Stake to an account.
- `undelegate`          Undelegate Stake from an account.
- `my_delegates`        Show all delegates where I am delegating a positive amount of stake
- `list_delegates`      List all delegates on the network
- `nominate`            Become a delegate on the network


## stake (`st` `stakes`)		
Commands for staking and removing stake from hotkey accounts.

 - `show`             	List all stake accounts for wallet.
 - `add`              	Add stake to your hotkey accounts from your coldkey.
 - `remove`           	Remove stake from your hotkey accounts into their coldkey accounts.


## wallet (`w,` `wallets`)		
Commands for managing and viewing wallets.

- `list`                	List wallets
- `overview`            	Show registered account overview.
- `transfer`            	Transfer Tao between accounts.
- `inspect`             	Inspect a wallet (cold, hot) pair
- `create`              	Creates a new coldkey (for containing balance) under the specified path.
- `new_hotkey`          	Creates a new hotkey (for running a miner) under the specified path.
- `new_coldkey`         	Creates a new coldkey (for containing balance) under the specified path.
- `regen_coldkey`       	Regenerates a coldkey from a passed value
- `regen_coldkeypub`    	Regenerates a coldkeypub from the public part of the coldkey.
- `regen_hotkey`        	Regenerates a hotkey from a passed mnemonic
- `faucet`              	Register a wallet to a network.
- `update`				Update wallets to encrypt coldkey


## sudo (`su`, `sudos`)    	
Commands for subnet management

- `set`					Set hyperparameters for a subnet
- `get`					View subnet hyperparameters

## legacy					
Miscellaneous commands.

- `update`				Update bittensor
- `faucet`				Register a wallet to a network.
