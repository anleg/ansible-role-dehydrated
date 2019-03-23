ansible-role-dehydrated
====

If you want to use cloudflare api for dehydrated:
```
dehydrated_domains:
 - domain: choiz.fr *.choiz.fr
   zone: "your_cloudflare_zone_for_this_domain"
   email: "your_cloudflare_account_email"
   api_key: "cloudflare_api_key_here"
   challenge: "dns-01"
   hook: "cloudflare"
```

Don't forget updating the domain, zone, email and api_key.
