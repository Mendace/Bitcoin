# CryptoDonateButton

A JavaScript library to put up donation buttons for Bitcoin.

To use it just upload the folder CryptoDonateButton in your website root folder,
then copy and paste the following script at the beinning of your HTML page:

	<script>
		! function(c) {
			var t = document.createElement("script");
			t.type = "text/javascript", t.async = !0, t.onload = c, t.src = "CryptoDonateButton/src/widget.js";
			var e = document.getElementsByTagName("script")[0];
			e.parentNode.insertBefore(t, e)
		}(function() {
			Fr.loadCD("bitcoin", {
				coin: "bitcoin",
				address: "bc1qpcfagedq6tqf55lr0cqzlywsewq07p682r7p5a",
				buttonClass: "large",
				dialogClass: "large",
			});
		});
	</script>
  
  You can edit the variables:
  
  - Fr.loadCD("CHOOSE AN ID", {

  - coin: "BITCOIN OR LIGHTNING"
  
  - address: "YOUR BITCOIN ADDRESS/YOUR LNURL",
  - buttonClass: "SMALL/MEDIUM/LARGE",
  - dialogClass: "SMALL/MEDIUM/LARGE",
        
     
Then just create an html tag in the website where you want the button with as ID the variable choosen in the Fr.loadCD row. Example:
<br><br>
	
"< span id="CHOOSE AN ID"></ span>"
	<Br><Br>
	
Now you have a beautiful Bitcoin donation button on your website!
	
	
  
 
