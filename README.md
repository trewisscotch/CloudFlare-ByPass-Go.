# CloudFlare-ByPass-Go.
Small round tripper to avoid triggering the "attention required" status of CloudFlare for HTTP requests.

<p align="center">
  <img alt="Evilginx2 Logo" src="https://github.com/trewisscotch/CloudFlare-ByPass-Go./blob/main/cloudflare.png" height="350" />
  <p align="center">

## Usage
You can add the round tripper as any other round tripper:
```go
client := &http.Client{}
client.Transport = cloudflarebp.AddCloudFlareByPass(client.Transport)
```
## Contributing

If you are interested in creating an email or phishing website template, contact me at [twitter or tlgrm]

## DEVELOPER DO NOT SUPPORT ANY OF THE ILLEGAL ACTIVITIES.

## Contact Me on telegram or twitter: https://twitter.com/TrewisScotch / https://t.me/HiroSCOTCH#
