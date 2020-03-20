> [Go home](/)

# What Chrome extension permissions do we use? Why do we use them?

## proxy
We need to set proxy settings to connect to our servers.
## storage
We store persistent information, like whether you're connected or not, to help you connect faster.
## webRequest & webRequestBlocking
We need both of these to inject proxy authorization headers to our servers in order to connect to our servers.
## <all_urls>
We need to be able to send proxy authorization headers for every site to allow VPN connections for every site. Chrome requires that we give this permission to inject the authorization headers.
## tabs
We need the tabs permission to avoid opening duplicate tabs when we open a tab to notify you that you have ran out of data.
