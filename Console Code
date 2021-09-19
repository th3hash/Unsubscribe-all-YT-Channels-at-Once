var i = 0;
var count = document.querySelectorAll("ytd-channel-renderer:not(.ytd-item-section-renderer)");
myTimer();
function myTimer () {
if (count == 0) return;
el = document.querySelector('.ytd-subscribe-button-renderer');
el.click();
setTimeout(function () {
var unSubBtn = document.getElementById("confirm-button").click();
i++;
count--;
console.log(i + " unsubscribed");
console.log(count + " remaining");
setTimeout(function () {
el = document.querySelector("ytd-channel-renderer");
el.parentNode.removeChild(el);
myTimer();
}, 250);
}, 250);
}
