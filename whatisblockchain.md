# What is a blockchain?

A blockchain is a distributed database or ledger (buku besar) shared across a computer network's nodes. While it is best known for its crucial role in cryptocurrency systems, maintaining a secure and decentralized record of transactions, blockchains are not limited to cryptocurrency uses. Blockchains can be used to make data in any industry immutable, meaning it cannot be altered.

Since a block can’t be changed, the only trust needed is at the point where a user or program enters data. This reduces the need for trusted third parties, such as auditors or other humans, who add costs and can make mistakes.

Since Bitcoin's introduction in 2009, blockchain use has exploded due to the creation of various cryptocurrencies, decentralized finance (DeFi) applications, non-fungible tokens (NFTs), and smart contracts. Bitcoin and other popular cryptocurrencies, such as Ethereum and Solana, can be purchased through leading crypto exchanges.

- Blockchain is a type of shared database that differs from a typical database in the way it stores information; blockchains store data in blocks linked together via cryptography.

- Different types of information can be stored on a blockchain, but the most common use has been as a transaction ledger. 

- In Bitcoin’s case, the blockchain is decentralized, so no single person or group has control—instead, all users collectively retain control.

- Decentralized blockchains are immutable, which means that the data entered is irreversible. For Bitcoin, transactions are permanently recorded and viewable to anyone.

# How Does a Blockchain Work?

You might be familiar with spreadsheets or databases. A blockchain is somewhat similar because it is a database where information is entered and stored. The key difference between a traditional database or spreadsheet and a blockchain is how the data is structured and accessed.

A blockchain consists of programs called scripts that conduct the tasks you usually would in a database: entering and accessing information, and saving and storing it somewhere. A blockchain is distributed, meaning multiple copies are saved on many machines and must match for it to be valid.

The Bitcoin blockchain collects transaction information and enters it into a 4MB file called a block (different blockchains have different-sized blocks). Once the block is full, the block data is run through a cryptographic hash function, which creates a hexadecimal number called the block header hash.

The hash is then entered into the following block header and encrypted with the other information in that block's header, creating a chain of blocks, hence the name “blockchain.”

# Transaction Process

Transactions follow a specific process, depending on the blockchain. For example, on Bitcoin's blockchain, if you initiate a transaction using your cryptocurrency wallet—the application that provides an interface for the blockchain—it starts a sequence of events.

In Bitcoin, your transaction is sent to a memory pool, where it is stored and queued until a miner picks it up. Once it is entered into a block and the block fills up with transactions, it is closed, and the mining begins.

Every node in the network proposes its own blocks in this way because it chooses different transactions. Each works on their own blocks, trying to find a solution to the difficulty target, using the "nonce," short for number used once.

The nonce value is a field in the block header that is changeable, and its value incrementally increases with every mining attempt. If the resulting hash isn't equal to or less than the target hash, a value of one is added to the nonce, a new hash is generated, and so on. The nonce rolls over about every 4.5 billion attempts (which takes less than one second) and uses another value called the extra nonce as an additional counter. This continues until a miner generates a valid hash, winning the race and receiving the reward.

Every node in the network proposes its own blocks in this way because it chooses different transactions. Each works on their own blocks, trying to find a solution to the difficulty target, using the "nonce," short for number used once.

The nonce value is a field in the block header that is changeable, and its value incrementally increases with every mining attempt. If the resulting hash isn't equal to or less than the target hash, a value of one is added to the nonce, a new hash is generated, and so on. The nonce rolls over about every 4.5 billion attempts (which takes less than one second) and uses another value called the extra nonce as an additional counter. This continues until a miner generates a valid hash, winning the race and receiving the reward.

# Blockchain Decentralization

A blockchain allows the data in a database to be spread out among several network nodes—computers or devices running software for the blockchain—at various locations. This creates redundancy and maintains the fidelity of the data. For example, if someone tries to alter a record on one node, the other nodes would prevent it from happening by comparing block hashes. This way, no single node can alter information within the chain.

Because of this distribution—and the encrypted proof that work was done—the blockchain data, such as transaction history, becomes irreversible. Such a record could be a list of transactions, but private blockchains can also hold a variety of other information like legal contracts, state identifications, or a company's inventory. Most blockchains wouldn't "store" these items directly; they would likely be sent through a hashing algorithm and represented on the blockchain by a token.

# Blockchain Transparency

Because of the decentralized nature of the Bitcoin blockchain, all transactions can be transparently viewed by downloading and inspecting them or by using blockchain explorers that allow anyone to see transactions occurring live. Each node has its own copy of the chain that gets updated as fresh blocks are confirmed and added. This means that if you wanted to, you could track a bitcoin wherever it goes. 

For example, crypto exchanges have been hacked in the past, resulting in the loss of large amounts of cryptocurrency. While the hackers may have been anonymous—except for their wallet address—the crypto they extracted is easily traceable because the wallet addresses are stored on the blockchain.
1

Of course, the records stored in the Bitcoin blockchain (as well as most others) are encrypted. This means that only the person assigned an address can reveal their identity. As a result, blockchain users can remain anonymous while preserving transparency.

# Is Blockchain Secure?

Blockchain technology achieves decentralized security and trust in several ways. To begin, new blocks are always stored linearly and chronologically. That is, they are always added to the "end" of the blockchain. After a block has been added to the end of the blockchain, previous blocks cannot be altered.

A change in any data changes the hash of the block it was in. Because each block contains the previous block's hash, a change in one would change the following blocks. The network would generally reject an altered block because the hashes would not match. However, a change can be accomplished on smaller blockchain networks.

A new and smaller chain might be susceptible to this kind of attack, but the attacker would need at least half of the computational power of the network (a 51% attack). On the Bitcoin and other larger blockchains, this is nearly impossible. By the time the hacker takes any action, the network is likely to have moved past the blocks they were trying to alter. This is because the rate at which these networks hash is exceptionally rapid—the Bitcoin network hashed at a rate of around 851 exahashes per second as of September 2025.

The Ethereum blockchain is not likely to be hacked either—again, the attackers would need to control more than half of the blockchain's staked ether. As of September 2025, over 35.7 million ETH have been staked by more than one million validators.

An attacker or a group would need to own almost 18 million ETH, and be randomly selected to validate blocks enough times to get their blocks implemented.

# Bitcoin vs. Blockchain

Blockchain technology was first outlined in 1991 by Stuart Haber and W. Scott Stornetta, two researchers who wanted to implement a system where document timestamps could not be tampered with.

But it wasn’t until almost two decades later, with the launch of Bitcoin in January 2009, that blockchain had its first real-world application.

# Bitcoin

The Bitcoin protocol is built on a blockchain. In a research paper introducing the digital currency, Bitcoin’s pseudonymous creator, Satoshi Nakamoto, referred to it as “a new electronic cash system that’s fully peer-to-peer, with no trusted third party.”


The key thing to understand is that Bitcoin uses blockchain as a means to transparently record a ledger of payments or other transactions between parties.

# Blockchain

Blockchain can be used to immutably record any number of data points. The data can be transactions, votes in an election, product inventories, state identifications, deeds to homes, and much more.

Currently, tens of thousands of projects are looking to implement blockchains in various ways to help society other than just recording transactions—for example, as a way to vote securely in democratic elections.

The nature of blockchain's immutability means that fraudulent voting would become far more difficult. For example, a voting system could work such that each country's citizens would be issued a single cryptocurrency or token.

Each candidate could then be given a specific wallet address, and the voters would send their token or crypto to the address of whichever candidate they wish to vote for. The transparent and traceable nature of blockchain would eliminate the need for human vote counting and the ability of bad actors to tamper with physical ballots.

# Blockchain vs. Banks

Blockchains have been heralded as a disruptive force in the finance sector, especially with the functions of payments and banking. However, banks and decentralized blockchains are vastly different.

To see how a bank differs from blockchain, let’s compare the banking system to Bitcoin’s blockchain implementation.

# How Are Blockchains Used?

As we now know, blocks on Bitcoin’s blockchain store transactional data. Today, tens of thousands of other cryptocurrencies run on a blockchain. However, blockchain can also be a reliable way to store other types of data.

Some companies that are experimenting with blockchain include Walmart, Pfizer, AIG, Siemens, Unilever, and others. For example, IBM has created its Food Trust blockchain to trace the journey that food products take to reach their locations.

Why do this? The food industry has seen countless outbreaks of E. coli, Salmonella, and Listeria; in some cases, hazardous materials were accidentally introduced to foods.

In the past, it has taken weeks to find the source of these outbreaks or the cause of sickness from what people are eating.

Using blockchain allows brands to track a food product’s route from its origin, through each stop it makes, to delivery. Not only that, but these companies can also now see everything else it may have come in contact with, allowing the identification of the problem to occur far sooner—potentially saving lives. This is one example of blockchain in practice, but many other forms of blockchain implementation exist or are being experimented with.

# Banking and Finance

Perhaps no industry stands to benefit from integrating blockchain into its business operations more than personal banking. Financial institutions only operate during business hours, usually five days a week. That means if you try to deposit a check on Friday at 6 p.m., you will likely have to wait until Monday morning to see the money in your account.

Even if you make your deposit during business hours, the transaction can still take one to three days to verify due to the sheer volume of transactions that banks need to settle. Blockchain, on the other hand, never sleeps.

By integrating blockchain into banks, consumers might see their transactions processed in minutes or seconds—the time it takes to add a block to the blockchain, regardless of holidays or the time of day or week. With blockchain, banks also have the opportunity to exchange funds between institutions more quickly and securely. Given the sums involved, even the few days the money is in transit can carry significant costs and risks for banks.

The settlement and clearing process for stock traders can take up to three days (or longer if trading internationally), meaning that the money and shares are frozen for that period. Blockchain can, in theory, drastically reduce that time.

# Currency

Blockchain forms the bedrock for cryptocurrencies like Bitcoin. This design also allows for easier cross-border transactions because it bypasses currency restrictions, instabilities, or lack of infrastructure by using a distributed network that can reach anyone with an internet connection.

# Healthcare

Healthcare providers can leverage blockchain to store their patients’ medical records securely. When a medical record is generated and signed, it can be written into the blockchain, which provides patients with proof and confidence that the record cannot be changed. These personal health records could be encoded and stored on the blockchain with a private key so that they are only accessible to specific individuals, thereby ensuring privacy.

# Property Records

If you have ever spent time in your local Recorder’s Office, you will know that recording property rights is both burdensome and inefficient. Today, a physical deed must be delivered to a government employee at the local recording office, where it is manually entered into the county’s central database and public index. In the case of a property dispute, claims to the property must be reconciled with the public index.

This process is not only costly and time-consuming but also prone to human error. Each inaccuracy makes tracking property ownership less efficient. Blockchain has the potential to eliminate the need for scanning documents and tracking down physical files in a local recording office. If property ownership is stored and verified on the blockchain, owners can trust that their deed is accurate and permanently recorded.

Proving property ownership can be nearly impossible in war-torn countries or areas with little to no government or financial infrastructure and no Recorder’s Office. If a group of people living in such an area can leverage blockchain, then transparent and clear timelines of property ownership could be maintained.

# Smart Contracts

A smart contract is computer code that can be built into the blockchain to facilitate transactions. It operates under a set of conditions to which users agree. When those conditions are met, the smart contract conducts the transaction for the users.

# Supply Chains

As in the IBM Food Trust example, suppliers can use blockchain to record the origins of materials that they have purchased. This would allow companies to verify the authenticity of not only their products but also common labels such as “Organic,” “Local,” and “Fair Trade.”

The food industry is increasingly adopting blockchain to track the path and safety of food throughout the farm-to-user journey.


# Voting

As mentioned above, blockchain could facilitate a modern voting system. Voting with blockchain carries the potential to eliminate election fraud and boost voter turnout, as was tested in the November 2018 midterm elections in West Virginia.


Using blockchain in this way would make votes nearly impossible to tamper with. The blockchain protocol would also maintain transparency in the electoral process, reducing the personnel needed to conduct an election and providing officials with nearly instant results. This would eliminate the need for recounts or any real concern that fraud might threaten the election.

# Pros and Cons of Blockchain

For all of its complexity, blockchain’s potential as a decentralized form of record-keeping is almost without limit. From greater user privacy and heightened security to lower processing fees and fewer errors, blockchain technology may very well see applications beyond those outlined above. But there are also some disadvantages.

## Pros

- Improved accuracy by removing human involvement in verification

- Cost reductions by eliminating third-party verification

- Decentralization makes it harder to tamper with

- Transactions are secure, private, and efficient

- Transparent technology

- Provides a banking alternative and a way to secure personal information for citizens of countries with unstable or underdeveloped governments

## Cons

- Significant technology cost associated with some blockchains

- Low number of transactions per second

- History of use in illicit activities, such as on the dark web

- Regulation varies by jurisdiction and remains uncertain

- Data storage limitations

## Benefits of Blockchains

# Accuracy of the Chain
Transactions on the blockchain network are approved by thousands of computers and devices. This removes almost all people from the verification process, resulting in less human error and an accurate record of information. Even if a computer on the network were to make a computational mistake, the error would only be made to one copy of the blockchain and not be accepted by the rest of the network.

# Cost Reductions
Typically, consumers pay a bank to verify a transaction or a notary to sign a document. Blockchain eliminates the need for third-party verification—and, with it, their associated costs. For example, business owners incur a small fee when they accept credit card payments because banks and payment-processing companies have to process those transactions. Bitcoin, on the other hand, does not have a central authority and has limited transaction fees.

# Decentralization
Blockchain does not store any information in a central location. Instead, it is copied and spread across a network of computers. Whenever a new block is added to the blockchain, every computer on the network updates its blockchain to reflect the change.

By spreading that information across a network, rather than storing it in one central database, blockchain becomes significantly more difficult to tamper with.

# Efficient Transactions
Transactions placed through a central authority can take up to a few days to settle. If you attempt to deposit a check on Friday evening, for example, you may not actually see funds in your account until Monday morning. Financial institutions operate during business hours, usually five days a week—but a blockchain runs 24 hours a day, seven days a week, and 365 days a year.

On some blockchains, transactions can be completed and considered secure in minutes. This is particularly useful for cross-border trades, which usually take much longer because of time zone issues and the fact that all parties must confirm payment processing.

# Private Transactions
Many blockchain networks operate as public databases, meaning anyone with an internet connection can view a list of the network’s transaction history. Although users can access transaction details, they cannot access identifying information about the users making those transactions. It is a common misconception that blockchain networks like Bitcoin are fully anonymous; they are actually pseudonymous because there is a viewable address that can be associated with a user if the information gets out.

# Secure Transactions
Once a transaction is recorded, its authenticity must be verified by the blockchain network. After the transaction is validated, it is added to the blockchain block. Each block on the blockchain contains its unique hash and the unique hash of the block before it. Therefore, the blocks cannot be altered once the network confirms them.

# Transparency
Many blockchains are entirely open source. This means that everyone can view its code. This gives auditors the ability to review cryptocurrencies like Bitcoin for security. However, it also means there is no real authority on who controls Bitcoin’s code or how it is edited. Because of this, anyone can suggest changes or upgrades to the system. If a majority of the network users agree that the new version of the code with the upgrade is sound and worthwhile, then Bitcoin can be updated.

Private or permissioned blockchains may not allow for public transparency, depending on how they are designed or their purpose. These types of blockchains might be made only for an organization that wishes to track data accurately without allowing anyone outside of the permissioned users to see it.

Alternatively, there might come a point where publicly traded companies are required to provide investors with financial transparency through a regulator-approved blockchain reporting system. Using blockchains in business accounting and financial reporting would prevent companies from altering their financials to appear more profitable than they really are.

# Banking the Unbanked
Perhaps the most profound facet of blockchain and cryptocurrency is the ability for anyone, regardless of ethnicity, gender, location, or cultural background, to use it. According to The World Bank, an estimated 1.3 billion adults do not have bank accounts or any means of storing their money or wealth.

Moreover, nearly all of these individuals live in developing countries where the economy is in its infancy and entirely dependent on cash. 

These people are often paid in physical cash. They then need to store this physical cash in hidden locations in their homes or other places, incentivizing robbers or violence. While not impossible to steal, crypto makes it more difficult for would-be thieves.

## Drawbacks of Blockchains
# Technology Cost
Although blockchain can save users money on transaction fees, the technology is far from free. For example, the Bitcoin network's proof-of-work system to validate transactions consumes vast amounts of computational power. In the real world, the energy consumed by the millions of devices on the Bitcoin network is more than what Finland uses.

Some solutions to these issues are beginning to arise. For example, bitcoin-mining farms have been set up to use solar power, excess natural gas from fracking sites, or energy from wind farms.

# Speed and Data Inefficiency
Bitcoin is a perfect case study of the inefficiencies of blockchain. Bitcoin's PoW system takes about 10 minutes to add a new block to the blockchain. At that rate, it's estimated that the blockchain network can only manage up to 10 transactions per second (TPS).

Although other cryptocurrencies, such as Ethereum, perform better than Bitcoin, the complex structure of blockchain still limits them. Legacy brand Visa, for context, can process 65,000 TPS.

Solutions to this issue have been in development for years. There are currently blockchain projects that claim tens of thousands of TPS. Ethereum is rolling out a series of upgrades that include data sampling, binary large objects (BLOBs), and rollups. These improvements are expected to increase network participation, reduce congestion, decrease fees, and increase transaction speeds.

The other issue with many blockchains is that each block can only hold so much data. The block size debate has been and continues to be one of the most pressing issues for future blockchains' scalability.

# Illegal Activity
While confidentiality on the blockchain network protects users from hacks and preserves privacy, it also allows for illegal trading and activity on the blockchain network. The most cited example of blockchain being used for illicit transactions is probably the Silk Road, an online dark web illegal-drug and money laundering marketplace operating from February 2011 until October 2013, when the FBI shut it down.

The dark web allows users to buy and sell illegal goods without being tracked by using the Tor Browser and make illicit purchases in Bitcoin or other cryptocurrencies. This is in stark contrast to U.S. regulations, which require financial service providers to obtain information about their customers when they open an account. They are supposed to verify the identity of each customer and confirm that they do not appear on any list of known or suspected terrorist organizations.