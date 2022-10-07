### Rewards: ${points} Points 🔥 *NFT! 👻
___
### Description
In this challenge your mission is to send a Version 0 Transaction. This is a brand new transaction format on Solana.
How long do you think it will take you to send it?
Good luck **${session?.user?.name}**!
1. Visit the new [Versioned Transactions Guide](https://docs.solana.com/developers) or the [Solana Cookbook](https://solanacookbook.com/#contributing).
2. Create a simple instruction, like [TransferSol](https://solana-labs.github.io/solana-web3.js/classes/SystemProgram.html#transfer).
3. Use that instruction to build a Transaction v0.
4. Successfully send that Transaction v0 over `devnet`.
💡 Record the end time. How long did it take?
### Tips:
- You'll need to build a Transaction Message using components such as BlockHash. These can be obtained using the `Connection` object.
- The function to send a transaction (ie. `sendAndConfirmTransaction`) will return a signature string. You can use this string to look up your transaction on the Explorer.
- Explorer on devnet to search for your Transaction Signature (ID): [Solana Explorer](https://explorer.solana.com/?cluster=devnet)
- [Example transaction Id](https://explorer.solana.com/tx/4v5StXx1jeuWzh9trtBQtQRMeeUjZzk7mJSq9MTx9XhDunbqY5ZpwPZQanVKfN7Tb3X1gHtMa6xgUcARVDaG7x91?cluster=devnet) is in the url followed by: /tx/.
### Resources:
[Solana Developer Docs](https://docs.solana.com/developers)   
[Web3 Examples](https://github.com/solana-developers/web3-examples)   
[Solana Bytes: Transaction v0](https://www.youtube.com/watch?v=8k68cMeLX2U&list=PLilwLeBwGuK51Ji870apdb88dnBr1Xqhm&index=12)   
___
### How to Submit
Your submission should include the following:
1. Your \`Transaction Id\` (tx, signature, address) from the url above.
2. Time it took to successfully send this transaction.
*That was almost too easy..*
___
### Submission Entered:
Challenge Id: [#${challengeID}]
Hunter: ${session?.user?.name}
1. Transaction ID:
${submitTransactionID}
2. How long did it take to deploy a program? (minutes): ${submitTime}