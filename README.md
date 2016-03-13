# Bigdata

Погоду можно брать по этому API через JAVASCRIPT

$.getJSON('http://api.worldweatheronline.com/premium/v1/past-weather.ashx?key=62078294d9aa47698bc140823161303&q=Vladivostok&date=2015-12-01&format=json&enddate=2015-12-31', function(r){
console.log(r.data.weather.map((w) => parseInt(w.mintempC)));
})
