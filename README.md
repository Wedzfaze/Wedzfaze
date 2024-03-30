<html>
<head>
  <title>Roblox Gift Card Checker</title>
</head>

<body>

  <h1>Roblox Gift Card Checker</h1>
  
  <input type="text" id="giftcard-code" placeholder="Enter gift card code">
  
  <button onclick="checkCode()">Check</button>
  
  <p id="result"></p>

  <script src="script.js"></script>

</body>
</html> 
function checkCode() {

  var code = document.getElementById("giftcard-code").value;
  
  // Show "Checking..." message
  document.getElementById("result").textContent = "Checking...";

  // Simulate delay of checking code
  setTimeout(function() {

    // Assume all codes are valid for this example
    document.getElementById("result").textContent = "Code is valid and not redeemed.";

  }, 3000); // 3 second delay

}
<div id="giftcard-checker">
  <!-- checker will load here -->
</div>

<script src="script.js"></script>
document.getElementById("giftcard-checker").innerHTML = "<div>Checker HTML</div>";
<div id="giftcard-checker"></div>

<script src="script.js"></script>
