# bitcoin-wallet

*Features:*

1) Secure storage of coins
   - Generate a wallet
     Workflow:
         a) Generate a source of randomness
         b) Use PRNG to create mnemonic 
         c) Convert mnemonic to a seed - used to generate wallet
   - Authentication
    
   - Balance

2) Receive coins 
   - Generate address (P2SH, P2PKH, P2WPKH, P2WSH)
  
3) Send coins
   - Create txn
   - Fee estimation
   - Coin selection
  
4) Extra
   - RBF
   - PSBT
   - Timelocks
   - Key Vault
