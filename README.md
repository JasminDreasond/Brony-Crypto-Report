# Brony - Crypto Scammers List

This is a collaborative volunteer project. The purpose of this repository is to create a blacklist of scammer projects on the brony community. All websites have been reviewed by someone who has checked the source code and the status of the contract.

If you suspect any websites, feel free to check them here. If you would like to report any website, you can contact me.
If you are a smart contract programmer, feel free to help keep the project up to date via pull requests.

<hr/>

## How is the validation of contracts done?

First, the website source code is checked. I need to first validate which web3 connection API is being used so I can identify which contract is being executed.

After the contract is discovered, I go to the blockchain explorer of the crypto network identified. Arriving at the contract, I first check that the contract is validated and the source code is decompiled.

If the source code is hidden, it's already my first red flag that the project is a scammer.

If the code is visible, my next step is to use my programming knowledge of the solidity language to check what each function in the contract actually does. If suspicious code is found, it will be blacklisted by the website.

If the smart contract is an NFT, both the source code will be checked and it will be checked on which websites this NFT is present.

If the NFT have a lot of NFT websites that have banned the NFT contract address from being traded, this also raises the suspicion of being a scammer.