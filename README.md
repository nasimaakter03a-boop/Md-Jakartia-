
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Jakartia Candle AI</title>
<style>
body{background:#080e19;color:white;font-family:Arial;margin:0;padding:15px}
h2{text-align:center;color:#35d9a0}
.card{background:#151f30;padding:15px;border-radius:12px;margin:12px 0}
iframe{width:100%;height:420px;border:0}
button{padding:13px;border:0;border-radius:8px;background:#16a879;color:white;font-weight:bold;width:100%}
.small{color:#9eabc0;font-size:13px}
</style>
</head>
<body>
<h2>📊 JAKARTIA CANDLE AI</h2>
<div class="card">
<h3>লাইভ মার্কেট চার্ট</h3>
<div class="small">USD / MXN · TradingView</div>
<iframe src="https://s.tradingview.com/widgetembed/?symbol=FX%3AUSDMXN&interval=1&hidesidetoolbar=1&symboledit=1&saveimage=0&toolbarbg=080e19&theme=dark&style=1&timezone=Etc%2FUTC&withdateranges=1&hideideas=1"></iframe>
</div>
<div class="card">
<h3>🤖 ক্যান্ডেল বিশ্লেষণ</h3>
<p id="signal">বিশ্লেষণের জন্য বাটনে চাপ দিন</p>
<button onclick="analyze()">ANALYZE MARKET</button>
</div>
<div class="card">
<h3>⚠️ গুরুত্বপূর্ণ</h3>
<p class="small">এই সংস্করণে লাইভ চার্ট দেখা যাবে। বিশ্লেষণ বাটনটি এখনো ডেমো। এটি বাস্তব Buy/Sell সংকেত দেয় না।</p>
</div>
<script>
function analyze(){
document.getElementById("signal").innerHTML=
"চার্ট পর্যবেক্ষণ করুন। পরবর্তী সংস্করণে প্রকৃত OHLC ডেটা দিয়ে ক্যান্ডেল প্যাটার্ন শনাক্তকরণ যুক্ত হবে।";
}
</script>
</body>
</html>
