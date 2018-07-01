# plutus_sandbox

This is a just a basic file structure for development purposes. The self-signed certificate will cause a warning in your Chrome browser, unless you follow some steps to trust the certificate. The deployed version will use a certificate from a CA. You will need to make your own .env file to get the app into a testable condition. The keys and instructions will be posted on the Slack channel for the unshared files that will be needed. At this stage, you will notice two instances of the same html page making interactions with Plaid. One is on the server, and the other is in the 'client' folder. I haven't yet created the routes in React, so I have included the external html file inside 'views' in the root level of the app.

The link below will provide instructions to allow Chrome to trust the self-signed certificate. Once the link is clicked, scroll down toward the bottom of the page to find the steps to trust the certificate.

## Note: The instructions provided below are for Windows users. All others will need to locate the analogous procedure for their respective operating systems.

[directions](https://stackoverflow.com/questions/21397809/create-a-trusted-self-signed-ssl-cert-for-localhost-for-use-with-express-node)
