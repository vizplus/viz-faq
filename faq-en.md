# VIZ FAQ

The given document is addressed mainly to beginners. It answers the questions that may arise while working with VIZ. Communication with other VIZ users, application manuals and independent study of the ecosystem of digital social capital will help you with the remaining aspects of the service.

***

### Content:

[General issues](#general-questions)

- How is it correct to write the name of the application - VIZ or viz?
- How do I use social capital?
- How should I act if something is not working?

[Accounts and keys](#accounts-and-keys)

- How do I create an account?
- How do I create a subaccount?
- How do I give a new account to another person as a gift?
- How do I change my account keys?
- How do I recover lost keys?
- How do I buy or sell a custom account?
- How do I view the history of actions in my own or someone else’s account?

[Digital Social Capital](#digital-social-capital)

- How do I reward other VIZ participants?
- How do I connect my account to the app?
- How do I increase social capital?
- How do I delegate social capital?

[Energy](#energy)

- How do I use energy in VIZ?
- How is energy restored?
- How is the minimum possible reward determined?

[Viz tokens and cheques](#viz-tokens-and-cheques)

- How do I get liquid viz tokens?
- How do I transfer viz tokens from one account to another?
- How do I use checks?

[Delegates and the DAO Fund](#delegates-dao-fund)

- How do I elect DAO delegates?
- How do I vote for applications to the DAO Fund?

[Best Practices](#best-practices)

- How is it more convenient and safer to use VIZ?

## General questions

### What is correct: VIZ, Viz or viz?

There is nothing "right" or "official" about VIZ. There are different points of view, which are accepted by majority or minority of participants and services. We in VIZPLUS decided that:

- **VIZ** is an ecosystem which means all applications, blockchain, tokens, instructions and everything else related to VIZ;
- **Viz or "blockchain VIZ"** is just the blockchain, the most important software, the "core" of the ecosystem. We don't usually write its name in Russian;
- **viz** is a unit of measurement of social capital. A person's height is measured in centimeters, weight in kilos and social capital in viz. We don't like to call viz "coin" or "cryptocurrency" as it doesn't refer to money, but is more like grades, rating points or even airline miles. When we talk about vizes as a means of capital accumulation, we call them "tokens" in analogy to the tokens of other blockchains and blockchain apps.

You can write and speak as you like so that others understand you correctly.

### How to use social capital?

You can use social capital (as well as other Viz blockchain features) via apps. These apps help you to reward people, vote, thank and do other things with social capital.

The apps create a *context of using* of social capital, in other words they tell you *why* to use it:

- to reward the author of an interesting article on the Internet (click "like" on the website);
- пvote for the best player at a match by pointing your phone at the QR code on the screen;
- make choice on a dating site (attract attention with a solid award);
- to thank for a useful tip in the chat (write "thank you" phrase and bot will turn it into reward)...

The context depends only on the imagination of the app creators. Technically, apps translate your "social" actions with different context into standard blockchain language and conduct the transaction on your behalf.

### What to do if something goes wrong?

Newcomers VIZ members sometimes find themselves in a situation where "something didn't work": the reward didn't come, the tokens didn't transfer to another account, the delegation cancellation didn't happen, etc. Why does this happen and what should be done?

Obviously, you should first make sure that you **don't do an impossible operation**, such as delegating 1200 viz if you only have 800 viz available in your capital. Or you are trying to use 5% of energy while you have only 3% of it left.

In the vast majority of cases, however, the application's refusal to perform a transaction means that the user typed the **private key incorrectly**.

Firstly, the key should match the transaction you are trying to do: different types of keys are used for different transactions in the Viz blockchain. This makes life a little more complicated, but makes using Viz much more secure. The right app should tell you which key you need to enter (simple, active or even master). Properly save keys with an appropriate description (sometimes users confuse key levels when saving) and check carefully which key you enter.

Secondly, quite often when copying a key from a storage location to an app, users accidentally forget 1-2 characters or on the contrary pick up an extra character at the beginning or at the end (space, comma, etc.). The keys are long, anyone can make a mistake. Make sure you copy the key exactly.

Less frequently the **app is wrong** or the **blockchain node is down** (server the app communicates with to record your transaction), but it's still a possibility that can't be precluded. The right app will tell you what error has occurred and how to avoid it, in such a case follow the instructions. If something is not clear at all, wait a couple of minutes and try again.

Finally, the rarest but the most possible variant: you **don’t have enough social capital** to perform the transaction. This happens either with very smal accounts, e.g. with 0.1 viz in capital or with a very heavy load on the blockchain (usually during a spam attack).

The point is that the Viz blockchain has a speed limit of recording information from users, so when the load is heavy, it queues up transactions that come in for saving. The transactions of the accounts with the biggest capital are executed first, then the ones with less capital, and so on. In addition, if a transaction from the tail of the queue isn’t in the nearest record (block), it is rejected.

One more time: a spike in blockchain activity is a rare occurrence. Accounts with at least a few vizes in capital shouldn’t have any problems with recording of transactions.

If you have followed all the recommendations and something is still wrong, contact the creators of the app or chat rooms and more experienced users can help you. For example, there is a group on Telegram for mutual help [VIZ+Help](https://t.me/vizplus_help).

## Accounts and keys

### How to create an account?

The operation of creating an account in viz requires the use of a small amount of social capital or viz tokens. These assets are not spent but are transferred to the new account and frozen on it for a period of time.

The amounts are set by the delegates and can be rarely changed. Now they are **at least 10 viz by delegating capital or at least 1 viz by transfer from wallet**. So, to create a new account, you should already have an account with a small amount of viz or a cheque for the required amount.

However, there are kind people in the VIZ ecosystem who use their resources to help newcomers to create accounts. For example, VIZPLUS has this service: [start.viz.plus](https://start.viz.plus). In other words, **you can create an account for free** (at someone else's expense) if it’s necessary, but you shouldn't misuse it as well as any help.

**At your own expense**, you can create accounts in apps that allow you to do so. This feature is available, for example, in My Account [my.viz.plus](https://my.viz.plus), the social telegram bot and other apps.

To create a new account using your existing account’s expense, you need to sign in to one of the appropriate apps, enter the name of your new account in correct section, choose a payment method (from capital or from your wallet) and click "Create" or a similar button. Now the app checks if there is an account with the same name, if you have enough assets. If everything is OK, it will proceed with the operation of creating a new account. You'll receive the keys to your new account, which you'll need to keep in a few safe places.

You may also create an account and **pay the required amount in cheque**. The scheme is the same: use an app that provides this service, enter the name of new account and the secret part of the cheque. If everything's OK, you’ll get the keys.

Finally, there is a slightly more complicated way **using a special "anonymous" account**. First, you have to create a key (public and private parts) and transfer the necessary amount to "anonymous" by writing `account:key` (without spaces) in the comment, where `account` is the name of new account and `key` is the **public part** of the key. The transfer can be made from anywhere, e.g. exchange or stocks, which makes the new account virtually anonymous. On the other hand, with services like [start.viz.plus](https://start.viz.plus), where new accounts are initially completely anonymous, this option doesn’t make much sense.

### How to create a subaccount?

A subaccount can only be created if you use the resources and sign the account or a subaccount from the previous level. For example, if you have an account `primer`, you can create subaccounts `second.primer`, `new.primer` etc. However, the next level subaccount `exactly.new.primer` can only be created by using the active key from `new.primer`. The key from `primer` won’t help anything in this case.

The cost of creating a subaccount is the same as for an account.

The app that you use to create a subaccount will ask for the active key from the previous account level (or use it in default, if you entered it when you logged in).

Otherwise, everything is simple: check that you have enough assets, enter the name of the subaccount and the amount of tokens you want to transfer or delegate to it, and click "Create".

### How to give a new account to someone else?

If you want to give an account with a specific name, **create it yourself** and give the person the master key for the new account, reminding him/her to reset the keys and save the new ones so you can't use his/her account. You can't reset keys until at least an hour after the account is created or after a previous reset.

If you prefer to let the person choose the name of the new account, **give him/her a cheque** for any amount from 1 viz or more. In this case, the cheque acts as an invite. The person will create an account at [start.viz.plus](https://start.viz.plus) by entering the secret part of the cheque at the appropriate step. The whole amount of the cheque will transfer to the social capital of the new account.

### How to change account keys?

The easiest way to change the keys is to reset them, i.e. using one button in the app you have to renounce all your old keys and get new ones. This requires you to enter a master key.

If you want to change only one key, go to Accounts - Account Accesses in My Account [my.viz.plus](https://my.viz.plus), find the access you need, generate a new one (there is a special button for this), add it, write it in several places and then delete the old key. You’ll also need to enter a master key for this operation.

###How to recover lost keys?

If you **lost your master key**, you can’t recover it or get a new one. It’s also impossible to change other keys in this case (but you can use them). If you lose your master key (and keep your active key) we strongly recommend you to create a new account and add all your vizes to it, and simply forget about the old one. If you lose all your keys, you'll have to accept this life lesson.

If your **master key was stolen** and changed, but you still have your old one, you can try to regain access to your account through a special and very complicated procedure. You'll have to find the owner of the account you used to create your account and ask him/her to perform a special access recovery transaction. Unfortunately, VIZPLUS doesn’t provide this service for accounts created via [start.viz.plus](https://start.viz.plus).

If **less significant keys are lost**, reset them as described above and save the new keys in a more secure place. 

### How to buy or sell a pretty account?

VIZ has a unique feature: an account marketplace built right into the blockchain. You can put any account or subaccount up for sale or buy one you like with a couple of clicks using the corresponding app. Payment is in vizes, of course. On [my.viz.plus](https://my.viz.plus) you’ll find a dedicated section.

Putting an account up for sale costs a small amount in viz, this’s done to protect the blockchain from spam bids. In addition, to prevent attackers from quickly selling a stolen account, it’ll only be available for purchase 7 days after being put up for sale.

Also, the owners of pretty accounts can allow anyone to create any subaccounts for a donation. This is similar to the Internet domain registration: for example, you can create any (free) subaccount for `com` or `blog` account and so on. The owner of the primary account, however, won’t be able to do anything with the new subaccount, because he doesn't know keys.

### How to view an account history?

On [info.viz.plus/accounts](https://info.viz.plus/accounts) you can find information about accounts and subaccounts created by VIZ members. If you know the name of the account you are interested in, start typing it in the search box on the page, all matching accounts will immediately appear below. When you click on the name, the account page will open with all its details and history.

There you can also find various sorted lists of accounts.

Not all accounts and transactions are displayed on [info.viz.plus/accounts](https://info.viz.plus/accounts) as the blockchain is periodically raided by spammers who create a lot of meaningless transactions that are removed from the site.

All transactions in raw form, without filtering, are presented in the [VIZ-API](https://api.dpos.space/viz/api/account_history/get_account_history) service. Specify the account name, the number in order of last transaction you need, and the amount of earlier transactions to display. A little trick: if you want to see just the last 20 transactions, and don't know the number of the most recent one, enter -1 instead.

## Digital Social Capital

### How to reward other VIZ members?

The main way to reward other people in VIZ is by using appropriate apps. For example, the "social" bot in Telegram allows you to reward participants in discussions in groups where it is switched on. To do this, just start a reply to someone's comment with a "+" sign (from one to five, the size of the reward depends on this), and the author of the comment will receive a reward, i.e. increase his or her social capital. In Telegram channels with the same bot, a button appears below the posts to reward the author.

On the social network [Readdle.Me](https://readdle.me/), an award button is onboarded directly in pages with posts. 

A special plugin for Chrome([link](https://chrome.google.com/webstore/detail/vizonator/iehoehfkanaobnbldjfjfabbpaiiojnp)) and Firefox ([link](https://addons.mozilla.org/ru/firefox/addon/vizonator/)) adds its reward button to pages and posts on Twitter, YouTube and some other sites, as if it was supposed to be there.

A list of applications can be seen on the homepage of [viz.plus](https://viz.plus). Gradually, many services on the Internet and in real life will be framed by apps (stand-alone or universal) for awards in VIZ.

The second way to reward someone is to do it directly, by the name of the recipient account. To do this, in My Account [my.viz.plus](https://my.viz.plus) find the page to reward, enter the name of the account being rewarded in the appropriate field and select the percentage of energy used. If you want, you can add a comment to the recipient, to explain why you're giving the reward. Remember that your energy usage is only 20% per day, so be careful.

### How to connect an account to the app?

There are two ways to connect an account to any app in VIZ. The first is **transferring to the app the necessary private key** (simple or active) from your account. The second is **granting the app the right to act on behalf of your account** without transferring a key. When you connect, the app will ask you for permission to act in one or another way.

Tips about how to keep yourself as safe as possible when using apps in VIZ, you can find in the Best Practices section on this page below.

### How to increase social capital?

Your digital social capital increases when other people reward you in gratitude for something. So, the most obvious and correct way to increase your social capital is to **provide other people with benefit or pleasure**.

A simpler and quicker option is to **purchase some viz tokens** and put them into capital. There isn’t and can’t be a single seller of tokens in VIZ. The system is decentralised, so participants sell and buy viz from each other at a negotiated price.

The sale and purchase of vizes is offered in some apps, as well as in crypto-exchanges (including money) and crypto-stocks. There are also "shops" where you can quickly and easily buy viz-cheques. In addition, it’s always possible to negotiate a direct deal with another participant in popular VIZ chat rooms. You’ll find links to many of the relevant resources on our homepage.

Social capital can also be rented. In this case you pay another VIZ member some money and get the agreed amount of capital by delegation for a certain period of time.

### How to delegate social capital?

Social capital can be delegated temporarily (until you withdraw it) to another account. The recipient only uses it, but can’t withdraw it into tokens, steal it, sell it or give it to someone else. This function is called "delegating" social capital.

The easiest way to delegate social capital is through an app, such as My Account [my.viz.plus](https://my.viz.plus), where it can done with a couple of clicks in the relevant section. Other apps may also offer this option. Be careful and **check** who is asking you to delegate capital and why. Nothing bad will happen anyway, but if scammers use your capital for something illegal, it will be a shame.

To withdraw delegated capital, contact the same app or any other app you trust. Some apps may not have a separate "revoke" button, in which case witness to the same account 0 viz. The withdrawn capital will be deducted from the recipient's capital instantly, but will revert back to you after 24 hours.

Note: increasing and decreasing delegated capital doesn’t work quite normal. If you have delegated 1000 viz to someone and now you want to delegate another 400 viz, you should add 1400 viz to the delegation amount, which is the final amount. Similarly with decrease: if you want to decrease the delegated amount by 400 viz, you must specify the new delegated amount, i.e. 600 viz, not "minus 400".

## Viz tokens and cheques

### How to get liquid viz tokens?

Sometimes you may need liquid viz tokens. For example, to add social capital to your other account, to give viz to a friend or to sell them via exchanger.

If you have enough social capital, you can withdraw (take away, convert) the right amount of tokens from it. The Viz blockchain is purposely built in such a way that it’s impossible to get liquid tokens out of the capital instantly: the withdrawal takes place in parts - no more than 1/28 of the capital per day. Therefore, a small amount can be withdrawn in 1-2 days, while it takes weeks to "cash out" a substantial amount of capital.

A quicker and more obvious way is to buy tokens from exchange, online shops, stocks or from private seller with other VIZ participants. The list of relevant venues varies, so, it’s better to check the locations and terms of transactions on VIZ information resources.

### How to transfer viz tokens from one account to another?

In any wallet or personal account app in VIZ, you will surely find a section for transferring tokens. All you need is the name of the recipient account and your private active key. If you want or need to, you can write a message, comment or service data in the transfer. The recipient will see the transfer information almost immediately, and in about a minute the transaction will be finally stored in the blockchain.

### How to use cheques?

Cheques allow you to transfer liquid viz tokens **outside the blockchain**. You create a cheque with your liquid tokens in the app (one or another wallet or My Account [my.viz.plus](https://my.viz.plus)) and save the public part and the secret part. Then you pass the secret part to another person, who cashes it in the same app in his account, by entering the secret part into the corresponding field.

When you create a cheque, the tokens are withdrawn from your "account" to the cheque, so you can't spend them. But if the cheque isn’t used, you can "cash" it back into your account.

The second way to use the cheque is to deposit it when you create your account. In this case, all of the tokens from the check go into the social capital of the new account.

Regardless of the way of use, the assets from the cheque are withdrawn only as a whole, i.e. the cheque can be cashed only once in full. There are no commissions on the creation and use of cheques.

## Delegates & DAO Fund

### How to elect delegates to DAO Fund?

Unlike elections to national parliaments, the election of delegates to the DAO VIZ is a continuous process. You have the right and opportunity to vote for delegates (one or more) or to withdraw your vote at any time.

Voting is a blockchain transaction like any other and is done through an app. For example, in My Account [my.viz.plus](https://my.viz.plus) on a special page you should tick the relevant account and your choice will be regarded.

When voting, the power of your vote, equal to your social capital, is equally divided among all the delegates you voted for. Therefore, it’s worth deciding in advance whether to give all your votes to one delegate to help him move up the list, or to divide them among several delegates.

### How to vote for applications for DAO Fund?

VIZ members who apply for a payment from the DAO Fund usually try to get as many social capital holders to vote for it as possible. Therefore, if you follow VIZ news, you will probably know that someone has applied.

If you wish to support or reject an application, you can do it in the relevant section of  My Account [my.viz.plus](https://my.viz.plus) or in other apps that provide such service.

When voting, you choose the approval percentage of the application: the higher the average percentage received by the application, the more vizes from the Fund the applicant will receive. A vote of 100% means that you agree to give the applicant the amount they are requesting. A lower percentage will result in a reduced amount.

It is also possible to set a negative percentage (up to -100%): this means that you don’t want to allocate assets from the Fund to the applicant.

You can change your decision at any time up to the end of voting. Please note: the voting on the application takes into account the effective social capital of your account at the end of the voting period. This means that if you voted, and then delegated some of your capital to another account or withdrew some of your capital into liquid tokens, only the remaining capital will be taken into account in the end result. Conversely, if after voting but before the vote is counted, your social capital has increased, your vote will be weighted.

## Best Practices

### What is the best and safest way to use VIZ?

**Separate keys**. The key system in VIZ greatly increases the security of using your account compared to the usual "login + password" system.

Of course, keeping three keys that you can't remember is more difficult than entering `12345asd` password. But in the case of a leak from a site or an app regular keys (which are used to make awards), you lose virtually nothing. Even if the active keys are leaked, your loss is minimal, especially if you use subaccounts from the following advice, and don’t keep any liquid vizes in your wallet.

**Use subaccounts and delegation**. On the one hand, VIZ is convenient because the same account can be used in all applications, accumulating social capital on it and rewarding other participants. On the other hand, it isn’t very safe: the app could be fraudulent or hacked by hackers, leading to trouble with the account.

A good way to increase the security of using VIZ is to have one "main" account with your social capital and one or more subaccounts for different purposes and individual apps.

For example, your main account is `johnnydepp`. You have bought 12500 vizes and put them into the social capital of this account. Now you can create a subaccount `twitter.johnnydepp` and delegate 2400 views to it, a subaccount `telegram.johnnydepp` and delegate 5800 views to it, and a subaccount `iam.johnnydepp` and delegate the rest 4300 views to it. You connect the first two accounts to their respective social gateways, and use the latter for all other tasks. The main account virtually securely holds your social capital and, if you wish, your liquid vizes in your wallet.

Even if you lose or compromise the keys to a sub-account, right down to the master key, nothing will happen: you will simply revoke the delegation and create a new subaccount.

Rewards will accrue in subaccounts, which can be slowly transferred to the main account, or retained to build up your social capital on Twitter and Telegram. You'll only log into your main account safe through the most trusted app, and even rarely.

**Try to use local apps**. Some apps in VIZ know how to work directly with the blockchain without accessing their own server. This is safer and more convenient because there is no middleman, who could be a crook, or his servers could be hacked, or could go offline at the most inopportune moment.

On the other hand, without a server it is unlikely to be possible to build an advanced app with complex features. In some cases, the same application can be presented in two versions - a "basic" local version and an "advanced" server version (as a website or mobile app). It's up to you which version you choose - depending on what you want to do with the app.

For example, [My account](https://my.viz.plus) of a VIZ member works both as a website and as a local web page which you should download to your computer and open in your browser. The local version will work even if the server goes down completely because it doesn’t communicate with it, but directly with the blockchain.
