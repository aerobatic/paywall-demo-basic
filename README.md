# aerobatic-paywall-basic-demo

Aerobatic demo site showing how to use the [paywall plugin](https://www.aerobatic.com/docs/plugins/paywall) to power a paid membership site built with [Jekyll](https://jekyllrb.com).

Try the live version of this demo at: [https://paywall-demo-basic.aerobaticapp.com](https://paywall-demo-basic.aerobaticapp.com)

To make the integration as easy as possible, the demo makes use of the [paywall.js](https://www.aerobatic.com/docs/paywall/paywall-js-script/) drop-in script which abstracts away the client-side plumbing using `data-paywall-*` attributes. However it's also straightforward to wire it up as part of your own client JavaScript if you choose. The [source code](https://github.com/aerobatic/js-libs/blob/master/libs/paywall.js) of the drop-in script can serve as a guide.

All webpages nested within the `/members` directory require a paid subscription to access.

For a more advanced demo with multiple subscription plans for accessing different sets of content, see the [advanced paywall demo](https://github.com/aerobatic/paywall-demo-advanced).
