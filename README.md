# MyEtherWallet

**Current Version:** v3.10.7.1

This is a tiny docker image that serves a static version of MyEtherWallet from https://github.com/kvhnuke/etherwallet. Use this image for airgapped operations or if you simply don't trust the internet.

Be aware that you can also just download the source files and open them in a browser.

## Run

The following command will run the image on port `8080`. Remap at will.

```
docker run -p 8080:80 dmichael/myetherwallet:latest
```

You should now be able to access the app at

http://localhost:8080