# Running Bittensor locally on your Mac (or Windows)

## Install and setup Conda

1. Download the Bittensor yaml file they made with all depenencies: [Bittensor YAML file](https://github.com/opentensor/bittensor/blob/master/scripts/environments/apple_m1_environment.yml)

2. If you don't have Conda (miniconda is fine it is conda and python, all you need) installed, do so here: [Downlad Miniconda](https://docs.conda.io/projects/miniconda/en/latest/) I did the Apple M1 bash script to my machine then ran it form there.

3. Create the conda environemt: `conda env create -f apple_m1_environment.yml` - i am going to assume those dependencies are pretty much the same for windows too.

4. Activate the new environment: `conda activate bittensor` (remember this command, you will need to do it for each new terminal session)

5. Verify that the new environment was installed correctly: `conda env list`


## Install Bittensor

6. Time to install Bittensor `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/opentensor/bittensor/master/scripts/install.sh)"`

7. Test your Bittensor installation with `btcli -h` - [Bittensor CLI Cheat Sheet](https://github.com/TaoStats/bittensor-resources/blob/main/btcli_cheat_sheet.md)


## Using Bittensor locally

8. Regenerate or Generate your keys (`btcli w new_coldkey`/`btcli w new_hotkey` or `btcli w regen_coldkey`/`btcli w regen_hotkey`)

9. Perform basic actions like check accounts (`w list`) balances (`w inspect`), delagate (`r delegate`) and transfer (`w transfer`)

## Managing and Maintaining your installation

10. Update Bittensor to latest version

`git fetch origin main`

`git checkout main`

`git pull `

`python3 -m pip install -e .`


11. Switch to another branch of Bittensor and back

`git fetch origin revolution`

`git checkout revolution`

`git pull `

`python3 -m pip install -e .`


## Misc

Configure mac terminal to look as good as mine - [Find out how here](https://www.youtube.com/watch?v=CF1tMjvHDRA)
