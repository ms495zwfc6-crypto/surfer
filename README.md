# Surfer (Silver Surfer Token)

Surfer är ett meme-token byggt på **Solana-blockkedjan**. Det är designat för att vara en rolig token för communityn och kan visas i wallets som Phantom.

## Token Information

- **Namn:** Silver Surfer  
- **Symbol:** M3surfer  
- **Mint-adress:** ECqnVWEsxUpTjHBDoBp4vDufcGnLeALPUt3S6vS6moon  
- **Decimals:** 9  
- **Metadata:** [IPFS-link](https://ipfs.io/ipfs/bafkreic7k6g2homucnnu2aus2qvtllxgacbkqdotbkhuamddbszrxet5ou)  

## Funktioner

- Snabba och billiga transaktioner på Solana.  
- Community-drivet meme-token.  
- Synligt med namn, symbol och logo i Solana wallets som Phantom.  

## Hur man kopplar metadata (för utvecklare)

Om du redan har **Solana CLI** och **Metaplex CLI** installerade, kan du köra följande:

```bash
metaplex token metadata create \
  --mint ECqnVWEsxUpTjHBDoBp4vDufcGnLeALPUt3S6vS6moon \
  --name "Silver Surfer" \
  --symbol "M3surfer" \
  --uri "https://ipfs.io/ipfs/bafkreic7k6g2homucnnu2aus2qvtllxgacbkqdotbkhuamddbszrxet5ou" \
  --seller-fee-basis-points 0
