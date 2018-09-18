# netlify-proxy

This repo is a quick and simple example to demonstrate how to poxify your Netlify website to restrict access (with Basic Auth).

## Steps

1. Customize the demo Nginx virtual host with your own domain / Netlify url.

2. Generate on your server `.htpasswd` file:

```
htpasswd -c .htpasswd username
```

3. If you want to use HTTPS, use [Certbot](https://certbot.eff.org/).

4. Restart Nginx and enjoy your proxy: https://sandbox.your-domain.com

## License

MIT © [Dimitri DO BAIRRO](https://github.com/rimiti/netlify-proxy/blob/master/LICENSE)
