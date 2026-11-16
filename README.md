<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>北陸粉雪 × 京都古都 親子六日旅</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Huninn&display=swap" rel="stylesheet">
<style>
:root{--paper:#FFFCF6;--ink:#3E3A39;--coral:#F2A497;--yellow:#F6D27A;--aqua:#A8D3E6;--green:#B9DAA5;color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*,*::before,*::after{box-sizing:border-box}
html{scroll-padding-top:calc(env(safe-area-inset-top,0px) + 64px);scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--ink);font-family:"Huninn","PingFang TC","Noto Sans TC","Microsoft JhengHei",sans-serif;font-size:16px;line-height:1.7}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--paper);z-index:60}
nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:50;background:var(--paper);border-bottom:3px solid var(--ink);display:flex;gap:8px;overflow-x:auto;padding:10px 14px;scrollbar-width:none}
nav::-webkit-scrollbar{display:none}
nav a{flex:none;color:var(--ink);text-decoration:none;border:3px solid var(--ink);border-radius:999px;padding:2px 14px;background:var(--paper);font-size:15px}
nav a:nth-child(4n+1){background:var(--coral)}nav a:nth-child(4n+2){background:var(--yellow)}nav a:nth-child(4n+3){background:var(--aqua)}nav a:nth-child(4n){background:var(--green)}
nav a:focus-visible,button:focus-visible{outline:3px dashed var(--ink);outline-offset:3px}
main{max-width:720px;margin:0 auto;padding:16px 14px 60px}
section{margin-top:34px}
h1,h2,h3,p{margin:0}
h2{font-size:24px;margin-bottom:14px;display:inline-block;background:var(--yellow);border:3px solid var(--ink);border-radius:18px;padding:0 16px}
.box{border:3px solid var(--ink);border-radius:26px;background:var(--paper);padding:16px}
.hero{padding:0;overflow:hidden}
.hero svg{display:block;width:100%;height:auto;border-bottom:3px solid var(--ink)}
.hero .tx{padding:16px;text-align:center}
.hero h1{font-size:28px;line-height:1.35}
.hero p{margin-top:4px}
.chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:10px}
.chip{border:3px solid var(--ink);border-radius:999px;padding:0 12px;font-size:14px;background:var(--aqua)}
.count{display:flex;gap:8px;justify-content:center;margin-top:14px}
.count div{border:3px solid var(--ink);border-radius:20px;background:var(--coral);min-width:68px;padding:4px 6px;text-align:center}
.count b{display:block;font-size:28px;line-height:1.2}.count span{font-size:13px}
.cnote{text-align:center;margin-top:8px;font-size:14px}
.flight{display:grid;gap:14px}
.fl{border:3px solid var(--ink);border-radius:26px;padding:14px 16px;background:var(--aqua)}
.fl.back{background:var(--green)}
.fl .tag{display:inline-block;border:3px solid var(--ink);border-radius:999px;background:var(--paper);padding:0 12px;font-size:14px}
.route{display:flex;align-items:center;justify-content:space-between;gap:6px;margin-top:8px;text-align:center}
.route b{display:block;font-size:26px;line-height:1.2}.route small{font-size:13px}
.route svg{flex:1;max-width:110px;height:34px}
.tabs{display:flex;gap:8px;overflow-x:auto;padding:4px 2px 12px;scrollbar-width:none}
.tabs::-webkit-scrollbar{display:none}
.tabs button{flex:none;font:inherit;color:var(--ink);border:3px solid var(--ink);border-radius:20px;background:var(--paper);padding:2px 14px;line-height:1.4;cursor:pointer;text-align:center}
.tabs button small{display:block;font-size:12px}
.tabs button[aria-selected=true]{background:var(--c);animation:pop .5s cubic-bezier(.3,1.8,.5,1)}
.panel.pop{animation:pop .55s cubic-bezier(.3,1.6,.5,1)}
.dhead{background:var(--c);border:3px solid var(--ink);border-radius:26px;padding:12px 16px;margin-bottom:16px}
.dhead h3{font-size:22px}.dhead p{font-size:14px}
.tl{position:relative;margin:0;padding:0 0 0 30px;list-style:none}
.tl::before{content:"";position:absolute;left:9px;top:8px;bottom:8px;border-left:3px dashed var(--ink)}
.tl li{position:relative;margin-bottom:14px;border:3px solid var(--ink);border-radius:22px;padding:10px 14px;background:var(--paper)}
.tl li::before{content:"";position:absolute;left:-29px;top:16px;width:16px;height:16px;border:3px solid var(--ink);border-radius:50%;background:var(--c)}
.tl .t{font-size:14px;display:flex;flex-wrap:wrap;gap:6px;align-items:center}
.lab{border:3px solid var(--ink);border-radius:999px;padding:0 10px;font-size:13px;line-height:1.5}
.lab.go{background:var(--aqua)}.lab.eat{background:var(--yellow)}.lab.tkt{background:var(--coral)}.lab.stay{background:var(--green)}.lab.see{background:var(--paper)}
.must{margin-left:auto;background:var(--coral);border:3px solid var(--ink);border-radius:12px;padding:0 10px;font-size:13px;transform:rotate(3deg)}
.tl h4{margin:4px 0 0;font-size:17px;font-weight:400}
.tl p{font-size:14px}
.tl li.bk{background:var(--green)}.tl li.bk::before{background:var(--paper)}
.two{display:grid;gap:14px}
.lodge{border:3px solid var(--ink);border-radius:26px;padding:14px 16px}
.lodge h3{font-size:19px}
.chk{list-style:none;margin:0;padding:0}
.chk li{margin-bottom:8px}
.chk label{display:flex;gap:10px;align-items:flex-start;border:3px solid var(--ink);border-radius:18px;padding:6px 12px;cursor:pointer;background:var(--paper)}
.chk input{appearance:none;flex:none;width:24px;height:24px;margin:3px 0 0;border:3px solid var(--ink);border-radius:8px;background:var(--paper);cursor:pointer;display:grid;place-content:center}
.chk input:checked{background:var(--green)}
.chk input:checked::after{content:"";width:6px;height:11px;border:solid var(--ink);border-width:0 3px 3px 0;transform:rotate(40deg) translate(-1px,-1px)}
.chk input:checked+span{text-decoration:line-through;opacity:.55}
.chk input:focus-visible{outline:3px dashed var(--ink);outline-offset:3px}
.chk small{display:block;font-size:13px;opacity:.8}
.bar{height:18px;border:3px solid var(--ink);border-radius:999px;background:var(--paper);margin:0 0 12px;overflow:hidden}
.bar i{display:block;height:100%;width:0;background:var(--c,var(--coral));transition:width .4s}
.grp{margin-top:14px}.grp h3{font-size:18px;display:inline-block;border:3px solid var(--ink);border-radius:14px;padding:0 12px;margin-bottom:8px;background:var(--g)}
.sc{overflow-x:auto;border:3px solid var(--ink);border-radius:22px}
table{border-collapse:collapse;width:100%;min-width:430px;font-size:14px}
th,td{padding:6px 10px;text-align:left;border-bottom:2px solid var(--ink)}
th{background:var(--yellow)}tr:last-child td{border-bottom:0}
footer{text-align:center;font-size:13px;margin-top:30px}
.snow{animation:fall var(--d,6s) linear var(--w,0s) infinite}
.cloud{animation:drift 9s ease-in-out infinite alternate}
.train{animation:run 14s linear infinite}
.sun{transform-box:fill-box;transform-origin:center;animation:spin 20s linear infinite}.tw{transform-box:fill-box;transform-origin:center;animation:tw 2.4s ease-in-out infinite}.beacon{animation:bk 1.6s ease-in-out infinite}
.plane{animation:fly 3s ease-in-out infinite alternate}
.smoke{animation:fall2 3s ease-out infinite}
@keyframes fall{from{transform:translateY(-12px)}to{transform:translateY(230px)}}
@keyframes drift{to{transform:translateX(26px)}}
@keyframes run{from{transform:translateX(-170px)}to{transform:translateX(380px)}}@keyframes tw{0%,100%{transform:scale(.3);opacity:.4}50%{transform:scale(1.2);opacity:1}}@keyframes bk{50%{opacity:.25}}
@keyframes spin{to{transform:rotate(360deg)}}
@keyframes fly{to{transform:translateY(-5px)}}
@keyframes fall2{from{opacity:.9;transform:translateY(0)}to{opacity:0;transform:translateY(-14px)}}
@keyframes pop{0%{transform:scale(.88) translateY(10px)}60%{transform:scale(1.04)}100%{transform:none}}
@media (prefers-reduced-motion:reduce){*,*::before,*::after{animation:none!important;transition:none!important;scroll-behavior:auto!important}}
@media(min-width:600px){.flight,.two{grid-template-columns:1fr 1fr}}
</style>
</head>
<body>
<nav aria-label="頁面選單"><a href="#top">首頁</a><a href="#flight">航班</a><a href="#days">每日行程</a><a href="#stay">住宿</a><a href="#todo">待辦</a><a href="#pre">出發前</a><a href="#pack">行李</a><a href="#info">資訊</a></nav>
<main id="top">

<div class="box hero">
<svg viewBox="0 0 360 250" role="img" aria-label="金澤鼓門與雪吊、京都塔、五重塔與鳥居，新幹線穿梭其間的插圖">
<rect width="360" height="250" fill="#A8D3E6"/>
<g class="sun"><circle cx="190" cy="42" r="15" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M190 14v7M190 63v7M162 42h7M211 42h7" stroke="#3E3A39" stroke-width="3" stroke-linecap="round"/></g>
<g class="cloud"><path d="M70 62q0-12 12-12 5-9 17-6 9 2 10 10 10 0 10 8H70z" fill="#FFFCF6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/></g>
<g class="cloud" style="animation-delay:-4s"><path d="M244 40q0-10 10-10 4-8 15-5 8 2 9 9 8 0 8 6h-42z" fill="#FFFCF6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/></g>
<path d="M-4 192 50 124 86 160 130 100 178 170 220 128 270 178 310 138 364 192V206H-4z" fill="#FFFCF6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<path d="M22 206C40 170 46 150 50 124L66 124C62 150 56 176 46 206Z" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<path d="M104 206C86 170 80 150 76 124L60 124C64 150 70 176 80 206Z" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<path d="M22 128Q63 78 104 128Z" fill="#A8D3E6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M63 100V126M42 112 50 126M84 112 76 126" stroke="#3E3A39" stroke-width="2" stroke-linecap="round"/>
<path d="M152 98 126 154M152 98 178 154M152 98 120 182M152 98 184 182M152 98 132 130M152 98 172 130" stroke="#3E3A39" stroke-width="1.8" fill="none"/>
<rect x="146" y="182" width="12" height="24" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<path d="M152 100 132 130H172Z" fill="#B9DAA5" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M152 118 126 154H178Z" fill="#B9DAA5" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M152 140 120 182H184Z" fill="#B9DAA5" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<path d="M152 100 143 113H161Z" fill="#FFFCF6"/><path d="M152 118 140 136H164Z" fill="#FFFCF6" opacity=".9"/>
<path d="M152 140 134 164H170Z" fill="#FFFCF6" opacity=".9"/>
<path d="M152 96v-8" stroke="#3E3A39" stroke-width="3" stroke-linecap="round"/>
<g transform="translate(40 96)"><path class="tw" style="animation-delay:0s" d="M0-7 2-2 7 0 2 2 0 7-2 2-7 0-2-2Z" fill="#F6D27A" stroke="#3E3A39" stroke-width="1.6" stroke-linejoin="round"/></g><g transform="translate(98 92)"><path class="tw" style="animation-delay:0.8s" d="M0-7 2-2 7 0 2 2 0 7-2 2-7 0-2-2Z" fill="#F6D27A" stroke="#3E3A39" stroke-width="1.6" stroke-linejoin="round"/></g><g transform="translate(168 82)"><path class="tw" style="animation-delay:1.6s" d="M0-7 2-2 7 0 2 2 0 7-2 2-7 0-2-2Z" fill="#F6D27A" stroke="#3E3A39" stroke-width="1.6" stroke-linejoin="round"/></g><g transform="translate(120 150)"><path class="tw" style="animation-delay:0.4s" d="M0-7 2-2 7 0 2 2 0 7-2 2-7 0-2-2Z" fill="#F6D27A" stroke="#3E3A39" stroke-width="1.6" stroke-linejoin="round"/></g><g transform="translate(24 150)"><path class="tw" style="animation-delay:1.2s" d="M0-7 2-2 7 0 2 2 0 7-2 2-7 0-2-2Z" fill="#F6D27A" stroke="#3E3A39" stroke-width="1.6" stroke-linejoin="round"/></g>
<path d="M224 190 229 112H235L240 190Z" fill="#FFFCF6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><rect x="216" y="190" width="32" height="16" fill="#FFFCF6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<path d="M214 98Q232 80 250 98Q232 114 214 98Z" fill="#FFFCF6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M220 98H244" stroke="#F2A497" stroke-width="5" stroke-linecap="round"/>
<path d="M232 82V58" stroke="#3E3A39" stroke-width="3" stroke-linecap="round"/><circle class="beacon" cx="232" cy="55" r="4" fill="#F2A497" stroke="#3E3A39" stroke-width="2.5"/>
<rect x="272.0" y="192" width="36.0" height="14" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M266.0 192H314.0L307.0 181H273.0Z" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><rect x="274.0" y="178" width="32.0" height="3" rx="1.5" fill="#FFFCF6"/><rect x="275.5" y="175" width="29.0" height="14" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M269.5 175H310.5L303.5 164H276.5Z" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><rect x="277.5" y="161" width="25.0" height="3" rx="1.5" fill="#FFFCF6"/><rect x="279.0" y="158" width="22.0" height="14" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M273.0 158H307.0L300.0 147H280.0Z" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><rect x="281.0" y="144" width="18.0" height="3" rx="1.5" fill="#FFFCF6"/><rect x="282.5" y="141" width="15.0" height="14" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M276.5 141H303.5L296.5 130H283.5Z" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><rect x="284.5" y="127" width="11.0" height="3" rx="1.5" fill="#FFFCF6"/><rect x="286.0" y="124" width="8.0" height="14" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M280.0 124H300.0L293.0 113H287.0Z" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><rect x="288.0" y="110" width="4.0" height="3" rx="1.5" fill="#FFFCF6"/><path d="M290 112V92" stroke="#3E3A39" stroke-width="3" stroke-linecap="round"/><circle cx="290" cy="94" r="3" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<rect x="323" y="158" width="7" height="48" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><rect x="343" y="158" width="7" height="48" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<rect x="326" y="170" width="21" height="6" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M317 156Q336.500 148 356 156L354 164H319Z" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/>
<rect y="206" width="360" height="44" fill="#FFFCF6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><path d="M0 244H360" stroke="#3E3A39" stroke-width="3"/>
<g class="train"><rect x="0" y="212" width="132" height="26" rx="13" fill="#FFFCF6" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><rect x="22" y="220" width="14" height="8" rx="3" fill="#A8D3E6" stroke="#3E3A39" stroke-width="2"/><rect x="44" y="220" width="14" height="8" rx="3" fill="#A8D3E6" stroke="#3E3A39" stroke-width="2"/><rect x="66" y="220" width="14" height="8" rx="3" fill="#A8D3E6" stroke="#3E3A39" stroke-width="2"/><rect x="88" y="220" width="14" height="8" rx="3" fill="#A8D3E6" stroke="#3E3A39" stroke-width="2"/><rect x="110" y="220" width="14" height="8" rx="4" fill="#A8D3E6" stroke="#3E3A39" stroke-width="2"/><path d="M12 233H122" stroke="#F2A497" stroke-width="4" stroke-linecap="round"/></g>
<rect x="10" y="10" width="64" height="26" rx="13" fill="#F2A497" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><text x="42" y="29" text-anchor="middle" font-size="15" fill="#3E3A39" font-family="Huninn,sans-serif">金澤</text>
<rect x="286" y="10" width="64" height="26" rx="13" fill="#F6D27A" stroke="#3E3A39" stroke-width="3" stroke-linejoin="round"/><text x="318" y="29" text-anchor="middle" font-size="15" fill="#3E3A39" font-family="Huninn,sans-serif">京都</text>
<g fill="#FFFCF6" stroke="#3E3A39" stroke-width="2"><circle class="snow" cx="18" cy="0" r="4" style="--d:5s;--w:-1s"/><circle class="snow" cx="52" cy="0" r="3" style="--d:7s;--w:-4s"/><circle class="snow" cx="96" cy="0" r="4" style="--d:6s;--w:-2s"/><circle class="snow" cx="140" cy="0" r="3" style="--d:8s;--w:-5s"/><circle class="snow" cx="190" cy="0" r="4" style="--d:5.5s;--w:-3s"/><circle class="snow" cx="228" cy="0" r="3" style="--d:7s;--w:-1s"/><circle class="snow" cx="270" cy="0" r="4" style="--d:6s;--w:-4.5s"/><circle class="snow" cx="310" cy="0" r="3" style="--d:8s;--w:-2.5s"/><circle class="snow" cx="344" cy="0" r="4" style="--d:6.5s;--w:-3.5s"/></g>
</svg>
<div class="tx">
<h1>北陸粉雪 × 京都古都<br>6天5夜親子旅</h1>
<p>金澤・京都・任天堂博物館・宇治</p>
<div class="chips"><span class="chip">2027/01/14（四）～ 01/19（二）</span><span class="chip" style="background:var(--coral)">2大2小（9歲、3歲）</span></div>
<div class="count" aria-live="polite"><div><b id="cd">–</b><span>天</span></div><div style="background:var(--yellow)"><b id="ch">–</b><span>小時</span></div><div style="background:var(--green)"><b id="cm">–</b><span>分鐘</span></div></div>
<p class="cnote" id="cn">距離出發</p>
</div>
</div>

<section id="flight"><h2>航班資訊</h2>
<div class="flight">
<div class="fl"><span class="tag">去程・長榮 BR158</span>
<div class="route"><div><b>06:35</b><small>桃園 TPE</small></div><svg viewBox="0 0 110 40" aria-hidden="true"><path d="M4 20h102" stroke="#3E3A39" stroke-width="3" stroke-dasharray="6 6" stroke-linecap="round"/><g class="plane"><g transform="translate(55 20)" fill="#FFFCF6" stroke="#3E3A39" stroke-width="2.5" stroke-linejoin="round" stroke-linecap="round"><path d="M3 -2.5 -5 -16H0L11 -2.5Z"/><path d="M3 2.5 -5 16H0L11 2.5Z"/><path d="M-12 -2.5-17 -8H-14L-8 -2.5Z"/><path d="M-12 2.5-17 8H-14L-8 2.5Z"/><path d="M-17 -2.5H11Q20 0 11 2.5H-17Q-20 0 -17 -2.5Z"/><circle cx="9" cy="0" r="1" fill="#3E3A39" stroke="none"/></g></g></svg><div><b>10:25</b><small>小松 KMQ</small></div></div></div>
<div class="fl back"><span class="tag">回程・長榮 BR129</span>
<div class="route"><div><b>18:10</b><small>關西 KIX</small></div><svg viewBox="0 0 110 40" aria-hidden="true"><path d="M4 20h102" stroke="#3E3A39" stroke-width="3" stroke-dasharray="6 6" stroke-linecap="round"/><g class="plane"><g transform="translate(55 20)" fill="#FFFCF6" stroke="#3E3A39" stroke-width="2.5" stroke-linejoin="round" stroke-linecap="round"><path d="M3 -2.5 -5 -16H0L11 -2.5Z"/><path d="M3 2.5 -5 16H0L11 2.5Z"/><path d="M-12 -2.5-17 -8H-14L-8 -2.5Z"/><path d="M-12 2.5-17 8H-14L-8 2.5Z"/><path d="M-17 -2.5H11Q20 0 11 2.5H-17Q-20 0 -17 -2.5Z"/><circle cx="9" cy="0" r="1" fill="#3E3A39" stroke="none"/></g></g></svg><div><b>20:25</b><small>桃園 TPE</small></div></div></div>
</div></section>

<section id="days"><h2>每日行程</h2>
<div class="tabs" id="tabs" role="tablist" aria-label="選擇日期"></div>
<div class="panel" id="panel" role="tabpanel"></div>
<div class="chips" style="justify-content:flex-start;margin-top:4px"><span class="lab go">交通</span><span class="lab eat">用餐</span><span class="lab tkt">門票</span><span class="lab see">景點</span><span class="lab stay">住宿</span></div>
</section>

<section id="stay"><h2>住宿資訊</h2>
<div class="two">
<div class="lodge" style="background:var(--aqua)"><h3>金澤｜Hyatt House Kanazawa</h3><p>Day 1～3（1/14–1/17 退房）</p><p>出站 1 分鐘，附微波爐、洗脫烘，適合帶小孩。</p></div>
<div class="lodge" style="background:var(--green)"><h3>京都｜MIMARU Kyoto Station</h3><p>Day 4～5（1/17–1/19 退房）</p><p>家庭公寓式、有廚房，近八條口。</p></div>
</div></section>

<section id="todo"><h2>待辦清單</h2><div class="bar"><i id="b-todo"></i></div><ul class="chk" id="l-todo"></ul></section>
<section id="pre"><h2>出發前清單</h2><div class="bar"><i id="b-pre" style="--c:var(--aqua)"></i></div><ul class="chk" id="l-pre"></ul></section>
<section id="pack"><h2>行李清單</h2><div class="bar"><i id="b-pack" style="--c:var(--green)"></i></div><div id="l-pack"></div></section>

<section id="info"><h2>交通與門票</h2>
<div class="sc"><table><tr><th>路段</th><th>方式</th><th>時間</th><th>成人</th></tr>
<tr><td>小松機場→金澤站</td><td>機場巴士</td><td>40–45 分</td><td>¥1,300</td></tr>
<tr><td>金澤→白川鄉</td><td>高速巴士</td><td>1 小時 15 分</td><td>¥2,600</td></tr>
<tr><td>金澤→京都</td><td>新幹線＋雷鳥</td><td>約 2 小時 10–30 分</td><td>¥7,480</td></tr>
<tr><td>京都→小倉</td><td>近鐵京都線</td><td>25–30 分</td><td>¥320</td></tr>
<tr><td>京都→宇治</td><td>JR 奈良線</td><td>約 17 分</td><td>¥240</td></tr>
<tr><td>京都→關西機場</td><td>Haruka 特急</td><td>約 75 分</td><td>¥3,630</td></tr></table></div>
<div class="sc" style="margin-top:14px"><table><tr><th>門票</th><th>成人</th><th>兒童</th></tr>
<tr><td>兼六園</td><td>¥320</td><td>¥100</td></tr><tr><td>金澤 21 世紀美術館</td><td>¥1,200</td><td>¥400</td></tr><tr><td>京都塔</td><td>¥1,000</td><td>¥700</td></tr><tr><td>任天堂博物館</td><td>¥3,300</td><td>¥1,100</td></tr><tr><td>平等院（庭園＋博物館）</td><td>¥700</td><td>¥300</td></tr><tr><td>京都府立植物園</td><td>¥200</td><td>免費</td></tr></table></div>
<p style="font-size:13px;margin-top:8px">※票價為現行參考，2027 年以官方公告為準。</p></section>
<footer>祝全家旅途平安，玩得開心 ❄️</footer>
</main>
<script>
const COL=['var(--aqua)','var(--green)','var(--yellow)','var(--coral)','var(--aqua)','var(--green)'];
const D=[
{d:'1/14（四）',w:'四',t:'降落雪國・自然庭園',s:'金澤｜住 Hyatt House',i:[
['10:25','go','抵達小松機場','機場巴士至金澤，約 40–45 分，¥1,300'],
['中午','eat','近江町市場','海鮮丼、松葉蟹'],
['下午','see','兼六園（雪吊）','成人 ¥320／兒童 ¥100（6 歲以下免費）',1],
['晚上','stay','金澤車站「鼓門」拍照','拍完入住 Hyatt House'],
['備案','bk','大雪改去','金澤 21 世紀美術館（室內）或金澤城公園']]},
{d:'1/15（五）',t:'童話雪景・動漫解凍',s:'金澤｜住 Hyatt House',i:[
['上午','go','白川鄉合掌村（半日遊）','金澤站⇄白川鄉，高巴須預約，單程約 1 小時 15 分、¥2,600',1],
['下午','see','金澤 FORUS 百貨 5F','寶可夢中心、鋼彈模型區'],
['晚上','eat','FORUS 6F 晚餐','金澤肉食堂或もりもり壽司'],
['備案','bk','大雪封路改去','石川縣立圖書館兒童區＋金箔工藝體驗（¥1,000 起）']]},
{d:'1/16（六）',t:'現代光影・江戶木造',s:'金澤｜住 Hyatt House',i:[
['上午','see','金澤 21 世紀美術館','泳池裝置等，成人 ¥1,200／國中小 ¥400',1],
['中午','eat','廣坂周邊洋食館或咖啡廳',''],
['下午','see','東茶屋街','江戶町家、金箔冰淇淋'],
['晚上','eat','金澤車站周邊商場','輕鬆晚餐、採買伴手禮'],
['備案','bk','大雪或低溫改去','金澤市內博物館（如設計館等室內展覽）']]},
{d:'1/17（日）',t:'行李解放・移防古都',s:'金澤→京都｜住 MIMARU',i:[
['上午','stay','退房，行李宅配','金澤→京都，約 ¥2,500–4,000／件'],
['中午','go','北陸新幹線＋特急雷鳥號','金澤→敦賀→京都，約 2 小時 10 分至 2 小時 30 分，成人約 ¥7,480／兒童約 ¥3,740'],
['下午','see','京都塔展望台','成人 ¥1,000／兒童 ¥700',1],
['晚上','eat','KYOTO TOWER SANDO B1 美食街','之後入住 MIMARU'],
['備案','bk','列車受天候影響','請先查 JR 西日本的列車時刻與運行資訊']]},
{d:'1/18（一）',t:'數位樂園・茶香美學',s:'京都｜住 MIMARU',i:[
['10:00','go','京都→近鐵京都線→小倉站','約 25–30 分，¥320'],
['11:00','tkt','入館任天堂博物館','成人 ¥3,300／兒童（6–11 歲）¥1,100，需事先預約，以官方最新票價為準',1],
['下午','see','JR 宇治站→平等院鳳凰堂','門票 ¥700／¥300，參道可吃抹茶甜點'],
['晚上','eat','回京都車站','涮涮鍋或壽喜燒'],
['備案','bk','任天堂館臨時調整','改去京都鐵道博物館或京都水族館（室內）']]},
{d:'1/19（二）',t:'植物溫室・直達機場',s:'京都→關西機場→桃園',i:[
['上午','see','京都府立植物園','巨大溫室，親子放電；門票 ¥200，中小學生免費'],
['下午','go','回 MIMARU 取行李','京都車站 1 樓 30 號月台搭 Haruka 特急，約 75 分，自由席約 ¥3,630'],
['傍晚','see','關西機場免稅店','最後採買'],
['18:10','go','搭 BR129 返台','20:25 抵達桃園']]}];
const LB={go:'交通',eat:'用餐',tkt:'門票',see:'景點',stay:'住宿',bk:'備案'};
const tabs=document.getElementById('tabs'),panel=document.getElementById('panel');
D.forEach((x,n)=>{const b=document.createElement('button');b.setAttribute('role','tab');b.style.setProperty('--c',COL[n]);b.innerHTML='Day '+(n+1)+'<small>'+x.d.split('（')[0]+'</small>';b.onclick=()=>show(n,true);tabs.appendChild(b)});
function show(n,anim){const x=D[n];[...tabs.children].forEach((b,k)=>b.setAttribute('aria-selected',k===n));
let h='<div class="dhead" style="--c:'+COL[n]+'"><h3>Day '+(n+1)+'｜'+x.t+'</h3><p>'+x.d+'・'+x.s+'</p></div><ol class="tl" style="--c:'+COL[n]+'">';
x.i.forEach(r=>{const bk=r[1]==='bk';h+='<li'+(bk?' class="bk"':'')+'><div class="t"><span>'+r[0]+'</span><span class="lab '+(bk?'see':r[1])+'">'+LB[r[1]]+'</span>'+(r[4]?'<span class="must">必去</span>':'')+'</div><h4>'+r[2]+'</h4>'+(r[3]?'<p>'+r[3]+'</p>':'')+'</li>'});
panel.innerHTML=h+'</ol>';panel.classList.remove('pop');if(anim){void panel.offsetWidth;panel.classList.add('pop')}}
show(0,false);
const LS={get(k){try{return JSON.parse(localStorage.getItem(k)||'{}')}catch(e){return{}}},set(k,v){try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}}};
function list(key,el,items){const st=LS.get(key),ul=document.getElementById(el),bar=document.getElementById('b-'+key);
const upd=()=>{const c=ul.querySelectorAll('input:checked').length,t=ul.querySelectorAll('input').length;bar.style.width=(t?c/t*100:0)+'%'};
items.forEach((it,n)=>{const li=document.createElement('li'),id=key+n;li.innerHTML='<label><input type="checkbox" '+(st[id]?'checked':'')+'><span>'+it[0]+(it[1]?'<small>'+it[1]+'</small>':'')+'</span></label>';
li.querySelector('input').onchange=e=>{const s=LS.get(key);s[id]=e.target.checked;LS.set(key,s);upd()};ul.appendChild(li)});upd()}
list('todo','l-todo',[['預約任天堂博物館 1/18 入館','11:00 入館，開放預約時就訂'],['預約白川鄉高速巴士','金澤⇄白川鄉，預約制'],['預約飯店行李宅配','金澤→京都，約 ¥2,500–4,000／件'],['查 JR 西日本列車時刻','新幹線與雷鳥號，天候受影響時備用'],['訂 Haruka 特急往關西機場','1/19 自由席約 ¥3,630'],['確認各景點門票與開放時間','2027 年以官方公告為準']]);
list('pre','l-pre',[['護照效期（6 個月以上）','全家四人'],['Visit Japan Web 填寫',''],['購買網卡或 eSIM',''],['兌換日幣現金','買 ICOCA 與小吃用'],['準備交通卡','建議每人一張 ICOCA（或 Suiica／PASMO）'],['旅平險與保險文件',''],['列印或截圖機票、訂房、預約憑證','']]);
const PK=[['衣物','var(--coral)',['洋蔥式穿法保暖衣物','防水雪靴','手套、毛帽、圍巾','小孩備用衣褲、襪子','睡衣、貼身衣物']],['證件與錢','var(--yellow)',['護照（全家）','日幣現金、信用卡','ICOCA 卡','訂房與票券截圖']],['3C','var(--aqua)',['手機、行動電源','充電線與日本轉接頭','網卡或 eSIM']],['小孩用品','var(--green)',['常備藥與暖暖包','濕紙巾、備用口罩','零食、水壺','玩具或繪本（交通移動用）']]];
const pk=document.getElementById('l-pack'),pst=LS.get('pack');let pn=0;
PK.forEach(g=>{const d=document.createElement('div');d.className='grp';d.innerHTML='<h3 style="--g:'+g[1]+'">'+g[0]+'</h3><ul class="chk"></ul>';const ul=d.querySelector('ul');
g[2].forEach(t=>{const id='p'+pn++,li=document.createElement('li');li.innerHTML='<label><input type="checkbox" '+(pst[id]?'checked':'')+'><span>'+t+'</span></label>';
li.querySelector('input').onchange=e=>{const s=LS.get('pack');s[id]=e.target.checked;LS.set('pack',s);pbar()};ul.appendChild(li)});pk.appendChild(d)});
function pbar(){const i=pk.querySelectorAll('input');document.getElementById('b-pack').style.width=(i.length?pk.querySelectorAll('input:checked').length/i.length*100:0)+'%'}pbar();
const T0=new Date('2027-01-14T06:35:00+08:00'),END=new Date('2027-01-19T20:25:00+08:00');
function tick(){const now=new Date(),ms=T0-now;if(ms<=0){document.getElementById('cn').textContent=now<END?'旅程進行中，玩得開心！':'旅程已結束，謝謝你們一起出遊';['cd','ch','cm'].forEach(i=>document.getElementById(i).textContent='0');return}
const m=Math.floor(ms/6e4);document.getElementById('cd').textContent=Math.floor(m/1440);document.getElementById('ch').textContent=Math.floor(m%1440/60);document.getElementById('cm').textContent=m%60;document.getElementById('cn').textContent='距離 1/14 06:35 桃園起飛'}
tick();setInterval(tick,3e4);
</script>
</body>
</html>
