To build and deploy:

npm i -g graph-cli     

graph codegen    

graph build    

# For Mainnet 
graph create quai-blocks --node https://graph.quai.network/deploy   

graph deploy \
  --node https://graph.quai.network/deploy \
  --ipfs https://ipfs.qu.ai \
  quai-blocks

# For Orchard Testnet
graph create quai-blocks --node https://orchard.graph.quai.network/deploy   

graph deploy \
  --node https://orchard.graph.quai.network/deploy \
  --ipfs https://ipfs.qu.ai \
  quai-blocks

