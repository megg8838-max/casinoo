<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Космическое Казино</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif;background:#07060f;overflow:hidden;height:100vh;width:100vw;user-select:none;color:#fff}
#app{height:100vh;max-width:500px;margin:0 auto;background:#07060f;position:relative;overflow:hidden;display:flex;flex-direction:column}

/* AUTH */
.auth-screen{position:absolute;inset:0;background:radial-gradient(circle at 50% 30%,#2a1233 0%,#07060f 70%);display:flex;flex-direction:column;align-items:center;justify-content:center;padding:30px;z-index:100;overflow-y:auto}
.auth-logo{font-size:4.5rem;margin-bottom:15px;animation:float 3s ease-in-out infinite;filter:drop-shadow(0 0 25px rgba(255,215,0,.6))}
@keyframes float{0%,100%{transform:translateY(0) rotate(-3deg)}50%{transform:translateY(-14px) rotate(3deg)}}
.auth-title{font-size:2rem;font-weight:900;margin-bottom:6px;background:linear-gradient(135deg,#ffd700,#ff8c00,#c792ea);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;text-align:center}
.auth-subtitle{color:#887;font-size:.85rem;margin-bottom:35px;text-align:center}
.auth-form{width:100%;max-width:320px}
.input-group{margin-bottom:18px;position:relative}
.input-label{position:absolute;top:-8px;left:15px;background:#07060f;padding:0 8px;font-size:.72rem;color:#ffd700;font-weight:600;opacity:0;transition:all .3s;pointer-events:none;z-index:2}
.input-group.focused .input-label,.input-group.filled .input-label{opacity:1}
.auth-input{width:100%;padding:17px 20px;background:rgba(255,255,255,.03);border:2px solid rgba(255,255,255,.08);border-radius:14px;font-size:1rem;color:#fff;outline:none;transition:all .3s;font-family:inherit}
.auth-input:focus{background:rgba(255,215,0,.05);border-color:rgba(255,215,0,.4);box-shadow:0 0 30px rgba(255,215,0,.15)}
.auth-input::placeholder{color:rgba(255,255,255,.2)}
.pass-meter{display:flex;gap:4px;margin-top:8px;height:4px}
.pass-bar{flex:1;background:rgba(255,255,255,.08);border-radius:2px;transition:all .3s}
.pass-bar.on{background:#ffc107}
.pass-bar.strong{background:#00ff88}
.pass-hint{font-size:.72rem;color:#667;margin-top:5px}
.pass-hint.ok{color:#00ff88}
.auth-btn{width:100%;padding:17px;border:none;border-radius:14px;font-size:1rem;font-weight:700;cursor:pointer;margin-bottom:12px;transition:all .25s;font-family:inherit;letter-spacing:1px}
.auth-btn.primary{background:linear-gradient(135deg,#ffd700,#ff8c00);color:#07060f;box-shadow:0 6px 25px rgba(255,215,0,.4)}
.auth-btn.primary:active{transform:scale(.98)}
.auth-btn.primary:disabled{opacity:.6}
.auth-btn.secondary{background:transparent;color:#fff;border:2px solid rgba(255,255,255,.15)}
.auth-btn.secondary:hover{border-color:rgba(255,215,0,.5);color:#ffd700}
.auth-switch{color:rgba(255,255,255,.45);font-size:.85rem;margin-top:10px;text-align:center}
.auth-switch span{color:#ffd700;font-weight:600;cursor:pointer}

.success-overlay{position:fixed;inset:0;background:rgba(7,6,15,.96);display:flex;align-items:center;justify-content:center;z-index:999;opacity:0;pointer-events:none;transition:opacity .4s}
.success-overlay.show{opacity:1;pointer-events:all}
.success-circle{width:110px;height:110px;border-radius:50%;background:linear-gradient(135deg,#00ff88,#00cc6a);display:flex;align-items:center;justify-content:center;font-size:3.5rem;color:#fff;transform:scale(0);box-shadow:0 0 60px rgba(0,255,136,.7);transition:transform .5s cubic-bezier(.68,-.55,.27,1.55)}
.success-overlay.show .success-circle{transform:scale(1)}

/* HEADER */
.header{background:#0f0d1e;padding:12px 14px;display:flex;align-items:center;gap:8px;min-height:56px;border-bottom:1px solid rgba(255,255,255,.06);z-index:20}
.header-title{font-size:.95rem;font-weight:800;flex:1;background:linear-gradient(135deg,#fff,#ffd700);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.header-coins{background:linear-gradient(135deg,#ffd700,#ffaa00);color:#000;padding:6px 12px;border-radius:20px;font-weight:800;font-size:.82rem;box-shadow:0 2px 12px rgba(255,215,0,.3);white-space:nowrap}

/* NAV */
.bottom-nav{display:flex;background:#0f0d1e;border-top:1px solid rgba(255,255,255,.06);padding:8px 0 10px;position:absolute;bottom:0;left:0;right:0;z-index:50}
.nav-item{flex:1;text-align:center;padding:5px;cursor:pointer;color:#556;transition:all .2s}
.nav-item.active{color:#ffd700}
.nav-icon{font-size:1.3rem;display:block;transition:transform .2s}
.nav-item.active .nav-icon{transform:scale(1.15)}
.nav-label{font-size:.62rem;margin-top:2px;font-weight:600}

/* SCREENS */
.screen{flex:1;overflow-y:auto;padding-bottom:90px;display:none}
.screen.active{display:block}

/* STAT BAR */
.stat-bar{background:#0f0d1e;padding:10px 14px;border-bottom:1px solid rgba(255,255,255,.05);display:flex;gap:8px}
.stat-pill{flex:1;background:#181528;border-radius:10px;padding:8px 10px;text-align:center;border:1px solid rgba(255,255,255,.05)}
.stat-pill .v{font-size:1rem;font-weight:800;color:#ffd700}
.stat-pill .l{font-size:.6rem;color:#667;margin-top:2px;text-transform:uppercase}

/* GAME GRID */
.game-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px;padding:14px}
.game-card{background:linear-gradient(135deg,#181528,#0f0d1e);border:2px solid rgba(255,215,0,.15);border-radius:18px;padding:20px 14px;text-align:center;cursor:pointer;transition:all .25s}
.game-card:hover{border-color:rgba(255,215,0,.5);transform:translateY(-3px);box-shadow:0 8px 30px rgba(255,215,0,.15)}
.game-card:active{transform:translateY(0)}
.game-card-icon{font-size:2.6rem;margin-bottom:8px;display:block}
.game-card-name{font-weight:800;font-size:.95rem;margin-bottom:3px}
.game-card-desc{font-size:.7rem;color:#778}

/* SLOTS */
.slots-wrap{padding:20px 14px;text-align:center}
.slots-machine{background:linear-gradient(135deg,#181528,#0f0d1e);border:3px solid rgba(255,215,0,.3);border-radius:20px;padding:20px 14px;margin-bottom:18px}
.slots-reels{display:flex;justify-content:center;gap:10px;margin:15px 0}
.reel{width:80px;height:100px;background:#07060f;border:2px solid rgba(255,215,0,.25);border-radius:14px;display:flex;align-items:center;justify-content:center;font-size:3rem;font-weight:900;transition:transform .1s}
.reel.spin{animation:reelSpin .1s infinite}
@keyframes reelSpin{0%{transform:translateY(-8px);opacity:.7}50%{transform:translateY(0);opacity:1}100%{transform:translateY(8px);opacity:.7}}
.reel.win{border-color:#00ff88;box-shadow:0 0 25px rgba(0,255,136,.7)}
.slots-payout{font-size:.75rem;color:#889;margin-bottom:10px;line-height:1.5}
.slots-payout b{color:#ffd700}

/* BET PANEL */
.bet-panel{background:#181528;border-radius:14px;padding:14px;margin-bottom:14px;border:1px solid rgba(255,255,255,.06)}
.bet-panel-title{font-size:.8rem;color:#889;margin-bottom:8px;text-transform:uppercase;letter-spacing:1px}
.bet-chips{display:flex;gap:8px;justify-content:center;flex-wrap:wrap}
.chip{padding:10px 14px;background:linear-gradient(135deg,#2a1f3d,#181528);border:2px solid rgba(255,215,0,.3);border-radius:12px;color:#ffd700;font-weight:800;font-size:.85rem;cursor:pointer;font-family:inherit;transition:all .2s;min-width:60px}
.chip:active{transform:scale(.95)}
.chip.selected{background:linear-gradient(135deg,#ffd700,#ff8c00);color:#07060f;border-color:#ffd700}

/* SPIN */
.spin-btn{width:100%;padding:20px;border:none;border-radius:16px;background:linear-gradient(135deg,#ffd700,#ff8c00);color:#07060f;font-weight:900;font-size:1.1rem;cursor:pointer;font-family:inherit;letter-spacing:2px;box-shadow:0 8px 30px rgba(255,215,0,.4);transition:all .2s;margin-top:10px}
.spin-btn:active{transform:scale(.98)}
.spin-btn:disabled{opacity:.5;cursor:not-allowed}

/* ROULETTE */
.roulette-wheel{width:240px;height:240px;margin:20px auto;border-radius:50%;background:conic-gradient(#ff1744 0deg 10deg,#000 10deg 20deg,#ff1744 20deg 30deg,#000 30deg 40deg,#ff1744 40deg 50deg,#000 50deg 60deg,#ff1744 60deg 70deg,#000 70deg 80deg,#ff1744 80deg 90deg,#000 90deg 100deg,#ff1744 100deg 110deg,#000 110deg 120deg,#ff1744 120deg 130deg,#000 130deg 140deg,#ff1744 140deg 150deg,#000 150deg 160deg,#ff1744 160deg 170deg,#000 170deg 180deg,#ff1744 180deg 190deg,#000 190deg 200deg,#ff1744 200deg 210deg,#000 210deg 220deg,#ff1744 220deg 230deg,#000 230deg 240deg,#ff1744 240deg 250deg,#000 250deg 260deg,#ff1744 260deg 270deg,#000 270deg 280deg,#ff1744 280deg 290deg,#000 290deg 300deg,#ff1744 300deg 310deg,#000 310deg 320deg,#ff1744 320deg 330deg,#000 330deg 340deg,#ff1744 340deg 350deg,#000 350deg 360deg);border:6px solid #ffd700;box-shadow:0 0 40px rgba(255,215,0,.3);position:relative;transition:transform 3s cubic-bezier(.2,.8,.3,1)}
.roulette-center{position:absolute;inset:0;display:flex;align-items:center;justify-content:center}
.roulette-center-btn{width:50px;height:50px;background:#ffd700;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:1.5rem;z-index:2}
.roulette-result{text-align:center;font-size:1.2rem;font-weight:900;margin:10px 0;min-height:30px}
.roulette-pointer{position:absolute;top:-15px;left:50%;transform:translateX(-50%);font-size:2rem;z-index:5}

/* CHOICE BUTTONS */
.choice-row{display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px;margin:10px 0}
.choice-row.two{grid-template-columns:1fr 1fr}
.choice-btn{padding:14px;border-radius:12px;font-weight:800;cursor:pointer;font-family:inherit;transition:all .2s;border:2px solid transparent;font-size:.85rem}
.choice-btn:active{transform:scale(.95)}
.choice-btn.selected{border-color:#ffd700;box-shadow:0 0 20px rgba(255,215,0,.5)}
.choice-red{background:linear-gradient(135deg,#e53935,#b71c1c);color:#fff}
.choice-black{background:linear-gradient(135deg,#000,#222);color:#fff;border-color:#666}
.choice-green{background:linear-gradient(135deg,#00ff88,#00aa55);color:#07060f}
.choice-neutral{background:#181528;color:#fff;border-color:rgba(255,215,0,.3)}
.choice-neutral.selected{background:linear-gradient(135deg,#ffd700,#ff8c00);color:#07060f}

/* BLACKJACK */
.bj-table{background:linear-gradient(180deg,#0a4d2a,#062b18);border-radius:20px;padding:20px;margin:14px;border:2px solid rgba(255,215,0,.3);min-height:400px;display:flex;flex-direction:column}
.bj-section-title{font-size:.75rem;color:#aaffcc;text-transform:uppercase;letter-spacing:2px;margin-bottom:8px;font-weight:700}
.bj-cards{display:flex;gap:6px;flex-wrap:wrap;min-height:90px;margin-bottom:10px}
.bj-card{width:56px;height:80px;background:#fff;border-radius:8px;display:flex;flex-direction:column;align-items:center;justify-content:center;font-weight:900;color:#000;font-size:1rem;box-shadow:0 3px 10px rgba(0,0,0,.3);animation:cardIn .3s;padding:4px}
@keyframes cardIn{from{transform:translateY(-30px) rotate(-10deg);opacity:0}to{transform:translateY(0) rotate(0);opacity:1}}
.bj-card.red{color:#e53935}
.bj-card .suit{font-size:1.5rem;line-height:1}
.bj-card.back{background:linear-gradient(135deg,#2a1f3d,#181528);color:#ffd700}
.bj-score{font-size:1.1rem;font-weight:900;color:#ffd700;margin-bottom:15px}
.bj-actions{display:flex;gap:8px;margin-top:auto}
.bj-actions .btn{flex:1;padding:14px}

/* DICE */
.dice-wrap{padding:20px;text-align:center}
.dice-display{display:flex;justify-content:center;gap:20px;margin:20px 0}
.dice{width:90px;height:90px;background:linear-gradient(135deg,#fff,#ddd);border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:3.5rem;box-shadow:0 8px 25px rgba(0,0,0,.4);transition:transform .3s}
.dice.rolling{animation:roll .15s infinite}
@keyframes roll{0%{transform:rotate(-15deg) translateY(-5px)}50%{transform:rotate(0) translateY(5px)}100%{transform:rotate(15deg) translateY(-5px)}}

/* POKER */
.poker-table{background:linear-gradient(180deg,#0a4d2a,#062b18);border-radius:20px;padding:18px;margin:14px;border:2px solid rgba(255,215,0,.3);min-height:420px;display:flex;flex-direction:column}
.poker-hand{display:flex;gap:6px;justify-content:center;min-height:90px;margin:12px 0;flex-wrap:wrap}
.poker-card{width:60px;height:86px;background:#fff;border-radius:8px;display:flex;flex-direction:column;align-items:center;justify-content:center;font-weight:900;color:#000;font-size:1.05rem;box-shadow:0 3px 10px rgba(0,0,0,.3);padding:4px;animation:cardIn .3s}
.poker-card.red{color:#e53935}
.poker-card .suit{font-size:1.6rem;line-height:1}
.poker-card.held{border:3px solid #ffd700;box-shadow:0 0 15px rgba(255,215,0,.6)}
.poker-info{text-align:center;color:#aaffcc;font-size:.8rem;font-weight:700;margin:5px 0}
.poker-result{text-align:center;font-size:1.1rem;font-weight:900;color:#ffd700;margin:12px 0;min-height:28px}

/* FORTUNE WHEEL */
.fortune-wrap{padding:20px;text-align:center}
.fortune-wheel{width:280px;height:280px;margin:15px auto;border-radius:50%;position:relative;transition:transform 4s cubic-bezier(.17,.67,.35,1);box-shadow:0 0 50px rgba(255,215,0,.4)}
.fortune-segment{position:absolute;width:50%;height:50%;left:50%;top:0;transform-origin:0% 100%;display:flex;align-items:flex-start;justify-content:center;padding-top:10px;font-weight:900;font-size:.75rem;color:#fff;text-shadow:1px 1px 3px #000}
.fortune-center{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);width:60px;height:60px;background:linear-gradient(135deg,#ffd700,#ff8c00);border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:1.8rem;z-index:5;box-shadow:0 0 20px rgba(255,215,0,.7)}
.fortune-pointer{position:absolute;top:-25px;left:50%;transform:translateX(-50%);font-size:2.5rem;z-index:10;filter:drop-shadow(0 0 5px #ffd700)}

/* TOURNAMENT */
.tourn-wrap{padding:14px}
.tourn-header{background:linear-gradient(135deg,#2a1233,#0f0d1e);border-radius:16px;padding:18px;margin-bottom:14px;text-align:center;border:2px solid rgba(255,215,0,.3)}
.tourn-title{font-size:1.1rem;font-weight:900;color:#ffd700}
.tourn-sub{font-size:.78rem;color:#889;margin-top:4px}
.tourn-player{background:#181528;border-radius:14px;padding:12px;margin-bottom:8px;display:flex;align-items:center;gap:10px;border:1px solid rgba(255,255,255,.06)}
.tourn-player.me{border-color:rgba(255,215,0,.5);background:linear-gradient(135deg,#181528,#2a1f3d)}
.tourn-avatar{width:40px;height:40px;border-radius:50%;background:linear-gradient(135deg,#c792ea,#7ec8ff);display:flex;align-items:center;justify-content:center;font-weight:900;color:#07060f;font-size:1rem;flex-shrink:0}
.tourn-player.me .tourn-avatar{background:linear-gradient(135deg,#ffd700,#ff8c00)}
.tourn-info{flex:1}
.tourn-name{font-weight:700;font-size:.9rem}
.tourn-score{color:#ffd700;font-weight:800;font-size:.85rem}
.tourn-place{font-size:1.2rem;font-weight:900;color:#889;width:30px;text-align:center}

/* ACH */
.ach-item{background:#181528;border:1px solid rgba(255,255,255,.06);border-radius:14px;margin:10px 14px;padding:14px;display:flex;gap:12px;align-items:center;transition:all .3s}
.ach-item.done{border-color:rgba(0,255,136,.3);background:linear-gradient(135deg,#181528,#0f2520)}
.ach-icon{font-size:2rem;flex-shrink:0;filter:grayscale(1);opacity:.4}
.ach-item.done .ach-icon{filter:none;opacity:1}
.ach-info{flex:1;min-width:0}
.ach-name{font-weight:700;font-size:.9rem;margin-bottom:2px}
.ach-desc{font-size:.72rem;color:#778}
.ach-progress{margin-top:6px;height:5px;background:rgba(255,255,255,.06);border-radius:3px;overflow:hidden}
.ach-progress-fill{height:100%;background:linear-gradient(90deg,#ffd700,#00ff88);border-radius:3px;transition:width .4s}
.ach-reward{font-size:.72rem;color:#ffd700;font-weight:700;margin-top:4px}
.ach-done-badge{color:#00ff88;font-size:.72rem;font-weight:700}

/* PROFILE */
.profile-top{background:linear-gradient(135deg,#2a1233,#07060f);padding:25px 20px;text-align:center;border-bottom:1px solid rgba(255,255,255,.05)}
.profile-avatar{width:80px;height:80px;background:linear-gradient(135deg,#ffd700,#ff8c00);border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:2.2rem;font-weight:900;color:#07060f;margin:0 auto 10px;box-shadow:0 0 30px rgba(255,215,0,.5)}
.profile-name{font-size:1.4rem;font-weight:800}
.profile-level{color:#ffd700;font-size:.85rem;margin-top:3px;font-weight:600}
.profile-stats{display:grid;grid-template-columns:1fr 1fr;gap:10px;padding:14px}
.stat-card{background:#181528;border:1px solid rgba(255,255,255,.06);border-radius:14px;padding:16px;text-align:center}
.stat-icon{font-size:1.6rem;margin-bottom:5px}
.stat-value{font-size:1.3rem;font-weight:800;color:#ffd700}
.stat-label{font-size:.7rem;color:#667;margin-top:2px}
.settings-btn{margin:0 14px 10px;padding:15px;background:#181528;border:1px solid rgba(255,255,255,.06);border-radius:14px;color:#fff;font-weight:700;cursor:pointer;font-family:inherit;font-size:.9rem;width:calc(100% - 28px);text-align:left;transition:all .2s}
.settings-btn:active{transform:scale(.98)}
.settings-btn.danger{color:#ff5566;border-color:rgba(255,85,102,.2)}

/* BANNERS */
.daily-banner{margin:14px;padding:18px;border-radius:16px;background:linear-gradient(135deg,#ffd700,#ff8c00);text-align:center;cursor:pointer;position:relative;overflow:hidden;box-shadow:0 6px 25px rgba(255,215,0,.4)}
.daily-banner:active{transform:scale(.98)}
.daily-title{font-weight:900;font-size:1.05rem;color:#07060f;position:relative;z-index:2}
.daily-desc{font-size:.78rem;color:rgba(0,0,0,.7);margin-top:3px;position:relative;z-index:2}
.rescue-banner{margin:14px;padding:16px;border-radius:16px;background:linear-gradient(135deg,#c792ea,#9b6bdd);text-align:center;cursor:pointer;box-shadow:0 6px 25px rgba(199,146,234,.4)}
.rescue-banner:active{transform:scale(.98)}
.rescue-title{font-weight:900;font-size:1rem;color:#fff}
.rescue-desc{font-size:.75rem;color:rgba(255,255,255,.8);margin-top:3px}

/* MODAL */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.85);display:flex;align-items:center;justify-content:center;z-index:200;padding:20px;animation:fadeIn .2s}
@keyframes fadeIn{from{opacity:0}to{opacity:1}}
.modal{background:#181528;border:1px solid rgba(255,215,0,.25);border-radius:18px;padding:22px;width:100%;max-width:360px;animation:modalIn .3s;max-height:85vh;overflow-y:auto}
@keyframes modalIn{from{transform:scale(.9);opacity:0}to{transform:scale(1);opacity:1}}
.modal h3{margin-bottom:8px;font-size:1.15rem}
.modal p{color:#889;font-size:.82rem;margin-bottom:15px;line-height:1.4}

/* BUTTONS */
.btn{padding:12px 20px;border:none;border-radius:12px;font-weight:700;font-size:.9rem;cursor:pointer;transition:all .2s;font-family:inherit}
.btn:active{transform:scale(.97)}
.btn-primary{background:linear-gradient(135deg,#ffd700,#ff8c00);color:#07060f}
.btn-ghost{background:transparent;color:#889;border:1px solid rgba(255,255,255,.1)}
.btn-success{background:linear-gradient(135deg,#00ff88,#00cc6a);color:#07060f}
.btn-full{width:100%}
.btn:disabled{opacity:.5;cursor:not-allowed}

/* TOAST */
.toast{position:fixed;top:80px;left:50%;transform:translateX(-50%);background:#181528;border:1px solid rgba(255,215,0,.4);color:#fff;padding:12px 22px;border-radius:12px;font-weight:600;z-index:999;animation:toastIn .3s ease,toastOut .3s ease 2.2s forwards;font-size:.88rem;max-width:90%;text-align:center;box-shadow:0 8px 30px rgba(0,0,0,.5)}
.toast.success{border-color:rgba(0,255,136,.5);color:#00ff88}
.toast.error{border-color:rgba(255,85,102,.5);color:#ff5566}
.toast.win{border-color:rgba(255,215,0,.7);color:#ffd700;box-shadow:0 0 30px rgba(255,215,0,.5)}
@keyframes toastIn{from{opacity:0;transform:translateX(-50%) translateY(-20px)}to{opacity:1;transform:translateX(-50%) translateY(0)}}
@keyframes toastOut{to{opacity:0;transform:translateX(-50%) translateY(-20px)}}
::-webkit-scrollbar{width:0}
</style>
</head>
<body>
<div id="app"></div>

<script>
/* ========== STATE ========== */
let state={currentUser:null,users:{}};
let currentScreen='home';
let activeTimers=[];

function loadState(){
try{const s=localStorage.getItem('spaceCasino_v2');if(s)state=JSON.parse(s)}catch(e){}
if(!state.users)state.users={};
}
function saveState(){try{localStorage.setItem('spaceCasino_v2',JSON.stringify(state))}catch(e){}}
function genId(){return Date.now().toString(36)+Math.random().toString(36).substr(2,5)}
function clearTimers(){activeTimers.forEach(t=>clearTimeout(t));activeTimers=[]}
function setT(fn,ms){const t=setTimeout(fn,ms);activeTimers.push(t);return t}

function createUser(name,pass){
return{
name,pass,
coins:1000,level:1,xp:0,xpNext:200,
stats:{spins:0,wins:0,biggestWin:0,totalWon:0,totalLost:0,blackjacks:0,tournWins:0,pokerWins:0},
achievements:[],lastDaily:0,dailyStreak:0,lastRescue:0,created:Date.now()
};
}

const ACHIEVEMENTS=[
{id:'a1',name:'Первый спин',desc:'Сделать первую ставку',icon:'🎰',target:1,reward:100,stat:'spins'},
{id:'a2',name:'Азартный',desc:'Сделать 50 ставок',icon:'🎲',target:50,reward:500,stat:'spins'},
{id:'a3',name:'Игрок',desc:'Сделать 200 ставок',icon:'🃏',target:200,reward:2000,stat:'spins'},
{id:'a4',name:'Первая победа',desc:'Выиграть 1 раз',icon:'🏆',target:1,reward:100,stat:'wins'},
{id:'a5',name:'Счастливчик',desc:'Выиграть 25 раз',icon:'🍀',target:25,reward:800,stat:'wins'},
{id:'a6',name:'Любимец фортуны',desc:'Выиграть 100 раз',icon:'⭐',target:100,reward:3000,stat:'wins'},
{id:'a7',name:'Крупный куш',desc:'Выиграть 5 000 ₡ за раз',icon:'💰',target:5000,reward:1000,stat:'biggestWin'},
{id:'a8',name:'Джекпот',desc:'Выиграть 25 000 ₡ за раз',icon:'💎',target:25000,reward:5000,stat:'biggestWin'},
{id:'a9',name:'Легендарный куш',desc:'Выиграть 100 000 ₡ за раз',icon:'👑',target:100000,reward:25000,stat:'biggestWin'},
{id:'a10',name:'Миллионер',desc:'Выиграть всего 1 000 000 ₡',icon:'🤑',target:1000000,reward:50000,stat:'totalWon'},
{id:'a11',name:'Блэкджек!',desc:'5 блэкджеков',icon:'🃏',target:5,reward:1500,stat:'blackjacks'},
{id:'a12',name:'Мастер блэкджека',desc:'25 блэкджеков',icon:'🎩',target:25,reward:8000,stat:'blackjacks'},
{id:'a13',name:'Покерист',desc:'Выиграть 10 раз в покер',icon:'♠️',target:10,reward:3000,stat:'pokerWins'},
{id:'a14',name:'Чемпион',desc:'Победить в 3 турнирах',icon:'🏅',target:3,reward:5000,stat:'tournWins'},
{id:'a15',name:'Уровень 10',desc:'Достичь 10 уровня',icon:'🔥',target:10,reward:5000,stat:'level'},
{id:'a16',name:'Уровень 20',desc:'Достичь 20 уровня',icon:'🌌',target:20,reward:25000,stat:'level'},
];

const app=document.getElementById('app');

/* ========== RENDER ========== */
function render(){
clearTimers();
if(!state.currentUser||!state.users[state.currentUser]){renderAuth();return}
const user=state.users[state.currentUser];
renderMain(user);
}

/* ========== AUTH ========== */
function renderAuth(){
app.innerHTML=`
<div class="auth-screen">
<div class="auth-logo">🎰</div>
<div class="auth-title">Космическое Казино</div>
<div class="auth-subtitle">Испытай удачу в бескрайней галактике</div>
<div class="auth-form">
<div class="input-group" id="ng">
<label class="input-label">Имя</label>
<input class="auth-input" id="an" placeholder="Ваше имя" maxlength="15" autocomplete="off">
</div>
<div class="input-group" id="pg">
<label class="input-label">Пароль</label>
<input class="auth-input" id="ap" placeholder="Пароль" type="password" maxlength="20" autocomplete="off">
<div class="pass-meter" id="pm"><div class="pass-bar"></div><div class="pass-bar"></div><div class="pass-bar"></div></div>
<div class="pass-hint" id="ph">Минимум 4 символа</div>
</div>
<button class="auth-btn primary" id="submit">Войти</button>
<button class="auth-btn secondary" id="toggle">Регистрация</button>
<div class="auth-switch" id="switchText">Нет аккаунта? <span id="switchLink">Зарегистрироваться</span></div>
</div>
</div>
<div class="success-overlay" id="successOverlay"><div class="success-circle">✓</div></div>
`;

let mode='login';
const an=document.getElementById('an');
const ap=document.getElementById('ap');

[['an','ng'],['ap','pg']].forEach(([id,gid])=>{
const inp=document.getElementById(id);const g=document.getElementById(gid);
inp.addEventListener('focus',()=>g.classList.add('focused'));
inp.addEventListener('blur',()=>{
g.classList.remove('focused');
if(inp.value)g.classList.add('filled');else g.classList.remove('filled');
});
inp.addEventListener('input',()=>{
if(inp.value)g.classList.add('filled');else g.classList.remove('filled');
});
});

ap.addEventListener('input',()=>{
const v=ap.value;
const bars=document.querySelectorAll('.pass-bar');
const hint=document.getElementById('ph');
bars.forEach(b=>b.className='pass-bar');
if(v.length>=4){
bars[0].classList.add('on');
if(v.length>=6)bars[1].classList.add('on');
if(v.length>=8)bars[2].classList.add('strong');
hint.textContent='Пароль надежный ✓';
hint.className='pass-hint ok';
}else{
hint.textContent='Минимум 4 символа';
hint.className='pass-hint';
}
});

document.getElementById('submit').onclick=()=>handleAuth(mode);
document.getElementById('toggle').onclick=()=>switchMode(mode==='login'?'register':'login');
document.getElementById('switchLink').onclick=()=>switchMode(mode==='login'?'register':'login');

function switchMode(m){
mode=m;
const btn=document.getElementById('submit');
const txt=document.getElementById('switchText');
const tog=document.getElementById('toggle');
if(m==='login'){
btn.textContent='Войти';
tog.textContent='Регистрация';
txt.innerHTML='Нет аккаунта? <span id="switchLink">Зарегистрироваться</span>';
}else{
btn.textContent='Создать аккаунт';
tog.textContent='Войти';
txt.innerHTML='Уже есть аккаунт? <span id="switchLink">Войти</span>';
}
document.getElementById('switchLink').onclick=()=>switchMode(m==='login'?'register':'login');
}

async function handleAuth(m){
const name=an.value.trim();
const pass=ap.value.trim();
if(!name||!pass){showToast('Заполните все поля','error');return}
if(pass.length<4){showToast('Пароль минимум 4 символа','error');return}
const btn=document.getElementById('submit');
btn.disabled=true;
btn.textContent='Проверка...';
await sleep(700);
if(m==='login'){
if(state.users[name]&&state.users[name].pass===pass){
state.currentUser=name;saveState();showSuccess();
}else{
btn.disabled=false;btn.textContent='Войти';
showToast('Неверное имя или пароль','error');
}
}else{
if(state.users[name]){
btn.disabled=false;btn.textContent='Создать аккаунт';
showToast('Пользователь уже существует','error');return;
}
state.users[name]=createUser(name,pass);
state.currentUser=name;saveState();showSuccess();
}
}

function showSuccess(){
const ov=document.getElementById('successOverlay');
ov.classList.add('show');
setT(()=>{render()},1300);
}
function sleep(ms){return new Promise(r=>setTimeout(r,ms))}
}

/* ========== MAIN ========== */
function renderMain(user){
app.innerHTML=`
<div class="header">
<div class="header-title">🎰 Казино</div>
<div class="header-coins" id="coinsHeader">${formatNum(user.coins)} ₡</div>
</div>
<div class="screen active" id="screen-home"></div>
<div class="screen" id="screen-slots"></div>
<div class="screen" id="screen-roulette"></div>
<div class="screen" id="screen-blackjack"></div>
<div class="screen" id="screen-dice"></div>
<div class="screen" id="screen-poker"></div>
<div class="screen" id="screen-fortune"></div>
<div class="screen" id="screen-tourn"></div>
<div class="screen" id="screen-ach"></div>
<div class="screen" id="screen-profile"></div>
<div class="bottom-nav">
<div class="nav-item active" data-screen="home"><span class="nav-icon">🎲</span><div class="nav-label">Игры</div></div>
<div class="nav-item" data-screen="tourn"><span class="nav-icon">🏅</span><div class="nav-label">Турниры</div></div>
<div class="nav-item" data-screen="ach"><span class="nav-icon">🏆</span><div class="nav-label">Награды</div></div>
<div class="nav-item" data-screen="profile"><span class="nav-icon">👤</span><div class="nav-label">Профиль</div></div>
</div>
`;
document.querySelectorAll('.nav-item[data-screen]').forEach(it=>{
it.onclick=()=>goTo(it.dataset.screen,user);
});
renderScreen(user);
}

function goTo(screen,user){
if(!user)user=state.users[state.currentUser];
clearTimers();
currentScreen=screen;
document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));
const nav=document.querySelector(`[data-screen="${screen}"]`);
if(nav)nav.classList.add('active');
else{
const h=document.querySelector('[data-screen="home"]');
if(h)h.classList.add('active');
}
document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
const el=document.getElementById('screen-'+screen);
if(el)el.classList.add('active');
renderScreen(user);
}

function renderScreen(user){
const el=document.getElementById('screen-'+currentScreen);
if(!el)return;
try{
if(currentScreen==='home')renderHome(el,user);
else if(currentScreen==='slots')renderSlots(el,user);
else if(currentScreen==='roulette')renderRoulette(el,user);
else if(currentScreen==='blackjack')renderBlackjack(el,user);
else if(currentScreen==='dice')renderDice(el,user);
else if(currentScreen==='poker')renderPoker(el,user);
else if(currentScreen==='fortune')renderFortune(el,user);
else if(currentScreen==='tourn')renderTourn(el,user);
else if(currentScreen==='ach')renderAch(el,user);
else if(currentScreen==='profile')renderProfile(el,user);
else goTo('home',user);
}catch(e){console.error(e);el.innerHTML='<div style="padding:30px;text-align:center;color:#889">Ошибка. Вернитесь назад.</div>';}
updateCoins(user);
}

function updateCoins(user){
const c=document.getElementById('coinsHeader');
if(c)c.textContent=formatNum(user.coins)+' ₡';
}

/* ========== HOME ========== */
function renderHome(el,user){
const canDaily=Date.now()-user.lastDaily>24*60*60*1000;
const canRescue=user.coins<100&&Date.now()-user.lastRescue>10*60*1000;
el.innerHTML=`
<div class="stat-bar">
<div class="stat-pill"><div class="v">${user.level}</div><div class="l">Уровень</div></div>
<div class="stat-pill"><div class="v">${user.stats.wins}</div><div class="l">Побед</div></div>
<div class="stat-pill"><div class="v">${formatNum(user.stats.biggestWin)}</div><div class="l">Макс.выигрыш</div></div>
</div>
${canDaily?`<div class="daily-banner" id="dailyBtn"><div class="daily-title">🎁 Ежедневный бонус!</div><div class="daily-desc">+${formatNum(500+user.level*100)} ₡ · Стрик: ${user.dailyStreak} дн.</div></div>`:''}
${canRescue?`<div class="rescue-banner" id="rescueBtn"><div class="rescue-title">💜 Спасение!</div><div class="rescue-desc">Бонус 300 ₡ (раз в 10 мин)</div></div>`:''}
<div style="padding:14px 14px 0"><div style="font-size:1.05rem;font-weight:800;color:#ffd700">Игры</div><div style="font-size:.78rem;color:#778;margin-top:2px">Выбери свою удачу</div></div>
<div class="game-grid">
<div class="game-card" data-go="slots"><span class="game-card-icon">🎰</span><div class="game-card-name">Слоты</div><div class="game-card-desc">3 барабана</div></div>
<div class="game-card" data-go="roulette"><span class="game-card-icon">🎡</span><div class="game-card-name">Рулетка</div><div class="game-card-desc">Цвет / число</div></div>
<div class="game-card" data-go="blackjack"><span class="game-card-icon">🃏</span><div class="game-card-name">Блэкджек</div><div class="game-card-desc">Против дилера</div></div>
<div class="game-card" data-go="dice"><span class="game-card-icon">🎲</span><div class="game-card-name">Кости</div><div class="game-card-desc">Больше/меньше</div></div>
<div class="game-card" data-go="poker"><span class="game-card-icon">♠️</span><div class="game-card-name">Покер</div><div class="game-card-desc">5 карт, обмен</div></div>
<div class="game-card" data-go="fortune"><span class="game-card-icon">🎡</span><div class="game-card-name">Фортуна</div><div class="game-card-desc">Колесо призов</div></div>
</div>
`;
el.querySelectorAll('[data-go]').forEach(c=>{
c.onclick=()=>goTo(c.dataset.go,user);
});
const d=document.getElementById('dailyBtn');
if(d)d.onclick=()=>{
const bonus=500+user.level*100;
user.coins+=bonus;
const now=Date.now();
if(now-user.lastDaily<48*60*60*1000)user.dailyStreak++;
else user.dailyStreak=1;
user.lastDaily=now;
addXP(user,50);
saveState();
showToast('🎁 +'+formatNum(bonus)+' ₡ · Стрик '+user.dailyStreak+' дн.','success');
renderHome(el,user);
updateCoins(user);
};
const r=document.getElementById('rescueBtn');
if(r)r.onclick=()=>{
user.coins+=300;
user.lastRescue=Date.now();
saveState();
showToast('💜 Спасение! +300 ₡','success');
renderHome(el,user);
updateCoins(user);
};
}

/* ========== SLOTS ========== */
const SLOT_SYMBOLS=[
{icon:'🍒',name:'Вишня',multi:1},
{icon:'🍋',name:'Лимон',multi:2},
{icon:'🍇',name:'Виноград',multi:3},
{icon:'⭐',name:'Звезда',multi:5},
{icon:'💎',name:'Алмаз',multi:10},
{icon:'7️⃣',name:'Семёрка',multi:20},
];
const SLOT_WEIGHTS=[30,25,18,12,8,2];
let slotState={bet:50,spinning:false,reels:['🍒','🍒','🍒']};

function renderSlots(el,user){
el.innerHTML=`
<div class="slots-wrap">
<div class="slots-machine">
<div style="font-size:1.1rem;font-weight:900;color:#ffd700;margin-bottom:5px">🎰 Слоты</div>
<div class="slots-reels">
<div class="reel" id="r0">${slotState.reels[0]}</div>
<div class="reel" id="r1">${slotState.reels[1]}</div>
<div class="reel" id="r2">${slotState.reels[2]}</div>
</div>
<div class="slots-payout">
🍒×3 = <b>x1</b> · 🍋×3 = <b>x2</b> · 🍇×3 = <b>x3</b><br>
⭐×3 = <b>x5</b> · 💎×3 = <b>x10</b> · 7️⃣×3 = <b>x20</b>
</div>
</div>
<div class="bet-panel">
<div class="bet-panel-title">Ставка</div>
<div class="bet-chips">
${[10,50,100,500,1000].map(b=>`<button class="chip ${slotState.bet===b?'selected':''}" data-bet="${b}">${b>=1000?'1K':b}</button>`).join('')}
</div>
</div>
<button class="spin-btn" id="spinBtn">КРУТИТЬ (${slotState.bet} ₡)</button>
<div style="text-align:center;margin-top:15px"><button class="btn btn-ghost" id="backBtn">← Назад</button></div>
</div>
`;
el.querySelectorAll('[data-bet]').forEach(b=>{
b.onclick=()=>{
if(slotState.spinning)return;
slotState.bet=parseInt(b.dataset.bet);
renderSlots(el,user);
};
});
document.getElementById('backBtn').onclick=()=>goTo('home',user);
document.getElementById('spinBtn').onclick=()=>spinSlots(user,el);
}

function pickSlot(){
const total=SLOT_WEIGHTS.reduce((a,b)=>a+b,0);
let r=Math.random()*total;
for(let i=0;i<SLOT_SYMBOLS.length;i++){
r-=SLOT_WEIGHTS[i];
if(r<=0)return SLOT_SYMBOLS[i];
}
return SLOT_SYMBOLS[0];
}

async function spinSlots(user,el){
if(slotState.spinning)return;
if(user.coins<slotState.bet){showToast('Недостаточно средств','error');return}
slotState.spinning=true;
user.coins-=slotState.bet;
user.stats.spins++;
user.stats.totalLost+=slotState.bet;
updateCoins(user);
addXP(user,Math.max(1,Math.floor(slotState.bet/20)));
const btn=document.getElementById('spinBtn');
if(btn){btn.disabled=true;btn.textContent='КРУТИМ...';}
const reels=[document.getElementById('r0'),document.getElementById('r1'),document.getElementById('r2')];
reels.forEach(r=>{if(r)r.classList.add('spin')});
for(let i=0;i<15;i++){
await sleep(80);
reels.forEach(r=>{if(r)r.textContent=SLOT_SYMBOLS[Math.floor(Math.random()*SLOT_SYMBOLS.length)].icon});
}
const result=[pickSlot(),pickSlot(),pickSlot()];
for(let i=0;i<3;i++){
setT(()=>{
const r=document.getElementById('r'+i);
if(r){r.classList.remove('spin');r.textContent=result[i].icon;}
},i*150);
}
await sleep(700);
reels.forEach(r=>{if(r)r.classList.remove('spin')});
slotState.reels=result.map(r=>r.icon);
let win=0,winType='';
if(result[0].icon===result[1].icon&&result[1].icon===result[2].icon){
win=slotState.bet*result[0].multi;
winType=result[0].name+' × '+result[0].multi;
}else if(result[0].icon===result[1].icon||result[1].icon===result[2].icon){
win=slotState.bet*1;
winType='Пара';
}
if(win>0){
user.coins+=win;
user.stats.wins++;
user.stats.totalWon+=win;
if(win>user.stats.biggestWin)user.stats.biggestWin=win;
reels.forEach(r=>{if(r)r.classList.add('win')});
setT(()=>reels.forEach(r=>{if(r)r.classList.remove('win')}),2000);
if(win>=slotState.bet*10)showToast('🎉 ДЖЕКПОТ! '+winType+' · +'+formatNum(win)+' ₡','win');
else showToast('✅ '+winType+' · +'+formatNum(win)+' ₡','success');
}else{
showToast('😢 Не повезло · -'+formatNum(slotState.bet)+' ₡','error');
}
slotState.spinning=false;
saveState();
checkAchievements(user);
updateCoins(user);
renderSlots(el,user);
}

/* ========== ROULETTE ========== */
const RED_NUMBERS=[1,3,5,7,9,12,14,16,18,19,21,23,25,27,30,32,34,36];
let rouletteState={bet:50,choice:null,spinning:false};

function renderRoulette(el,user){
el.innerHTML=`
<div style="padding:20px;text-align:center">
<div style="font-size:1.1rem;font-weight:900;color:#ffd700;margin-bottom:5px">🎡 Рулетка</div>
<div style="font-size:.78rem;color:#778;margin-bottom:10px">Ставь на цвет или число</div>
<div style="position:relative;display:inline-block">
<div class="roulette-pointer">▼</div>
<div class="roulette-wheel" id="wheel"><div class="roulette-center"><div class="roulette-center-btn">🎯</div></div></div>
</div>
<div class="roulette-result" id="rouletteResult">Выбери ставку</div>
<div class="bet-panel">
<div class="bet-panel-title">Сумма</div>
<div class="bet-chips">
${[10,50,100,500].map(b=>`<button class="chip ${rouletteState.bet===b?'selected':''}" data-bet="${b}">${b}</button>`).join('')}
</div>
</div>
<div class="choice-row">
<button class="choice-btn choice-red ${rouletteState.choice==='red'?'selected':''}" data-choice="red">🔴 Красное x2</button>
<button class="choice-btn choice-black ${rouletteState.choice==='black'?'selected':''}" data-choice="black">⚫ Чёрное x2</button>
<button class="choice-btn choice-green ${rouletteState.choice==='green'?'selected':''}" data-choice="green">🟢 Зеро x14</button>
</div>
<button class="spin-btn" id="spinBtn" ${!rouletteState.choice?'disabled':''}>КРУТИТЬ</button>
<div style="margin-top:15px"><button class="btn btn-ghost" id="backBtn">← Назад</button></div>
</div>
`;
el.querySelectorAll('[data-bet]').forEach(b=>{
b.onclick=()=>{
if(rouletteState.spinning)return;
rouletteState.bet=parseInt(b.dataset.bet);
renderRoulette(el,user);
};
});
el.querySelectorAll('[data-choice]').forEach(c=>{
c.onclick=()=>{
if(rouletteState.spinning)return;
rouletteState.choice=c.dataset.choice;
renderRoulette(el,user);
};
});
document.getElementById('backBtn').onclick=()=>goTo('home',user);
document.getElementById('spinBtn').onclick=()=>spinRoulette(user,el);
}

async function spinRoulette(user,el){
if(rouletteState.spinning||!rouletteState.choice)return;
if(user.coins<rouletteState.bet){showToast('Недостаточно средств','error');return}
rouletteState.spinning=true;
user.coins-=rouletteState.bet;
user.stats.spins++;
user.stats.totalLost+=rouletteState.bet;
updateCoins(user);
addXP(user,Math.max(1,Math.floor(rouletteState.bet/20)));
const wheel=document.getElementById('wheel');
const res=document.getElementById('rouletteResult');
const spins=5+Math.random()*5;
if(wheel)wheel.style.transform=`rotate(${spins*360}deg)`;
await sleep(3100);
const rnd=Math.random();
let num,color;
if(rnd<1/37){num=0;color='green';}
else{num=1+Math.floor(Math.random()*36);color=RED_NUMBERS.includes(num)?'red':'black';}
if(res)res.textContent=`Выпало: ${num} ${color==='red'?'🔴':color==='black'?'⚫':'🟢'}`;
if(wheel)wheel.style.transform=`rotate(0deg)`;
await sleep(200);
let win=0;
if(rouletteState.choice===color){
win=rouletteState.bet*(color==='green'?14:2);
}
if(win>0){
user.coins+=win;
user.stats.wins++;
user.stats.totalWon+=win;
if(win>user.stats.biggestWin)user.stats.biggestWin=win;
showToast('🎉 Выигрыш! +'+formatNum(win)+' ₡','win');
}else{
showToast('😢 Мимо · -'+formatNum(rouletteState.bet)+' ₡','error');
}
rouletteState.spinning=false;
saveState();
checkAchievements(user);
updateCoins(user);
renderRoulette(el,user);
}

/* ========== BLACKJACK ========== */
const SUITS=['♠','♥','♦','♣'];
const RANKS=['2','3','4','5','6','7','8','9','10','J','Q','K','A'];
let bjState={bet:50,player:[],dealer:[],phase:'bet',message:''};

function newCard(){
const suit=SUITS[Math.floor(Math.random()*4)];
const rank=RANKS[Math.floor(Math.random()*13)];
return{suit,rank,red:suit==='♥'||suit==='♦'};
}
function cardValue(c){
if(c.rank==='A')return 11;
if(['J','Q','K'].includes(c.rank))return 10;
return parseInt(c.rank);
}
function handValue(hand){
let sum=0,aces=0;
hand.forEach(c=>{sum+=cardValue(c);if(c.rank==='A')aces++;});
while(sum>21&&aces>0){sum-=10;aces--;}
return sum;
}
function cardHTML(c,back){
if(back)return `<div class="bj-card back">🂠</div>`;
return `<div class="bj-card ${c.red?'red':''}"><div>${c.rank}</div><div class="suit">${c.suit}</div></div>`;
}

function renderBlackjack(el,user){
if(bjState.phase==='bet'){
el.innerHTML=`
<div style="padding:14px">
<div style="font-size:1.1rem;font-weight:900;color:#ffd700;margin-bottom:5px;text-align:center">🃏 Блэкджек</div>
<div style="font-size:.78rem;color:#778;margin-bottom:15px;text-align:center">Набери 21 или ближе к нему, чем дилер</div>
<div class="bet-panel">
<div class="bet-panel-title">Ставка</div>
<div class="bet-chips">
${[10,50,100,500].map(b=>`<button class="chip ${bjState.bet===b?'selected':''}" data-bet="${b}">${b}</button>`).join('')}
</div>
</div>
<button class="spin-btn" id="startBtn">НАЧАТЬ ИГРУ</button>
<div style="margin-top:15px"><button class="btn btn-ghost btn-full" id="backBtn">← Назад</button></div>
</div>
`;
el.querySelectorAll('[data-bet]').forEach(b=>{
b.onclick=()=>{bjState.bet=parseInt(b.dataset.bet);renderBlackjack(el,user)};
});
document.getElementById('backBtn').onclick=()=>goTo('home',user);
document.getElementById('startBtn').onclick=()=>startBlackjack(user,el);
return;
}
const pv=handValue(bjState.player);
const dv=handValue(bjState.dealer);
el.innerHTML=`
<div class="bj-table">
<div class="bj-section-title">🤵 Дилер</div>
<div class="bj-cards">
${bjState.dealer.map((c,i)=>i===1&&bjState.phase==='playing'?cardHTML(c,true):cardHTML(c)).join('')}
</div>
<div class="bj-score">${bjState.phase==='playing'?'?':dv}</div>
<div class="bj-section-title" style="margin-top:10px">🙋 Вы</div>
<div class="bj-cards">${bjState.player.map(c=>cardHTML(c)).join('')}</div>
<div class="bj-score">${pv}</div>
${bjState.message?`<div style="text-align:center;font-size:1.05rem;font-weight:900;color:#ffd700;margin:15px 0;min-height:30px">${bjState.message}</div>`:''}
${bjState.phase==='playing'?`
<div class="bj-actions">
<button class="btn btn-primary" id="hitBtn">Взять</button>
<button class="btn btn-ghost" id="standBtn">Хватит</button>
</div>
`:`<button class="spin-btn" id="againBtn">Играть снова</button>
<div style="margin-top:10px"><button class="btn btn-ghost btn-full" id="backBtn">← Назад</button></div>`}
</div>
`;
if(bjState.phase==='playing'){
document.getElementById('hitBtn').onclick=()=>bjHit(user,el);
document.getElementById('standBtn').onclick=()=>bjStand(user,el);
}else{
document.getElementById('againBtn').onclick=()=>{
bjState.phase='bet';bjState.player=[];bjState.dealer=[];bjState.message='';
renderBlackjack(el,user);
};
document.getElementById('backBtn').onclick=()=>goTo('home',user);
}
}

function startBlackjack(user,el){
if(user.coins<bjState.bet){showToast('Недостаточно средств','error');return}
user.coins-=bjState.bet;
user.stats.spins++;
user.stats.totalLost+=bjState.bet;
addXP(user,Math.max(1,Math.floor(bjState.bet/20)));
bjState.player=[newCard(),newCard()];
bjState.dealer=[newCard(),newCard()];
bjState.phase='playing';
bjState.message='';
saveState();
updateCoins(user);
renderBlackjack(el,user);
}

function bjHit(user,el){
bjState.player.push(newCard());
const pv=handValue(bjState.player);
if(pv>21){
bjState.message='💥 Перебор! Вы проиграли';
bjState.phase='over';
saveState();
renderBlackjack(el,user);
return;
}
if(pv===21){bjStand(user,el);return;}
renderBlackjack(el,user);
}

async function bjStand(user,el){
bjState.phase='dealer';
renderBlackjack(el,user);
while(handValue(bjState.dealer)<17){
await sleep(600);
bjState.dealer.push(newCard());
renderBlackjack(el,user);
}
const pv=handValue(bjState.player);
const dv=handValue(bjState.dealer);
let win=0,msg='';
if(dv>21){win=bjState.bet*2;msg='🎉 Дилер перебрал! Вы выиграли!';}
else if(pv>dv){
win=bjState.bet*2;
msg='🎉 Вы выиграли!';
if(pv===21&&bjState.player.length===2){
user.stats.blackjacks++;
msg='🃏 БЛЭКДЖЕК! x2.5';
win=Math.floor(bjState.bet*2.5);
}
}else if(pv===dv){win=bjState.bet;msg='🤝 Ничья';}
else msg='😢 Дилер выиграл';
if(win>0){
user.coins+=win;
if(win>bjState.bet){
user.stats.wins++;
user.stats.totalWon+=win;
if(win>user.stats.biggestWin)user.stats.biggestWin=win;
}
showToast(msg+' +'+formatNum(win)+' ₡',win>bjState.bet?'win':'success');
}else showToast(msg,'error');
bjState.message=msg;
bjState.phase='over';
saveState();
checkAchievements(user);
updateCoins(user);
renderBlackjack(el,user);
}

/* ========== DICE ========== */
let diceState={bet:50,choice:null,rolling:false};

function renderDice(el,user){
el.innerHTML=`
<div class="dice-wrap">
<div style="font-size:1.1rem;font-weight:900;color:#ffd700;margin-bottom:5px">🎲 Кости</div>
<div style="font-size:.78rem;color:#778;margin-bottom:10px">Угадай больше или меньше (7 — проигрыш)</div>
<div class="dice-display">
<div class="dice" id="d0">⚀</div>
<div class="dice" id="d1">⚀</div>
</div>
<div class="bet-panel">
<div class="bet-panel-title">Сумма</div>
<div class="bet-chips">
${[10,50,100,500].map(b=>`<button class="chip ${diceState.bet===b?'selected':''}" data-bet="${b}">${b}</button>`).join('')}
</div>
</div>
<div class="choice-row two">
<button class="choice-btn choice-neutral ${diceState.choice==='more'?'selected':''}" data-choice="more">Больше 7</button>
<button class="choice-btn choice-neutral ${diceState.choice==='less'?'selected':''}" data-choice="less">Меньше 7</button>
</div>
<button class="spin-btn" id="rollBtn" ${!diceState.choice?'disabled':''}>БРОСИТЬ</button>
<div style="margin-top:15px"><button class="btn btn-ghost" id="backBtn">← Назад</button></div>
</div>
`;
el.querySelectorAll('[data-bet]').forEach(b=>{
b.onclick=()=>{if(!diceState.rolling){diceState.bet=parseInt(b.dataset.bet);renderDice(el,user)}};
});
el.querySelectorAll('[data-choice]').forEach(c=>{
c.onclick=()=>{if(!diceState.rolling){diceState.choice=c.dataset.choice;renderDice(el,user)}};
});
document.getElementById('backBtn').onclick=()=>goTo('home',user);
document.getElementById('rollBtn').onclick=()=>rollDice(user,el);
}

async function rollDice(user,el){
if(diceState.rolling||!diceState.choice)return;
if(user.coins<diceState.bet){showToast('Недостаточно средств','error');return}
diceState.rolling=true;
user.coins-=diceState.bet;
user.stats.spins++;
user.stats.totalLost+=diceState.bet;
addXP(user,Math.max(1,Math.floor(diceState.bet/20)));
const d0=document.getElementById('d0'),d1=document.getElementById('d1');
const faces=['⚀','⚁','⚂','⚃','⚄','⚅'];
if(d0)d0.classList.add('rolling');
if(d1)d1.classList.add('rolling');
for(let i=0;i<12;i++){
await sleep(80);
if(d0)d0.textContent=faces[Math.floor(Math.random()*6)];
if(d1)d1.textContent=faces[Math.floor(Math.random()*6)];
}
const r0=1+Math.floor(Math.random()*6);
const r1=1+Math.floor(Math.random()*6);
if(d0){d0.classList.remove('rolling');d0.textContent=faces[r0-1];}
if(d1){d1.classList.remove('rolling');d1.textContent=faces[r1-1];}
const sum=r0+r1;
await sleep(400);
let win=0,msg='';
if(sum===7)msg='😢 Ровно 7 — проигрыш';
else if((diceState.choice==='more'&&sum>7)||(diceState.choice==='less'&&sum<7)){
win=diceState.bet*2;msg='🎉 Победа! '+sum;
}else msg='😢 Мимо · '+sum;
if(win>0){
user.coins+=win;
user.stats.wins++;
user.stats.totalWon+=win;
if(win>user.stats.biggestWin)user.stats.biggestWin=win;
showToast(msg+' +'+formatNum(win)+' ₡','win');
}else showToast(msg,'error');
diceState.rolling=false;
saveState();
checkAchievements(user);
updateCoins(user);
renderDice(el,user);
}

/* ========== POKER (5-CARD DRAW) ========== */
let pokerState={bet:50,hand:[],held:[false,false,false,false,false],phase:'bet',message:'',draws:0};

function newPokerCard(){
const suit=SUITS[Math.floor(Math.random()*4)];
const rank=RANKS[Math.floor(Math.random()*13)];
return{suit,rank,red:suit==='♥'||suit==='♦'};
}
function pokerRankValue(r){
const map={'2':2,'3':3,'4':4,'5':5,'6':6,'7':7,'8':8,'9':9,'10':10,'J':11,'Q':12,'K':13,'A':14};
return map[r]||0;
}
function evaluatePoker(hand){
const values=hand.map(c=>pokerRankValue(c.rank)).sort((a,b)=>a-b);
const suits=hand.map(c=>c.suit);
const isFlush=suits.every(s=>s===suits[0]);
const isStraight=values.every((v,i)=>i===0||v===values[i-1]+1);
const counts={};
values.forEach(v=>counts[v]=(counts[v]||0)+1);
const cnt=Object.values(counts).sort((a,b)=>b-a);
if(isFlush&&isStraight&&values[0]===10)return{name:'Роял-флеш',multi:250};
if(isFlush&&isStraight)return{name:'Стрит-флеш',multi:50};
if(cnt[0]===4)return{name:'Каре',multi:25};
if(cnt[0]===3&&cnt[1]===2)return{name:'Фулл-хаус',multi:9};
if(isFlush)return{name:'Флеш',multi:6};
if(isStraight)return{name:'Стрит',multi:4};
if(cnt[0]===3)return{name:'Сет',multi:3};
if(cnt[0]===2&&cnt[1]===2)return{name:'Две пары',multi:2};
if(cnt[0]===2)return{name:'Пара',multi:1};
return{name:'Ничего',multi:0};
}

function pokerCardHTML(c,i){
return `<div class="poker-card ${c.red?'red':''} ${pokerState.held[i]?'held':''}" data-card="${i}"><div>${c.rank}</div><div class="suit">${c.suit}</div></div>`;
}

function renderPoker(el,user){
if(pokerState.phase==='bet'){
el.innerHTML=`
<div style="padding:14px">
<div style="font-size:1.1rem;font-weight:900;color:#ffd700;margin-bottom:5px;text-align:center">♠️ Покер</div>
<div style="font-size:.78rem;color:#778;margin-bottom:15px;text-align:center">Собери лучшую комбинацию из 5 карт</div>
<div class="bet-panel">
<div class="bet-panel-title">Ставка</div>
<div class="bet-chips">
${[10,50,100,500].map(b=>`<button class="chip ${pokerState.bet===b?'selected':''}" data-bet="${b}">${b}</button>`).join('')}
</div>
</div>
<button class="spin-btn" id="dealBtn">РАЗДАТЬ</button>
<div style="margin-top:15px"><button class="btn btn-ghost btn-full" id="backBtn">← Назад</button></div>
<div style="background:#181528;border-radius:14px;padding:14px;margin-top:15px;font-size:.72rem;color:#889;line-height:1.7">
<b style="color:#ffd700">Комбинации:</b><br>
Пара x1 · Две пары x2 · Сет x3<br>
Стрит x4 · Флеш x6 · Фулл-хаус x9<br>
Каре x25 · Стрит-флеш x50 · Роял x250
</div>
</div>
`;
el.querySelectorAll('[data-bet]').forEach(b=>{
b.onclick=()=>{pokerState.bet=parseInt(b.dataset.bet);renderPoker(el,user)};
});
document.getElementById('backBtn').onclick=()=>goTo('home',user);
document.getElementById('dealBtn').onclick=()=>dealPoker(user,el);
return;
}
el.innerHTML=`
<div class="poker-table">
<div class="poker-info">Ваша рука</div>
<div class="poker-hand">${pokerState.hand.map((c,i)=>pokerCardHTML(c,i)).join('')}</div>
<div class="poker-info">Нажмите на карты, чтобы оставить их (золотая рамка = оставить)</div>
${pokerState.message?`<div class="poker-result">${pokerState.message}</div>`:''}
${pokerState.phase==='draw'?`
<div style="display:flex;gap:8px;margin-top:10px">
<button class="btn btn-primary" id="drawBtn" style="flex:1">ОБМЕНЯТЬ (${pokerState.held.filter(h=>!h).length})</button>
<button class="btn btn-ghost" id="stayBtn" style="flex:1">ОСТАВИТЬ</button>
</div>
`:`<button class="spin-btn" id="againBtn">Играть снова</button>
<div style="margin-top:10px"><button class="btn btn-ghost btn-full" id="backBtn">← Назад</button></div>`}
</div>
`;
if(pokerState.phase==='draw'){
el.querySelectorAll('[data-card]').forEach(c=>{
c.onclick=()=>{
const i=parseInt(c.dataset.card);
pokerState.held[i]=!pokerState.held[i];
renderPoker(el,user);
};
});
document.getElementById('drawBtn').onclick=()=>drawPoker(user,el);
document.getElementById('stayBtn').onclick=()=>finishPoker(user,el);
}else{
document.getElementById('againBtn').onclick=()=>{
pokerState.phase='bet';pokerState.hand=[];pokerState.held=[false,false,false,false,false];pokerState.message='';
renderPoker(el,user);
};
document.getElementById('backBtn').onclick=()=>goTo('home',user);
}
}

function dealPoker(user,el){
if(user.coins<pokerState.bet){showToast('Недостаточно средств','error');return}
user.coins-=pokerState.bet;
user.stats.spins++;
user.stats.totalLost+=pokerState.bet;
addXP(user,Math.max(1,Math.floor(pokerState.bet/20)));
pokerState.hand=[newPokerCard(),newPokerCard(),newPokerCard(),newPokerCard(),newPokerCard()];
pokerState.held=[false,false,false,false,false];
pokerState.phase='draw';
pokerState.message='';
saveState();
updateCoins(user);
renderPoker(el,user);
}

function drawPoker(user,el){
pokerState.hand=pokerState.hand.map((c,i)=>pokerState.held[i]?c:newPokerCard());
pokerState.phase='finish';
finishPoker(user,el,true);
}

function finishPoker(user,el,noReeval){
const res=evaluatePoker(pokerState.hand);
const win=Math.floor(pokerState.bet*res.multi);
if(win>0){
user.coins+=win;
user.stats.wins++;
user.stats.totalWon+=win;
user.stats.pokerWins++;
if(win>user.stats.biggestWin)user.stats.biggestWin=win;
pokerState.message=`${res.name} · +${formatNum(win)} ₡ 🎉`;
showToast('🎉 '+res.name+'! +'+formatNum(win)+' ₡',res.multi>=6?'win':'success');
}else{
pokerState.message=`${res.name} · Увы, проигрыш`;
showToast('😢 '+res.name,'error');
}
pokerState.phase='over';
saveState();
checkAchievements(user);
updateCoins(user);
renderPoker(el,user);
}

/* ========== FORTUNE WHEEL ========== */
const FORTUNE_PRIZES=[
{label:'x0',multi:0,color:'#333'},
{label:'x0.5',multi:0.5,color:'#555'},
{label:'x1',multi:1,color:'#2a6e3f'},
{label:'x1',multi:1,color:'#2a6e3f'},
{label:'x2',multi:2,color:'#2a3f6e'},
{label:'x2',multi:2,color:'#2a3f6e'},
{label:'x3',multi:3,color:'#6e2a3f'},
{label:'x5',multi:5,color:'#6e5e2a'},
{label:'x10',multi:10,color:'#6e2a6e'},
{label:'x25',multi:25,color:'#aa2a2a'},
];
let fortuneState={bet:50,spinning:false,angle:0};

function renderFortune(el,user){
const seg=FORTUNE_PRIZES.length;
const segDeg=360/seg;
let grad='conic-gradient(';
FORTUNE_PRIZES.forEach((p,i)=>{
const from=i*segDeg;
const to=(i+1)*segDeg;
grad+=`${p.color} ${from}deg ${to}deg${i<seg-1?',':''}`;
});
grad+=')';
el.innerHTML=`
<div class="fortune-wrap">
<div style="font-size:1.1rem;font-weight:900;color:#ffd700;margin-bottom:5px">🎡 Колесо Фортуны</div>
<div style="font-size:.78rem;color:#778;margin-bottom:10px">Крути и испытай удачу</div>
<div style="position:relative;width:280px;height:280px;margin:15px auto">
<div class="fortune-pointer">▼</div>
<div class="fortune-wheel" id="fWheel" style="background:${grad}">
<div class="fortune-center">🎯</div>
</div>
</div>
<div class="poker-result" id="fResult" style="color:#ffd700">Нажми "КРУТИТЬ"</div>
<div class="bet-panel">
<div class="bet-panel-title">Ставка</div>
<div class="bet-chips">
${[10,50,100,500].map(b=>`<button class="chip ${fortuneState.bet===b?'selected':''}" data-bet="${b}">${b}</button>`).join('')}
</div>
</div>
<button class="spin-btn" id="fSpinBtn">КРУТИТЬ (${fortuneState.bet} ₡)</button>
<div style="margin-top:15px"><button class="btn btn-ghost" id="backBtn">← Назад</button></div>
</div>
`;
el.querySelectorAll('[data-bet]').forEach(b=>{
b.onclick=()=>{if(!fortuneState.spinning){fortuneState.bet=parseInt(b.dataset.bet);renderFortune(el,user)}};
});
document.getElementById('backBtn').onclick=()=>goTo('home',user);
document.getElementById('fSpinBtn').onclick=()=>spinFortune(user,el);
}

async function spinFortune(user,el){
if(fortuneState.spinning)return;
if(user.coins<fortuneState.bet){showToast('Недостаточно средств','error');return}
fortuneState.spinning=true;
user.coins-=fortuneState.bet;
user.stats.spins++;
user.stats.totalLost+=fortuneState.bet;
addXP(user,Math.max(1,Math.floor(fortuneState.bet/20)));
updateCoins(user);
const wheel=document.getElementById('fWheel');
const res=document.getElementById('fResult');
const segDeg=360/FORTUNE_PRIZES.length;
const idx=Math.floor(Math.random()*FORTUNE_PRIZES.length);
const prize=FORTUNE_PRIZES[idx];
// Крутим так, чтобы выбранный сегмент оказался сверху (указатель наверху)
const targetAngle=360*5 + (360 - idx*segDeg - segDeg/2);
fortuneState.angle+=targetAngle;
if(wheel)wheel.style.transform=`rotate(${fortuneState.angle}deg)`;
await sleep(4200);
let win=Math.floor(fortuneState.bet*prize.multi);
if(win>0){
user.coins+=win;
user.stats.wins++;
user.stats.totalWon+=win;
if(win>user.stats.biggestWin)user.stats.biggestWin=win;
if(res)res.textContent=`Выпало: ${prize.label} · +${formatNum(win)} ₡ 🎉`;
showToast('🎉 '+prize.label+'! +'+formatNum(win)+' ₡',prize.multi>=5?'win':'success');
}else{
if(res)res.textContent=`Выпало: ${prize.label} · Увы`;
showToast('😢 '+prize.label,'error');
}
fortuneState.spinning=false;
saveState();
checkAchievements(user);
updateCoins(user);
}

/* ========== TOURNAMENT ========== */
const BOT_NAMES=['Космо','Звёздный','Галакто','Астро','Небула','Квазар','Пульсар','Комета','Орион','Вега'];
let tournState={active:false,bots:[],playerScore:0,round:0,totalRounds:5,myBet:0,finished:false,myPlace:0,prize:0};

function renderTourn(el,user){
if(!tournState.active&&!tournState.finished){
el.innerHTML=`
<div class="tourn-wrap">
<div class="tourn-header">
<div class="tourn-title">🏅 Турнир с ботами</div>
<div class="tourn-sub">5 раундов · у кого больше очков — тот победил</div>
</div>
<div class="bet-panel">
<div class="bet-panel-title">Вступительный взнос</div>
<div class="bet-chips">
${[50,100,500,1000].map(b=>`<button class="chip ${tournState.myBet===b?'selected':''}" data-bet="${b}">${b}</button>`).join('')}
</div>
</div>
<div style="background:#181528;border-radius:14px;padding:14px;font-size:.78rem;color:#889;line-height:1.7;margin-bottom:14px">
<b style="color:#ffd700">Как играть:</b><br>
• 5 раундов, в каждом вы выбираете 1 из 3 карт<br>
• Карта даёт от 1 до 10 очков<br>
• Боты тоже играют<br>
• 1 место: <b style="color:#ffd700">x5</b> от взноса<br>
• 2 место: <b style="color:#ffd700">x2</b><br>
• 3 место: возврат ставки
</div>
<button class="spin-btn" id="startTourn">НАЧАТЬ ТУРНИР (${tournState.myBet} ₡)</button>
<div style="margin-top:15px"><button class="btn btn-ghost btn-full" id="backBtn">← Назад</button></div>
</div>
`;
el.querySelectorAll('[data-bet]').forEach(b=>{
b.onclick=()=>{tournState.myBet=parseInt(b.dataset.bet);renderTourn(el,user)};
});
document.getElementById('backBtn').onclick=()=>goTo('home',user);
document.getElementById('startTourn').onclick=()=>startTournament(user,el);
return;
}

if(tournState.finished){
const sorted=[...tournState.bots].sort((a,b)=>b.score-a.score);
el.innerHTML=`
<div class="tourn-wrap">
<div class="tourn-header">
<div class="tourn-title">🏆 Результаты турнира</div>
<div class="tourn-sub">${tournState.myPlace===1?'🎉 Победа!':tournState.myPlace<=3?'Хороший результат':'Повезёт в следующий раз'}</div>
</div>
${sorted.map((b,i)=>`
<div class="tourn-player ${b.me?'me':''}">
<div class="tourn-avatar">${b.name[0]}</div>
<div class="tourn-info">
<div class="tourn-name">${b.me?'🙋 Вы':b.name}</div>
<div class="tourn-score">${b.score} очков</div>
</div>
<div class="tourn-place">${i+1}${i===0?'🥇':i===1?'🥈':i===2?'🥉':''}</div>
</div>
`).join('')}
<div style="background:#181528;border-radius:14px;padding:16px;text-align:center;margin-top:14px">
<div style="color:#889;font-size:.85rem">Ваш выигрыш</div>
<div style="font-size:1.8rem;font-weight:900;color:#ffd700">+${formatNum(tournState.prize)} ₡</div>
</div>
<button class="spin-btn" id="againBtn" style="margin-top:14px">Играть снова</button>
<div style="margin-top:10px"><button class="btn btn-ghost btn-full" id="backBtn">← Назад</button></div>
</div>
`;
document.getElementById('againBtn').onclick=()=>{
tournState={active:false,bots:[],playerScore:0,round:0,totalRounds:5,myBet:tournState.myBet,finished:false,myPlace:0,prize:0};
renderTourn(el,user);
};
document.getElementById('backBtn').onclick=()=>goTo('home',user);
return;
}

// Игра идёт
el.innerHTML=`
<div class="tourn-wrap">
<div class="tourn-header">
<div class="tourn-title">🏅 Раунд ${tournState.round}/${tournState.totalRounds}</div>
<div class="tourn-sub">Ваши очки: <b style="color:#ffd700">${tournState.playerScore}</b></div>
</div>
<div style="background:#181528;border-radius:14px;padding:14px;font-size:.8rem;color:#889;margin-bottom:14px">
<b style="color:#ffd700">Выберите карту:</b>
</div>
<div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:10px">
<button class="choice-btn choice-neutral" data-pick="0" style="padding:30px 10px;font-size:1.8rem">🂠</button>
<button class="choice-btn choice-neutral" data-pick="1" style="padding:30px 10px;font-size:1.8rem">🂠</button>
<button class="choice-btn choice-neutral" data-pick="2" style="padding:30px 10px;font-size:1.8rem">🂠</button>
</div>
<div style="margin-top:14px">
${tournState.bots.map(b=>`
<div class="tourn-player ${b.me?'me':''}">
<div class="tourn-avatar">${b.name[0]}</div>
<div class="tourn-info"><div class="tourn-name">${b.me?'🙋 Вы':b.name}</div></div>
<div class="tourn-score">${b.score}</div>
</div>
`).join('')}
</div>
</div>
`;
el.querySelectorAll('[data-pick]').forEach(b=>{
b.onclick=()=>playTournRound(parseInt(b.dataset.pick),user,el);
});
}

function startTournament(user,el){
if(user.coins<tournState.myBet){showToast('Недостаточно средств','error');return}
user.coins-=tournState.myBet;
user.stats.spins++;
user.stats.totalLost+=tournState.myBet;
addXP(user,Math.max(1,Math.floor(tournState.myBet/20)));
tournState.active=true;
tournState.finished=false;
tournState.round=1;
tournState.playerScore=0;
tournState.prize=0;
tournState.myPlace=0;
const botCount=3+Math.floor(Math.random()*3);
tournState.bots=[];
for(let i=0;i<botCount;i++){
tournState.bots.push({name:BOT_NAMES[Math.floor(Math.random()*BOT_NAMES.length)]+i,score:0,me:false});
}
tournState.bots.push({name:user.name,score:0,me:true});
saveState();
updateCoins(user);
renderTourn(el,user);
}

function playTournRound(pick,user,el){
const cardVal=[1,2,3,4,5,6,7,8,9,10];
const myGain=cardVal[Math.floor(Math.random()*cardVal.length)];
tournState.playerScore+=myGain;
tournState.bots.forEach(b=>{
if(b.me)b.score=tournState.playerScore;
else b.score+=cardVal[Math.floor(Math.random()*cardVal.length)];
});
tournState.round++;
saveState();
if(tournState.round>tournState.totalRounds){
finishTournament(user,el);
}else{
renderTourn(el,user);
}
}

function finishTournament(user,el){
tournState.active=false;
tournState.finished=true;
const sorted=[...tournState.bots].sort((a,b)=>b.score-a.score);
const myPlace=sorted.findIndex(b=>b.me)+1;
tournState.myPlace=myPlace;
let prize=0;
if(myPlace===1)prize=tournState.myBet*5;
else if(myPlace===2)prize=tournState.myBet*2;
else if(myPlace===3)prize=tournState.myBet;
if(prize>0){
user.coins+=prize;
if(prize>tournState.myBet){
user.stats.wins++;
user.stats.totalWon+=prize;
if(prize>user.stats.biggestWin)user.stats.biggestWin=prize;
}
if(myPlace===1)user.stats.tournWins++;
showToast('🏆 Место '+myPlace+'! +'+formatNum(prize)+' ₡',myPlace===1?'win':'success');
}else{
showToast('😢 Вы заняли '+myPlace+' место','error');
}
tournState.prize=prize;
saveState();
checkAchievements(user);
updateCoins(user);
renderTourn(el,user);
}

/* ========== ACH ========== */
function renderAch(el,user){
const done=user.achievements.length;
el.innerHTML=`
<div style="padding:14px 16px 0;font-size:1.1rem;font-weight:800;color:#ffd700">🏆 Достижения</div>
<div style="font-size:.78rem;color:#778;padding:0 16px 10px">Выполнено: ${done} из ${ACHIEVEMENTS.length}</div>
${ACHIEVEMENTS.map(a=>{
const isDone=user.achievements.includes(a.id);
const cur=user.stats[a.stat]||0;
const prog=Math.min(100,(cur/a.target)*100);
return `<div class="ach-item ${isDone?'done':''}">
<div class="ach-icon">${a.icon}</div>
<div class="ach-info">
<div class="ach-name">${a.name}</div>
<div class="ach-desc">${a.desc}</div>
${isDone?'<div class="ach-done-badge">✓ Получено · +'+formatNum(a.reward)+' ₡</div>':`
<div class="ach-progress"><div class="ach-progress-fill" style="width:${prog}%"></div></div>
<div class="ach-reward">${formatNum(cur)}/${formatNum(a.target)} · Награда: ${formatNum(a.reward)} ₡</div>
`}
</div>
</div>`;
}).join('')}
`;
}

function checkAchievements(user){
let changed=false;
ACHIEVEMENTS.forEach(a=>{
if(user.achievements.includes(a.id))return;
const cur=user.stats[a.stat]||0;
if(cur>=a.target){
user.achievements.push(a.id);
user.coins+=a.reward;
changed=true;
setT(()=>showToast('🏆 '+a.name+'! +'+formatNum(a.reward)+' ₡','win'),100);
}
});
if(changed){
saveState();
updateCoins(user);
if(currentScreen==='ach')renderAch(document.getElementById('screen-ach'),user);
}
}

/* ========== PROFILE ========== */
function renderProfile(el,user){
const achDone=user.achievements.length;
const profit=user.stats.totalWon-user.stats.totalLost;
el.innerHTML=`
<div class="profile-top">
<div class="profile-avatar">${user.name[0].toUpperCase()}</div>
<div class="profile-name">${user.name}</div>
<div class="profile-level">🎰 Уровень ${user.level} · XP ${user.xp}/${user.xpNext}</div>
</div>
<div class="profile-stats">
<div class="stat-card"><div class="stat-icon">💰</div><div class="stat-value">${formatNum(user.coins)}</div><div class="stat-label">Баланс</div></div>
<div class="stat-card"><div class="stat-icon">${profit>=0?'📈':'📉'}</div><div class="stat-value" style="color:${profit>=0?'#00ff88':'#ff5566'}">${profit>=0?'+':''}${formatNum(profit)}</div><div class="stat-label">Профит</div></div>
<div class="stat-card"><div class="stat-icon">🎲</div><div class="stat-value">${user.stats.spins}</div><div class="stat-label">Ставок</div></div>
<div class="stat-card"><div class="stat-icon">🏆</div><div class="stat-value">${achDone}/${ACHIEVEMENTS.length}</div><div class="stat-label">Достижения</div></div>
</div>
<button class="settings-btn" id="renameBtn">✏️ Сменить имя</button>
<button class="settings-btn" id="passBtn">🔑 Сменить пароль</button>
<button class="settings-btn danger" id="logoutBtn">🚪 Выйти</button>
<div style="text-align:center;color:#445;font-size:.75rem;padding:20px">Космическое Казино v2.0</div>
`;
document.getElementById('renameBtn').onclick=()=>openRename(user);
document.getElementById('passBtn').onclick=()=>openChangePass(user);
document.getElementById('logoutBtn').onclick=()=>{
state.currentUser=null;saveState();render();
};
}

function openRename(user){
const m=document.createElement('div');
m.className='modal-overlay';
m.innerHTML=`<div class="modal"><h3>Сменить имя</h3>
<input class="auth-input" id="nn" value="${user.name}" maxlength="15" style="margin-bottom:12px">
<div style="display:flex;gap:10px"><button class="btn btn-ghost" id="c" style="flex:1">Отмена</button><button class="btn btn-primary" id="s" style="flex:1">Сохранить</button></div></div>`;
document.body.appendChild(m);
document.getElementById('c').onclick=()=>m.remove();
document.getElementById('s').onclick=()=>{
const n=document.getElementById('nn').value.trim();
if(!n){showToast('Введите имя','error');return}
if(state.users[n]&&n!==user.name){showToast('Имя занято','error');return}
if(n!==user.name){
state.users[n]={...user,name:n};
delete state.users[user.name];
state.currentUser=n;saveState();m.remove();render();
showToast('Имя изменено','success');
}
};
m.onclick=(e)=>{if(e.target===m)m.remove()};
}

function openChangePass(user){
const m=document.createElement('div');
m.className='modal-overlay';
m.innerHTML=`<div class="modal"><h3>Сменить пароль</h3>
<input class="auth-input" id="np" type="password" placeholder="Новый пароль" maxlength="20" style="margin-bottom:12px">
<div style="display:flex;gap:10px"><button class="btn btn-ghost" id="c" style="flex:1">Отмена</button><button class="btn btn-primary" id="s" style="flex:1">Сохранить</button></div></div>`;
document.body.appendChild(m);
document.getElementById('c').onclick=()=>m.remove();
document.getElementById('s').onclick=()=>{
const p=document.getElementById('np').value.trim();
if(p.length<4){showToast('Минимум 4 символа','error');return}
user.pass=p;saveState();m.remove();
showToast('Пароль изменён','success');
};
m.onclick=(e)=>{if(e.target===m)m.remove()};
}

/* ========== UTILS ========== */
function addXP(user,amount){
user.xp+=amount;
let leveled=false;
while(user.xp>=user.xpNext){
user.xp-=user.xpNext;
user.level++;
user.xpNext=Math.floor(user.xpNext*1.4);
const bonus=user.level*100;
user.coins+=bonus;
user.stats.level=user.level;
leveled=true;
setT(()=>showToast('🎉 Уровень '+user.level+'! +'+formatNum(bonus)+' ₡','win'),100);
}
saveState();
checkAchievements(user);
if(leveled)updateCoins(user);
}

function formatNum(n){
n=Math.floor(n);
if(n>=1000000000)return (n/1000000000).toFixed(1)+'B';
if(n>=1000000)return (n/1000000).toFixed(1)+'M';
if(n>=10000)return (n/1000).toFixed(1)+'K';
return n.toString().replace(/\B(?=(\d{3})+(?!\d))/g,' ');
}

function showToast(msg,type){
const old=document.querySelector('.toast');
if(old)old.remove();
const t=document.createElement('div');
t.className='toast'+(type?' '+type:'');
t.textContent=msg;
document.body.appendChild(t);
setTimeout(()=>t.remove(),2400);
}

/* ========== START ========== */
loadState();
render();
</script>
</body>
</html>
