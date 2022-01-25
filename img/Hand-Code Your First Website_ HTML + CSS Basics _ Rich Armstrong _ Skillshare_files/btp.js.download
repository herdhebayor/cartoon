//Skillshare

!function(f,b,e,v,n,t,s)
{if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init', '479819059784676');
fbq('trackSingle', '479819059784676', 'PageView');

if(!!~window.location.href.indexOf("home") && document.querySelector("img[src*='adsrvr'][src*='td1']")){
	window.cybOrderData = {
		order_id: document.querySelector("img[src*='adsrvr'][src*='td1']").src.match(/td1\=([0-9]+)/)[1],
		value: "1",
	};
	fbq('trackSingle', '479819059784676', 'CompleteRegistration');
	window._vteq = window._vteq || [];
	window._vteq.push({
  		confirmation: {
    		items: [],
    		orderId: cybOrderData.order_id,
    		total: cybOrderData.value
  		}
	});
}