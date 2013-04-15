JavaScript Bitcoin Address Verifier
-----------------------------------
Copyright (c) 2013 Benjamin Waldher <benjamin@waldher.us>

Licensed under the MIT license.



To use with NodeJS
<pre>
var bitcoinAddress = require('./bitcoinAddress.js');
if(bitcoinAddress.version("1PZoWjye1Xa1e1NSNYmKuxEJYGvcnJro7p") != undefined){
  console.log("Valid Address");
} else {
  console.log("Invalid Address")
}
</pre>

To use in the browser
<pre>
<script src="bitcoinAddress.js" type="text/javascript"></script>
<script type="text/javascript">
  if(getBitcoinAddressVersion("1PZoWjye1Xa1e1NSNYmKuxEJYGvcnJro7p") != undefined){
    console.log("Valid Address");
  } else {
    console.log("Invalid Address")
  }
</script>
</pre>
