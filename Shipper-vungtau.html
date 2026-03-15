<!DOCTYPE html>  
<html lang="vi">  
<head>  
  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1">  
  
<title>Shipper Huy Mee | Bà Rịa Vũng Tàu</title>  
  
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css"/>  
  
<style>  
  
body{  
margin:0;  
font-family:Arial;  
background:#f2f2f2;  
text-align:center;  
}  
  
header{  
background:#ff3c00;  
color:white;  
padding:18px;  
}  
  
.logo{  
font-size:26px;  
font-weight:bold;  
}  
  
#map{  
height:320px;  
width:100%;  
}  
  
.container{  
padding:15px;  
}  
  
.box{  
background:white;  
padding:15px;  
margin:10px;  
border-radius:10px;  
box-shadow:0 3px 10px rgba(0,0,0,0.1);  
}  
  
.service{  
padding:8px;  
margin:4px;  
background:#fafafa;  
border-radius:6px;  
}  
  
input,select{  
width:90%;  
padding:10px;  
margin:6px;  
border-radius:6px;  
border:1px solid #ccc;  
}  
  
button{  
padding:12px 18px;  
border:none;  
border-radius:8px;  
margin:5px;  
font-size:16px;  
cursor:pointer;  
}  
  
.price{background:#ff9900;color:white;}  
.order{background:#0068ff;color:white;}  
.call{background:#00a86b;color:white;}  
  
footer{  
background:#222;  
color:white;  
padding:18px;  
margin-top:10px;  
}  
  
</style>  
  
</head>  
  
<body>  
  
<header>  
  
<div class="logo">🚚 Shipper Huy Mee</div>  
<p>Xe ôm – Giao hàng – Đi chợ – Gọi ô tô</p>  
  
</header>  
  
<div id="map"></div>  
  
<div class="container">  
  
<div class="box">  
  
<h3>Dịch vụ</h3>  
  
<div class="service">🛵 Xe ôm</div>  
<div class="service">📦 Giao hàng</div>  
<div class="service">🛒 Đi chợ</div>  
<div class="service">💸 Chuyển tiền</div>  
<div class="service">🚗 Gọi ô tô</div>  
  
</div>  
  
<div class="box">  
  
<h3>Đặt xe</h3>  
  
<input id="pickup" placeholder="Nhập điểm đón">  
  
<input id="drop" placeholder="Nhập điểm đến">  
  
<select id="vehicle">  
  
<option value="7000">Xe máy (7.000đ/km)</option>  
<option value="18000">Ô tô (18.000đ/km)</option>  
  
</select>  
  
<button class="price" onclick="calculate()">Tính quãng đường & giá</button>  
  
<h3 id="result"></h3>  
  
<button class="order" onclick="sendZalo()">Đặt xe qua Zalo</button>  
  
</div>  
  
<div class="box">  
  
<h3>Liên hệ nhanh</h3>  
  
<a href="tel:0932153207">  
<button class="call">📞 Gọi trực tiếp</button>  
</a>  
  
<a href="https://zalo.me/0932153207">  
<button class="order">💬 Chat Zalo</button>  
</a>  
  
</div>  
  
</div>  
  
<footer>  
  
📍 Phục vụ khu vực Bà Rịa – Vũng Tàu    
  
<br><br>  
  
Hotline: 0932153207  
  
</footer>  
  
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>  
  
<script>  
  
var map = L.map('map').setView([10.4113,107.1362],13);  
  
L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',{  
maxZoom:19  
}).addTo(map);  
  
let distanceKM=0;  
  
async function calculate(){  
  
let pickup=document.getElementById("pickup").value  
let drop=document.getElementById("drop").value  
  
let url1="https://nominatim.openstreetmap.org/search?format=json&q="+pickup  
let url2="https://nominatim.openstreetmap.org/search?format=json&q="+drop  
  
let res1=await fetch(url1)  
let data1=await res1.json()  
  
let res2=await fetch(url2)  
let data2=await res2.json()  
  
let lat1=data1[0].lat  
let lon1=data1[0].lon  
  
let lat2=data2[0].lat  
let lon2=data2[0].lon  
  
let route=`https://router.project-osrm.org/route/v1/driving/${lon1},${lat1};${lon2},${lat2}?overview=false`  
  
let res3=await fetch(route)  
let data3=await res3.json()  
  
distanceKM=data3.routes[0].distance/1000  
  
let vehicle=document.getElementById("vehicle").value  
  
let price=Math.round(distanceKM*vehicle)  
  
document.getElementById("result").innerHTML=  
  
"Quãng đường: "+distanceKM.toFixed(2)+" km <br>"  
  
+"💰 Giá tạm: "+price.toLocaleString()+" đ"  
  
}  
  
function sendZalo(){  
  
let pickup=document.getElementById("pickup").value  
let drop=document.getElementById("drop").value  
  
let vehicle=document.getElementById("vehicle")  
let type=vehicle.options[vehicle.selectedIndex].text  
  
let price=Math.round(distanceKM*vehicle.value)  
  
let message="ĐẶT XE%0A"  
  
+"Loại xe: "+type+"%0A"  
  
+"Điểm đón: "+pickup+"%0A"  
  
+"Điểm đến: "+drop+"%0A"  
  
+"Khoảng cách: "+distanceKM.toFixed(2)+" km%0A"  
  
+"Giá tạm: "+price+" đ"  
  
window.open("https://zalo.me/0932153207?text="+message)  
  
}  
  
</script>  
  
</body>  
</html>  
