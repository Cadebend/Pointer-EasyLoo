# Pointer-EasyLoo

follow my step to create your own pointer-NFT easily.

if u like this course , tip me on any network.

erc : 0x707cC7ff415DA0262a153c853c0E34e7D6D6cAdc

trc : TNJ9WwrTuDQMPaQ4NyvqSbNkbNXJid67iy

# Preparatory work

Get test coins (matic,link) : https://faucet.polygon.technology

Login thirdweb create a new project : https://thirdweb.com/dashboard

![image.png](https://cdn.steemitimages.com/DQmXmJhgCEXMFUvXhEwEXQzTpUHEjyDuxqxN9Nt6b4D39rD/image.png)

# First 
~~~
git clone https://github.com/laoma6/Pointer-EasyLoo
npm install
npm install @3rdweb/sdk ethers dotenv
~~~

Put your private key in .evm `WALLET_PRIVATE_KEY=`

Put your project id in .evm `THIRDWEB_PROJECT=`

## Create bundle
`node 1-create-bundle-module.js`

![image.png](https://cdn.steemitimages.com/DQmXqrGM2KaCwtcPZtbpcctBX4JMLprShX4zWJBcE5qkTLH/image.png)

Paste the address in .evm `THIRDWEB_PROJECT=`

## Create cards
`node 2-mint-bundle-nfts.js`

`node 3-create-pack-module.js`

After node 3 you'll get an address

![image.png](https://cdn.steemitimages.com/DQmZ3trX9JhXr3zXaCD7bNUq7c54GKxfAXzT3ND2Wi7x5cF/image.png)

Paste the address in .evm `PACK_ADDRESS=`

## Open pack

Use 3 codes to open

`node 4-create-pack-from-bundle.js`

`node 5-deposit-link.js`

`node 6-open-pack.js`

We got a Tesla!

![image.png](https://cdn.steemitimages.com/DQmQM2Vwkxj9XgdtbUcr51kr99t7EzbJFhmMSzPGT4gGCvU/image.png)

![image.png](https://cdn.steemitimages.com/DQmVJxZoDUox835VwZ8nU9gn1uV5GP4CeCE9dPwMEF3i9VS/image.png)

## Rewards

https://www.pointer.gg/tutorials/thirdweb-nft-lootbox

Pull to the bottom , submit your PACK_ADDRESS in .evm

![image.png](https://cdn.steemitimages.com/DQmRnTDSnGp1a9fCykvCdhQG6xisrEeuAxijy9gpEK6Yawm/image.png)

## End

What I wrote above is a quick way to get rewards. If you are interested in creating NFT card package, it is strongly recommended to read the whole tutorial, which is very good.
