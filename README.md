To build and deploy:

npm i -g graph-cli     

graph codegen    

graph build    

graph create quai-blocks --node https://graph.quai.network   

graph deploy \
  --node https://graph.quai.network \
  --ipfs https://ipfs.qu.ai \
  quai-blocks
