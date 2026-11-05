# Google Ads Conversion Tracking Code for Shopify (YT)

*Converted from `PPC Co Pilot/Ecom Accelerator/3. Account Setup & Structure/Google Ads Conversion Tracking Code for Shopify (YT).pdf`*

//gtag starts here
const script = document.createElement('script');
script.setAttribute('src', 'https://www.googletagmanager.com/gtag/js?id=AW-CONVERSIONID');
script.setAttribute('async', '');
document.head.appendChild(script);
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
gtag('config', 'AW-CONVERSIONID');
//gtag ends here
//ec + purchase code starts here
analytics.subscribe("checkout_completed", (event) => {
gtag('set', 'user_data', {
"email": event.data.checkout.email,
"phone_number": event.data.checkout.phone
});
gtag('event', 'conversion', {
'send_to': 'AW-CONVERSIONID/CONVERSIONLABEL',
'value': event.data.checkout.totalPrice.amount,
'transaction_id': event.data.checkout.order.id,
'currency': event.data.checkout.currencyCode
});
});
