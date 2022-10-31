# NFT-Generator

![Forks](https://badgen.net/github/forks/SPROKTAL/NFT-GENERATOR?icon=github&scale=1.2&color=red&cache=300) &nbsp;
![Stars](https://badgen.net/github/stars/SPROKTAL/NFT-GENERATOR?icon=https://upload.wikimedia.org/wikipedia/commons/a/a3/Orange_star.svg&scale=1.2&color=orange&cache=300) &nbsp;
![License](https://badgen.net/badge/license/MIT/purple?scale=1.2) &nbsp;

**NFT-Generator** is the best way to generate thousands of NFTs quick and easily with Python. Just add your files, set your configuration and run the script. You'll get all the images and metadata required for your NFT project!

## How to use?

1. Install the dependencies by running `pip install -r requirements.txt`
2. Add all your layer files in the 'traits' folder. They should be separated in different layer folders.
3. Add the probability of each trait. You can do this by adding the number after a '#' in the file name. For example, if the 'Background' layer had two files called 'Black#50.png' and 'White#50.png' then there would be a 50% chance of each being selected.
4. Edit the `config.py` file with your settings.
5. Run `generator.py`

:warning: **Important:** you can't use the traits files provided in the repo
