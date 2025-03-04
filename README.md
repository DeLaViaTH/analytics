<div align="center">
  <img src="https://cdn.microlink.io/logo/banner.png" alt="microlink oss">
  <br>
  <br>
</div>

[![Deploy with Vercel](https://zeit.co/button)](https://vercel.com/new/project?template=https://github.com/microlinkhq/analytics)

> Microservice to retrieve your CloudFlare Analytics.

It converts your CloudFlare Analytics information

![](https://i.imgur.com/iH0vyim.png)

In something easy to consume for any UI as JSON payload, from anywhere.

See on live at [analytics.microlink.io](https://analytics.microlink.io/).

# Environment Variables

### ZONE_ID

*Required*</br>
Type: `string`

The zone identifier associated with your domain.

### X_AUTH_EMAIL

*Required*</br>
Type: `string`

The email associated with your CloudFlare account.

### X_AUTH_KEY

*Required*</br>
Type: `string`

The authorization token associated with your CloudFlare account.

### REQ_TIMEOUT

Type: `number`<br>
Default: 8000

It specifies how much time after consider a request as timeout, in milliseconds.

### MAX_CACHE

Type: `number`<br>
Default: 86400 (1d)

It specifies how much time a response can be cached, in seconds.

## License

**oss** © [microlink.io](https://microlink.io), released under the [MIT](https://github.com/microlinkhq/oss/blob/master/LICENSE.md) License.<br>
Authored and maintained by [Kiko Beats](https://kikobeats.com) with help from [contributors](https://github.com/microlinkhq/oss/contributors).

> [microlink.io](https://microlink.io) · GitHub [microlink.io](https://github.com/microlinkhq) · Twitter [@microlinkhq](https://twitter.com/microlinkhq)
