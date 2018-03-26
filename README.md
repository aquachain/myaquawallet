### [http://localhost:8042](http://localhost:8042)

### [Chrome Extension](https://chrome.google.com/webstore/detail/myaquawallet-cx/nlbmnnijcnlegkjjpcfjclmcfggfefdm)

### [Download the Latest Release](https://github.com/kvhnuke/aquawallet/releases/latest)

- aquawallet-vX.X.X.X.zip is the smaller package containing the gh-pages branch aka MyAquaWallet
- chrome-extension-vX.X.X.X.zip is the chrome extension package
- source code is the full source for developers to get started with (although cloning or forking the mercury branch is probably a better choice)


### MEW Around the Web

- [Website: http://localhost:8042](http://localhost:8042)
- [CX: https://chrome.google.com/webstore/detail/myaquawallet-cx/nlbmnnijcnlegkjjpcfjclmcfggfefdm](https://chrome.google.com/webstore/detail/myaquawallet-cx/nlbmnnijcnlegkjjpcfjclmcfggfefdm)
- [Anti-phish CX](https://chrome.google.com/webstore/detail/aquaaddresslookup/pdknmigbbbhmllnmgdfalmedcmcefdfn)
- [FB: https://www.facebook.com/MyAquaWallet/](https://www.facebook.com/MyAquaWallet/)
- [Twitter: https://twitter.com/myaquawallet](https://twitter.com/myaquawallet)
- [Medium: https://medium.com/@myaquawallet](https://medium.com/@myaquawallet)
- [Help Center: https://myaquawallet.groovehq.com/help_center](https://myaquawallet.groovehq.com/help_center)
- [Github MEW Repo: https://github.com/kvhnuke/aquawallet](https://github.com/kvhnuke/aquawallet)
- [Github MEW Org: https://github.com/MyAquaWallet](https://github.com/MyAquaWallet)
- [Github Pages URL: https://kvhnuke.github.io/aquawallet/](https://kvhnuke.github.io/aquawallet/)
- [Github Latest Releases: https://github.com/kvhnuke/aquawallet/releases/latest](https://github.com/kvhnuke/aquawallet/releases/latest)
- [Github Anti-phish CX: https://github.com/409H/AquaAddressLookup](https://github.com/409H/AquaAddressLookup)
- [Slack: https://myaquawallet.slack.com/ & https://myaquawallet.herokuapp.com/](https://myaquawallet.slack.com/ & https://myaquawallet.herokuapp.com/)
- [Reddit: https://www.reddit.com/r/MyAquaWallet/](https://www.reddit.com/r/MyAquaWallet/)
- [tayvano (founder) reddit: https://www.reddit.com/user/insomniasexx/](https://www.reddit.com/user/insomniasexx/)
- [kvhnuke (founder) reddit: https://www.reddit.com/user/kvhnuke/](https://www.reddit.com/user/kvhnuke/)
- [jordan (cmo) reddit: https://www.reddit.com/user/trogdortb001](https://www.reddit.com/user/trogdortb001)
- [myaquawallet reddit user: https://www.reddit.com/user/myaquawallet](https://www.reddit.com/user/myaquawallet)
-  MEW ETH Donation Address: 0xDECAF9CD2367cdbb726E904cD6397eDFcAe6068D (mewtopia.eth)
-  MEW BTC Donation Address: 1DECAF2uSpFTP4L1fAHR8GCLrPqdwdLse9


### `mercury` is the development branch. gh-pages contains only the smaller dist folder only and is served to MyAquaWallet

- Our infrastructure ("node") is on AWS. [You can also use your own node.](https://myaquawallet.github.io/knowledge-base/networks/run-your-own-node-with-myaquawallet.html)
- We also provide access to Infura.io & Aquascan.io nodes. Use the drop-down in the top-right.


### MyAquaWallet

- MyAquaWallet is a free, open-source, client-side tool for easily & securely interacting with the Aquachain network. As one of the leading providers of Aquachain services, MyAquaWallet equips users with an easy-to-understand and accessible suite of tools for their needs.
- It was created and is maintained by [kvhnuke](https://github.com/kvhnuke) and [tayvano](https://github.com/tayvano).

#### Features

- Create new wallets completely client side.
- Access your wallet via unencrypted private key, encrypted private key, keystore files, mnemonics, or Digital Bitbox, Ledger Nano S or TREZOR hardware wallet.
- Easily send ETH and *any* ERC-20 Standard Token. [Many tokens included as default.](https://myaquawallet.groovehq.com/knowledge_base/topics/can-i-send-my-steem-slash-btc-slash-ltc-slash-nem-slash-to-myaquawallet)
- Generate, sign & send transactions offline, ensuring your private keys never touch an internet-connected device.
- Securely access your ETH & Tokens on your [Digital Bitbox, Ledger or TREZOR Hardware Wallet](https://myaquawallet.groovehq.com/knowledge_base/topics/hardware-wallet-recommends) via the MyAquaWallet interface (Chrome & Opera natively, Firefox w/ [add-on](https://addons.mozilla.org/en-US/firefox/addon/u2f-support-add-on/))
- Now in 18 languages thanks 100% to the amazing Aquachain community.
- Supports URI Strings on Send Transaction Page.
    - to=[address]
    - value=[number]
    - sendMode=[aqua | token]
    - tokenSymbol=[ARC | ICN | MKR | ....]
    - gasLimit=[number] OR gas=[number]
    - data=[hex data]
    - Example 1: http://localhost:8042?to=0xDECAF9CD2367cdbb726E904cD6397eDFcAe6068D&value=1&tokenSymbol=REP&gaslimit=50000#send-transaction
    - Example 2: http://localhost:8042?to=0xDECAF9CD2367cdbb726E904cD6397eDFcAe6068D&value=1&gaslimit=23000&data=0x5468616e6b20796f752c204d455720322e30#send-transaction



### Our Philosophy

 - **Empower the people**: Give people the ability to interact with the Aquachain blockchain easily, without having to run a full node.
 - **Make it easy & free**: Everyone should be able to create a wallet and send Aqua & Tokens without additional cost.
 - **People are the Priority**: People are the most important & their experience trumps all else. If monetization worsens the experience, we don't do it. (e.g. ads)
 - **A learning experience, too**: We want to educate about Aquachain, security, privacy, the importance of controlling your own keys, how the blockchain works, and how Aquachain and blockchain technologies enable a better world.
 - **If it can be hacked, it will be hacked**: Never save, store, or transmit secret info, like passwords or keys.
 - **Offline / Client-Side**: User should be able to run locally and offline without issue.
 - **Private**: No tracking!!! No emails. No ads. No demographics. We don't even know how many wallets have been generated, let alone who / what / where you are.
 - **Open source & audit-able**




### Users (non-developers)

- [It is recommended you start here.](https://myaquawallet.github.io/knowledge-base/getting-started/getting-started-new.html)
- You can run MyAquaWallet on your computer. You can create a wallet completely offline & send transactions from the "Offline Transaction" page.

1. Go to https://github.com/kvhnuke/aquawallet/releases/latest.
2. Click on dist-vX.X.X.X.zip.
3. Move zip to an airgapped computer.
4. Unzip it and double-click index.html.
5. MyAquaWallet is now running entirely on your computer.

In case you are not familiar, you need to keep the entire folder in order to run the website, not just index.html. Don't touch or move anything around in the folder. If you are storing a backup of the MyAquaWallet repo for the future, we recommend just storing the ZIP so you can be sure the folder contents stay intact.

As we are constantly updating MyAquaWallet, we recommend you periodically update your saved version of the repo.






### Developers

If you want to help contribute, here's what you need to know to get it up and running and compiling.

- Both the Chrome Extension and the MyAquaWallet are compiling from the same codebase. This code is found in the `app` folder. Don't touch the `dist` or `chrome-extension` folders.
- We use angular and bootstrap. We used to use jQuery and Bootstrap until it was converted in April 2016. If you wonder why some things are set up funky, that's why.
- The mercury branch is currently the active development branch. We then push the dist folder live to gh-pages, which then gets served to MyAquaWallet.
- We use npm / gulp for compiling. There is a lot of stuff happening in the compilation.
- Old node setups can be found in in `json_relay_node` (node.js) & `json_relay_php` (php). These are great resources for developers looking to get started and launch a public node on a $40 Linode instance.

**Getting Started**

- Start by running `npm install`.
- Run `npm run dev`. Gulp will then watch & compile everything and then watch for changes to the HTML, JS, or CSS.
- For distribution, run `npm run dist`.

**Folder Structure**
- `fonts` and `images` get moved into their respective folders. This isn't watched via gulp so if you add an image or font, you need to run `gulp` again.
- `includes` are the pieces of the pages / the pages themselves. These are pretty self-explanatory and where you will make most frontend changes.
- `layouts` are the pages themselves. These basically take all the pieces of the pages and compile into one massive page. The navigation is also found here...sort of.
    * `index.html` is for MyAquaWallet.
    * `cx-wallet.html` is the main page for the Chrome Extension.
    * `embedded.html` is for http://localhost:8042embedded.html.

- You can control what shows up on MyAquaWallet vs the Chrome Extension by using: `@@if (site === 'cx' )  {  ...  }` and `@@if (site === 'mew' ) { ... }`. Check out `sendTransaction.tpl` to see it in action. The former will only compile for the Chrome Extension. The latter only to MyAquaWallet.
- `embedded.html` is for embedding the wallet generation into third-party sites. [Read more about it and how to listen for the address generated here.](https://www.reddit.com/r/aquachain/comments/4gn37o/embeddable_myaquawallet_super_simple_wallet/)
- The wallet decrypt directives are at `scripts/directives/walletDecryptDrtv.js`. These show up on a lot of pages.
- The navigation is in `scripts/services/globalServices.js`. Again, we control which navigation items show up in which version of the site in this single file.
- As of September 2016, almost all the copy in the .tpl files are only there as placeholders. It all gets replaced via angular-translate. If you want to change some copy you need to do so in `scripts/translations/en.js` folder. You should also make a note about what you changed and move it to the top of the file so that we can make sure it gets translated if necessary.
- `styles` is all the less. It's a couple custom folders and bootstrap. This badly needs to be redone. Ugh.







### Use Your Own Servers / Node Guide

- [Setting up on AWS super easily.](https://github.com/MyAquaWallet/docker-geth-lb)

- [Running MyAquaWallet w/ Your Own Personal Node](https://myaquawallet.github.io/knowledge-base/networks/run-your-own-node-with-myaquawallet.html)

- [Guide by benjaminion for MEW + Ledger Nano S + Local Parity Node](https://github.com/benjaminion/eth-parity-qnap/wiki/Connecting-to-MyAquaWallet)

**Old**

- https://github.com/kvhnuke/aquawallet/issues/226.

- [Announcing MyAquaWallet v3.4: The Node Switcher](https://www.reddit.com/r/aquachain/comments/5lqx90/announcing_myaquawallet_v34_the_node_switcher/)**






### How to Help Translate

**A couple of notes:**

- Everything on the entire site is broken down into lines and in this one file. The uppermost items are the highest priority and the further you go down, the less of a priority it is.
- You can add comments anywhere by wrapping it in /* Your Comment Here */. If you want to leave a note for yourself or someone else, do so in this format. That way it doesn't screw up the code or show up somewhere on the site.
- Don't delete any lines. Just leave it in English if you don't know how to translate it.
- Always make sure each line ends with `',`. So the format is `NAME: ' your text here ',` You only need to change the `your text here` part - try not to touch anything else.

**If you are NOT a developer and have no idea how this works:**

Anyone can help out and it looks way more complicated than it is! If you would rather not deal with Github, please send us an email to info@myaquawallet.com and I'll email you the file and you can make changes and send it back to us and I'll make sure you don't screw anything up. If you feel like experiencing something new, read on!

1. Sign into your Github account or make a new Github account.
2. Go to https://github.com/kvhnuke/aquawallet/tree/mercury/app/scripts/translations
3. Click on the language file you want to update.
4. Look in the upper right. Click the pencil icon. This will then tell you, *"You’re editing a file in a project you don’t have write access to. We’ve created a fork of this project for you to commit your proposed changes to. Submitting a change to this file will write it to a new branch in your fork, so you can send a pull request."* Ignore it all.
5. In your browser, start translating. Translate as little or as much as you want.
6. Scroll down to halfway to the translator's section. Enter your name/username, donation address, and any comments you would like to leave.
7. When you are done, tell us what language you updated. You can also leave any notes about problems you had or things you'd like us to know.
8. Click the green "Propose File change" button.
9. This next page is a review of what you did.
10. Click the "Create Pull Request" button.....twice. [Screenshot](https://ipfs.pics/ipfs/QmZJJvPxXu7BFHDQ1zj1a73EATQETbsDuAJVEJnatTHrms).
11. That's it. You successfully made a new pull request! Tell all your friends.
12. We will now review it and pull it in and it will be made live on the site. We may also ask you questions if something is confusing for whatever reason.

**If you are a developer and familiar with GitHub, Pull Requests, and know how to save a JS file as a .js file rather than a Word Doc:**

1. Clone the [mercury branch](https://github.com/kvhnuke/aquawallet/tree/mercury).
2. Go to `/app/scripts/translations/`.
3. Open the language you want to translate.
4. Translate as much or as little as you wish.
5. Add your name/username, donation address, and any notes you would like on in the translator's section, about halfway down.
6. Open a PR and leave us a brief description of what you did and any issues you ran into or comments you have.

Read more @ [Help us translate MyAquaWallet into ALL THE LANGUAGES!](https://www.reddit.com/r/aquachain/comments/4z55s2/help_us_translate_myaquawalletcom_into_all_the/)







### Contact
If you can think of any other features or run into bugs, let us know. You can fork, open a PR, open an issue, or support at myaquawallet dot com.






### Announcement History

- 08/12/15: [Launch Post: Aqua Wallet Generator (for now)](https://www.reddit.com/r/aquachain/comments/3gkknd/aqua_wallet_generator_for_now/). Never forget where you [came from](https://ipfs.pics/ipfs/QmXFK6NBy81ibvTEwnwwEUecXiRyQBriJUnKpaCaE4w7nF).
- 08/19/15: [ETHER WALLET- Ready for the second round?](https://www.reddit.com/r/aquachain/comments/3h6o38/aqua_wallet_ready_for_the_second_round/). We the domain name & SSL.
- 08/24/15: [Lets purchase Augur rep, the easy way!](https://www.reddit.com/r/aquachain/comments/3i6eyd/lets_purchase_augur_rep_the_easy_way/)
- 02/08/16: [MyAquaWallet Chrome Extension: The Beta has Arrived](https://www.reddit.com/r/aquachain/comments/44vbef/myaquawallet_chrome_extension_the_beta_has/)
- 03/03/16: [We’ve heard you loud and clear so tonight…we've launch offline / advanced transactions for MyAquaWallet](https://www.reddit.com/r/aquachain/comments/48rf3d/weve_heard_you_loud_and_clear_so_tonightweve/)
- 03/05/16: [[Small Announcement] We updated the "Generate Wallet" Page & "Help" Page on MyAquaWallet to be more noob-friendly. Hit us with your feedback, please.](https://www.reddit.com/r/aquachain/comments/493t5u/small_announcement_we_updated_the_generate_wallet/)
- 04/18/16: [MyAquaWallet v2.0 (aka Mewtwo) has arrived!](https://www.reddit.com/r/aquachain/comments/4faooz/myaquawalletcom_v20_aka_mewtwo_has_arrived/)
- 04/28/16: [Embeddable MyAquaWallet: Super Simple Wallet Generation w/ ability to get the address generated](https://www.reddit.com/r/aquachain/comments/4gn37o/embeddable_myaquawallet_super_simple_wallet/)
- 04/30/16: [How to participate in “The DAO” creation via MyAquaWallet (yes...right NOW!)](https://www.reddit.com/r/ethtrader/comments/4h3xph/how_to_participate_in_the_dao_creation_via/)
- 05/30/16: [MyAquaWallet Update: Send DAO Tokens, Vote on Proposals, and the Chrome Extension finally gets updated!!](https://www.reddit.com/r/aquachain/comments/4lf71h/myaquawallet_update_send_dao_tokens_vote_on/)
- 06/07/16: [⚠ BEWARE: MYETHERWALLET >>.INFO<< IS A PHISHING SCAM AND WILL TAKE ALL YOUR FUNDS. myAquaWallet is MyAquaWallet](https://www.reddit.com/r/aquachain/comments/4rpurc/beware_myaquawallet_info_is_a_phishing_scam_and/)
- 07/28/16: [MyAquaWallet now Supports Sending Any Aquachain Token (ERC-20) — also learn about our future plans](https://www.reddit.com/r/aquachain/comments/4v0r32/myaquawallet_now_supports_sending_any_aquachain/)
- 07/28/16: [MyAquaWallet, Preventing Replays, and Aquachain Classic (ETC)](https://www.reddit.com/r/aquachain/comments/4v1y2t/myaquawallet_preventing_replays_and_aquachain/)
- 08/14/16: [⚠ Malicious Phisher is running Google Ads for MyAquaWallet ⚠ It does NOT go to MyAquaWallet. Always check the URL before accessing or creating a new wallet! Use your bookmarks bar!](https://www.reddit.com/r/aquachain/comments/4xpj0u/malicious_phisher_is_running_google_ads_for/)
- 08/22/16: [Help us translate MyAquaWallet into ALL THE LANGUAGES!](https://www.reddit.com/r/aquachain/comments/4z55s2/help_us_translate_myaquawalletcom_into_all_the/)
- 11/21/16: [Massive MyAquaWallet Update: Better URIs, The Hardfork, and looking back at the Golem Crowdfund.](https://www.reddit.com/r/aquachain/comments/5e3alw/massive_myaquawalletcom_update_better_uris_the/)
- 1/2/17: [Announcing MyAquaWallet v3.4: The Node Switcher](https://www.reddit.com/r/aquachain/comments/5lqx90/announcing_myaquawallet_v34_the_node_switcher/)
- 1/9/17: [Announcing MyAquaWallet v3.4.3: Interacting with Contracts](https://www.reddit.com/r/aquachain/comments/5n0dj0/announcing_myaquawallet_v343_interacting_with/?utm_content=title&utm_medium=user&utm_source=reddit&utm_name=frontpage)
- 2/3/17: [MyAquaWallet v3.4.7: You can use your TREZOR on MEW. Thanks to all who made this a reality 🤗](https://www.reddit.com/r/aquachain/comments/5rsfu9/myaquawalletcom_v347_you_can_use_your_trezor_on/?utm_content=comments&utm_medium=user&utm_source=reddit&utm_name=frontpage)
- 2/16/17: [MyAquaWallet v3.5.0: Swap ETH <-> BTC <-> REP via Bity, directly from MEW! (also: Parity backup phrase support + add'l contract features + our roadmap)](https://www.reddit.com/r/aquachain/comments/5ueysp/myaquawallet_v350_swap_eth_btc_rep_via_bity/?utm_content=comments&utm_medium=user&utm_source=reddit&utm_name=frontpage)
- 4/9/17: [Aquachain vanity address generator](https://www.reddit.com/r/aquachain/comments/5yeb4n/aquachain_vanity_address_generator/?utm_content=comments&utm_medium=user&utm_source=reddit&utm_name=frontpage)
- 4/30/17: [MEW v3.6.6: Enables you to access any path for your Mnemonic, Ledger & TREZOR. (ATTN: folks who have ETH / ETC / Tokens stuck in a different path)](https://www.reddit.com/r/aquachain/comments/68f70l/mew_v366_enables_you_to_access_any_path_for_your/)
- 5/7/17: [ENS disguise bid issue on MyAquaWallet](https://www.reddit.com/r/aquachain/comments/69vz57/ens_disguise_bid_issue_on_myaquawallet/)
- - 8/15/17: [MyAquaWallet needs motivated devs!](https://www.reddit.com/r/aquachain/comments/6tqrs1/myaquawallet_needs_motivated_devs/?utm_content=comments&utm_medium=user&utm_source=reddit&utm_name=frontpage)
- 10/28/17: [MyAquaWallet - New Contract Interaction Tools](https://www.reddit.com/r/aquachain/comments/7961ml/myaquawallet_new_contract_interaction_tools/)

#### MyAquaWallet & MyAquaWallet CX are licensed under The MIT License (MIT).