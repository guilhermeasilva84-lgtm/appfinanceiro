<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
<meta name="theme-color" content="#11110f" />
<meta name="description" content="Banco Premium: app de controle financeiro pessoal, rápido e instalável." />
<link rel="manifest" href="manifest.json" />
<link rel="apple-touch-icon" href="icon-192.png" />
<title>Banco Premium — Controle Financeiro</title>
<style>

:root{
  --bg:#f4f1ea;
  --panel:#fffdf8;
  --panel2:#ffffff;
  --text:#15130f;
  --muted:#7b756b;
  --line:rgba(21,19,15,.08);
  --black:#11110f;
  --gold:#c6a15b;
  --gold2:#f1e4c7;
  --green:#14905f;
  --red:#cc4049;
  --orange:#d98b24;
  --blue:#3a72e8;
  --shadow:0 26px 70px rgba(25,20,12,.10);
  --radius:28px;
  --ease:cubic-bezier(.2,.8,.2,1);
  --ease-out:cubic-bezier(.16,1,.3,1);
}
[data-theme="dark"]{
  --bg:#080808;
  --panel:#111111;
  --panel2:#171717;
  --text:#f8f5ee;
  --muted:#a8a198;
  --line:rgba(255,255,255,.09);
  --black:#f8f5ee;
  --gold:#d6b56e;
  --gold2:rgba(214,181,110,.14);
  --green:#58d695;
  --red:#ff737c;
  --orange:#ffc061;
  --blue:#86a8ff;
  --shadow:0 30px 80px rgba(0,0,0,.42);
}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
@property --p{syntax:'<percentage>';inherits:true;initial-value:0%}
html{scroll-behavior:smooth}
body{
  margin:0;
  min-height:100vh;
  color:var(--text);
  background:radial-gradient(circle at 50% -15%,rgba(198,161,91,.16),transparent 360px),var(--bg);
  font-family:-apple-system,BlinkMacSystemFont,"SF Pro Display","Segoe UI",Roboto,Arial,sans-serif;
  letter-spacing:-.02em;
  transition:background-color .38s var(--ease-out),color .3s var(--ease-out);
}
.card,.tx,.topbar,.nav,.action,.hero-stat,.accordion-item,.bill-row,.notif-row,.empty,.round{
  transition:background-color .32s var(--ease-out),border-color .32s var(--ease-out),box-shadow .32s var(--ease-out),transform .18s var(--ease);
}
button,input,select,textarea{font:inherit}
button{border:0;cursor:pointer;color:inherit}
.app{
  width:min(100%,480px);
  min-height:100vh;
  margin:0 auto;
  padding:max(14px,env(safe-area-inset-top)) 14px calc(96px + env(safe-area-inset-bottom));
}
.topbar{
  position:sticky;
  top:0;
  z-index:30;
  margin:0 -14px;
  padding:10px 14px 12px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:12px;
  background:color-mix(in srgb,var(--bg) 88%,transparent);
  backdrop-filter:blur(22px);
  -webkit-backdrop-filter:blur(22px);
}
.profile{display:flex;align-items:center;gap:10px;min-width:0}
.avatar{
  width:36px;height:36px;border-radius:50%;
  display:grid;place-items:center;
  background:linear-gradient(135deg,#f5deb1,var(--gold));
  color:#111;font-weight:860;
  box-shadow:0 12px 30px rgba(198,161,91,.22);
  background-size:cover;background-position:center;
  transition:transform .16s var(--ease);
  overflow:hidden;
}
.avatar.has-photo{color:transparent}
.avatar{cursor:pointer}
.avatar:active{transform:scale(.93)}
.avatar-edit{display:flex;flex-direction:column;align-items:center;gap:10px;padding:6px 0 18px;border-bottom:1px solid var(--line);margin-bottom:8px}
.avatar-big{
  width:92px;height:92px;border-radius:50%;position:relative;
  background:linear-gradient(135deg,#f5deb1,var(--gold));
  display:grid;place-items:center;color:#111;font-weight:860;font-size:30px;
  box-shadow:0 18px 40px rgba(198,161,91,.28);
  background-size:cover;background-position:center;
  transition:transform .18s var(--ease);
  overflow:hidden;
}
.avatar-big:active{transform:scale(.95)}
.avatar-big.has-photo span:first-child{color:transparent}
.avatar-edit-badge{
  position:absolute;right:-2px;bottom:-2px;width:30px;height:30px;border-radius:50%;
  background:var(--black);color:var(--bg);display:grid;place-items:center;font-size:13px;
  border:3px solid var(--panel2);
}
[data-theme="dark"] .avatar-edit-badge{color:#111}
.avatar-edit-actions{display:flex;gap:8px}
.profile small{display:block;color:var(--muted);font-size:12px;line-height:1}
.profile strong{display:block;margin-top:3px;font-size:15px;line-height:1}
.top-actions{display:flex;gap:8px}
.round{
  width:36px;height:36px;border-radius:50%;
  display:grid;place-items:center;
  background:var(--panel);
  border:1px solid var(--line);
  box-shadow:0 10px 26px rgba(0,0,0,.05);
  transition:transform .18s var(--ease),background .18s var(--ease);
}
.round:active,.nav button:active,.action:active,.primary:active,.chip:active,.ghost:active,.drawer-link:active,.tabs button:active,.close:active,.star-btn:active,.accordion-head:active,.fab:active,.toggle:active,.dialog-actions button:active,.cal-day:active{transform:scale(.95)}
.screen{display:none;animation:rise .32s var(--ease-out) both}
.screen.active{display:block}
@keyframes rise{from{opacity:0;transform:translateY(10px) scale(.99)}to{opacity:1;transform:translateY(0) scale(1)}}
.hero{
  margin-top:8px;
  min-height:190px;
  padding:22px 20px;
  border-radius:32px;
  color:#f8f5ee;
  background:linear-gradient(145deg,#111 0%,#161616 52%,#2a2318 100%);
  box-shadow:0 28px 76px rgba(0,0,0,.20);
  position:relative;
  overflow:hidden;
  isolation:isolate;
}
.hero:before{
  content:"";
  position:absolute;
  width:230px;height:230px;
  right:-116px;top:-130px;
  border-radius:50%;
  border:1px solid rgba(198,161,91,.35);
  z-index:-1;
}
.hero:after{
  content:"";
  position:absolute;
  width:46px;height:30px;right:22px;bottom:18px;
  border-radius:50%;
  background:radial-gradient(circle,rgba(198,161,91,.95),rgba(198,161,91,.18) 68%,transparent 70%);
  opacity:.78;
}
.label{color:var(--muted);font-size:12px;font-weight:650}
.hero .label{color:rgba(248,245,238,.64)}
.balance{
  margin-top:12px;
  font-size:40px;
  line-height:.98;
  letter-spacing:-.065em;
  font-weight:780;
}
.hero-row{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:22px}
.hero-stat{
  padding:12px;
  border-radius:20px;
  background:rgba(255,255,255,.075);
  border:1px solid rgba(255,255,255,.08);
}
.hero-stat small{display:block;color:rgba(248,245,238,.58);font-size:11px}
.hero-stat b{display:block;margin-top:5px;font-size:14px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.actions-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:9px;margin-top:14px}
.action{
  min-height:74px;
  border-radius:24px;
  background:var(--panel);
  border:1px solid var(--line);
  box-shadow:0 14px 34px rgba(0,0,0,.04);
  display:grid;
  place-items:center;
  gap:5px;
  animation:rise .34s var(--ease-out) both;
  transition:transform .18s var(--ease),background .18s var(--ease);
}
.action i{
  width:30px;height:30px;border-radius:50%;
  display:grid;place-items:center;
  font-style:normal;
  color:var(--gold);
  background:var(--gold2);
  font-weight:850;
}
.action span{font-size:11px;color:var(--muted);font-weight:700}
.section{margin-top:24px}
.section-head{display:flex;align-items:end;justify-content:space-between;gap:12px;margin-bottom:10px}
h2{margin:0;font-size:17px;font-weight:780;letter-spacing:-.035em}
.link{background:transparent;color:var(--gold);font-size:12px;font-weight:780;padding:5px}
.card{
  background:var(--panel);
  border:1px solid var(--line);
  border-radius:26px;
  box-shadow:var(--shadow);
}
.insight-card{
  padding:16px;
  display:grid;
  grid-template-columns:60px 1fr;
  gap:14px;
  align-items:center;
}
.ring{
  width:60px;height:60px;border-radius:50%;
  display:grid;place-items:center;
  position:relative;
  background:conic-gradient(var(--gold) var(--p,0%),var(--gold2) 0);
  font-size:12px;font-weight:790;
  transition:--p .6s var(--ease-out);
}
.ring:after{content:"";position:absolute;inset:7px;border-radius:inherit;background:var(--panel)}
.ring span{position:relative;z-index:1}
.insight-card b{display:block;font-size:14px;margin-bottom:5px}
.insight-card p{margin:0;color:var(--muted);font-size:12.5px;line-height:1.42}
.list{display:grid;gap:8px}
.list>*:nth-child(1){animation-delay:.02s}
.list>*:nth-child(2){animation-delay:.06s}
.list>*:nth-child(3){animation-delay:.10s}
.list>*:nth-child(4){animation-delay:.14s}
.list>*:nth-child(5){animation-delay:.18s}
.list>*:nth-child(6){animation-delay:.22s}
.list>*:nth-child(7){animation-delay:.26s}
.list>*:nth-child(8){animation-delay:.30s}
.list>*:nth-child(n+9){animation-delay:.33s}
.actions-grid .action:nth-child(1){animation-delay:.03s}
.actions-grid .action:nth-child(2){animation-delay:.07s}
.actions-grid .action:nth-child(3){animation-delay:.11s}
.actions-grid .action:nth-child(4){animation-delay:.15s}
.tx{
  display:grid;
  grid-template-columns:40px 1fr auto;
  gap:10px;
  align-items:center;
  padding:11px;
  border-radius:22px;
  background:var(--panel);
  border:1px solid var(--line);
  animation:rise .2s var(--ease) both;
}
.tx-icon{
  width:40px;height:40px;border-radius:50%;
  display:grid;place-items:center;
  background:var(--gold2);
  font-size:17px;
}
.tx h3{margin:0;font-size:14px;font-weight:730;line-height:1.15}
.tx p{margin:4px 0 0;font-size:12px;color:var(--muted);line-height:1.2}
.tx-value{text-align:right;display:grid;gap:2px}
.tx-value b{font-size:14px;font-weight:780;white-space:nowrap}
.in{color:var(--green)}.out{color:var(--red)}
.del{width:24px;height:20px;background:transparent;color:var(--muted);font-size:16px;justify-self:end;opacity:.7}
.form{display:grid;gap:11px}
.field{display:grid;gap:6px}
.field label{font-size:12px;color:var(--muted);padding-left:3px;font-weight:680}
input,select,textarea{
  width:100%;
  min-height:49px;
  border-radius:19px;
  border:1px solid var(--line);
  background:var(--panel);
  color:var(--text);
  outline:none;
  padding:0 14px;
  transition:border-color .18s var(--ease),box-shadow .18s var(--ease);
}
textarea{padding:13px 14px;resize:vertical;min-height:96px}
input:focus,select:focus,textarea:focus{
  border-color:rgba(198,161,91,.56);
  box-shadow:0 0 0 4px rgba(198,161,91,.12);
}
.row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.segment{
  display:grid;grid-template-columns:1fr 1fr;
  gap:4px;padding:4px;
  min-height:49px;border-radius:19px;
  border:1px solid var(--line);background:var(--panel);
}
.segment button{border-radius:15px;background:transparent;color:var(--muted);font-size:13px;font-weight:760}
.segment button.active{color:#111;background:linear-gradient(135deg,#f0dba9,var(--gold))}
.primary{
  min-height:51px;border-radius:20px;
  background:var(--black);color:var(--bg);
  font-weight:820;letter-spacing:-.015em;
  transition:transform .18s var(--ease),opacity .18s var(--ease);
}
[data-theme="dark"] .primary{color:#111}
.chips{display:flex;gap:8px;overflow:auto;padding-bottom:4px;scrollbar-width:none}
.chips::-webkit-scrollbar{display:none}
.chip{
  flex:0 0 auto;
  min-height:37px;
  padding:0 14px;
  border-radius:999px;
  background:var(--panel);
  border:1px solid var(--line);
  color:var(--muted);
  font-size:12px;
  font-weight:720;
  transition:transform .16s var(--ease),background .22s var(--ease-out),color .22s var(--ease-out),border-color .22s var(--ease-out);
}
.chip.active{color:#111;background:linear-gradient(135deg,#f0dba9,var(--gold));border-color:transparent}
.tools{display:grid;grid-template-columns:1fr auto;gap:9px;margin-bottom:10px}
.tools select{width:132px}
.empty{
  padding:24px 14px;
  text-align:center;
  color:var(--muted);
  font-size:13px;
  border:1px dashed var(--line);
  border-radius:24px;
  background:var(--panel);
}
.budget-card{padding:15px;display:grid;gap:14px}
.line-top{display:flex;justify-content:space-between;gap:10px;font-size:13px}
.line-top span{color:var(--muted)}
.track{height:8px;border-radius:999px;background:var(--gold2);overflow:hidden}
.fill{height:100%;width:0%;border-radius:inherit;background:linear-gradient(90deg,var(--gold),#111);transition:width .36s var(--ease)}
[data-theme="dark"] .fill{background:linear-gradient(90deg,var(--gold),#f8f5ee)}
.canvas-box{height:190px;padding:10px}
canvas{display:block;width:100%;height:100%}
.nav{
  position:fixed;
  left:50%;
  bottom:max(12px,env(safe-area-inset-bottom));
  transform:translateX(-50%);
  width:min(452px,calc(100% - 28px));
  height:67px;
  border-radius:29px;
  padding:7px;
  background:color-mix(in srgb,var(--panel) 86%,transparent);
  border:1px solid var(--line);
  box-shadow:0 20px 60px rgba(0,0,0,.14);
  backdrop-filter:blur(24px);
  -webkit-backdrop-filter:blur(24px);
  display:grid;
  grid-template-columns:repeat(5,1fr);
  gap:4px;
  z-index:40;
}
.nav button{
  background:transparent;
  border-radius:23px;
  display:grid;
  place-items:center;
  gap:2px;
  color:var(--muted);
  font-size:10px;
  font-weight:760;
  transition:transform .18s var(--ease),background .18s var(--ease),color .18s var(--ease);
}
.nav button i{font-style:normal;font-size:16px;line-height:1}
.nav button.active{background:var(--black);color:var(--bg)}
[data-theme="dark"] .nav button.active{color:#111}
.sheet-bg{
  position:fixed;inset:0;z-index:60;
  display:none;place-items:end center;
  background:rgba(0,0,0,.38);
  padding:14px;
}
.sheet-bg.show{display:grid}
.sheet{
  width:min(452px,100%);
  background:var(--panel2);
  border:1px solid var(--line);
  border-radius:31px;
  padding:14px;
  box-shadow:0 34px 110px rgba(0,0,0,.30);
  animation:sheet .34s var(--ease-out) both;
}
@keyframes sheet{from{opacity:0;transform:translateY(38px) scale(.98)}to{opacity:1;transform:translateY(0) scale(1)}}
.sheet-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:10px}
.close{width:36px;height:36px;border-radius:50%;background:var(--gold2);color:var(--muted);transition:transform .16s var(--ease),background .2s var(--ease-out)}
.settings{display:grid;gap:6px}
.setting{display:grid;grid-template-columns:1fr auto;gap:12px;align-items:center;padding:12px 4px;border-bottom:1px solid var(--line)}
.setting:last-child{border-bottom:0}
.setting b{font-size:14px}.setting p{margin:4px 0 0;color:var(--muted);font-size:12px;line-height:1.35}
.toggle{width:49px;height:29px;border-radius:999px;background:var(--gold2);padding:3px;transition:transform .16s var(--ease),background .22s var(--ease-out)}
.toggle i{display:block;width:23px;height:23px;border-radius:50%;background:var(--panel2);box-shadow:0 5px 13px rgba(0,0,0,.14);transition:transform .3s var(--ease-out)}
.toggle.on{background:var(--gold)}.toggle.on i{transform:translateX(20px)}
.ghost{height:36px;padding:0 12px;border-radius:999px;background:var(--gold2);color:var(--muted);font-size:12px;font-weight:760}
.toast{
  position:fixed;
  left:50%;
  bottom:92px;
  transform:translateX(-50%) translateY(12px);
  width:min(420px,calc(100% - 28px));
  padding:12px 14px;
  border-radius:18px;
  background:var(--black);
  color:var(--bg);
  opacity:0;
  pointer-events:none;
  transition:opacity .22s var(--ease),transform .22s var(--ease);
  z-index:90;
  font-size:13px;
  font-weight:720;
  box-shadow:0 20px 70px rgba(0,0,0,.20);
}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0)}
[data-theme="dark"] .toast{color:#111}
@media(max-width:360px){
  .balance{font-size:34px}
  .actions-grid{grid-template-columns:repeat(2,1fr)}
  .row,.tools{grid-template-columns:1fr}
  .tools select{width:100%}
}
@media(min-width:760px){
  body:before{
    content:"";
    position:fixed;
    inset:22px 50%;
    transform:translateX(-50%);
    width:508px;
    border:1px solid rgba(0,0,0,.05);
    border-radius:50px;
    pointer-events:none;
  }
}



/* ===== v4 additions: components, drawer, dialogs, charts, calendar ===== */
.top-actions .round{position:relative}
.badge-dot{
  position:absolute;top:-3px;right:-3px;
  min-width:16px;height:16px;padding:0 3px;
  border-radius:999px;background:var(--red);color:#fff;
  font-size:9px;font-weight:800;display:grid;place-items:center;
  border:2px solid var(--bg);
  transform:scale(0);transition:transform .18s var(--ease);
}
.badge-dot.show{transform:scale(1)}

/* Skeleton loading */
.skeleton-overlay{
  position:fixed;inset:0;z-index:200;background:var(--bg);
  display:grid;place-items:center;transition:opacity .32s var(--ease),visibility .32s;
}
.skeleton-overlay.hide{opacity:0;visibility:hidden;pointer-events:none}
.skeleton-wrap{width:min(100%,480px);padding:16px}
.sk{
  border-radius:22px;background:linear-gradient(100deg,var(--line) 8%,rgba(198,161,91,.16) 18%,var(--line) 33%);
  background-size:200% 100%;animation:shimmer 1.3s ease-in-out infinite;
}
@keyframes shimmer{0%{background-position:180% 0}100%{background-position:-20% 0}}
.sk-hero{height:190px;border-radius:32px;margin-bottom:14px}
.sk-row{height:64px;border-radius:22px;margin-bottom:8px}

/* Drawer (side menu) */
.drawer-bg{position:fixed;inset:0;z-index:70;display:none;background:rgba(0,0,0,.38)}
.drawer-bg.show{display:block}
.drawer{
  position:fixed;top:0;left:0;bottom:0;width:min(300px,84%);
  background:var(--panel2);border-right:1px solid var(--line);
  padding:max(20px,env(safe-area-inset-top)) 16px 20px;
  transform:translateX(-100%);transition:transform .36s var(--ease-out);
  display:flex;flex-direction:column;gap:4px;
  box-shadow:0 0 60px rgba(0,0,0,.2);
}
.drawer-bg.show .drawer{transform:translateX(0)}
.drawer-profile{display:flex;align-items:center;gap:12px;padding:6px 6px 18px;border-bottom:1px solid var(--line);margin-bottom:10px}
.drawer-profile .avatar{width:46px;height:46px;font-size:18px}
.drawer-profile strong{display:block;font-size:15px}
.drawer-profile small{display:block;color:var(--muted);font-size:12px;margin-top:2px}
.drawer-link{
  display:flex;align-items:center;gap:12px;padding:12px 10px;border-radius:16px;
  background:transparent;color:var(--text);font-size:14px;font-weight:700;text-align:left;
  transition:background .16s var(--ease);position:relative;
}
.drawer-link:active{background:var(--gold2)}
.drawer-link i{font-style:normal;width:26px;text-align:center;color:var(--gold);font-size:16px}
.drawer-link .mini-badge{
  margin-left:auto;background:var(--red);color:#fff;font-size:10px;font-weight:800;
  border-radius:999px;min-width:18px;height:18px;padding:0 4px;display:grid;place-items:center;
}
.drawer-foot{margin-top:auto;padding-top:14px;border-top:1px solid var(--line);color:var(--muted);font-size:11px;text-align:center}

/* Dialog (confirm/alert) */
.dialog-bg{position:fixed;inset:0;z-index:95;display:none;place-items:center;background:rgba(0,0,0,.42);padding:24px}
.dialog-bg.show{display:grid}
.dialog{
  width:min(340px,100%);background:var(--panel2);border:1px solid var(--line);
  border-radius:26px;padding:22px 20px;box-shadow:0 34px 110px rgba(0,0,0,.32);
  animation:dialogIn .28s var(--ease-out) both;text-align:center;
}
@keyframes dialogIn{from{opacity:0;transform:scale(.9)}to{opacity:1;transform:scale(1)}}
.dialog h3{margin:0 0 8px;font-size:16px;font-weight:800}
.dialog p{margin:0 0 18px;color:var(--muted);font-size:13px;line-height:1.5}
.dialog-actions{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.dialog-actions.single{grid-template-columns:1fr}
.dialog-actions button{min-height:44px;border-radius:16px;font-weight:780;font-size:13px}
.dialog-cancel{background:var(--gold2);color:var(--muted)}
.dialog-confirm{background:var(--red);color:#fff}
.dialog-confirm.neutral{background:var(--black);color:var(--bg)}
[data-theme="dark"] .dialog-confirm.neutral{color:#111}

/* Snackbar action */
.toast{display:flex;align-items:center;justify-content:space-between;gap:12px}
.toast-action{background:transparent;color:var(--gold);font-weight:800;font-size:12px;flex:0 0 auto}

/* FAB */
.fab{
  position:fixed;right:max(18px,calc(50% - 210px));bottom:calc(90px + env(safe-area-inset-bottom));
  width:56px;height:56px;border-radius:50%;z-index:45;
  background:linear-gradient(135deg,#f0dba9,var(--gold));color:#111;
  font-size:24px;font-weight:800;display:grid;place-items:center;
  box-shadow:0 18px 40px rgba(198,161,91,.38);
  transition:transform .18s var(--ease);
}
.fab:active{transform:scale(.92) rotate(90deg)}

/* Back / screen head */
.back-row{display:flex;align-items:center;gap:10px;margin:2px 0 4px}
.back-btn{width:34px;height:34px;border-radius:50%;background:var(--panel);border:1px solid var(--line);color:var(--text);font-size:15px}
.back-row h2{font-size:18px}

/* Tabs (generic pill switch, more than 2 options) */
.tabs{display:flex;gap:4px;padding:4px;border-radius:19px;border:1px solid var(--line);background:var(--panel)}
.tabs button{flex:1;min-height:38px;border-radius:15px;background:transparent;color:var(--muted);font-size:12.5px;font-weight:760}
.tabs button.active{color:#111;background:linear-gradient(135deg,#f0dba9,var(--gold))}
[data-theme="dark"] .tabs button.active{color:#111}

/* Accordion */
.accordion-item{border:1px solid var(--line);border-radius:22px;background:var(--panel);margin-bottom:8px;overflow:hidden}
.accordion-head{display:grid;grid-template-columns:40px 1fr auto auto;gap:10px;align-items:center;padding:11px;width:100%;background:transparent}
.accordion-head .tx-icon{width:40px;height:40px;border-radius:50%;background:var(--gold2);display:grid;place-items:center;font-size:17px}
.accordion-head b{font-size:14px;text-align:left}
.accordion-head .chev{color:var(--muted);transition:transform .2s var(--ease);font-size:12px}
.accordion-item.open .chev{transform:rotate(180deg)}
.accordion-body{max-height:0;overflow:hidden;transition:max-height .26s var(--ease)}
.accordion-item.open .accordion-body{max-height:600px}
.accordion-body-in{padding:0 11px 11px}
.sub-row{display:flex;justify-content:space-between;padding:8px 4px;font-size:12.5px;color:var(--muted);border-top:1px solid var(--line)}
.sub-row:first-child{border-top:0}

/* Favorite star */
.star-btn{background:transparent;color:var(--line);font-size:15px;padding:2px;transition:transform .16s var(--ease),color .22s var(--ease-out)}
.star-btn.on{animation:starPop .34s var(--ease-out)}
@keyframes starPop{0%{transform:scale(1)}40%{transform:scale(1.35)}100%{transform:scale(1)}}
.star-btn.on{color:var(--gold)}
.tx.is-fav{border-color:rgba(198,161,91,.4)}

/* Account chip */
.acc-chip{font-size:10px;color:var(--muted);background:var(--gold2);border-radius:999px;padding:2px 7px;font-weight:700;display:inline-block;margin-top:3px}

/* Calendar */
.cal-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:10px}
.cal-head button{width:34px;height:34px;border-radius:50%;background:var(--panel);border:1px solid var(--line)}
.cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:5px;text-align:center}
.cal-dow{font-size:10px;color:var(--muted);font-weight:700;padding-bottom:4px}
.cal-day{
  aspect-ratio:1;border-radius:14px;background:var(--panel);border:1px solid var(--line);
  display:flex;flex-direction:column;align-items:center;justify-content:center;gap:2px;
  font-size:12px;font-weight:700;position:relative;transition:transform .15s var(--ease);
}
.cal-day.muted{opacity:.28}
.cal-day.today{border-color:var(--gold);box-shadow:0 0 0 2px rgba(198,161,91,.18)}
.cal-day:active{transform:scale(.92)}
.cal-dots{display:flex;gap:2px}
.cal-dots i{width:4px;height:4px;border-radius:50%;background:var(--line)}
.cal-dots i.in{background:var(--green)}
.cal-dots i.out{background:var(--red)}

/* Pie / donut chart */
.pie-wrap{display:flex;align-items:center;gap:16px;padding:8px}
.pie-svg{flex:0 0 auto}
.pie-svg circle{transition:stroke-dasharray .6s var(--ease)}
.pie-legend{display:grid;gap:7px;flex:1;min-width:0}
.pie-legend-row{display:flex;align-items:center;gap:8px;font-size:12px}
.pie-legend-row i{width:9px;height:9px;border-radius:50%;flex:0 0 auto}
.pie-legend-row span{color:var(--muted);flex:1;min-width:0;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.pie-legend-row b{font-size:12px}

/* Line / area chart */
.line-svg path.area{opacity:.14}
.line-svg path.line{stroke-dasharray:600;stroke-dashoffset:600;animation:drawline 1s var(--ease) forwards}
@keyframes drawline{to{stroke-dashoffset:0}}
.line-svg circle.dot{opacity:0;animation:fadeIn .3s var(--ease) forwards}
@keyframes fadeIn{to{opacity:1}}

/* Compare row */
.compare-row{display:flex;justify-content:space-between;align-items:center;padding:12px 4px}
.compare-row b{font-size:13px}
.compare-pill{font-size:11px;font-weight:800;padding:3px 9px;border-radius:999px}
.compare-pill.up{background:rgba(204,64,73,.14);color:var(--red)}
.compare-pill.down{background:rgba(20,144,95,.14);color:var(--green)}

/* Bills / reminders */
.bill-row{display:grid;grid-template-columns:1fr auto;gap:10px;align-items:center;padding:12px;border-radius:20px;background:var(--panel);border:1px solid var(--line);margin-bottom:8px}
.bill-row.paid{opacity:.55}
.bill-row b{display:block;font-size:13.5px}
.bill-row p{margin:3px 0 0;font-size:11.5px;color:var(--muted)}
.bill-row.late p{color:var(--red)}

/* Notification item */
.notif-row{display:grid;grid-template-columns:36px 1fr;gap:10px;padding:12px;border-radius:20px;background:var(--panel);border:1px solid var(--line);margin-bottom:8px}
.notif-row.unread{border-color:rgba(198,161,91,.5)}
.notif-icon{width:36px;height:36px;border-radius:50%;background:var(--gold2);display:grid;place-items:center;font-size:15px}
.notif-row b{font-size:13px;display:block}
.notif-row p{margin:3px 0 0;font-size:11.5px;color:var(--muted);line-height:1.4}
.notif-row time{font-size:10px;color:var(--muted)}

/* recurring/installment tags in add form */
.check-row{display:flex;align-items:center;justify-content:space-between;padding:12px 4px;gap:10px}
.check-row b{font-size:13px}
.check-row p{margin:2px 0 0;font-size:11.5px;color:var(--muted)}
.inline-num{width:64px !important;min-height:38px !important;text-align:center;padding:0 6px !important}

@media(min-width:760px){
  .fab{right:calc(50% - 210px)}
}
</style>
<body>
<div class="skeleton-overlay" id="skeletonOverlay">
  <div class="skeleton-wrap">
    <div class="sk sk-hero"></div>
    <div class="sk sk-row"></div>
    <div class="sk sk-row"></div>
    <div class="sk sk-row"></div>
  </div>
</div>

<div class="app">
  <header class="topbar">
    <div class="profile">
      <button class="round" id="menuButton" title="Menu">≡</button>
      <div class="avatar" id="avatar">G</div>
      <div>
        <small>controle financeiro</small>
        <strong id="profileName">Guilherme</strong>
      </div>
    </div>
    <div class="top-actions">
      <button class="round" id="privacyButton" title="Ocultar valores">◉</button>
      <button class="round" id="bellButton" title="Notificações">🔔<span class="badge-dot" id="bellBadge">0</span></button>
      <button class="round" id="settingsButton" title="Configurações">⚙</button>
    </div>
  </header>

  <main>
    <section class="screen active" id="dashboardScreen">
      <div class="hero">
        <div class="label">saldo disponível</div>
        <div class="balance" id="balanceText">R$ 0,00</div>
        <div class="hero-row">
          <div class="hero-stat"><small>entradas</small><b id="incomeText">R$ 0,00</b></div>
          <div class="hero-stat"><small>saídas</small><b id="expenseText">R$ 0,00</b></div>
        </div>
      </div>
      <div class="actions-grid">
        <button class="action" data-open-add="expense"><i>−</i><span>Gasto</span></button>
        <button class="action" data-open-add="income"><i>+</i><span>Receita</span></button>
        <button class="action" id="transferButton"><i>⇄</i><span>Transferir</span></button>
        <button class="action" id="themeButton"><i>◐</i><span>Tema</span></button>
      </div>
      <section class="section">
        <div class="section-head"><h2>Seu mês</h2><button class="link" data-route="statistics">Ver análise</button></div>
        <div class="card insight-card">
          <div class="ring" id="mainRing" style="--p:0%"><span id="mainRingText">0%</span></div>
          <div><b id="mainInsightTitle">Tudo no controle</b><p id="mainInsightText">Adicione seus dados para começar.</p></div>
        </div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Contas do mês</h2><button class="link" data-route="planning">Gerenciar</button></div>
        <div class="list" id="dashboardBillsList"></div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Recentes</h2><button class="link" data-route="transactions">Ver tudo</button></div>
        <div class="list" id="recentList"></div>
      </section>
    </section>

    <section class="screen" id="addScreen">
      <section class="section" style="margin-top:6px">
        <div class="section-head"><h2 id="addScreenTitle">Novo lançamento</h2><button class="link" id="quickDemoButton">Exemplo</button></div>
        <form class="form" id="transactionForm">
          <input type="hidden" id="txId" value="" />
          <div class="segment"><button type="button" id="typeExpense" class="active">Gasto</button><button type="button" id="typeIncome">Receita</button></div>
          <div class="field"><label>Descrição</label><input id="txTitle" required placeholder="Mercado, aluguel, salário..." /></div>
          <div class="row">
            <div class="field"><label>Valor</label><input id="txValue" required type="number" step="0.01" min="0.01" placeholder="0,00" /></div>
            <div class="field"><label>Data</label><input id="txDate" type="date" /></div>
          </div>
          <div class="row">
            <div class="field"><label>Categoria</label><select id="txCategory"></select></div>
            <div class="field"><label>Subcategoria</label><select id="txSubcategory"></select></div>
          </div>
          <div class="field"><label>Conta</label><select id="txAccount"></select></div>
          <div class="field"><label>Observação</label><textarea id="txNote" placeholder="Opcional"></textarea></div>

          <div class="card" style="padding:2px 10px">
            <div class="check-row">
              <div><b>Favoritar</b><p>Fixar como lançamento importante.</p></div>
              <button type="button" class="toggle" id="txFavToggle"><i></i></button>
            </div>
            <div class="check-row" style="border-top:1px solid var(--line)">
              <div><b>Repetir mensalmente</b><p>Cria automaticamente todo mês.</p></div>
              <button type="button" class="toggle" id="txRecurringToggle"><i></i></button>
            </div>
            <div class="check-row" style="border-top:1px solid var(--line)">
              <div><b>Parcelar</b><p>Divide em várias parcelas mensais.</p></div>
              <input type="number" min="2" max="24" value="2" class="inline-num" id="txInstallments" disabled />
            </div>
          </div>

          <button class="primary" type="submit" id="txSubmitButton">Salvar lançamento</button>
        </form>
      </section>
      <section class="section">
        <div class="section-head"><h2>Atalhos</h2></div>
        <div class="chips" id="quickChips"></div>
      </section>
    </section>

    <section class="screen" id="transactionsScreen">
      <section class="section" style="margin-top:6px">
        <div class="section-head"><h2>Extrato</h2><button class="link" id="clearFiltersButton">Limpar</button></div>
        <div class="tools">
          <input id="searchInput" placeholder="Buscar..." />
          <select id="sortSelect">
            <option value="newest">Mais recentes</option>
            <option value="oldest">Mais antigos</option>
            <option value="highest">Maior valor</option>
            <option value="lowest">Menor valor</option>
          </select>
        </div>
        <div class="chips" id="filterChips"></div>
      </section>
      <section class="section">
        <div class="list" id="transactionList"></div>
      </section>
    </section>

    <section class="screen" id="statisticsScreen">
      <section class="section" style="margin-top:6px">
        <div class="section-head"><h2>Estatísticas</h2><span class="label" id="periodLabel">este mês</span></div>
        <div class="tabs" id="periodTabs">
          <button data-period="week">Semana</button>
          <button data-period="month" class="active">Mês</button>
          <button data-period="year">Ano</button>
        </div>
      </section>
      <section class="section">
        <div class="card budget-card">
          <div>
            <div class="line-top"><b>Orçamento do período</b><span id="budgetText">R$ 0,00</span></div>
            <div class="track"><div class="fill" id="budgetFill"></div></div>
          </div>
          <div>
            <div class="line-top"><b>Média diária</b><span id="dailyText">R$ 0,00</span></div>
            <div class="track"><div class="fill" id="dailyFill"></div></div>
          </div>
          <div class="compare-row">
            <b>Comparado ao período anterior</b>
            <span class="compare-pill" id="comparePill">—</span>
          </div>
        </div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Fluxo</h2></div>
        <div class="card canvas-box"><canvas id="flowCanvas" width="680" height="280"></canvas></div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Tendência</h2></div>
        <div class="card" style="padding:12px" id="lineChartHost"></div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Por categoria</h2></div>
        <div class="card" id="pieChartHost"></div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Detalhe das categorias</h2></div>
        <div id="categoryAccordion"></div>
      </section>
    </section>

    <section class="screen" id="planningScreen">
      <section class="section" style="margin-top:6px">
        <div class="section-head"><h2>Planejamento</h2><button class="link" id="simulateButton">Simular</button></div>
        <div class="card budget-card">
          <div class="field"><label>Quanto quer guardar?</label><input id="goalInput" type="number" step="10" min="0" /></div>
          <div class="field"><label>Até quando?</label><input id="goalDateInput" type="date" /></div>
          <button class="primary" id="saveGoalButton">Salvar meta</button>
        </div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Contas a pagar</h2><button class="link" id="addBillButton">+ Adicionar</button></div>
        <div class="list" id="billsList"></div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Recorrências ativas</h2></div>
        <div class="list" id="recurringList"></div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Insights</h2></div>
        <div class="list" id="insightsList"></div>
      </section>
    </section>

    <section class="screen" id="calendarScreen">
      <section class="section" style="margin-top:6px">
        <div class="back-row"><button class="back-btn" data-route="dashboard">←</button><h2>Calendário financeiro</h2></div>
        <div class="card" style="padding:14px">
          <div class="cal-head">
            <button id="calPrevButton">‹</button>
            <b id="calMonthLabel">—</b>
            <button id="calNextButton">›</button>
          </div>
          <div class="cal-grid" id="calGrid"></div>
        </div>
      </section>
      <section class="section">
        <div class="section-head"><h2>Resumo do mês</h2></div>
        <div class="card budget-card">
          <div class="line-top"><b>Entradas</b><span id="calIncomeText">R$ 0,00</span></div>
          <div class="line-top"><b>Saídas</b><span id="calExpenseText">R$ 0,00</span></div>
          <div class="line-top"><b>Saldo</b><span id="calBalanceText">R$ 0,00</span></div>
        </div>
      </section>
    </section>

    <section class="screen" id="notificationsScreen">
      <section class="section" style="margin-top:6px">
        <div class="back-row"><button class="back-btn" data-route="dashboard">←</button><h2>Notificações</h2></div>
        <div class="section-head" style="margin-top:-6px"><span class="label">central de avisos</span><button class="link" id="markAllReadButton">Marcar tudo como lido</button></div>
        <div class="list" id="notificationsList"></div>
      </section>
    </section>
  </main>
</div>

<button class="fab" id="fabButton" title="Novo lançamento">＋</button>

<nav class="nav">
  <button class="active" data-route="dashboard"><i>⌂</i><span>Início</span></button>
  <button data-route="transactions"><i>≡</i><span>Extrato</span></button>
  <button data-route="add"><i>＋</i><span>Novo</span></button>
  <button data-route="statistics"><i>⌁</i><span>Análise</span></button>
  <button data-route="planning"><i>◌</i><span>Plano</span></button>
</nav>

<div class="drawer-bg" id="drawerBg">
  <div class="drawer" id="drawer">
    <div class="drawer-profile">
      <div class="avatar" id="drawerAvatar">G</div>
      <div>
        <strong id="drawerName">Guilherme</strong>
        <small id="drawerBalance">R$ 0,00</small>
      </div>
    </div>
    <button class="drawer-link" data-drawer-route="dashboard"><i>⌂</i>Início</button>
    <button class="drawer-link" data-drawer-route="calendar"><i>▦</i>Calendário financeiro</button>
    <button class="drawer-link" data-drawer-route="notifications"><i>🔔</i>Notificações<span class="mini-badge" id="drawerBellBadge" style="display:none">0</span></button>
    <button class="drawer-link" data-drawer-route="planning"><i>◌</i>Contas e metas</button>
    <button class="drawer-link" id="drawerSettingsLink"><i>⚙</i>Ajustes</button>
    <button class="drawer-link" id="drawerBackupLink"><i>↧</i>Backup e exportação</button>
    <button class="drawer-link" id="drawerAboutLink"><i>ℹ</i>Sobre o app</button>
    <div class="drawer-foot">Banco Premium • v<span id="drawerVersion"></span></div>
  </div>
</div>

<div class="sheet-bg" id="settingsSheet">
  <div class="sheet">
    <div class="sheet-head"><h2>Ajustes</h2><button class="close" id="closeSettingsButton">×</button></div>
    <div class="avatar-edit">
      <button class="avatar-big" id="avatarPreviewButton" title="Alterar foto">
        <span id="avatarPreviewInitial">G</span>
        <span class="avatar-edit-badge">✎</span>
      </button>
      <div class="avatar-edit-actions">
        <button class="ghost" id="changePhotoButton">Alterar foto</button>
        <button class="ghost" id="removePhotoButton">Remover</button>
      </div>
      <input type="file" id="avatarInput" accept="image/*" style="display:none" />
    </div>
    <div class="settings">
      <div class="setting"><div><b>Nome</b><p>Mostrado no topo do app.</p></div><input style="width:132px;height:38px;border-radius:999px;text-align:right" id="nameInput" /></div>
      <div class="setting"><div><b>Ocultar valores</b><p>Modo privacidade para abrir em público.</p></div><button class="toggle" id="privacyToggle"><i></i></button></div>
      <div class="setting"><div><b>Tema escuro</b><p>Visual preto premium.</p></div><button class="toggle" id="themeToggle"><i></i></button></div>
      <div class="setting"><div><b>Tema automático</b><p>Segue o sistema do aparelho.</p></div><button class="toggle" id="autoThemeToggle"><i></i></button></div>
      <div class="setting"><div><b>Orçamento</b><p>Limite usado na análise do período.</p></div><input style="width:116px;height:38px;border-radius:999px;text-align:right" id="budgetInput" type="number" min="0" step="50" /></div>
      <div class="setting"><div><b>Backup</b><p>Exporta tudo em JSON.</p></div><button class="ghost" id="backupButton">Backup</button></div>
      <div class="setting"><div><b>Restaurar</b><p>Importa backup JSON.</p></div><button class="ghost" id="importButton">Importar</button></div>
      <div class="setting"><div><b>Exportar CSV</b><p>Extrato completo em planilha.</p></div><button class="ghost" id="exportButton">Exportar</button></div>
      <div class="setting"><div><b>Apagar dados</b><p>Limpa apenas este app.</p></div><button class="ghost" id="resetButton">Resetar</button></div>
    </div>
  </div>
</div>

<div class="sheet-bg" id="txDetailSheet">
  <div class="sheet">
    <div class="sheet-head"><h2>Lançamento</h2><button class="close" id="closeTxDetailButton">×</button></div>
    <div class="list" id="txDetailBody" style="margin-bottom:12px"></div>
    <div class="row">
      <button class="primary" id="txDetailEditButton" style="background:var(--gold2);color:var(--text)">Editar</button>
      <button class="primary" id="txDetailDuplicateButton" style="background:var(--gold2);color:var(--text)">Duplicar</button>
    </div>
    <button class="primary" id="txDetailDeleteButton" style="margin-top:10px;background:var(--red);color:#fff">Excluir</button>
  </div>
</div>

<div class="sheet-bg" id="transferSheet">
  <div class="sheet">
    <div class="sheet-head"><h2>Transferência entre contas</h2><button class="close" id="closeTransferButton">×</button></div>
    <div class="form">
      <div class="row">
        <div class="field"><label>De</label><select id="transferFrom"></select></div>
        <div class="field"><label>Para</label><select id="transferTo"></select></div>
      </div>
      <div class="field"><label>Valor</label><input id="transferValue" type="number" step="0.01" min="0.01" placeholder="0,00" /></div>
      <button class="primary" id="transferSubmitButton">Transferir</button>
    </div>
  </div>
</div>

<div class="sheet-bg" id="billSheet">
  <div class="sheet">
    <div class="sheet-head"><h2>Nova conta a pagar</h2><button class="close" id="closeBillButton">×</button></div>
    <div class="form">
      <div class="field"><label>Descrição</label><input id="billTitle" placeholder="Aluguel, internet..." /></div>
      <div class="row">
        <div class="field"><label>Valor</label><input id="billValue" type="number" step="0.01" min="0.01" placeholder="0,00" /></div>
        <div class="field"><label>Vencimento</label><input id="billDate" type="date" /></div>
      </div>
      <button class="primary" id="billSubmitButton">Salvar conta</button>
    </div>
  </div>
</div>

<div class="sheet-bg" id="dayDetailSheet">
  <div class="sheet">
    <div class="sheet-head"><h2 id="dayDetailTitle">Dia</h2><button class="close" id="closeDayDetailButton">×</button></div>
    <div class="list" id="dayDetailList"></div>
  </div>
</div>

<div class="dialog-bg" id="dialogBg">
  <div class="dialog">
    <h3 id="dialogTitle">Confirmar</h3>
    <p id="dialogText">Tem certeza?</p>
    <div class="dialog-actions" id="dialogActions">
      <button class="dialog-cancel" id="dialogCancelButton">Cancelar</button>
      <button class="dialog-confirm" id="dialogConfirmButton">Confirmar</button>
    </div>
  </div>
</div>

<div class="toast" id="toast">
  <span id="toastText"></span>
  <button class="toast-action" id="toastActionButton" style="display:none"></button>
</div>

<script>
"use strict";

/* =========================================================================
   BANCO PREMIUM — app financeiro
   Arquitetura em módulos (namespaces/classes) dentro de um único arquivo,
   para garantir que o app funcione abrindo o HTML diretamente (file://),
   sem precisar de servidor ou bundler.
   ========================================================================= */

const AppVersion = "4.0.0";
const StorageKeys = Object.freeze({
  txs: "bancoPremium.transactions",
  settings: "bancoPremium.settings",
  recurring: "bancoPremium.recurring",
  bills: "bancoPremium.bills",
  notifications: "bancoPremium.notifications"
});

/* ---------------------------- Dados de referência ---------------------------- */

const CategoryCatalog = Object.freeze({
  food: { id: "food", name: "Alimentação", icon: "🍽️", kind: "expense", subcats: ["Restaurante", "Lanche", "Delivery"] },
  market: { id: "market", name: "Mercado", icon: "🛒", kind: "expense", subcats: ["Supermercado", "Feira", "Padaria"] },
  transport: { id: "transport", name: "Transporte", icon: "🚗", kind: "expense", subcats: ["Combustível", "App de corrida", "Transporte público"] },
  home: { id: "home", name: "Casa", icon: "🏠", kind: "expense", subcats: ["Aluguel", "Manutenção", "Móveis"] },
  bills: { id: "bills", name: "Contas", icon: "🧾", kind: "expense", subcats: ["Luz", "Água", "Internet"] },
  health: { id: "health", name: "Saúde", icon: "💊", kind: "expense", subcats: ["Farmácia", "Consulta", "Plano de saúde"] },
  shopping: { id: "shopping", name: "Compras", icon: "🛍️", kind: "expense", subcats: ["Roupas", "Eletrônicos", "Presentes"] },
  leisure: { id: "leisure", name: "Lazer", icon: "✨", kind: "expense", subcats: ["Streaming", "Cinema", "Viagem"] },
  education: { id: "education", name: "Estudos", icon: "🎓", kind: "expense", subcats: ["Curso", "Livros", "Mensalidade"] },
  work: { id: "work", name: "Trabalho", icon: "💼", kind: "expense", subcats: ["Material", "Software", "Coworking"] },
  income: { id: "income", name: "Receita", icon: "💰", kind: "income", subcats: ["Salário", "Pix", "Freelance"] },
  investment: { id: "investment", name: "Investimento", icon: "📈", kind: "income", subcats: ["Renda fixa", "Ações", "Dividendos"] },
  other: { id: "other", name: "Outros", icon: "•", kind: "both", subcats: ["Diversos"] }
});

const AccountCatalog = Object.freeze([
  { id: "checking", name: "Conta Corrente", icon: "🏦" },
  { id: "wallet", name: "Carteira", icon: "👛" },
  { id: "savings", name: "Poupança", icon: "🐷" }
]);

const QuickTemplates = Object.freeze([
  { title: "Mercado", value: 120, category: "market", type: "expense" },
  { title: "Almoço", value: 28, category: "food", type: "expense" },
  { title: "Uber", value: 34, category: "transport", type: "expense" },
  { title: "Conta de luz", value: 95, category: "bills", type: "expense" },
  { title: "Pix recebido", value: 250, category: "income", type: "income" },
  { title: "Salário", value: 2500, category: "income", type: "income" }
]);

const DefaultSettings = Object.freeze({
  name: "Guilherme",
  theme: "light",
  autoTheme: false,
  hidden: false,
  budget: 1800,
  goal: 500,
  goalDate: "",
  route: "dashboard",
  sort: "newest",
  filter: "all",
  search: "",
  period: "month",
  photo: ""
});

const DemoTransactions = Object.freeze([
  { id: "demo-001", type: "income", title: "Salário", value: 2500, category: "income", subcategory: "Salário", account: "checking", date: todayISO(), note: "Entrada principal", favorite: true },
  { id: "demo-002", type: "expense", title: "Mercado", value: 128.40, category: "market", subcategory: "Supermercado", account: "checking", date: todayISO(), note: "" },
  { id: "demo-003", type: "expense", title: "Transporte", value: 36.00, category: "transport", subcategory: "App de corrida", account: "wallet", date: todayISO(), note: "" },
  { id: "demo-004", type: "expense", title: "Almoço", value: 28.00, category: "food", subcategory: "Restaurante", account: "wallet", date: todayISO(), note: "" }
]);

const DemoBills = Object.freeze([
  { id: "bill-001", title: "Internet", value: 99.9, dueDate: addDaysISO(todayISO(), 4), paid: false },
  { id: "bill-002", title: "Aluguel", value: 1200, dueDate: addDaysISO(todayISO(), 9), paid: false }
]);

/* ---------------------------------- Utils ---------------------------------- */

function $(selector) { return document.querySelector(selector); }
function $all(selector) { return Array.from(document.querySelectorAll(selector)); }
function byId(id) { return document.getElementById(id); }
function clamp(value, min, max) { return Math.max(min, Math.min(max, value)); }

function safeNumber(value, fallback = 0) {
  const parsed = Number(value);
  return Number.isFinite(parsed) ? parsed : fallback;
}

function todayISO() { return new Date().toISOString().slice(0, 10); }

function addDaysISO(date, days) {
  const d = new Date(date + "T12:00:00");
  d.setDate(d.getDate() + days);
  return d.toISOString().slice(0, 10);
}

function addMonthsISO(date, months) {
  const d = new Date(date + "T12:00:00");
  d.setMonth(d.getMonth() + months);
  return d.toISOString().slice(0, 10);
}

function monthKey(date = todayISO()) {
  const d = new Date(date + "T12:00:00");
  return `${d.getFullYear()}-${String(d.getMonth() + 1).padStart(2, "0")}`;
}

function yearKey(date = todayISO()) {
  return String(new Date(date + "T12:00:00").getFullYear());
}

function weekKey(date = todayISO()) {
  const d = new Date(date + "T12:00:00");
  const onejan = new Date(d.getFullYear(), 0, 1);
  const week = Math.ceil((((d - onejan) / 86400000) + onejan.getDay() + 1) / 7);
  return `${d.getFullYear()}-W${week}`;
}

function monthName(date = new Date()) {
  return date.toLocaleDateString("pt-BR", { month: "long", year: "numeric" });
}

function daysInMonth(year, month) { return new Date(year, month + 1, 0).getDate(); }
function daysInCurrentMonth() { const n = new Date(); return daysInMonth(n.getFullYear(), n.getMonth()); }
function currentDayOfMonth() { return new Date().getDate(); }
function remainingDaysInMonth() { return Math.max(1, daysInCurrentMonth() - currentDayOfMonth() + 1); }

function formatDateBR(iso) {
  const d = new Date(`${iso}T12:00:00`);
  return d.toLocaleDateString("pt-BR", { day: "2-digit", month: "short" });
}

function formatDateLongBR(iso) {
  const d = new Date(`${iso}T12:00:00`);
  return d.toLocaleDateString("pt-BR", { day: "2-digit", month: "long", year: "numeric" });
}

function escapeHTML(value) {
  return String(value).replace(/[&<>"']/g, char => ({
    "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;", "'": "&#039;"
  }[char]));
}

function uid(prefix = "id") {
  return `${prefix}-${Date.now().toString(36)}-${Math.random().toString(36).slice(2, 9)}`;
}

function clone(value) { return JSON.parse(JSON.stringify(value)); }

function downloadFile(filename, content, type) {
  const blob = new Blob([content], { type });
  const url = URL.createObjectURL(blob);
  const anchor = document.createElement("a");
  anchor.href = url;
  anchor.download = filename;
  anchor.click();
  URL.revokeObjectURL(url);
}

function moneyRaw(value) {
  return new Intl.NumberFormat("pt-BR", { style: "currency", currency: "BRL" }).format(value || 0);
}

function debounce(fn, wait = 220) {
  let timer = null;
  return (...args) => {
    clearTimeout(timer);
    timer = setTimeout(() => fn(...args), wait);
  };
}

function throttle(fn, wait = 120) {
  let last = 0;
  let queued = null;
  return (...args) => {
    const now = Date.now();
    if (now - last >= wait) {
      last = now;
      fn(...args);
    } else {
      clearTimeout(queued);
      queued = setTimeout(() => { last = Date.now(); fn(...args); }, wait - (now - last));
    }
  };
}

/* --------------------------------- EventBus --------------------------------- */

const EventBus = {
  events: new Map(),
  on(name, handler) {
    if (!this.events.has(name)) this.events.set(name, []);
    this.events.get(name).push(handler);
    return () => this.off(name, handler);
  },
  off(name, handler) {
    const list = this.events.get(name) || [];
    this.events.set(name, list.filter(item => item !== handler));
  },
  emit(name, payload) {
    (this.events.get(name) || []).forEach(handler => handler(payload));
  }
};

/* --------------------------------- Storage --------------------------------- */

const Storage = {
  read(key, fallback) {
    try {
      const raw = localStorage.getItem(key);
      if (!raw) return clone(fallback);
      return JSON.parse(raw);
    } catch (error) {
      console.warn("Storage read error", error);
      return clone(fallback);
    }
  },
  write(key, value) {
    try {
      localStorage.setItem(key, JSON.stringify(value));
      return true;
    } catch (error) {
      console.warn("Storage write error", error);
      return false;
    }
  },
  clearApp() {
    Object.values(StorageKeys).forEach(key => localStorage.removeItem(key));
  }
};

/* ---------------------------------- State ---------------------------------- */

const State = {
  settings: Storage.read(StorageKeys.settings, DefaultSettings),
  txs: Storage.read(StorageKeys.txs, DemoTransactions),
  recurring: Storage.read(StorageKeys.recurring, []),
  bills: Storage.read(StorageKeys.bills, DemoBills),
  notifications: Storage.read(StorageKeys.notifications, []),
  route: "dashboard",
  previousRoute: "dashboard",
  type: "expense",
  editingId: null,
  listeners: [],

  hydrate() {
    this.settings = { ...DefaultSettings, ...this.settings };
    if (!Array.isArray(this.txs)) this.txs = clone(DemoTransactions);
    if (!Array.isArray(this.recurring)) this.recurring = [];
    if (!Array.isArray(this.bills)) this.bills = clone(DemoBills);
    if (!Array.isArray(this.notifications)) this.notifications = [];
    this.route = this.settings.route || "dashboard";
    this.type = "expense";
  },
  save() {
    Storage.write(StorageKeys.settings, this.settings);
    Storage.write(StorageKeys.txs, this.txs);
    Storage.write(StorageKeys.recurring, this.recurring);
    Storage.write(StorageKeys.bills, this.bills);
    Storage.write(StorageKeys.notifications, this.notifications);
  },
  notify(reason = "state") {
    this.save();
    this.listeners.forEach(fn => fn(reason));
    EventBus.emit("state:change", reason);
  },
  subscribe(fn) {
    this.listeners.push(fn);
    return () => { this.listeners = this.listeners.filter(item => item !== fn); };
  },
  setSetting(key, value) { this.settings[key] = value; this.notify(`setting:${key}`); },
  setRoute(route) {
    if (route !== this.route) this.previousRoute = this.route;
    this.route = route;
    this.settings.route = route;
    this.notify("route");
  },
  setType(type) { this.type = type; this.notify("type"); },
  setSearch(value) { this.settings.search = value; this.notify("search"); },
  setFilter(value) { this.settings.filter = value; this.notify("filter"); },
  setSort(value) { this.settings.sort = value; this.notify("sort"); },
  setPeriod(value) { this.settings.period = value; this.notify("period"); },
  addTransaction(tx) { this.txs.unshift(tx); this.notify("transaction:add"); },
  updateTransaction(id, patch) {
    this.txs = this.txs.map(tx => tx.id === id ? { ...tx, ...patch } : tx);
    this.notify("transaction:update");
  },
  removeTransaction(id) {
    this.txs = this.txs.filter(tx => tx.id !== id);
    this.notify("transaction:remove");
  },
  replaceTransactions(txs) { this.txs = txs; this.notify("transaction:replace"); }
};

/* --------------------------------- Currency --------------------------------- */

const CountUp = {
  cache: new Map(),
  to(el, targetValue) {
    if (!el) return;
    if (State.settings.hidden) { el.textContent = "••••"; this.cache.set(el, targetValue); return; }
    const from = this.cache.has(el) ? this.cache.get(el) : targetValue;
    this.cache.set(el, targetValue);
    if (Math.abs(targetValue - from) < 0.01) { el.textContent = moneyRaw(targetValue); return; }
    const duration = 520;
    const start = performance.now();
    const ease = t => 1 - Math.pow(1 - t, 3);
    const step = now => {
      const t = clamp((now - start) / duration, 0, 1);
      const value = from + (targetValue - from) * ease(t);
      el.textContent = moneyRaw(value);
      if (t < 1) requestAnimationFrame(step);
      else el.textContent = moneyRaw(targetValue);
    };
    requestAnimationFrame(step);
  }
};

const Currency = {
  format(value) {
    if (State.settings.hidden) return "••••";
    return moneyRaw(value);
  },
  signed(type, value) {
    const sign = type === "income" ? "+" : "−";
    return `${sign} ${this.format(value)}`;
  },
  parse(value) {
    if (typeof value === "number") return safeNumber(value);
    return safeNumber(String(value).replace(/\./g, "").replace(",", "."));
  }
};

/* ------------------------------ CategoryService ------------------------------ */

const CategoryService = {
  list() { return Object.values(CategoryCatalog); },
  get(id) { return CategoryCatalog[id] || CategoryCatalog.other; },
  expenseCategories() { return this.list().filter(cat => cat.kind !== "income"); },
  incomeCategories() { return this.list().filter(cat => cat.kind !== "expense"); },
  options(type) {
    const items = type === "income" ? this.incomeCategories() : this.expenseCategories();
    return items.map(cat => `<option value="${cat.id}">${cat.icon} ${cat.name}</option>`).join("");
  },
  subcategoryOptions(categoryId) {
    const cat = this.get(categoryId);
    return (cat.subcats || []).map(name => `<option value="${escapeHTML(name)}">${escapeHTML(name)}</option>`).join("");
  },
  detectByTitle(title, type) {
    const text = String(title).toLowerCase();
    if (type === "income") return "income";
    if (text.includes("mercado")) return "market";
    if (text.includes("uber") || text.includes("ônibus") || text.includes("metro") || text.includes("transporte")) return "transport";
    if (text.includes("almoço") || text.includes("lanche") || text.includes("ifood") || text.includes("comida")) return "food";
    if (text.includes("luz") || text.includes("água") || text.includes("internet") || text.includes("conta")) return "bills";
    if (text.includes("farmácia") || text.includes("remédio") || text.includes("saúde")) return "health";
    if (text.includes("roupa") || text.includes("shopping") || text.includes("compra")) return "shopping";
    return "other";
  }
};

/* ------------------------------- AccountService ------------------------------- */

const AvatarService = {
  maxSize: 240,
  fromFile(file) {
    return new Promise((resolve, reject) => {
      if (!file || !file.type.startsWith("image/")) { reject(new Error("Escolha um arquivo de imagem.")); return; }
      const reader = new FileReader();
      reader.onerror = () => reject(new Error("Não foi possível ler a imagem."));
      reader.onload = () => {
        const img = new Image();
        img.onerror = () => reject(new Error("Não foi possível abrir a imagem."));
        img.onload = () => {
          try { resolve(this.crop(img)); }
          catch (error) { reject(error); }
        };
        img.src = reader.result;
      };
      reader.readAsDataURL(file);
    });
  },
  crop(img) {
    const size = this.maxSize;
    const canvas = document.createElement("canvas");
    canvas.width = size; canvas.height = size;
    const ctx = canvas.getContext("2d");
    const side = Math.min(img.width, img.height);
    const sx = (img.width - side) / 2;
    const sy = (img.height - side) / 2;
    ctx.drawImage(img, sx, sy, side, side, 0, 0, size, size);
    return canvas.toDataURL("image/jpeg", 0.86);
  },
  apply(elements) {
    const photo = State.settings.photo;
    elements.forEach(el => {
      if (!el) return;
      if (photo) {
        el.style.backgroundImage = `url(${photo})`;
        el.classList.add("has-photo");
      } else {
        el.style.backgroundImage = "";
        el.classList.remove("has-photo");
      }
    });
  }
};

const AccountService = {
  list() { return AccountCatalog; },
  get(id) { return AccountCatalog.find(acc => acc.id === id) || AccountCatalog[0]; },
  options() {
    return this.list().map(acc => `<option value="${acc.id}">${acc.icon} ${acc.name}</option>`).join("");
  },
  balance(id) {
    return TransactionService.all()
      .filter(tx => tx.account === id)
      .reduce((sum, tx) => sum + (tx.type === "income" ? tx.value : -tx.value), 0);
  }
};

/* ----------------------------- TransactionService ----------------------------- */

const TransactionService = {
  normalize(input) {
    const type = ["income", "expense", "transfer"].includes(input.type) ? input.type : "expense";
    const value = Math.abs(Currency.parse(input.value));
    return {
      id: input.id || uid("tx"),
      type,
      title: String(input.title || "Sem descrição").trim(),
      value,
      category: input.category || CategoryService.detectByTitle(input.title, type),
      subcategory: input.subcategory || "",
      account: input.account || "checking",
      date: input.date || todayISO(),
      note: String(input.note || "").trim(),
      favorite: !!input.favorite,
      recurringId: input.recurringId || null,
      installmentGroup: input.installmentGroup || null,
      installmentLabel: input.installmentLabel || "",
      createdAt: input.createdAt || new Date().toISOString()
    };
  },
  add(input) {
    const tx = this.normalize(input);
    if (!tx.title) throw new Error("Digite uma descrição.");
    if (tx.value <= 0) throw new Error("Digite um valor válido.");
    State.addTransaction(tx);
    Snackbar.show("Lançamento salvo");
    return tx;
  },
  addWithInstallments(input, installments) {
    const n = clamp(Math.round(installments), 2, 24);
    const groupId = uid("group");
    const perValue = Math.round((Currency.parse(input.value) / n) * 100) / 100;
    const created = [];
    for (let i = 0; i < n; i++) {
      const tx = this.normalize({
        ...input,
        id: uid("tx"),
        value: perValue,
        date: addMonthsISO(input.date || todayISO(), i),
        installmentGroup: groupId,
        installmentLabel: `${i + 1}/${n}`
      });
      created.push(tx);
    }
    State.txs.unshift(...created.reverse());
    State.notify("transaction:installments");
    Snackbar.show(`Lançamento parcelado em ${n}x`);
    return created;
  },
  update(id, patch) {
    State.updateTransaction(id, this.normalize({ ...this.byId(id), ...patch, id }));
    Snackbar.show("Lançamento atualizado");
  },
  remove(id) {
    const removed = State.txs.find(tx => tx.id === id);
    State.removeTransaction(id);
    if (removed) {
      Snackbar.show("Lançamento removido", "Desfazer", () => {
        State.addTransaction(removed);
      });
    }
  },
  duplicate(id) {
    const original = this.byId(id);
    if (!original) return;
    const copy = this.normalize({ ...original, id: null, date: todayISO(), createdAt: null, installmentGroup: null, installmentLabel: "" });
    copy.title = `${copy.title} (cópia)`;
    State.addTransaction(copy);
    Snackbar.show("Lançamento duplicado");
  },
  toggleFavorite(id) {
    const tx = this.byId(id);
    if (!tx) return;
    State.updateTransaction(id, { favorite: !tx.favorite });
  },
  byId(id) { return State.txs.find(tx => tx.id === id); },
  all() { return State.txs.map(tx => this.normalize(tx)); },
  currentMonth() {
    const key = monthKey();
    return this.all().filter(tx => monthKey(tx.date) === key);
  },
  byPeriod(period = State.settings.period || "month") {
    const all = this.all();
    if (period === "week") {
      const key = weekKey();
      return all.filter(tx => weekKey(tx.date) === key);
    }
    if (period === "year") {
      const key = yearKey();
      return all.filter(tx => yearKey(tx.date) === key);
    }
    const key = monthKey();
    return all.filter(tx => monthKey(tx.date) === key);
  },
  byPreviousPeriod(period = State.settings.period || "month") {
    const all = this.all();
    if (period === "week") {
      const key = weekKey(addDaysISO(todayISO(), -7));
      return all.filter(tx => weekKey(tx.date) === key);
    }
    if (period === "year") {
      const key = String(Number(yearKey()) - 1);
      return all.filter(tx => yearKey(tx.date) === key);
    }
    const key = monthKey(addMonthsISO(todayISO(), -1));
    return all.filter(tx => monthKey(tx.date) === key);
  },
  income(list = this.currentMonth()) {
    return list.filter(tx => tx.type === "income").reduce((sum, tx) => sum + tx.value, 0);
  },
  expense(list = this.currentMonth()) {
    return list.filter(tx => tx.type === "expense").reduce((sum, tx) => sum + tx.value, 0);
  },
  balance(list = this.currentMonth()) { return this.income(list) - this.expense(list); },
  byCategory(list = this.currentMonth()) {
    const grouped = {};
    list.filter(tx => tx.type === "expense").forEach(tx => {
      grouped[tx.category] = (grouped[tx.category] || 0) + tx.value;
    });
    return Object.entries(grouped).sort((a, b) => b[1] - a[1]);
  },
  lastDays(days = 14) {
    const result = [];
    for (let i = days - 1; i >= 0; i--) {
      const iso = addDaysISO(todayISO(), -i);
      const dayTxs = this.all().filter(tx => tx.date === iso);
      result.push({ date: iso, income: this.income(dayTxs), expense: this.expense(dayTxs) });
    }
    return result;
  },
  trendSeries(period = State.settings.period || "month") {
    if (period === "week") {
      return this.lastDays(7).map(d => ({ label: formatDateBR(d.date), value: d.income - d.expense }));
    }
    if (period === "year") {
      const result = [];
      for (let i = 11; i >= 0; i--) {
        const iso = addMonthsISO(todayISO(), -i);
        const key = monthKey(iso);
        const list = this.all().filter(tx => monthKey(tx.date) === key);
        result.push({ label: new Date(iso + "T12:00:00").toLocaleDateString("pt-BR", { month: "short" }), value: this.balance(list) });
      }
      return result;
    }
    return this.lastDays(30).filter((_, i) => i % 3 === 0).map(d => ({ label: formatDateBR(d.date), value: d.income - d.expense }));
  },
  filtered() {
    let list = this.all();
    const filter = State.settings.filter || "all";
    const search = String(State.settings.search || "").trim().toLowerCase();
    const sort = State.settings.sort || "newest";
    if (filter !== "all") {
      if (filter === "favorite") list = list.filter(tx => tx.favorite);
      else if (filter === "income" || filter === "expense" || filter === "transfer") list = list.filter(tx => tx.type === filter);
      else list = list.filter(tx => tx.category === filter);
    }
    if (search) {
      list = list.filter(tx => {
        const cat = CategoryService.get(tx.category).name.toLowerCase();
        const haystack = `${tx.title} ${cat} ${tx.note}`.toLowerCase();
        return haystack.includes(search);
      });
    }
    if (sort === "newest") list.sort((a, b) => new Date(b.date) - new Date(a.date));
    if (sort === "oldest") list.sort((a, b) => new Date(a.date) - new Date(b.date));
    if (sort === "highest") list.sort((a, b) => b.value - a.value);
    if (sort === "lowest") list.sort((a, b) => a.value - b.value);
    return list;
  },
  transfer(fromAccount, toAccount, value, date = todayISO()) {
    const v = Math.abs(Currency.parse(value));
    if (fromAccount === toAccount) throw new Error("Escolha contas diferentes.");
    if (v <= 0) throw new Error("Digite um valor válido.");
    const groupId = uid("transfer");
    const out = this.normalize({ type: "transfer", title: `Transferência para ${AccountService.get(toAccount).name}`, value: v, account: fromAccount, category: "other", date, installmentGroup: groupId });
    const inn = this.normalize({ type: "transfer", title: `Transferência de ${AccountService.get(fromAccount).name}`, value: v, account: toAccount, category: "other", date, installmentGroup: groupId });
    State.txs.unshift(inn, out);
    State.notify("transaction:transfer");
    Snackbar.show("Transferência realizada");
  }
};

/* -------------------------------- RecurringService -------------------------------- */

const RecurringService = {
  list() { return State.recurring; },
  add(template) {
    const item = {
      id: uid("rec"),
      title: template.title,
      value: template.value,
      type: template.type,
      category: template.category,
      subcategory: template.subcategory || "",
      account: template.account || "checking",
      lastRun: monthKey(template.date || todayISO())
    };
    State.recurring.push(item);
    State.notify("recurring:add");
  },
  remove(id) {
    State.recurring = State.recurring.filter(item => item.id !== id);
    State.notify("recurring:remove");
  },
  runDue() {
    const key = monthKey();
    let created = 0;
    State.recurring.forEach(item => {
      if (item.lastRun === key) return;
      const tx = TransactionService.normalize({
        title: item.title, value: item.value, type: item.type, category: item.category,
        subcategory: item.subcategory, account: item.account, date: todayISO(), recurringId: item.id,
        note: "Lançamento recorrente automático"
      });
      State.txs.unshift(tx);
      item.lastRun = key;
      created++;
    });
    if (created > 0) {
      NotificationService.push({
        title: "Lançamentos recorrentes criados",
        text: `${created} lançamento(s) recorrente(s) foram adicionados automaticamente este mês.`,
        icon: "↻"
      });
      State.notify("recurring:run");
    }
  }
};

/* ----------------------------------- BillService ----------------------------------- */

const BillService = {
  list() { return State.bills.slice().sort((a, b) => new Date(a.dueDate) - new Date(b.dueDate)); },
  upcoming() { return this.list().filter(bill => !bill.paid); },
  add(input) {
    const bill = {
      id: uid("bill"),
      title: String(input.title || "Conta").trim(),
      value: Math.abs(Currency.parse(input.value)),
      dueDate: input.dueDate || todayISO(),
      paid: false
    };
    if (!bill.title) throw new Error("Digite uma descrição.");
    if (bill.value <= 0) throw new Error("Digite um valor válido.");
    State.bills.push(bill);
    State.notify("bill:add");
    Snackbar.show("Conta adicionada");
  },
  markPaid(id) {
    const bill = State.bills.find(item => item.id === id);
    if (!bill) return;
    bill.paid = true;
    TransactionService.add({ title: bill.title, value: bill.value, type: "expense", category: "bills", date: todayISO(), note: "Conta paga" });
    State.notify("bill:paid");
  },
  remove(id) {
    State.bills = State.bills.filter(item => item.id !== id);
    State.notify("bill:remove");
  },
  status(bill) {
    if (bill.paid) return "paid";
    const days = Math.ceil((new Date(bill.dueDate + "T12:00:00") - new Date(todayISO() + "T12:00:00")) / 86400000);
    if (days < 0) return "late";
    if (days <= 3) return "soon";
    return "ok";
  },
  checkReminders() {
    this.upcoming().forEach(bill => {
      const status = this.status(bill);
      if (status === "late" || status === "soon") {
        const flag = `bill-notif-${bill.id}-${todayISO()}`;
        if (State.notifications.some(n => n.flag === flag)) return;
        NotificationService.push({
          title: status === "late" ? "Conta atrasada" : "Conta vence em breve",
          text: `${bill.title} • ${Currency.format(bill.value)} • vencimento ${formatDateBR(bill.dueDate)}`,
          icon: status === "late" ? "⚠" : "⏰",
          flag
        });
      }
    });
  }
};

/* -------------------------------- NotificationService -------------------------------- */

const NotificationService = {
  push(item) {
    State.notifications.unshift({
      id: uid("notif"),
      title: item.title,
      text: item.text,
      icon: item.icon || "🔔",
      flag: item.flag || null,
      read: false,
      createdAt: new Date().toISOString()
    });
    State.notifications = State.notifications.slice(0, 60);
    State.notify("notification:push");
  },
  list() { return State.notifications; },
  unreadCount() { return State.notifications.filter(n => !n.read).length; },
  markRead(id) {
    State.notifications = State.notifications.map(n => n.id === id ? { ...n, read: true } : n);
    State.notify("notification:read");
  },
  markAllRead() {
    State.notifications = State.notifications.map(n => ({ ...n, read: true }));
    State.notify("notification:readall");
  }
};

/* ---------------------------------- BudgetService ---------------------------------- */

const BudgetService = {
  budget() { return safeNumber(State.settings.budget, 0); },
  spent(list = TransactionService.byPeriod()) { return TransactionService.expense(list); },
  left() { return Math.max(0, this.budget() - this.spent()); },
  percent() {
    const budget = this.budget();
    if (!budget) return 0;
    return clamp((this.spent() / budget) * 100, 0, 999);
  },
  dailyAverage() { return this.spent() / Math.max(1, currentDayOfMonth()); },
  safeDaily() { return this.left() / remainingDaysInMonth(); },
  status() {
    const pct = this.percent();
    if (pct >= 100) return "danger";
    if (pct >= 80) return "warning";
    return "good";
  }
};

/* ----------------------------------- GoalService ----------------------------------- */

const GoalService = {
  goal() { return safeNumber(State.settings.goal, 0); },
  date() { return State.settings.goalDate || ""; },
  daysLeft() {
    const goalDate = this.date();
    if (!goalDate) return 30;
    const today = new Date(todayISO() + "T12:00:00");
    const goal = new Date(goalDate + "T12:00:00");
    return Math.max(1, Math.ceil((goal - today) / 86400000));
  },
  dailyNeed() { return this.goal() / Math.max(1, this.daysLeft()); },
  progress() {
    const balance = TransactionService.balance();
    const target = Math.max(1, this.goal());
    return clamp((balance / target) * 100, 0, 100);
  }
};

/* ---------------------------------- InsightEngine ---------------------------------- */

const InsightEngine = {
  build() {
    const insights = [];
    const spent = BudgetService.spent();
    const budget = BudgetService.budget();
    const pct = BudgetService.percent();
    const safe = BudgetService.safeDaily();
    const avg = BudgetService.dailyAverage();
    const balance = TransactionService.balance();
    const byCat = TransactionService.byCategory();

    if (pct >= 100) {
      insights.push({ title: "Orçamento passou", text: `Você passou do orçamento em ${Currency.format(spent - budget)}.`, icon: "!" });
    } else if (pct >= 80) {
      insights.push({ title: "Atenção no mês", text: `Você já usou ${Math.round(pct)}% do orçamento. Pode gastar ${Currency.format(safe)} por dia.`, icon: "!" });
    } else {
      insights.push({ title: "Ritmo saudável", text: `Você ainda tem ${Currency.format(BudgetService.left())} livres no orçamento.`, icon: "✓" });
    }
    insights.push({ title: "Média diária", text: `Sua média diária de gastos é ${Currency.format(avg)}.`, icon: "⌁" });
    if (balance > 0) {
      insights.push({ title: "Saldo positivo", text: `Sobraram ${Currency.format(balance)} no mês atual.`, icon: "+" });
    } else if (balance < 0) {
      insights.push({ title: "Saldo negativo", text: `O mês está negativo em ${Currency.format(Math.abs(balance))}.`, icon: "−" });
    }
    if (byCat[0]) {
      const cat = CategoryService.get(byCat[0][0]);
      insights.push({ title: "Maior categoria", text: `${cat.name} lidera com ${Currency.format(byCat[0][1])}.`, icon: cat.icon });
    }
    const late = BillService.upcoming().filter(b => BillService.status(b) === "late");
    if (late.length) {
      insights.push({ title: "Contas atrasadas", text: `Você tem ${late.length} conta(s) vencida(s) para regularizar.`, icon: "⚠" });
    }
    insights.push({ title: "Meta", text: `Para guardar ${Currency.format(GoalService.goal())}, separe ${Currency.format(GoalService.dailyNeed())} por dia.`, icon: "◌" });
    return insights;
  },
  main() {
    const list = this.build();
    return list[0] || { title: "Tudo pronto", text: "Comece adicionando lançamentos.", icon: "✓" };
  }
};

/* ------------------------------------------------------------------------------- */
/*  Componentes de UI reutilizáveis                                                */
/* ------------------------------------------------------------------------------- */

const Snackbar = {
  timer: null,
  show(message, actionLabel = "", onAction = null) {
    const el = byId("toast");
    const text = byId("toastText");
    const action = byId("toastActionButton");
    text.textContent = message;
    if (actionLabel && onAction) {
      action.textContent = actionLabel;
      action.style.display = "block";
      action.onclick = () => { onAction(); el.classList.remove("show"); };
    } else {
      action.style.display = "none";
      action.onclick = null;
    }
    el.classList.add("show");
    clearTimeout(this.timer);
    this.timer = setTimeout(() => el.classList.remove("show"), 3200);
  }
};
// Compatibilidade com nome anterior
const Toast = Snackbar;

const Dialog = {
  resolver: null,
  ask(title, text, confirmLabel = "Confirmar", tone = "danger") {
    byId("dialogTitle").textContent = title;
    byId("dialogText").textContent = text;
    const confirmBtn = byId("dialogConfirmButton");
    confirmBtn.textContent = confirmLabel;
    confirmBtn.className = `dialog-confirm ${tone === "neutral" ? "neutral" : ""}`;
    byId("dialogCancelButton").style.display = tone === "neutral" ? "none" : "block";
    byId("dialogActions").classList.toggle("single", tone === "neutral");
    byId("dialogBg").classList.add("show");
    return new Promise(resolve => { this.resolver = resolve; });
  },
  resolve(value) {
    byId("dialogBg").classList.remove("show");
    if (this.resolver) { this.resolver(value); this.resolver = null; }
  }
};

const Sheet = {
  open(id) { byId(id).classList.add("show"); },
  close(id) { byId(id).classList.remove("show"); },
  bindBackdrop(id) {
    byId(id).addEventListener("click", event => {
      if (event.target.id === id) this.close(id);
    });
  }
};

const Drawer = {
  open() { byId("drawerBg").classList.add("show"); },
  close() { byId("drawerBg").classList.remove("show"); }
};

const Accordion = {
  init(container) {
    container.addEventListener("click", event => {
      const head = event.target.closest("[data-accordion-toggle]");
      if (!head) return;
      head.closest(".accordion-item").classList.toggle("open");
    });
  }
};

const Tabs = {
  init(container, onChange) {
    container.addEventListener("click", event => {
      const btn = event.target.closest("button[data-tab]");
      if (!btn) return;
      $all("button", container).forEach(b => b.classList.remove("active"));
      btn.classList.add("active");
      onChange(btn.dataset.tab);
    });
  }
};

const Skeleton = {
  hide() {
    setTimeout(() => byId("skeletonOverlay").classList.add("hide"), 420);
  }
};

/* ------------------------------------------------------------------------------- */
/*  Serviços de dados auxiliares (CSV / Backup)                                     */
/* ------------------------------------------------------------------------------- */

const CsvService = {
  export() {
    const header = "tipo,titulo,valor,categoria,subcategoria,conta,data,observacao\n";
    const rows = TransactionService.all().map(tx => [
      tx.type,
      `"${String(tx.title).replaceAll('"', '""')}"`,
      tx.value,
      CategoryService.get(tx.category).name,
      tx.subcategory || "",
      AccountService.get(tx.account).name,
      tx.date,
      `"${String(tx.note || "").replaceAll('"', '""')}"`
    ].join(","));
    downloadFile("extrato-financeiro.csv", header + rows.join("\n"), "text/csv;charset=utf-8");
    Snackbar.show("CSV exportado");
  }
};

const BackupService = {
  createPayload() {
    return {
      version: AppVersion,
      exportedAt: new Date().toISOString(),
      settings: clone(State.settings),
      transactions: clone(State.txs),
      recurring: clone(State.recurring),
      bills: clone(State.bills)
    };
  },
  export() {
    const payload = JSON.stringify(this.createPayload(), null, 2);
    downloadFile("backup-financeiro.json", payload, "application/json;charset=utf-8");
    Snackbar.show("Backup gerado");
  },
  importText(text) {
    const data = JSON.parse(text);
    if (!Array.isArray(data.transactions)) throw new Error("Backup inválido.");
    State.settings = { ...DefaultSettings, ...(data.settings || {}) };
    State.replaceTransactions(data.transactions.map(tx => TransactionService.normalize(tx)));
    State.recurring = Array.isArray(data.recurring) ? data.recurring : [];
    State.bills = Array.isArray(data.bills) ? data.bills : [];
    State.notify("backup:import");
    Snackbar.show("Backup importado");
  },
  askImport() {
    const input = document.createElement("input");
    input.type = "file";
    input.accept = "application/json,.json";
    input.addEventListener("change", async () => {
      const file = input.files[0];
      if (!file) return;
      try {
        const text = await file.text();
        this.importText(text);
      } catch (error) {
        Snackbar.show("Não foi possível importar");
      }
    });
    input.click();
  }
};

/* ------------------------------------------------------------------------------- */
/*  Roteamento                                                                      */
/* ------------------------------------------------------------------------------- */

const Router = {
  routes: ["dashboard", "transactions", "add", "statistics", "planning", "calendar", "notifications"],
  bottomNavRoutes: ["dashboard", "transactions", "add", "statistics", "planning"],
  go(route) {
    if (!this.routes.includes(route)) return;
    State.setRoute(route);
  },
  back() { this.go(State.previousRoute || "dashboard"); },
  render() {
    const route = State.route || "dashboard";
    $all(".screen").forEach(screen => screen.classList.remove("active"));
    const screen = byId(`${route}Screen`);
    if (screen) screen.classList.add("active");
    $all("[data-route]").forEach(btn => btn.classList.toggle("active", btn.dataset.route === route));
    byId("fabButton").style.display = this.bottomNavRoutes.includes(route) && route !== "add" ? "grid" : "none";
    window.scrollTo({ top: 0, behavior: "smooth" });
  }
};

/* ------------------------------------------------------------------------------- */
/*  Gráficos                                                                        */
/* ------------------------------------------------------------------------------- */

const ChartRenderer = {
  drawFlow() {
    const canvas = byId("flowCanvas");
    if (!canvas) return;
    const ctx = canvas.getContext && canvas.getContext("2d");
    if (!ctx) return;
    const width = canvas.width;
    const height = canvas.height;
    ctx.clearRect(0, 0, width, height);
    const days = TransactionService.lastDays(14);
    const max = Math.max(100, ...days.map(day => Math.max(day.income, day.expense)));
    const pad = 28;
    const base = height - 34;
    const gap = (width - pad * 2) / days.length;
    const styles = getComputedStyle(document.documentElement);
    ctx.strokeStyle = styles.getPropertyValue("--line").trim();
    ctx.lineWidth = 1;
    for (let i = 0; i < 4; i++) {
      const y = 24 + i * 54;
      ctx.beginPath();
      ctx.moveTo(pad, y);
      ctx.lineTo(width - pad, y);
      ctx.stroke();
    }
    days.forEach((day, index) => {
      const x = pad + index * gap + gap / 2;
      const expenseHeight = (day.expense / max) * 160;
      const incomeHeight = (day.income / max) * 160;
      ctx.fillStyle = styles.getPropertyValue("--red").trim();
      this.roundRect(ctx, x - 8, base - expenseHeight, 7, expenseHeight, 4);
      ctx.fill();
      ctx.fillStyle = styles.getPropertyValue("--green").trim();
      this.roundRect(ctx, x + 1, base - incomeHeight, 7, incomeHeight, 4);
      ctx.fill();
    });
    if (days.every(day => day.expense === 0 && day.income === 0)) {
      ctx.fillStyle = styles.getPropertyValue("--muted").trim();
      ctx.font = "22px -apple-system, BlinkMacSystemFont, Segoe UI";
      ctx.textAlign = "center";
      ctx.fillText("Sem dados", width / 2, height / 2);
    }
  },
  roundRect(ctx, x, y, width, height, radius) {
    if (height <= 0) return;
    ctx.beginPath();
    ctx.moveTo(x + radius, y);
    ctx.arcTo(x + width, y, x + width, y + height, radius);
    ctx.arcTo(x + width, y + height, x, y + height, radius);
    ctx.arcTo(x, y + height, x, y, radius);
    ctx.arcTo(x, y, x + width, y, radius);
    ctx.closePath();
  }
};

const PieChart = {
  palette: ["#c6a15b", "#3a72e8", "#14905f", "#d98b24", "#cc4049", "#9a6fd8", "#2ba7a0", "#b56ad6"],
  render(hostId, entries) {
    const host = byId(hostId);
    if (!host) return;
    const total = entries.reduce((sum, [, value]) => sum + value, 0);
    if (!total) {
      host.innerHTML = `<div class="empty">Sem gastos neste período.</div>`;
      return;
    }
    const radius = 52;
    const circumference = 2 * Math.PI * radius;
    let offset = 0;
    const circles = entries.slice(0, 8).map(([id, value], index) => {
      const pct = value / total;
      const length = pct * circumference;
      const dash = `${length} ${circumference - length}`;
      const rotation = (offset / circumference) * 360;
      offset += length;
      return `<circle cx="60" cy="60" r="${radius}" fill="none" stroke="${this.palette[index % this.palette.length]}" stroke-width="14" stroke-dasharray="${dash}" transform="rotate(${rotation - 90} 60 60)" stroke-linecap="butt" />`;
    }).join("");
    const legend = entries.slice(0, 8).map(([id, value], index) => {
      const cat = CategoryService.get(id);
      const pct = Math.round((value / total) * 100);
      return `<div class="pie-legend-row"><i style="background:${this.palette[index % this.palette.length]}"></i><span>${cat.icon} ${cat.name}</span><b>${pct}%</b></div>`;
    }).join("");
    host.innerHTML = `
      <div class="pie-wrap">
        <svg class="pie-svg" width="120" height="120" viewBox="0 0 120 120">${circles}</svg>
        <div class="pie-legend">${legend}</div>
      </div>
    `;
  }
};

const LineChart = {
  render(hostId, series) {
    const host = byId(hostId);
    if (!host) return;
    if (!series.length) { host.innerHTML = `<div class="empty">Sem dados suficientes.</div>`; return; }
    const width = 620, height = 180, pad = 16;
    const values = series.map(s => s.value);
    const max = Math.max(1, ...values.map(Math.abs));
    const stepX = (width - pad * 2) / Math.max(1, series.length - 1);
    const midY = height / 2;
    const points = series.map((s, i) => {
      const x = pad + i * stepX;
      const y = midY - (s.value / max) * (midY - 20);
      return [x, y];
    });
    const linePath = points.map((p, i) => `${i === 0 ? "M" : "L"} ${p[0].toFixed(1)} ${p[1].toFixed(1)}`).join(" ");
    const areaPath = `${linePath} L ${points[points.length - 1][0].toFixed(1)} ${midY} L ${points[0][0].toFixed(1)} ${midY} Z`;
    const dots = points.map((p, i) => `<circle class="dot" cx="${p[0].toFixed(1)}" cy="${p[1].toFixed(1)}" r="3" fill="var(--gold)" style="animation-delay:${i * 40}ms" />`).join("");
    const labels = series.filter((_, i) => i % Math.ceil(series.length / 6 || 1) === 0)
      .map((s, i) => `<span>${escapeHTML(s.label)}</span>`).join("");
    host.innerHTML = `
      <svg class="line-svg" viewBox="0 0 ${width} ${height}" width="100%" height="${height}">
        <line x1="${pad}" y1="${midY}" x2="${width - pad}" y2="${midY}" stroke="var(--line)" stroke-width="1" />
        <path class="area" d="${areaPath}" fill="var(--gold)" />
        <path class="line" d="${linePath}" fill="none" stroke="var(--gold)" stroke-width="2.5" />
        ${dots}
      </svg>
      <div style="display:flex;justify-content:space-between;margin-top:4px;font-size:10px;color:var(--muted)">${labels}</div>
    `;
  }
};

/* ------------------------------------------------------------------------------- */
/*  Renderização de itens                                                          */
/* ------------------------------------------------------------------------------- */

const Render = {
  money(value) { return Currency.format(value); },
  transaction(tx, opts = {}) {
    const cat = CategoryService.get(tx.category);
    const cls = tx.type === "income" ? "in" : (tx.type === "transfer" ? "" : "out");
    const favClass = tx.favorite ? "is-fav" : "";
    const installmentTag = tx.installmentLabel ? ` • ${tx.installmentLabel}` : "";
    return `
      <article class="tx ${favClass}" data-open-tx="${tx.id}">
        <div class="tx-icon">${cat.icon}</div>
        <div>
          <h3>${escapeHTML(tx.title)}</h3>
          <p>${cat.name} • ${formatDateBR(tx.date)}${installmentTag}</p>
        </div>
        <div class="tx-value">
          <b class="${cls}">${tx.type === "transfer" ? Currency.format(tx.value) : Currency.signed(tx.type, tx.value)}</b>
          <button class="star-btn ${tx.favorite ? "on" : ""}" data-toggle-fav="${tx.id}" title="Favoritar">★</button>
        </div>
      </article>
    `;
  },
  empty(text) { return `<div class="empty">${escapeHTML(text)}</div>`; },
  categoryRow(id, value, total) {
    const cat = CategoryService.get(id);
    const pct = total ? Math.round((value / total) * 100) : 0;
    return `
      <article class="tx">
        <div class="tx-icon">${cat.icon}</div>
        <div><h3>${cat.name}</h3><p>${pct}% dos gastos do período</p></div>
        <div class="tx-value"><b>${Currency.format(value)}</b></div>
      </article>
    `;
  },
  insight(item) {
    return `
      <article class="tx">
        <div class="tx-icon">${item.icon || "•"}</div>
        <div><h3>${escapeHTML(item.title)}</h3><p>${escapeHTML(item.text)}</p></div>
      </article>
    `;
  },
  bill(bill) {
    const status = BillService.status(bill);
    const cls = bill.paid ? "paid" : (status === "late" ? "late" : "");
    const statusText = bill.paid ? "Pago" : (status === "late" ? "Atrasada" : (status === "soon" ? "Vence em breve" : "Em dia"));
    return `
      <div class="bill-row ${cls}">
        <div>
          <b>${escapeHTML(bill.title)}</b>
          <p>${Currency.format(bill.value)} • vence ${formatDateBR(bill.dueDate)} • ${statusText}</p>
        </div>
        <div style="display:flex;gap:6px">
          ${!bill.paid ? `<button class="ghost" data-pay-bill="${bill.id}">Pagar</button>` : ""}
          <button class="ghost" data-remove-bill="${bill.id}">×</button>
        </div>
      </div>
    `;
  },
  recurring(item) {
    const cat = CategoryService.get(item.category);
    return `
      <article class="tx">
        <div class="tx-icon">↻</div>
        <div><h3>${escapeHTML(item.title)}</h3><p>${cat.name} • todo mês</p></div>
        <div class="tx-value">
          <b class="${item.type === "income" ? "in" : "out"}">${Currency.signed(item.type, item.value)}</b>
          <button class="del" data-remove-recurring="${item.id}">×</button>
        </div>
      </article>
    `;
  },
  notification(item) {
    const time = new Date(item.createdAt).toLocaleString("pt-BR", { day: "2-digit", month: "short", hour: "2-digit", minute: "2-digit" });
    return `
      <div class="notif-row ${item.read ? "" : "unread"}" data-read-notif="${item.id}">
        <div class="notif-icon">${item.icon}</div>
        <div>
          <b>${escapeHTML(item.title)}</b>
          <p>${escapeHTML(item.text)}</p>
          <time>${time}</time>
        </div>
      </div>
    `;
  }
};

/* ------------------------------------------------------------------------------- */
/*  Views                                                                           */
/* ------------------------------------------------------------------------------- */

const DashboardView = {
  render() {
    const month = TransactionService.currentMonth();
    const income = TransactionService.income(month);
    const expense = TransactionService.expense(month);
    const balance = income - expense;
    CountUp.to(byId("balanceText"), balance);
    CountUp.to(byId("incomeText"), income);
    CountUp.to(byId("expenseText"), expense);
    const pct = Math.round(clamp(BudgetService.percent(), 0, 100));
    byId("mainRing").style.setProperty("--p", `${pct}%`);
    byId("mainRingText").textContent = State.settings.hidden ? "••" : `${pct}%`;
    const main = InsightEngine.main();
    byId("mainInsightTitle").textContent = main.title;
    byId("mainInsightText").textContent = main.text;
    const recent = TransactionService.all().sort((a, b) => new Date(b.date) - new Date(a.date)).slice(0, 4);
    byId("recentList").innerHTML = recent.map(tx => Render.transaction(tx)).join("") || Render.empty("Nenhuma movimentação ainda.");
    const bills = BillService.upcoming().slice(0, 3);
    byId("dashboardBillsList").innerHTML = bills.map(Render.bill).join("") || Render.empty("Nenhuma conta pendente.");
  }
};

const AddView = {
  render() {
    byId("txDate").value = byId("txDate").value || todayISO();
    byId("txCategory").innerHTML = CategoryService.options(State.type);
    byId("txCategory").value = State.type === "income" ? "income" : "other";
    byId("txSubcategory").innerHTML = CategoryService.subcategoryOptions(byId("txCategory").value);
    byId("txAccount").innerHTML = AccountService.options();
    byId("typeExpense").classList.toggle("active", State.type === "expense");
    byId("typeIncome").classList.toggle("active", State.type === "income");
    byId("quickChips").innerHTML = QuickTemplates.map((item, index) => {
      return `<button class="chip" data-quick="${index}">${escapeHTML(item.title)} ${Currency.format(item.value)}</button>`;
    }).join("");
    const editing = !!State.editingId;
    byId("addScreenTitle").textContent = editing ? "Editar lançamento" : "Novo lançamento";
    byId("txSubmitButton").textContent = editing ? "Salvar alterações" : "Salvar lançamento";
  },
  fillDemo() {
    const sample = State.type === "income"
      ? { title: "Pix recebido", value: 250, category: "income" }
      : { title: "Mercado", value: 120, category: "market" };
    byId("txTitle").value = sample.title;
    byId("txValue").value = sample.value;
    byId("txCategory").value = sample.category;
    byId("txSubcategory").innerHTML = CategoryService.subcategoryOptions(sample.category);
  },
  loadForEdit(tx) {
    State.editingId = tx.id;
    State.type = tx.type === "income" ? "income" : "expense";
    Router.go("add");
    byId("txId").value = tx.id;
    byId("txTitle").value = tx.title;
    byId("txValue").value = tx.value;
    byId("txDate").value = tx.date;
    byId("txCategory").innerHTML = CategoryService.options(State.type);
    byId("txCategory").value = tx.category;
    byId("txSubcategory").innerHTML = CategoryService.subcategoryOptions(tx.category);
    byId("txSubcategory").value = tx.subcategory || "";
    byId("txAccount").innerHTML = AccountService.options();
    byId("txAccount").value = tx.account;
    byId("txNote").value = tx.note || "";
    byId("txFavToggle").classList.toggle("on", !!tx.favorite);
    byId("txRecurringToggle").classList.remove("on");
    byId("txInstallments").disabled = true;
    this.render();
  },
  reset() {
    State.editingId = null;
    byId("txId").value = "";
    byId("transactionForm").reset();
    byId("txDate").value = todayISO();
    byId("txFavToggle").classList.remove("on");
    byId("txRecurringToggle").classList.remove("on");
    byId("txInstallments").disabled = true;
    this.render();
  }
};

const TransactionsView = {
  render() {
    byId("searchInput").value = State.settings.search || "";
    byId("sortSelect").value = State.settings.sort || "newest";
    const chips = [
      { id: "all", label: "Tudo" },
      { id: "favorite", label: "★ Favoritos" },
      { id: "expense", label: "Gastos" },
      { id: "income", label: "Receitas" },
      { id: "transfer", label: "Transferências" },
      ...CategoryService.expenseCategories().slice(0, 7).map(cat => ({ id: cat.id, label: `${cat.icon} ${cat.name}` }))
    ];
    byId("filterChips").innerHTML = chips.map(chip => {
      const active = State.settings.filter === chip.id ? "active" : "";
      return `<button class="chip ${active}" data-filter="${chip.id}">${chip.label}</button>`;
    }).join("");
    const list = TransactionService.filtered();
    byId("transactionList").innerHTML = list.map(tx => Render.transaction(tx)).join("") || Render.empty("Nada encontrado nesse filtro.");
  }
};

const StatisticsView = {
  render() {
    const period = State.settings.period || "month";
    $all("#periodTabs button").forEach(btn => btn.classList.toggle("active", btn.dataset.period === period));
    const labelMap = { week: "esta semana", month: "este mês", year: "este ano" };
    byId("periodLabel").textContent = labelMap[period];

    const list = TransactionService.byPeriod(period);
    const prevList = TransactionService.byPreviousPeriod(period);
    const spent = TransactionService.expense(list);
    const prevSpent = TransactionService.expense(prevList);
    const budget = BudgetService.budget();
    const avg = spent / Math.max(1, period === "year" ? 365 : (period === "week" ? 7 : currentDayOfMonth()));
    const dailyTarget = budget ? budget / (period === "year" ? 365 : daysInCurrentMonth()) : 1;

    byId("budgetText").textContent = `${Currency.format(spent)} / ${Currency.format(budget)}`;
    byId("budgetFill").style.width = `${clamp(budget ? (spent / budget) * 100 : 0, 0, 100)}%`;
    byId("dailyText").textContent = Currency.format(avg);
    byId("dailyFill").style.width = `${clamp((avg / Math.max(1, dailyTarget)) * 100, 0, 100)}%`;

    const pill = byId("comparePill");
    if (prevSpent === 0 && spent === 0) {
      pill.textContent = "—"; pill.className = "compare-pill";
    } else {
      const diff = prevSpent ? ((spent - prevSpent) / prevSpent) * 100 : 100;
      const up = diff >= 0;
      pill.textContent = `${up ? "▲" : "▼"} ${Math.abs(Math.round(diff))}%`;
      pill.className = `compare-pill ${up ? "up" : "down"}`;
    }

    const cats = TransactionService.byCategory(list);
    byId("categoryAccordion").innerHTML = cats.map(([id, value]) => {
      const cat = CategoryService.get(id);
      const subEntries = {};
      list.filter(tx => tx.category === id && tx.type === "expense").forEach(tx => {
        const key = tx.subcategory || "Outros";
        subEntries[key] = (subEntries[key] || 0) + tx.value;
      });
      const subRows = Object.entries(subEntries).sort((a, b) => b[1] - a[1])
        .map(([name, v]) => `<div class="sub-row"><span>${escapeHTML(name)}</span><b>${Currency.format(v)}</b></div>`).join("");
      return `
        <div class="accordion-item">
          <button class="accordion-head" data-accordion-toggle>
            <span class="tx-icon">${cat.icon}</span>
            <b>${cat.name}</b>
            <span style="font-size:13px;font-weight:780">${Currency.format(value)}</span>
            <span class="chev">▾</span>
          </button>
          <div class="accordion-body"><div class="accordion-body-in">${subRows}</div></div>
        </div>
      `;
    }).join("") || Render.empty("Sem gastos por categoria neste período.");

    PieChart.render("pieChartHost", cats);
    LineChart.render("lineChartHost", TransactionService.trendSeries(period));
    ChartRenderer.drawFlow();
  }
};

const PlanningView = {
  render() {
    byId("goalInput").value = State.settings.goal || "";
    byId("goalDateInput").value = State.settings.goalDate || "";
    const insights = InsightEngine.build();
    byId("insightsList").innerHTML = insights.map(Render.insight).join("");
    byId("billsList").innerHTML = BillService.list().map(Render.bill).join("") || Render.empty("Nenhuma conta cadastrada.");
    byId("recurringList").innerHTML = RecurringService.list().map(Render.recurring).join("") || Render.empty("Nenhuma recorrência ativa.");
  }
};

const CalendarView = {
  cursor: new Date(),
  render() {
    const year = this.cursor.getFullYear();
    const month = this.cursor.getMonth();
    byId("calMonthLabel").textContent = this.cursor.toLocaleDateString("pt-BR", { month: "long", year: "numeric" });
    const first = new Date(year, month, 1);
    const startOffset = first.getDay();
    const totalDays = daysInMonth(year, month);
    const prevTotal = daysInMonth(year, month - 1 < 0 ? 11 : month - 1);
    const cells = [];
    const dows = ["D", "S", "T", "Q", "Q", "S", "S"];
    dows.forEach(d => cells.push(`<div class="cal-dow">${d}</div>`));
    for (let i = startOffset - 1; i >= 0; i--) {
      cells.push(`<div class="cal-day muted">${prevTotal - i}</div>`);
    }
    const all = TransactionService.all();
    let monthIncome = 0, monthExpense = 0;
    for (let day = 1; day <= totalDays; day++) {
      const iso = `${year}-${String(month + 1).padStart(2, "0")}-${String(day).padStart(2, "0")}`;
      const dayTxs = all.filter(tx => tx.date === iso);
      const hasIncome = dayTxs.some(tx => tx.type === "income");
      const hasExpense = dayTxs.some(tx => tx.type === "expense");
      monthIncome += TransactionService.income(dayTxs);
      monthExpense += TransactionService.expense(dayTxs);
      const isToday = iso === todayISO();
      cells.push(`
        <button class="cal-day ${isToday ? "today" : ""}" data-cal-day="${iso}">
          <span>${day}</span>
          <span class="cal-dots">${hasIncome ? '<i class="in"></i>' : ""}${hasExpense ? '<i class="out"></i>' : ""}</span>
        </button>
      `);
    }
    byId("calGrid").innerHTML = cells.join("");
    byId("calIncomeText").textContent = Currency.format(monthIncome);
    byId("calExpenseText").textContent = Currency.format(monthExpense);
    byId("calBalanceText").textContent = Currency.format(monthIncome - monthExpense);
  },
  openDay(iso) {
    const list = TransactionService.all().filter(tx => tx.date === iso);
    byId("dayDetailTitle").textContent = formatDateLongBR(iso);
    byId("dayDetailList").innerHTML = list.map(tx => Render.transaction(tx)).join("") || Render.empty("Nenhuma movimentação neste dia.");
    Sheet.open("dayDetailSheet");
  }
};

const NotificationsView = {
  render() {
    const list = NotificationService.list();
    byId("notificationsList").innerHTML = list.map(Render.notification).join("") || Render.empty("Nenhuma notificação por aqui.");
    const count = NotificationService.unreadCount();
    const bellBadge = byId("bellBadge");
    bellBadge.textContent = count > 9 ? "9+" : String(count);
    bellBadge.classList.toggle("show", count > 0);
    const drawerBadge = byId("drawerBellBadge");
    drawerBadge.textContent = count > 9 ? "9+" : String(count);
    drawerBadge.style.display = count > 0 ? "grid" : "none";
  }
};

const SettingsView = {
  render() {
    byId("profileName").textContent = State.settings.name || "Usuário";
    const initial = String(State.settings.name || "U").trim().charAt(0).toUpperCase();
    byId("avatar").textContent = initial;
    byId("drawerAvatar").textContent = initial;
    byId("avatarPreviewInitial").textContent = initial;
    byId("drawerName").textContent = State.settings.name || "Usuário";
    byId("drawerBalance").textContent = Currency.format(TransactionService.balance());
    byId("drawerVersion").textContent = AppVersion;
    byId("nameInput").value = State.settings.name || "";
    byId("budgetInput").value = State.settings.budget || "";
    document.documentElement.dataset.theme = State.settings.theme;
    byId("themeToggle").classList.toggle("on", State.settings.theme === "dark");
    byId("autoThemeToggle").classList.toggle("on", !!State.settings.autoTheme);
    byId("privacyToggle").classList.toggle("on", !!State.settings.hidden);
    byId("privacyButton").textContent = State.settings.hidden ? "◌" : "◉";
    AvatarService.apply([byId("avatar"), byId("drawerAvatar"), byId("avatarPreviewButton")]);
    byId("removePhotoButton").style.display = State.settings.photo ? "block" : "none";
  },
  open() { Sheet.open("settingsSheet"); this.render(); },
  close() { Sheet.close("settingsSheet"); }
};

/* ------------------------------------------------------------------------------- */
/*  App: inicialização e ligação de eventos                                        */
/* ------------------------------------------------------------------------------- */

const App = {
  booted: false,

  init() {
    State.hydrate();
    this.applyAutoTheme();
    RecurringService.runDue();
    BillService.checkReminders();
    this.bind();
    this.render("init");
    this.booted = true;
    Skeleton.hide();
    Snackbar.show("App pronto");
  },

  applyAutoTheme() {
    if (!State.settings.autoTheme) return;
    const prefersDark = window.matchMedia && window.matchMedia("(prefers-color-scheme: dark)").matches;
    State.settings.theme = prefersDark ? "dark" : "light";
  },

  bind() {
    State.subscribe(reason => this.render(reason));

    $all("[data-route]").forEach(button => {
      button.addEventListener("click", event => {
        event.preventDefault();
        Router.go(button.dataset.route);
      });
    });

    $all("[data-drawer-route]").forEach(button => {
      button.addEventListener("click", () => {
        Router.go(button.dataset.drawerRoute);
        Drawer.close();
      });
    });

    $all("[data-open-add]").forEach(button => {
      button.addEventListener("click", () => {
        AddView.reset();
        State.setType(button.dataset.openAdd);
        Router.go("add");
      });
    });

    byId("fabButton").addEventListener("click", () => {
      AddView.reset();
      State.setType("expense");
      Router.go("add");
    });

    byId("menuButton").addEventListener("click", () => Drawer.open());
    byId("drawerBg").addEventListener("click", event => { if (event.target.id === "drawerBg") Drawer.close(); });

    byId("bellButton").addEventListener("click", () => Router.go("notifications"));
    byId("drawerSettingsLink").addEventListener("click", () => { Drawer.close(); SettingsView.open(); });
    byId("drawerBackupLink").addEventListener("click", () => { Drawer.close(); SettingsView.open(); });
    byId("drawerAboutLink").addEventListener("click", () => {
      Drawer.close();
      Dialog.ask("Sobre o app", `Banco Premium v${AppVersion} — controle financeiro pessoal, 100% local no seu navegador. Nenhum dado é enviado para servidores.`, "Ok", "neutral");
    });

    byId("settingsButton").addEventListener("click", () => SettingsView.open());
    byId("closeSettingsButton").addEventListener("click", () => SettingsView.close());
    Sheet.bindBackdrop("settingsSheet");

    byId("avatar").addEventListener("click", () => SettingsView.open());
    byId("drawerAvatar").addEventListener("click", () => { Drawer.close(); SettingsView.open(); });
    const triggerAvatarPicker = () => byId("avatarInput").click();
    byId("avatarPreviewButton").addEventListener("click", triggerAvatarPicker);
    byId("changePhotoButton").addEventListener("click", triggerAvatarPicker);
    byId("avatarInput").addEventListener("change", async () => {
      const file = byId("avatarInput").files[0];
      byId("avatarInput").value = "";
      if (!file) return;
      try {
        const dataUrl = await AvatarService.fromFile(file);
        State.setSetting("photo", dataUrl);
        Snackbar.show("Foto de perfil atualizada");
      } catch (error) {
        Snackbar.show(error.message);
      }
    });
    byId("removePhotoButton").addEventListener("click", () => {
      State.setSetting("photo", "");
      Snackbar.show("Foto removida");
    });

    byId("privacyButton").addEventListener("click", () => State.setSetting("hidden", !State.settings.hidden));
    byId("privacyToggle").addEventListener("click", () => State.setSetting("hidden", !State.settings.hidden));
    byId("themeButton").addEventListener("click", () => {
      State.setSetting("autoTheme", false);
      State.setSetting("theme", State.settings.theme === "dark" ? "light" : "dark");
    });
    byId("themeToggle").addEventListener("click", () => {
      State.setSetting("autoTheme", false);
      State.setSetting("theme", State.settings.theme === "dark" ? "light" : "dark");
    });
    byId("autoThemeToggle").addEventListener("click", () => {
      State.setSetting("autoTheme", !State.settings.autoTheme);
      this.applyAutoTheme();
      State.notify("theme:auto");
    });
    if (window.matchMedia) {
      window.matchMedia("(prefers-color-scheme: dark)").addEventListener("change", () => {
        if (State.settings.autoTheme) { this.applyAutoTheme(); State.notify("theme:system"); }
      });
    }

    byId("nameInput").addEventListener("input", event => State.setSetting("name", event.target.value));
    byId("budgetInput").addEventListener("input", event => State.setSetting("budget", safeNumber(event.target.value)));

    byId("typeExpense").addEventListener("click", () => State.setType("expense"));
    byId("typeIncome").addEventListener("click", () => State.setType("income"));
    byId("txCategory").addEventListener("change", event => {
      byId("txSubcategory").innerHTML = CategoryService.subcategoryOptions(event.target.value);
    });
    byId("quickDemoButton").addEventListener("click", () => AddView.fillDemo());

    byId("txFavToggle").addEventListener("click", () => byId("txFavToggle").classList.toggle("on"));
    byId("txRecurringToggle").addEventListener("click", () => {
      const on = byId("txRecurringToggle").classList.toggle("on");
      byId("txInstallments").disabled = on ? true : byId("txInstallments").disabled;
      if (on) { byId("txInstallments").value = 2; byId("txInstallments").disabled = true; }
    });
    byId("txInstallments").addEventListener("focus", () => {
      byId("txRecurringToggle").classList.remove("on");
    });

    byId("transactionForm").addEventListener("submit", event => {
      event.preventDefault();
      try {
        const payload = {
          id: byId("txId").value || null,
          type: State.type,
          title: byId("txTitle").value,
          value: byId("txValue").value,
          category: byId("txCategory").value,
          subcategory: byId("txSubcategory").value,
          account: byId("txAccount").value,
          date: byId("txDate").value || todayISO(),
          note: byId("txNote").value,
          favorite: byId("txFavToggle").classList.contains("on")
        };
        const wantsRecurring = byId("txRecurringToggle").classList.contains("on") && !payload.id;
        const wantsInstallments = !byId("txInstallments").disabled && !payload.id && payload.type === "expense";

        if (payload.id) {
          TransactionService.update(payload.id, payload);
        } else if (wantsInstallments) {
          TransactionService.addWithInstallments(payload, byId("txInstallments").value);
        } else {
          TransactionService.add(payload);
          if (wantsRecurring) RecurringService.add(payload);
        }
        AddView.reset();
        Router.go(payload.id ? "transactions" : "dashboard");
      } catch (error) {
        Snackbar.show(error.message);
      }
    });

    byId("quickChips").addEventListener("click", event => {
      const button = event.target.closest("[data-quick]");
      if (!button) return;
      const item = QuickTemplates[Number(button.dataset.quick)];
      TransactionService.add({ ...item, date: todayISO(), account: "checking" });
    });

    // Delegação: abrir detalhe / favoritar em qualquer lista de transações
    document.body.addEventListener("click", event => {
      const favButton = event.target.closest("[data-toggle-fav]");
      if (favButton) {
        event.stopPropagation();
        TransactionService.toggleFavorite(favButton.dataset.toggleFav);
        return;
      }
      const openTx = event.target.closest("[data-open-tx]");
      if (openTx) {
        TxDetail.open(openTx.dataset.openTx);
      }
    });

    byId("searchInput").addEventListener("input", debounce(event => State.setSearch(event.target.value), 180));
    byId("sortSelect").addEventListener("change", event => State.setSort(event.target.value));
    byId("filterChips").addEventListener("click", event => {
      const button = event.target.closest("[data-filter]");
      if (button) State.setFilter(button.dataset.filter);
    });
    byId("clearFiltersButton").addEventListener("click", () => {
      State.settings.filter = "all";
      State.settings.search = "";
      State.settings.sort = "newest";
      State.notify("filters:clear");
    });

    byId("exportButton").addEventListener("click", () => CsvService.export());
    byId("backupButton").addEventListener("click", () => BackupService.export());
    byId("importButton").addEventListener("click", () => BackupService.askImport());
    this.bindResetConfirmation();

    byId("saveGoalButton").addEventListener("click", () => {
      State.settings.goal = safeNumber(byId("goalInput").value);
      State.settings.goalDate = byId("goalDateInput").value;
      State.notify("goal");
      Snackbar.show("Meta salva");
    });
    byId("simulateButton").addEventListener("click", () => {
      Snackbar.show(`Para bater a meta: ${Currency.format(GoalService.dailyNeed())}/dia`);
    });

    // Tabs de período nas estatísticas
    byId("periodTabs").addEventListener("click", event => {
      const btn = event.target.closest("button[data-period]");
      if (!btn) return;
      State.setPeriod(btn.dataset.period);
    });

    Accordion.init(byId("categoryAccordion"));

    // Transferência entre contas
    byId("transferButton").addEventListener("click", () => {
      byId("transferFrom").innerHTML = AccountService.options();
      byId("transferTo").innerHTML = AccountService.options();
      byId("transferTo").value = AccountService.list()[1]?.id || AccountService.list()[0].id;
      Sheet.open("transferSheet");
    });
    byId("closeTransferButton").addEventListener("click", () => Sheet.close("transferSheet"));
    Sheet.bindBackdrop("transferSheet");
    byId("transferSubmitButton").addEventListener("click", () => {
      try {
        TransactionService.transfer(byId("transferFrom").value, byId("transferTo").value, byId("transferValue").value);
        byId("transferValue").value = "";
        Sheet.close("transferSheet");
      } catch (error) {
        Snackbar.show(error.message);
      }
    });

    // Contas a pagar
    byId("addBillButton").addEventListener("click", () => {
      byId("billDate").value = addDaysISO(todayISO(), 5);
      Sheet.open("billSheet");
    });
    byId("closeBillButton").addEventListener("click", () => Sheet.close("billSheet"));
    Sheet.bindBackdrop("billSheet");
    byId("billSubmitButton").addEventListener("click", () => {
      try {
        BillService.add({ title: byId("billTitle").value, value: byId("billValue").value, dueDate: byId("billDate").value });
        byId("billTitle").value = ""; byId("billValue").value = "";
        Sheet.close("billSheet");
      } catch (error) {
        Snackbar.show(error.message);
      }
    });
    document.body.addEventListener("click", event => {
      const pay = event.target.closest("[data-pay-bill]");
      if (pay) { BillService.markPaid(pay.dataset.payBill); Snackbar.show("Conta paga e lançada no extrato"); }
      const del = event.target.closest("[data-remove-bill]");
      if (del) BillService.remove(del.dataset.removeBill);
      const delRec = event.target.closest("[data-remove-recurring]");
      if (delRec) RecurringService.remove(delRec.dataset.removeRecurring);
      const readNotif = event.target.closest("[data-read-notif]");
      if (readNotif) NotificationService.markRead(readNotif.dataset.readNotif);
    });
    byId("markAllReadButton").addEventListener("click", () => NotificationService.markAllRead());

    // Calendário
    byId("calPrevButton").addEventListener("click", () => { CalendarView.cursor.setMonth(CalendarView.cursor.getMonth() - 1); CalendarView.render(); });
    byId("calNextButton").addEventListener("click", () => { CalendarView.cursor.setMonth(CalendarView.cursor.getMonth() + 1); CalendarView.render(); });
    byId("calGrid").addEventListener("click", event => {
      const day = event.target.closest("[data-cal-day]");
      if (day) CalendarView.openDay(day.dataset.calDay);
    });
    byId("closeDayDetailButton").addEventListener("click", () => Sheet.close("dayDetailSheet"));
    Sheet.bindBackdrop("dayDetailSheet");

    // Detalhe de transação
    byId("closeTxDetailButton").addEventListener("click", () => Sheet.close("txDetailSheet"));
    Sheet.bindBackdrop("txDetailSheet");
    byId("txDetailEditButton").addEventListener("click", () => {
      const tx = TransactionService.byId(TxDetail.currentId);
      if (tx) { Sheet.close("txDetailSheet"); AddView.loadForEdit(tx); }
    });
    byId("txDetailDuplicateButton").addEventListener("click", () => {
      TransactionService.duplicate(TxDetail.currentId);
      Sheet.close("txDetailSheet");
    });
    byId("txDetailDeleteButton").addEventListener("click", async () => {
      const ok = await Dialog.ask("Excluir lançamento?", "Você pode desfazer logo em seguida pela notificação.", "Excluir");
      Dialog.resolve(ok);
      if (ok) { TransactionService.remove(TxDetail.currentId); Sheet.close("txDetailSheet"); }
    });

    byId("dialogCancelButton").addEventListener("click", () => Dialog.resolve(false));
    byId("dialogConfirmButton").addEventListener("click", () => Dialog.resolve(true));
    byId("dialogBg").addEventListener("click", event => { if (event.target.id === "dialogBg") Dialog.resolve(false); });

    window.addEventListener("resize", throttle(() => { if (State.route === "statistics") ChartRenderer.drawFlow(); }, 200));
  },

  bindResetConfirmation() {
    byId("resetButton").addEventListener("click", async () => {
      const ok = await Dialog.ask("Apagar todos os dados?", "Essa ação remove lançamentos, contas e configurações deste app. Não pode ser desfeita.", "Apagar tudo");
      Dialog.resolve(ok);
      if (!ok) return;
      Storage.clearApp();
      State.settings = { ...DefaultSettings };
      State.txs = [];
      State.recurring = [];
      State.bills = [];
      State.notifications = [];
      State.notify("reset");
      SettingsView.close();
    });
  },

  render(reason) {
    Router.render();
    SettingsView.render();
    DashboardView.render();
    AddView.render();
    TransactionsView.render();
    if (State.route === "statistics") StatisticsView.render();
    PlanningView.render();
    if (State.route === "calendar") CalendarView.render();
    NotificationsView.render();
  }
};

const TxDetail = {
  currentId: null,
  open(id) {
    const tx = TransactionService.byId(id);
    if (!tx) return;
    this.currentId = id;
    const cat = CategoryService.get(tx.category);
    const acc = AccountService.get(tx.account);
    byId("txDetailBody").innerHTML = `
      <article class="tx">
        <div class="tx-icon">${cat.icon}</div>
        <div><h3>${escapeHTML(tx.title)}</h3><p>${cat.name}${tx.subcategory ? " • " + escapeHTML(tx.subcategory) : ""}</p></div>
        <div class="tx-value"><b class="${tx.type === "income" ? "in" : "out"}">${Currency.signed(tx.type, tx.value)}</b></div>
      </article>
      <div class="setting"><div><b>Data</b></div><span class="label">${formatDateLongBR(tx.date)}</span></div>
      <div class="setting"><div><b>Conta</b></div><span class="label">${acc.icon} ${acc.name}</span></div>
      ${tx.note ? `<div class="setting"><div><b>Observação</b></div><span class="label">${escapeHTML(tx.note)}</span></div>` : ""}
      ${tx.installmentLabel ? `<div class="setting"><div><b>Parcela</b></div><span class="label">${tx.installmentLabel}</span></div>` : ""}
    `;
    Sheet.open("txDetailSheet");
  }
};

document.addEventListener("DOMContentLoaded", () => App.init());

if ("serviceWorker" in navigator && (location.protocol === "https:" || location.hostname === "localhost")) {
  window.addEventListener("load", () => {
    navigator.serviceWorker.register("sw.js").catch(() => {});
  });
}

</script>
</body>
</html>
