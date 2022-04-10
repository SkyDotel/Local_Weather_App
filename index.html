<!DOCTYPE html>
<html>
 <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous">

 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
 <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js" integrity="sha384-vBWWzlZJ8ea9aCX4pEW3rVHjgjt7zpkNpZk+02D9phzyeVkE+jo0ieGizqPLForn" crossorigin="anonymous"></script>
 </head>
<body>


<script>
  function getWeather(){
  
  var ipCall = 'https://ipapi.co/json/';
  $.getJSON(ipCall, locationCallBack)
  
  function locationCallBack(locationData){
    var lat =locationData.latitude; 
    var lon = locationData.longitude;
    
    var apiCall = 'https://api.openweathermap.org/data/2.5/weather?lat='+lat+'&lon='+lon+'&units=imperial&appid=34e8aa0c1d8d15a560df7a7093711071';
    
    $.getJSON(apiCall, weatherCallBack)
  }
    
  function weatherCallBack(weatherData){
  var cityName = weatherData.name;
    
  var cityTemp = weatherData.main.temp;
  var cityTempRound = Math.round(cityTemp)
  
  var cityWind= weatherData.wind.speed;
  var cityWindRound = Math.round(cityWind);
  
  var weatherType = weatherData.weather[0].description;
  
  var weatherIcon = weatherData.weather[0].icon;
  var iconURL = 'http://openweathermap.org/img/w/' + weatherIcon + '.png';
  
  $('.icon').html("<img src = '" + iconURL + "'>");
  $('.cityTemp').append(cityTempRound);
  $('.cityName').append(cityName);
  $('.weatherType').append("There appears to be: " + weatherType);
  $('.cityWind').append("Wind Speed: "+ cityWindRound + " MPH");  
  
    }

  }
getWeather()

</script>
  
  
<script>
  function toggle(){
    var x = document.getElementById("myUnit");
    var z = x.innerHTML;
    
    
    
    if( x.innerHTML == "F"){
        x.innerHTML = "C";
      
      var y = document.getElementById("temp");
    var t = y.innerHTML;
    var intValue = parseInt(t);
      var cValue = Math.round((intValue - 32)/1.8);
        y.innerHTML = cValue;
    } else {
        x.innerHTML = "F";
      var y = document.getElementById("temp");
    var t = y.innerHTML;
    var intValue = parseInt(t);
      var fValue = Math.round((intValue * 1.8) + 32);
        y.innerHTML = fValue;
      
    }
    

  }      
</script>
  
  <div class="alert">
  <span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span> 
  Tip: Click the switch to toggle between F and C.
</div>
  <center> 
  <h1 id="title"> Local Weather App</h1>
   

<div class="well b">
  <div class="row justify-content-sm-center">
    <div id="weatherIcon" class ="icon" class="col-sm-auto">
    </div>
    <div id= "temp" class="cityTemp" class="col-sm-auto" style= "color:white">
    </div>
    <div id="tempUnit" class="col-sm-auto" style= "color:white">
      <p id="myUnit" >F</p>
    </div>
    <div id="sliderId">
      <label class="switch">
      <input onchange= "toggle()" type="checkbox">
      <div class="slider round"></div>
      </label>
    </div>

  </div>  
  
  <div class="row justify-content-sm-center">
    <div id="city" class="cityName" class = "col-sm-auto">
      
    </div>
    <div id="type" class="weatherType" class = "col-sm-auto">
      
    </div>
  
    <div id="wind" class="cityWind" class= "col-sm-auto" >
    </div>
  </div>
  </div>
</div>
  
  </center>
  
  <div id="TM">
    <p>Coded by <a href="https://github.com/tkfriend89" target="_blank">Sky Dotel</a></p>
    </div>
</body>
</html>
