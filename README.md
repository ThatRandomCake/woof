<!DOCTYPE HTML>

<html>
    
<head>

<title>The Ultimate Coin Clicker</title>

<link rel="icon" href="http://icons.iconarchive.com/icons/ph03nyx/super-mario/256/Retro-Coin-icon.png">

<style>

body {
 background-image: url("https://gadget.co.za/wp-content/uploads/2019/02/markus-spiske-666905-unsplash-1024x683.jpg");
 background-color: #ffffff;
 max-width: 960px; 
    max-height: 601px;
 
}

</style>

<script>

 var count = 0;

 var coins = 1;

 var trackOne = 0;

 var trackTwo = 0;

 var trackThree = 0;

 console.log(count);

 function coin(){
  count = count + coins;
  console.log(count);
  document.getElementById("displayCount").innerHTML = "$" + count
 }

 function upgradeOne(){
    if (count >= 2){
    count = count + 8;
    trackOne = trackOne + 1;
    console.log(count);
    document.getElementById("displayCount").innerHTML = "$" + count
    document.getElementById("trackOne").innerHTML = "Times used:" + trackOne
    }
 }

 function upgradeTwo(){
    if (count >= 10){
    count = count - 10;
    count = count * 2;
    trackTwo = trackTwo + 1
    console.log(count);
    document.getElementById("displayCount").innerHTML = "$" + count
    document.getElementById("trackTwo").innerHTML = "Times used:" + trackTwo
    }
 }

 function upgradeThree(){
    if (count >= 20){
    coins = 1000;
    count = count - 20;
    trackThree = trackThree + 1
    console.log(count);
    document.getElementById("displayCount").innerHTML = "$" + count
    document.getElementById("trackThree").innerHTML = "You have successfully upgraded the main button!"
    document.getElementById("buttonThree").disabled = true;
    }
 }

 function upgradeFour(){
    if (count >= 50){
   
    coins = count + 1
    count = count - 20;
    trackThree = trackThree + 1
    console.log(count);
    document.getElementById("displayCount").innerHTML = "$" + count
    document.getElementById("trackThree").innerHTML = "You have successfully upgraded the main button!"
    document.getElementById("buttonThree").disabled = true;
    }
 }

</script>

<div>





<body>

      <link href="https://fonts.googleapis.com/css?family=VT323|Cousine" rel="stylesheet">

<font face="Cousine" color="#00ff00">

      <bold><h1>The Ultimate Coin Clicker</h1></bold>
      <h4>Press the main coin button below to begin! Upgrade your balance using the buttons below!</h4>

</font>

<font face="VT323" color="#00b200">


<h1 style="font-size:90px">

<div id="displayCount">

</div>

</p>

</center>

<button type="button" onclick="coin()"><img src="http://icons.iconarchive.com/icons/ph03nyx/super-mario/256/Retro-Coin-icon.png">

<style>

   .button {
      background-color: #4CAF50; /* Green */
      border: none;
      color: white;
      padding: 15px 32px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 16px;
    }

</style>

</button>

<h1>THE SHOP</h1>

<h2>Buy upgrades to increase your balance below!</h2>

<div><button type="button" id="buttonOne" onclick="upgradeOne()">Adds $10 to your balance - $2</button>

 <h2><div id="trackOne"></div></h2>

</div><br>

<div><button type="button" id="buttonTwo" onclick="upgradeTwo()">Doubles your current balance - $10</button>

   <h2><div id="trackTwo"></div></h2>

</div><br>

<div><button type="button" id="buttonThree" onclick="upgradeThree()">Permanently makes every click on the main button give you $1000 each time - $20</button></div>

 <h2><div id="trackThree"></div></h2>

<br>


<h2>About Coin Clicker</h2>

<p>Click the main coin button to receive a coin! When you receive enough coins, you can upgrade your balance using the buttons above! Here are some incredibly relevant websites!</p><br>

<div><a href="http://orteil.dashnet.org/cookieclicker/">A Wholesome Clicker Program</a></div><br>

<div><a href="https://www.youtube.com/watch?v=6jjzNsDAOgQ">A Wholesome Video</a></div>

<div><br><img src="http://aux.iconspalace.com/uploads/1667068018.png" alt="Mushroom"></div>

</body>

</font>

</html>
