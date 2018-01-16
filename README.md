# Tippr


Tippr revolutionizes Bitcoin tipping by allowing people to tip anyone, even if they don't already have a Bitcoin wallet or social account.
---
# Basic Usage
You can summon the bot into any thread. Just post a comment with a comment command (listed below).  
You can also PM it directly with commands, but leave out `/u/tippr` and `u/tippr` if PMing it.  
After that, it takes arguments which I'll explain below.

### Balance
Usage in comment: `None`  
Usage in PM: `balance`  [or click here](https://reddit.com/message/compose?to=tippr&subject=Balance&message=balance)

This command will have tippr reply to you with your current balance.  
Your balance is a combination of your deposits and received tips, minus your sent tips and withdrawals, and can be both tipped or withdrawn.

### Deposit  
Usage in comment: `None`  
Usage in PM: `deposit`  [or click here](https://reddit.com/message/compose?to=tippr&subject=Deposit&message=deposit)

With this, tippr will send you a PM with an address to deposit at.  
Your deposit will be stored in an intermediary wallet that you can withdraw from at any time.  
For reasons, the deposit requires **3 confirmations** before being credited to your account. You'll receive a PM upon successful crediting.

### Tip  
Usage in comment: `<amount> <unit> u/tippr`  
Usage in PM: You can't use this command in a PM. Sorry.  

Currently the only supported currencies are `bch`, `bits`, and `usd`. Others will be implemented ASAP.  
Example: `0.5 bch u/tippr`  
This will (internally) transfer the `<amount>` to the user you're replying to.  
If they don't have an address registered with tippr, that's okay; it'll notify the recipient and store the tip until the user is ready to claim it.  
Received tips can be re-tipped or withdrawn.  
**Note: `$10 u/tippr` (or any other amount) will also work, and for now will assume USD, since no other currencies are yet in place.**
**Additional Note: 1 bit = 100 satoshis = 0.000001 BCH**

### Withdraw
Usage in comment: You can't use this command in a comment. Sorry.  
Usage in PM: `withdraw <amount> <address>` [or click here](https://reddit.com/message/compose?to=tippr&subject=Withdrawal&message=withdraw AMOUNT ADDRESS)

This command will send the specified `amount` of BCH to `address`  
**There is currently no confirmation on this as long as the address is valid, so make sure you're passing it a valid Bitcoin Cash address that you control**

### Gild
Usage in comment: `gild u/tippr`  
This command will charge you the equivalent of $2.50 USD in BCH from your balance and gild the post you're replying to.     
---

# To Do List
- [X] Create Repository
- [X] Upload u/Tippr
- [X] Update readme wiki with commands
- [ ] Add "tip all subreddit users" feature
- [ ] Create Github Page
- [ ] Raise funds
- [ ] Create Reddit sub-forum
- [ ] Launch


---
This is version v0.0.1.a Some thanks is in order:

-Thanks to Wade Dempsey for buying the tippr.org domain.
<br />
-Thanks to /u/cryptodude1 on Reddit for the original idea.
<br />
-Thanks to Twitter Bootstrap for being awesome. (Enough said.)
<br />
-Thanks to the countless others who have helped us work out the kinks!
<br /><br />
If you know PHP, please help contribute code! The files for the Chrome extension are also in here, so if you know any special Chrome tips that we don't- help out!
