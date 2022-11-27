# Expanded Guide: Storefronts

This guide covers:

- [About Storefronts](#about-storefronts)
- [How to Add Listings](#how-to-add-listings)
- [How to Edit and Close Listings](#how-to-edit-and-close-listings)
- [How to Claim Royalties](#how-to-claim-royalties)
- [Guide Links](#guide-links)

## About Storefronts

Storefronts are a way for creators to monetize their work and for readers to support their favorite authors and illustrators on Spindle. Content creators can sell NFTs related to their stories published on Spindle using the [Spindle Storefronts](https://www.spindle-asa.com/store). 

Only wallets whitelisted for stories published on Spindle can add NFT listings. If you want to whitelist a wallet for your story, contact us on the [Spindle Discord](https://discord.gg/D8P9esv6Vn) or via [email](mailto:contact@spindle-asa.com).

The royalty functionality of the underlying smart contract allows to add multiple collaborators to a listing who can claim royalties from the sales. This way, co-authors, illustrators, etc. do not have to struggle to handle the payouts from sales.

## How to Buy

Support your favorite Spindle writers and illustrators and buy NFTs related to their stories. You can use the search and filter functionality to find the creators or NFTs you are looking for.

![filter](/images/storefronts/filter-dark.jpg)

If you haven't already, connect your wallet and then click on the ‘Buy’ button underneath the NFT you want to buy.

![filter](/images/storefronts/buy-dark.jpg)

Creators can choose whether they want to offer their NFTs for ALGO, YARN, or both. Select the currency you want to pay with and enter how many units of the NFT you want to buy. Finally, sign the prompted transactions to receive the NFT(s).

## How to Add Listings

To add a listing, you must connect a wallet to the Spindle ASA website. The connected wallet must be whitelisted for a story to be able to add a listing to the story's storefront. If you use the wallet that also receives tips or voting cards for a story, it is already whitelisted. If you want to whitelist additional wallets for your story, contact us on the [Spindle Discord](https://discord.gg/D8P9esv6Vn) or via [email](mailto:contact@spindle-asa.com).

After you connected your wallet, click on the ‘+’-Symbol and you will be forwarded to a form where you can input all relevant information for the listing.

![add-listing](/images/storefronts/add-listing-dark.jpg)

### Enter Information

**Related Story.** Only ASAs / NFTs which are related to a story are allowed to be listed. Unrelated listings can be [reported](mailto:contact@spindle-asa.com) and will no longer be shown on the website. All listings will be grouped by their related story on the [Spindle Storefronts](https://www.spindle-asa.com/store) page.

**ASA / NFT.** Select an asset that is related to your story published on Spindle. The asset can be unique or multi-mint. Currently, we do not offer to mint new ASAs / NFTs through our website. To mint assets, you can use services, such as [Rand Gallery](https://www.randgallery.com/algo-collection/), [AB2 Gallery](https://ab2.gallery/manage) or [Algogems](https://www.algogems.io/create).

[Mint NFTs](/videos/Spindle_Mint_NFT.mp4)

**Quantity.** Enter how many units of the selected asset you want to list for sale. You can change the amount later by adding or withdrawing units of your asset. 

**Price Per Unit.** You can accept ALGO, YARN or both. The prices are independent of each other and you can still change them later.

**Royalty Receivers.** The royalty functionality of the underlying smart contract allows to add multiple collaborators to a listing who can claim royalties from the sales. This way, co-authors, illustrators, etc. do not have to struggle to handle the payouts from sales.

Spindle takes a fee of 2.5% of the sales price. The remaining 97.5% can be split among up to 7 other wallets/collaborators. The payouts are not automatic, so each collaborator can decide for themselves when to claim their royalties.

![royalty-receivers](/images/storefronts/royalty-receivers-dark.jpg)

Make sure the entered wallets exist and that the collaborators are informed on [how to claim royalties](#how-to-claim-royalties). If the royalties are not claimed, they will remain in the contract indefinitely.

### Create Listing

Click on the ‘Create listing’ button to deploy the smart contract. You will have to sign 3 transaction groups. Funding the contract costs 0.4 ALGO (+ transaction fees). This is because Algorand wallets require a minimum balance to hold ASAs. You will get the funding back when you close the listing, but the listing can only be closed when there are no unclaimed royalties.

After signing the transactions with your preferred wallet, your listing should show up on your story's storefront.

## How to Edit and Close Listings

Find the listing you want to edit on the [Spindle Storefronts](https://www.spindle-asa.com/store) page. You can use the filter functionality to easily find the listing you are looking for, e.g only show your listings or search for the name of your story.

![filter](/images/storefronts/filter-dark.jpg)

If you are connected with the wallet that created the listing, an ‘Edit’ button will be visible underneath the listed ASA / NFT. When you click on it, you will be forwarded to the edit form.

![edit](/images/storefronts/edit-dark.jpg)

**Change Prices.** You can change the price, e.g. accept YARN if you haven't before or ask for a higher price. You will have to sign a transaction to save the changes.

**Withdraw Asset(s).** You can withdraw some or all of the ASAs / NFTs for a listing. You don't have to withdraw the assets before you close the listing. The remaining assets will be sent to you automatically when closing the listing. You will have to sign a transaction to withdraw the assets.

**Add Asset(s).** You can add more ASAs / NFTs to the existing listing. You will have to sign a transaction group to add the assets.

**Close Listing.** This will terminate the smart contract and send the remaining assets to your wallet. You will have to sign a transaction to close the listing. To be able to do this, all collaborators must claim or must be sent their royalties (if there are any royalties). You can check the unclaimed royalties by clicking on the ‘Claim royalties’ link.

## How to Claim Royalties

Find the listing you want to claim royalties for on the [Spindle Storefronts](https://www.spindle-asa.com/store) page. You can use the filter functionality to only show listings where you can claim royalties.

![filter-royalties](/images/storefronts/filter-royalties-dark.jpg)

If you are connected with a wallet that is a collaborator of a listing, a ‘Royalties’ button will be visible underneath the listed ASA / NFT. When you click on it, you will be forwarded to the royalties overview.

![claim-royalties](/images/storefronts/claim-royalties-dark.jpg)

The creator of the listing can view all royalties, other collaborators can only view their own. 

Your unclaimed royalties will be sent to your wallet when you click on ‘Claim royalties’ and sign the transaction. If you are the creator of a listing, you can also decide to send the royalties to a collaborator by clicking ‘Send royalties’ (e.g. if you want to close the listing and do not want to wait for collaborators to claim their royalties. However, in this case, you will have to pay the transaction fees). For YARN payouts this will only work if the collaborator is already opted-in to YARN (ASA ID #544217506).

<br>
<br>

## Guide Links

- [Start Here](/start-here.md)
- [Beginner’s Guide to Crypto](/crypto.md)
- [Expanded Guide: Fiction](/fiction.md)
- [Expanded Guide: Voting](/voting.md)
- [Expanded Guide: Storefronts](/storefronts.md)
- [Expanded Guide: Warp & Weft](/warp-and-weft.md)
- [Expanded Guide: Spindle ASA](/spindle.md)
