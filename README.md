<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aman Catering — Premium Catering & Professional Waiter Services</title>
<meta name="description" content="Aman Catering offers premium catering, banquet buffets and trained professional waiters in black suits & white shirts for weddings, corporate events and private parties. Call Aman Ji +91 98141 71748.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Jost:wght@300;400;500;600&display=swap" rel="stylesheet">
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><rect width='100' height='100' fill='%230a0a0a'/><text y='72' x='50' text-anchor='middle' font-size='62' fill='%23c9a227' font-family='serif'>A</text></svg>">
<style>
/* ============ BASE ============ */
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box}
:root{
  --black:#0a0a0a; --ink:#151515; --soft:#1c1c1c;
  --white:#ffffff; --off:#f7f6f3; --line:#e6e3dc;
  --gold:#c9a227; --gold-lt:#e3c675; --gold-dk:#a5831a;
  --grey:#6d6d6d; --grey-lt:#a8a8a8;
  --serif:'Cormorant Garamond',Georgia,serif;
  --sans:'Jost',-apple-system,'Segoe UI',sans-serif;
  --shadow:0 18px 50px rgba(0,0,0,.12);
  --maxw:1240px;
}
html{scroll-behavior:smooth;scroll-padding-top:86px}
body{font-family:var(--sans);font-weight:300;color:var(--ink);background:var(--white);line-height:1.75;overflow-x:hidden;-webkit-font-smoothing:antialiased}
img{max-width:100%;display:block}
a{text-decoration:none;color:inherit}
ul{list-style:none}
h1,h2,h3,h4{font-family:var(--serif);font-weight:600;line-height:1.15;letter-spacing:.01em}
.wrap{max-width:var(--maxw);margin:0 auto;padding:0 26px}
.sec{padding:110px 0}
.sec--dark{background:var(--black);color:var(--white)}
.sec--off{background:var(--off)}

/* ============ SHARED BITS ============ */
.eyebrow{display:inline-flex;align-items:center;gap:12px;font-family:var(--sans);font-size:.7rem;font-weight:500;letter-spacing:.34em;text-transform:uppercase;color:var(--gold-dk);margin-bottom:20px}
.sec--dark .eyebrow{color:var(--gold-lt)}
.eyebrow::before{content:"";width:40px;height:1px;background:currentColor;opacity:.7}
.h-sec{font-size:clamp(2.1rem,4.4vw,3.5rem);margin-bottom:20px}
.h-sec em{font-style:italic;color:var(--gold-dk)}
.sec--dark .h-sec em{color:var(--gold-lt)}
.lead{font-size:1.02rem;color:var(--grey);max-width:640px}
.sec--dark .lead{color:var(--grey-lt)}
.center{text-align:center}
.center .eyebrow{justify-content:center}
.center .eyebrow::after{content:"";width:40px;height:1px;background:currentColor;opacity:.7}
.center .lead{margin:0 auto}

.btn{display:inline-flex;align-items:center;justify-content:center;gap:10px;padding:16px 36px;font-family:var(--sans);font-size:.76rem;font-weight:500;letter-spacing:.2em;text-transform:uppercase;border:1px solid transparent;cursor:pointer;transition:.35s cubic-bezier(.4,0,.2,1);background:none}
.btn--gold{background:var(--gold);color:#120e02;border-color:var(--gold)}
.btn--gold:hover{background:var(--gold-lt);border-color:var(--gold-lt);transform:translateY(-3px);box-shadow:0 14px 32px rgba(201,162,39,.32)}
.btn--ghost{border-color:rgba(255,255,255,.4);color:#fff}
.btn--ghost:hover{background:#fff;color:var(--black);border-color:#fff;transform:translateY(-3px)}
.btn--dark{border-color:var(--ink);color:var(--ink)}
.btn--dark:hover{background:var(--ink);color:#fff;transform:translateY(-3px)}

.reveal{opacity:0;transform:translateY(38px);transition:opacity .9s ease,transform .9s cubic-bezier(.22,1,.36,1)}
.reveal.in{opacity:1;transform:none}

/* ============ TOPBAR ============ */
.topbar{background:var(--black);color:var(--grey-lt);font-size:.76rem;letter-spacing:.06em;border-bottom:1px solid rgba(255,255,255,.08)}
.topbar .wrap{display:flex;justify-content:space-between;align-items:center;gap:20px;min-height:44px;flex-wrap:wrap}
.topbar-l{display:flex;gap:26px;flex-wrap:wrap}
.topbar a:hover{color:var(--gold-lt)}
.topbar b{color:var(--gold-lt);font-weight:500}
.topbar-r{display:flex;gap:16px;align-items:center}
.topbar-r a{width:26px;height:26px;display:grid;place-items:center;border:1px solid rgba(255,255,255,.18);border-radius:50%;transition:.3s}
.topbar-r a:hover{background:var(--gold);border-color:var(--gold);color:#0a0a0a}
.topbar-r svg{width:12px;height:12px;fill:currentColor}

/* ============ NAV ============ */
.nav{position:sticky;top:0;z-index:900;background:rgba(10,10,10,.96);backdrop-filter:blur(14px);border-bottom:1px solid rgba(255,255,255,.09);transition:.4s}
.nav.small{background:rgba(10,10,10,.99);box-shadow:0 8px 34px rgba(0,0,0,.42)}
.nav .wrap{display:flex;align-items:center;justify-content:space-between;min-height:82px;transition:.4s}
.nav.small .wrap{min-height:66px}
.logo{display:flex;align-items:center;gap:13px;color:#fff}
.logo-mark{width:46px;height:46px;display:grid;place-items:center;border:1px solid var(--gold);color:var(--gold);font-family:var(--serif);font-size:1.45rem;font-weight:700;letter-spacing:-.02em;flex:0 0 auto}
.logo-txt strong{display:block;font-family:var(--serif);font-size:1.32rem;font-weight:600;letter-spacing:.06em;line-height:1.1;color:#fff}
.logo-txt span{display:block;font-size:.56rem;letter-spacing:.42em;text-transform:uppercase;color:var(--gold-lt);margin-top:3px}
.menu{display:flex;align-items:center;gap:32px}
.menu a{font-size:.78rem;font-weight:400;letter-spacing:.16em;text-transform:uppercase;color:#e9e9e9;position:relative;padding:6px 0;white-space:nowrap}
.menu a::after{content:"";position:absolute;left:0;bottom:0;width:0;height:1px;background:var(--gold);transition:width .35s}
.menu a:hover{color:var(--gold-lt)}
.menu a:hover::after{width:100%}
.nav-cta{display:flex;align-items:center;gap:18px}
.nav-phone{display:flex;align-items:center;gap:10px;color:#fff}
.nav-phone svg{width:30px;height:30px;padding:7px;border:1px solid var(--gold);border-radius:50%;fill:var(--gold);flex:0 0 auto}
.nav-phone small{display:block;font-size:.58rem;letter-spacing:.24em;text-transform:uppercase;color:var(--gold-lt)}
.nav-phone b{font-size:.92rem;font-weight:400;letter-spacing:.04em}
.burger{display:none;flex-direction:column;gap:5px;background:none;border:0;cursor:pointer;padding:9px}
.burger span{width:25px;height:1.6px;background:#fff;transition:.34s}
.burger.x span:nth-child(1){transform:translateY(6.6px) rotate(45deg)}
.burger.x span:nth-child(2){opacity:0}
.burger.x span:nth-child(3){transform:translateY(-6.6px) rotate(-45deg)}

/* ============ HERO ============ */
.hero{position:relative;min-height:calc(100vh - 126px);display:flex;align-items:center;overflow:hidden;background:var(--black)}
.hero-bg{position:absolute;inset:0}
.hero-slide{position:absolute;inset:0;opacity:0;transform:scale(1.1);transition:opacity 1.7s ease,transform 8s linear}
.hero-slide.on{opacity:1;transform:scale(1)}
.hero-slide img{width:100%;height:100%;object-fit:cover}
.hero-bg::after{content:"";position:absolute;inset:0;background:linear-gradient(100deg,rgba(6,6,6,.93) 0%,rgba(8,8,8,.76) 42%,rgba(8,8,8,.42) 100%)}
.hero-in{position:relative;z-index:3;padding:90px 0;color:#fff;max-width:780px}
.hero-in .eyebrow{color:var(--gold-lt)}
.hero h1{font-size:clamp(2.7rem,6.6vw,5.3rem);margin-bottom:26px}
.hero h1 em{font-style:italic;color:var(--gold-lt)}
.hero p{font-size:clamp(1rem,1.5vw,1.16rem);color:#dcdcdc;max-width:600px;margin-bottom:40px}
.hero-btns{display:flex;gap:16px;flex-wrap:wrap;margin-bottom:46px}
.hero-mini{display:flex;gap:40px;flex-wrap:wrap;padding-top:32px;border-top:1px solid rgba(255,255,255,.16)}
.hero-mini div b{display:block;font-family:var(--serif);font-size:1.9rem;color:var(--gold-lt);line-height:1}
.hero-mini div span{font-size:.68rem;letter-spacing:.2em;text-transform:uppercase;color:#b4b4b4}
.hero-dots{position:absolute;right:34px;bottom:40px;z-index:4;display:flex;flex-direction:column;gap:12px}
.hero-dots button{width:9px;height:9px;border-radius:50%;border:1px solid rgba(255,255,255,.6);background:none;cursor:pointer;transition:.3s;padding:0}
.hero-dots button.on{background:var(--gold);border-color:var(--gold);transform:scale(1.35)}

/* ============ STATS ============ */
.stats{background:var(--gold);color:#120e02;padding:52px 0}
.stats-g{display:grid;grid-template-columns:repeat(4,1fr);gap:26px;text-align:center}
.stats-g>div{padding:6px 10px;border-right:1px solid rgba(18,14,2,.16)}
.stats-g>div:last-child{border:0}
.stats-g b{display:block;font-family:var(--serif);font-size:2.8rem;font-weight:700;line-height:1}
.stats-g span{font-size:.7rem;font-weight:500;letter-spacing:.22em;text-transform:uppercase}

/* ============ ABOUT ============ */
.about{display:grid;grid-template-columns:1.02fr 1fr;gap:74px;align-items:center}
.about-pics{position:relative}
.about-pics .big{aspect-ratio:4/4.6;overflow:hidden}
.about-pics .big img{width:100%;height:100%;object-fit:cover}
.about-pics .small{position:absolute;right:-32px;bottom:-40px;width:56%;aspect-ratio:4/3;overflow:hidden;border:9px solid #fff;box-shadow:var(--shadow)}
.about-pics .small img{width:100%;height:100%;object-fit:cover}
.about-badge{position:absolute;left:-26px;top:32px;background:var(--black);color:#fff;padding:22px 24px;text-align:center;border-bottom:3px solid var(--gold)}
.about-badge b{display:block;font-family:var(--serif);font-size:2.3rem;color:var(--gold-lt);line-height:1}
.about-badge span{font-size:.6rem;letter-spacing:.22em;text-transform:uppercase;color:#cfcfcf}
.about p{margin-bottom:18px;color:var(--grey)}
.about-list{display:grid;grid-template-columns:1fr 1fr;gap:14px 22px;margin:30px 0 36px}
.about-list li{display:flex;gap:11px;align-items:flex-start;font-size:.9rem;color:var(--ink)}
.about-list svg{width:17px;height:17px;fill:var(--gold-dk);flex:0 0 auto;margin-top:5px}
.sign{display:flex;align-items:center;gap:18px;padding-top:26px;border-top:1px solid var(--line)}
.sign b{font-family:var(--serif);font-size:1.32rem;display:block;line-height:1.2}
.sign span{font-size:.7rem;letter-spacing:.18em;text-transform:uppercase;color:var(--gold-dk)}

/* ============ SERVICES ============ */
.svc-g{display:grid;grid-template-columns:repeat(3,1fr);gap:30px;margin-top:62px}
.svc{background:#fff;border:1px solid var(--line);overflow:hidden;transition:.45s cubic-bezier(.4,0,.2,1)}
.svc:hover{transform:translateY(-10px);box-shadow:0 26px 58px rgba(0,0,0,.14);border-color:var(--gold)}
.svc-img{position:relative;aspect-ratio:16/10.6;overflow:hidden}
.svc-img img{width:100%;height:100%;object-fit:cover;transition:transform .9s cubic-bezier(.22,1,.36,1)}
.svc:hover .svc-img img{transform:scale(1.09)}
.svc-no{position:absolute;left:0;top:0;background:var(--black);color:var(--gold-lt);font-family:var(--serif);font-size:1.05rem;padding:9px 16px;letter-spacing:.06em}
.svc-b{padding:30px 28px 34px}
.svc-b h3{font-size:1.42rem;margin-bottom:12px}
.svc-b p{font-size:.9rem;color:var(--grey);margin-bottom:16px}
.svc-tags{display:flex;flex-wrap:wrap;gap:7px}
.svc-tags span{font-size:.64rem;letter-spacing:.1em;text-transform:uppercase;padding:5px 11px;background:var(--off);border:1px solid var(--line);color:var(--grey)}

/* ============ CATERING WAITERS (EXPLAINER) ============ */
.cw-top{display:grid;grid-template-columns:1fr 1.05fr;gap:70px;align-items:center;margin-bottom:78px}
.cw-img{position:relative;aspect-ratio:4/4.4;overflow:hidden}
.cw-img img{width:100%;height:100%;object-fit:cover}
.cw-img::after{content:"";position:absolute;inset:16px;border:1px solid rgba(255,255,255,.28);pointer-events:none}
.cw-top p{color:var(--grey-lt);margin-bottom:18px}
.cw-quote{border-left:2px solid var(--gold);padding:6px 0 6px 24px;margin:28px 0;font-family:var(--serif);font-size:1.26rem;font-style:italic;color:#fff}
.cw-g{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:rgba(255,255,255,.12)}
.cw-c{background:var(--black);padding:40px 32px;transition:.45s}
.cw-c:hover{background:var(--soft)}
.cw-ico{width:54px;height:54px;display:grid;place-items:center;border:1px solid var(--gold);margin-bottom:22px;transition:.4s}
.cw-ico svg{width:24px;height:24px;fill:var(--gold-lt);transition:.4s}
.cw-c:hover .cw-ico{background:var(--gold)}
.cw-c:hover .cw-ico svg{fill:#120e02}
.cw-c h4{font-size:1.24rem;color:#fff;margin-bottom:10px}
.cw-c p{font-size:.87rem;color:var(--grey-lt)}
.cw-note{margin-top:56px;padding:34px 38px;border:1px solid rgba(255,255,255,.16);display:flex;gap:30px;align-items:center;flex-wrap:wrap;justify-content:space-between;background:linear-gradient(90deg,rgba(201,162,39,.11),transparent)}
.cw-note h4{font-size:1.5rem;color:#fff;margin-bottom:6px}
.cw-note p{font-size:.9rem;color:var(--grey-lt);max-width:640px}

/* ============ OUR WAITERS ============ */
.team-g{display:grid;grid-template-columns:repeat(3,1fr);gap:32px;margin-top:62px}
.tm{background:#fff;border:1px solid var(--line);overflow:hidden;transition:.45s cubic-bezier(.4,0,.2,1)}
.tm:hover{transform:translateY(-10px);box-shadow:0 26px 58px rgba(0,0,0,.15);border-color:var(--gold)}
.tm-img{position:relative;aspect-ratio:1/1.12;overflow:hidden;background:#111}
.tm-img img{width:100%;height:100%;object-fit:cover;object-position:center 22%;filter:grayscale(100%) contrast(1.04);transition:transform .9s cubic-bezier(.22,1,.36,1),filter .6s}
.tm:hover .tm-img img{filter:grayscale(0%);transform:scale(1.07)}
.tm-yrs{position:absolute;right:14px;top:14px;background:var(--gold);color:#120e02;font-size:.63rem;font-weight:600;letter-spacing:.12em;text-transform:uppercase;padding:7px 12px}
.tm-uni{position:absolute;left:0;right:0;bottom:0;padding:14px 18px;background:linear-gradient(transparent,rgba(0,0,0,.88));color:#e8e8e8;font-size:.66rem;letter-spacing:.14em;text-transform:uppercase;display:flex;align-items:center;gap:8px}
.tm-uni i{width:8px;height:8px;background:var(--gold-lt);border-radius:50%;display:inline-block;flex:0 0 auto}
.tm-b{padding:26px 26px 30px}
.tm-b h3{font-size:1.3rem;margin-bottom:3px}
.tm-role{font-size:.68rem;letter-spacing:.2em;text-transform:uppercase;color:var(--gold-dk);margin-bottom:14px;display:block}
.tm-b p{font-size:.86rem;color:var(--grey);margin-bottom:16px}
.tm-sk{display:flex;flex-wrap:wrap;gap:6px;padding-top:15px;border-top:1px solid var(--line)}
.tm-sk span{font-size:.62rem;letter-spacing:.09em;text-transform:uppercase;color:var(--grey);background:var(--off);padding:5px 10px}
.uniform-strip{margin-top:60px;background:var(--black);color:#fff;padding:44px 46px;display:grid;grid-template-columns:auto 1fr auto;gap:34px;align-items:center}
.uniform-strip h4{font-size:1.42rem;margin-bottom:6px}
.uniform-strip p{font-size:.9rem;color:var(--grey-lt)}
.swatches{display:flex;gap:12px;flex:0 0 auto}
.sw{width:56px;height:56px;border:1px solid rgba(255,255,255,.28);display:grid;place-items:center;font-size:.55rem;letter-spacing:.1em;text-transform:uppercase;text-align:center;line-height:1.2}
.sw.b{background:#0f0f0f;color:#9a9a9a}
.sw.w{background:#fff;color:#555}
.sw.g{background:var(--gold);color:#120e02}

/* ============ WHY ============ */
.why-g{display:grid;grid-template-columns:repeat(4,1fr);gap:28px;margin-top:58px}
.why{text-align:center;padding:42px 26px;background:#fff;border:1px solid var(--line);transition:.42s}
.why:hover{background:var(--black);border-color:var(--black);transform:translateY(-8px)}
.why-ico{width:62px;height:62px;margin:0 auto 22px;display:grid;place-items:center;border-radius:50%;background:var(--off);transition:.42s}
.why-ico svg{width:26px;height:26px;fill:var(--gold-dk);transition:.42s}
.why:hover .why-ico{background:var(--gold)}
.why:hover .why-ico svg{fill:#120e02}
.why h4{font-size:1.2rem;margin-bottom:9px;transition:.42s}
.why p{font-size:.86rem;color:var(--grey);transition:.42s}
.why:hover h4{color:#fff}
.why:hover p{color:var(--grey-lt)}

/* ============ GALLERY ============ */
.gal-f{display:flex;justify-content:center;gap:10px;flex-wrap:wrap;margin:44px 0 40px}
.gal-f button{padding:11px 25px;font-size:.7rem;font-weight:500;letter-spacing:.18em;text-transform:uppercase;background:none;border:1px solid var(--line);color:var(--grey);cursor:pointer;transition:.35s}
.gal-f button:hover{border-color:var(--ink);color:var(--ink)}
.gal-f button.on{background:var(--black);border-color:var(--black);color:#fff}
.gal-g{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.gi{position:relative;overflow:hidden;cursor:pointer;aspect-ratio:1/1;background:#111}
.gi.tall{grid-row:span 2;aspect-ratio:1/2.06}
.gi.wide{grid-column:span 2;aspect-ratio:2.06/1}
.gi img{width:100%;height:100%;object-fit:cover;transition:transform 1s cubic-bezier(.22,1,.36,1)}
.gi:hover img{transform:scale(1.11)}
.gi-ov{position:absolute;inset:0;background:linear-gradient(transparent 38%,rgba(6,6,6,.9));opacity:0;transition:.45s;display:flex;flex-direction:column;justify-content:flex-end;padding:22px}
.gi:hover .gi-ov{opacity:1}
.gi-ov b{font-family:var(--serif);font-size:1.12rem;color:#fff}
.gi-ov span{font-size:.63rem;letter-spacing:.2em;text-transform:uppercase;color:var(--gold-lt)}
.gi-ov::before{content:"+";position:absolute;top:20px;right:22px;font-size:1.6rem;color:var(--gold-lt);font-weight:200;line-height:1}
.gi.hide{display:none}

/* LIGHTBOX */
.lb{position:fixed;inset:0;background:rgba(5,5,5,.97);z-index:1200;display:none;align-items:center;justify-content:center;padding:70px 26px}
.lb.on{display:flex}
.lb img{max-width:min(1100px,92vw);max-height:80vh;object-fit:contain;box-shadow:0 30px 80px rgba(0,0,0,.7)}
.lb-cap{position:absolute;bottom:30px;left:0;right:0;text-align:center;color:#ddd;font-size:.76rem;letter-spacing:.2em;text-transform:uppercase}
.lb-btn{position:absolute;background:none;border:1px solid rgba(255,255,255,.3);color:#fff;width:50px;height:50px;font-size:1.5rem;cursor:pointer;transition:.3s;display:grid;place-items:center;line-height:1}
.lb-btn:hover{background:var(--gold);border-color:var(--gold);color:#120e02}
.lb-x{top:26px;right:26px}
.lb-p{left:26px;top:50%;transform:translateY(-50%)}
.lb-n{right:26px;top:50%;transform:translateY(-50%)}

/* ============ TESTIMONIALS ============ */
.tst{position:relative;max-width:900px;margin:0 auto;text-align:center}
.tst-q{font-family:var(--serif);font-size:5.4rem;color:var(--gold);line-height:.6;opacity:.5;margin-bottom:26px}
.tst-track{position:relative;min-height:300px}
.tst-item{position:absolute;inset:0;opacity:0;transform:translateY(22px);transition:.75s cubic-bezier(.22,1,.36,1);pointer-events:none}
.tst-item.on{opacity:1;transform:none;pointer-events:auto;position:relative}
.tst-item p{font-family:var(--serif);font-size:clamp(1.14rem,2.2vw,1.66rem);font-style:italic;color:#fff;line-height:1.66;margin-bottom:34px}
.stars{display:flex;justify-content:center;gap:5px;margin-bottom:24px}
.stars svg{width:17px;height:17px;fill:var(--gold-lt)}
.tst-who{display:flex;align-items:center;justify-content:center;gap:16px}
.tst-who img{width:64px;height:64px;border-radius:50%;object-fit:cover;border:2px solid var(--gold)}
.tst-who b{display:block;font-family:var(--serif);font-size:1.16rem;color:#fff;text-align:left}
.tst-who span{font-size:.68rem;letter-spacing:.16em;text-transform:uppercase;color:var(--gold-lt);display:block;text-align:left}
.tst-dots{display:flex;justify-content:center;gap:11px;margin-top:44px}
.tst-dots button{width:34px;height:2px;background:rgba(255,255,255,.26);border:0;cursor:pointer;transition:.35s;padding:0}
.tst-dots button.on{background:var(--gold);height:3px}
.logos{margin-top:88px;padding-top:50px;border-top:1px solid rgba(255,255,255,.12);display:flex;flex-wrap:wrap;justify-content:center;gap:16px 54px;align-items:center}
.logos span{font-family:var(--serif);font-size:1.16rem;letter-spacing:.14em;color:rgba(255,255,255,.44);transition:.35s;text-transform:uppercase}
.logos span:hover{color:var(--gold-lt)}

/* ============ FAQ ============ */
.faq-g{display:grid;grid-template-columns:1fr 1fr;gap:18px 34px;margin-top:56px}
details{border:1px solid var(--line);background:#fff;transition:.35s}
details[open]{border-color:var(--gold);box-shadow:var(--shadow)}
summary{cursor:pointer;padding:22px 26px;font-family:var(--serif);font-size:1.1rem;font-weight:600;display:flex;justify-content:space-between;align-items:center;gap:16px;list-style:none}
summary::-webkit-details-marker{display:none}
summary::after{content:"+";font-family:var(--sans);font-size:1.3rem;font-weight:300;color:var(--gold-dk);transition:.3s;flex:0 0 auto}
details[open] summary::after{transform:rotate(45deg)}
details p{padding:0 26px 24px;font-size:.89rem;color:var(--grey)}

/* ============ CONTACT ============ */
.ct-g{display:grid;grid-template-columns:.92fr 1.08fr;gap:66px;margin-top:60px}
.ct-card{background:var(--black);color:#fff;padding:46px 40px;border-top:3px solid var(--gold)}
.ct-card h3{font-size:1.72rem;margin-bottom:10px}
.ct-card>p{font-size:.9rem;color:var(--grey-lt);margin-bottom:34px}
.ct-row{display:flex;gap:18px;padding:22px 0;border-bottom:1px solid rgba(255,255,255,.12)}
.ct-row:last-of-type{border:0}
.ct-ico{width:44px;height:44px;flex:0 0 auto;display:grid;place-items:center;border:1px solid var(--gold)}
.ct-ico svg{width:18px;height:18px;fill:var(--gold-lt)}
.ct-row small{display:block;font-size:.62rem;letter-spacing:.22em;text-transform:uppercase;color:var(--gold-lt);margin-bottom:4px}
.ct-row b{font-size:1.06rem;font-weight:400;line-height:1.5;display:block}
.ct-row b.big{font-family:var(--serif);font-size:1.5rem;letter-spacing:.02em}
.ct-row a:hover{color:var(--gold-lt)}
.wa{display:flex;align-items:center;justify-content:center;gap:11px;margin-top:30px;padding:15px;background:#1faa58;color:#fff;font-size:.74rem;font-weight:500;letter-spacing:.18em;text-transform:uppercase;transition:.35s}
.wa:hover{background:#178f48;transform:translateY(-3px)}
.wa svg{width:18px;height:18px;fill:#fff}
form{background:#fff;border:1px solid var(--line);padding:46px 42px}
form h3{font-size:1.72rem;margin-bottom:8px}
form>p{font-size:.88rem;color:var(--grey);margin-bottom:30px}
.f-g{display:grid;grid-template-columns:1fr 1fr;gap:20px}
.f{display:flex;flex-direction:column;gap:8px;margin-bottom:20px}
.f.full{grid-column:1/-1}
label{font-size:.64rem;font-weight:500;letter-spacing:.2em;text-transform:uppercase;color:var(--grey)}
input,select,textarea{font-family:var(--sans);font-size:.94rem;font-weight:300;padding:14px 16px;border:1px solid var(--line);background:var(--off);color:var(--ink);transition:.3s;width:100%}
input:focus,select:focus,textarea:focus{outline:0;border-color:var(--gold);background:#fff;box-shadow:0 0 0 3px rgba(201,162,39,.12)}
textarea{resize:vertical;min-height:118px}
.f-note{font-size:.74rem;color:var(--grey-lt);margin-top:16px;text-align:center}
.ok{display:none;margin-top:22px;padding:17px 20px;background:#edf8f0;border-left:3px solid #1faa58;color:#146c37;font-size:.88rem}
.ok.on{display:block}

/* ============ FOOTER ============ */
.foot{background:var(--black);color:var(--grey-lt);padding:86px 0 0;border-top:1px solid rgba(255,255,255,.08)}
.foot-g{display:grid;grid-template-columns:1.5fr 1fr 1fr 1.25fr;gap:52px;padding-bottom:58px}
.foot h5{font-family:var(--serif);font-size:1.16rem;color:#fff;margin-bottom:22px;letter-spacing:.04em}
.foot p,.foot li{font-size:.88rem;margin-bottom:11px}
.foot a:hover{color:var(--gold-lt)}
.foot .logo{margin-bottom:22px}
.foot-social{display:flex;gap:11px;margin-top:22px}
.foot-social a{width:36px;height:36px;display:grid;place-items:center;border:1px solid rgba(255,255,255,.18);transition:.32s}
.foot-social a:hover{background:var(--gold);border-color:var(--gold);color:#0a0a0a;transform:translateY(-3px)}
.foot-social svg{width:14px;height:14px;fill:currentColor}
.foot-hrs{display:flex;justify-content:space-between;gap:14px;font-size:.85rem;padding:8px 0;border-bottom:1px dashed rgba(255,255,255,.1)}
.foot-bot{border-top:1px solid rgba(255,255,255,.1);padding:26px 0;display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap;font-size:.79rem}
.foot-bot a{color:var(--gold-lt)}

/* FLOATERS */
.float{position:fixed;right:24px;z-index:800;width:52px;height:52px;display:grid;place-items:center;cursor:pointer;border:0;transition:.35s}
.f-wa{bottom:92px;background:#1faa58;border-radius:50%;box-shadow:0 10px 26px rgba(31,170,88,.42)}
.f-wa svg{width:26px;height:26px;fill:#fff}
.f-wa:hover{transform:scale(1.11)}
.f-top{bottom:24px;background:var(--black);color:#fff;border:1px solid var(--gold);opacity:0;pointer-events:none}
.f-top.on{opacity:1;pointer-events:auto}
.f-top:hover{background:var(--gold);color:#120e02}
.f-top svg{width:17px;height:17px;fill:currentColor}

/* ============ ADMIN ============ */
.admin{position:fixed;inset:0;z-index:2000;background:var(--black);display:none;overflow-y:auto}
.admin.on{display:block}
.ad-login{min-height:100vh;display:grid;grid-template-columns:1fr 1fr}
.ad-vis{position:relative;overflow:hidden}
.ad-vis img{width:100%;height:100%;object-fit:cover;filter:grayscale(100%) brightness(.5)}
.ad-vis-txt{position:absolute;inset:0;display:flex;flex-direction:column;justify-content:center;padding:60px;color:#fff;background:linear-gradient(rgba(6,6,6,.5),rgba(6,6,6,.82))}
.ad-vis-txt h2{font-size:2.6rem;margin:18px 0 14px}
.ad-vis-txt p{color:var(--grey-lt);max-width:400px}
.ad-form-side{display:flex;align-items:center;justify-content:center;padding:60px 40px;background:#0e0e0e}
.ad-box{width:100%;max-width:400px}
.ad-box .logo{justify-content:center;margin-bottom:34px}
.ad-box h3{color:#fff;font-size:1.86rem;text-align:center;margin-bottom:8px}
.ad-box>p{text-align:center;font-size:.86rem;color:var(--grey-lt);margin-bottom:34px}
.ad-box label{color:var(--grey-lt)}
.ad-box input{background:#161616;border-color:rgba(255,255,255,.16);color:#fff}
.ad-box input:focus{background:#1c1c1c;border-color:var(--gold)}
.ad-box .btn{width:100%;margin-top:8px}
.ad-err{display:none;margin-bottom:18px;padding:13px 16px;background:rgba(200,40,40,.12);border-left:3px solid #d9534f;color:#ffb3b0;font-size:.84rem}
.ad-err.on{display:block}
.ad-back{display:block;text-align:center;margin-top:26px;font-size:.72rem;letter-spacing:.18em;text-transform:uppercase;color:var(--grey-lt)}
.ad-back:hover{color:var(--gold-lt)}
.ad-hint{margin-top:26px;padding:15px 18px;border:1px dashed rgba(255,255,255,.16);font-size:.76rem;color:var(--grey-lt);text-align:center}
.ad-hint b{color:var(--gold-lt);font-weight:500}

.ad-panel{display:none;min-height:100vh;color:#fff}
.ad-panel.on{display:block}
.ad-bar{display:flex;justify-content:space-between;align-items:center;gap:20px;padding:20px 34px;border-bottom:1px solid rgba(255,255,255,.1);background:#0e0e0e;position:sticky;top:0;z-index:5;flex-wrap:wrap}
.ad-bar-r{display:flex;gap:11px;align-items:center;flex-wrap:wrap}
.ad-bar-r .btn{padding:11px 22px;font-size:.66rem}
.ad-body{padding:40px 34px 70px;max-width:1300px;margin:0 auto}
.ad-kpi{display:grid;grid-template-columns:repeat(4,1fr);gap:18px;margin-bottom:42px}
.kpi{padding:28px;background:#131313;border:1px solid rgba(255,255,255,.1);border-left:3px solid var(--gold)}
.kpi b{display:block;font-family:var(--serif);font-size:2.4rem;color:var(--gold-lt);line-height:1}
.kpi span{font-size:.66rem;letter-spacing:.2em;text-transform:uppercase;color:var(--grey-lt)}
.ad-body h3{font-size:1.6rem;margin-bottom:20px}
.tbl-wrap{overflow-x:auto;border:1px solid rgba(255,255,255,.1)}
table{width:100%;border-collapse:collapse;min-width:920px}
th,td{padding:15px 18px;text-align:left;font-size:.86rem;border-bottom:1px solid rgba(255,255,255,.08);vertical-align:top}
th{background:#131313;font-size:.64rem;font-weight:500;letter-spacing:.18em;text-transform:uppercase;color:var(--gold-lt);white-space:nowrap}
td{color:#ddd}
tr:hover td{background:rgba(255,255,255,.03)}
.del{background:none;border:1px solid rgba(255,255,255,.2);color:#e08b88;padding:6px 13px;font-size:.66rem;letter-spacing:.1em;text-transform:uppercase;cursor:pointer;transition:.3s;font-family:var(--sans)}
.del:hover{background:#d9534f;color:#fff;border-color:#d9534f}
.empty{padding:66px 20px;text-align:center;color:var(--grey-lt);border:1px dashed rgba(255,255,255,.14);font-size:.92rem}

/* ============ RESPONSIVE ============ */
@media(max-width:1080px){
  .menu{position:fixed;inset:0 0 0 auto;width:min(330px,84vw);background:#0c0c0c;flex-direction:column;justify-content:flex-start;align-items:flex-start;padding:112px 34px;gap:4px;transform:translateX(100%);transition:transform .45s cubic-bezier(.4,0,.2,1);border-left:1px solid rgba(255,255,255,.1);z-index:950;overflow-y:auto}
  .menu.open{transform:none}
  .menu a{width:100%;padding:16px 0;font-size:.86rem;border-bottom:1px solid rgba(255,255,255,.07)}
  .burger{display:flex;z-index:960}
  .nav-phone{display:none}
  .svc-g,.team-g,.cw-g,.faq-g{grid-template-columns:1fr 1fr}
  .why-g{grid-template-columns:1fr 1fr}
  .about,.cw-top,.ct-g{grid-template-columns:1fr;gap:60px}
  .about-pics{max-width:540px;margin:0 auto 34px}
  .cw-img{aspect-ratio:16/10}
  .foot-g{grid-template-columns:1fr 1fr;gap:42px}
  .gal-g{grid-template-columns:repeat(3,1fr)}
  .uniform-strip{grid-template-columns:1fr;text-align:center}
  .swatches{justify-content:center}
  .ad-login{grid-template-columns:1fr}
  .ad-vis{display:none}
  .ad-kpi{grid-template-columns:1fr 1fr}
}
@media(max-width:700px){
  .sec{padding:76px 0}
  .stats-g{grid-template-columns:1fr 1fr;gap:34px 12px}
  .stats-g>div:nth-child(2){border:0}
  .svc-g,.team-g,.cw-g,.faq-g,.why-g,.f-g{grid-template-columns:1fr}
  .gal-g{grid-template-columns:1fr 1fr}
  .gi.wide,.gi.tall{grid-column:auto;grid-row:auto;aspect-ratio:1/1}
  .about-list{grid-template-columns:1fr}
  .about-pics .small{display:none}
  .foot-g{grid-template-columns:1fr}
  .hero{min-height:auto;padding:70px 0}
  .hero-mini{gap:26px}
  .hero-dots{flex-direction:row;right:auto;left:26px;bottom:24px}
  .topbar-l{gap:14px;font-size:.7rem}
  form,.ct-card{padding:32px 24px}
  .cw-note{padding:28px 24px}
  .lb-p{left:10px}.lb-n{right:10px}
  .ad-kpi{grid-template-columns:1fr}
  .ad-body{padding:28px 18px 60px}
}
</style>
</head>
<body>

<!-- ======== TOP BAR ======== -->
<div class="topbar">
  <div class="wrap">
    <div class="topbar-l">
      <span>Serving Ludhiana, Jalandhar, Amritsar &amp; all of Punjab</span>
      <a href="tel:+919814171748">Call <b>+91 98141 71748</b></a>
    </div>
    <div class="topbar-r">
      <span style="letter-spacing:.14em">FOLLOW</span>
      <a href="#contact" aria-label="Facebook"><svg viewBox="0 0 24 24"><path d="M15 3h-3a5 5 0 0 0-5 5v3H5v4h2v6h4v-6h3l1-4h-4V8a1 1 0 0 1 1-1h3V3z"/></svg></a>
      <a href="#contact" aria-label="Instagram"><svg viewBox="0 0 24 24"><path d="M12 2c2.7 0 3.1 0 4.1.06 1.1.05 1.8.22 2.4.47.6.24 1.1.56 1.6 1.05.5.5.8 1 1.05 1.6.25.6.42 1.3.47 2.4.06 1 .06 1.4.06 4.1s0 3.1-.06 4.1c-.05 1.1-.22 1.8-.47 2.4-.25.6-.55 1.1-1.05 1.6-.5.5-1 .8-1.6 1.05-.6.25-1.3.42-2.4.47-1 .06-1.4.06-4.1.06s-3.1 0-4.1-.06c-1.1-.05-1.8-.22-2.4-.47-.6-.25-1.1-.55-1.6-1.05-.5-.5-.8-1-1.05-1.6-.25-.6-.42-1.3-.47-2.4C2 15.1 2 14.7 2 12s0-3.1.06-4.1c.05-1.1.22-1.8.47-2.4.25-.6.55-1.1 1.05-1.6.5-.5 1-.8 1.6-1.05.6-.25 1.3-.42 2.4-.47C8.9 2 9.3 2 12 2zm0 5a5 5 0 1 0 0 10 5 5 0 0 0 0-10zm0 2a3 3 0 1 1 0 6 3 3 0 0 1 0-6zm5.5-3.3a1.2 1.2 0 1 0 0 2.4 1.2 1.2 0 0 0 0-2.4z"/></svg></a>
      <a href="https://wa.me/919814171748" aria-label="WhatsApp"><svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 0 0-8.5 15.2L2 22l4.9-1.4A10 10 0 1 0 12 2zm5.3 14.1c-.2.6-1.2 1.2-1.7 1.2-.5.1-1 .1-1.7-.1-.4-.1-1-.3-1.7-.6-2.9-1.3-4.8-4.3-5-4.5-.1-.2-1.2-1.5-1.2-2.9s.7-2 1-2.3c.2-.3.5-.3.7-.3h.5c.2 0 .4 0 .6.5l.8 2c.1.2.1.3 0 .5l-.4.6c-.1.1-.3.3-.1.6.1.3.6 1.1 1.3 1.7.9.8 1.6 1 1.9 1.2.2.1.4.1.6-.1l.8-.9c.2-.2.4-.1.6 0l1.9.9c.2.1.4.2.4.3.1.2.1.8-.1 1.2z"/></svg></a>
    </div>
  </div>
</div>

<!-- ======== NAV ======== -->
<nav class="nav" id="nav">
  <div class="wrap">
    <a href="#home" class="logo">
      <span class="logo-mark">A</span>
      <span class="logo-txt"><strong>Aman Catering</strong><span>Fine Catering &amp; Service</span></span>
    </a>
    <ul class="menu" id="menu">
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About Us</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#catering-waiters">Catering Waiters</a></li>
      <li><a href="#waiters">Our Waiters</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#testimonials">Reviews</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <div class="nav-cta">
      <a href="tel:+919814171748" class="nav-phone">
        <svg viewBox="0 0 24 24"><path d="M6.6 10.8c1.4 2.8 3.8 5.1 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.6.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1h3.5c.6 0 1 .4 1 1 0 1.2.2 2.4.6 3.6.1.4 0 .7-.2 1l-2.3 2.2z"/></svg>
        <span><small>Call Aman Ji</small><b>+91 98141 71748</b></span>
      </a>
      <a href="#contact" class="btn btn--gold">Enquire Now</a>
      <button class="burger" id="burger" aria-label="Menu"><span></span><span></span><span></span></button>
    </div>
  </div>
</nav>

<!-- ======== HERO ======== -->
<header class="hero" id="home">
  <div class="hero-bg">
    <div class="hero-slide on"><img src="https://images.pexels.com/photos/29040997/pexels-photo-29040997.jpeg?auto=compress&cs=tinysrgb&w=1920" alt="Elegant banquet hall set with tables for a catered wedding reception"></div>
    <div class="hero-slide"><img src="https://images.pexels.com/photos/8921574/pexels-photo-8921574.jpeg?auto=compress&cs=tinysrgb&w=1920" alt="Professional waiter in a black suit serving food from a silver tray"></div>
    <div class="hero-slide"><img src="https://images.pexels.com/photos/38502557/pexels-photo-38502557.jpeg?auto=compress&cs=tinysrgb&w=1920" alt="Outdoor wedding reception setup with decorated dining tables"></div>
  </div>
  <div class="wrap hero-in">
    <span class="eyebrow">Since 2011 · Trusted by 1,200+ Hosts</span>
    <h1>Exceptional Food.<br>Impeccable <em>Service.</em></h1>
    <p>Aman Catering brings kitchen craft and disciplined, well-presented waitstaff together — so your guests are looked after from the first welcome drink to the last dessert plate.</p>
    <div class="hero-btns">
      <a href="#contact" class="btn btn--gold">Enquire For Your Event</a>
      <a href="#waiters" class="btn btn--ghost">Meet Our Waiters</a>
    </div>
    <div class="hero-mini">
      <div><b>14+</b><span>Years Experience</span></div>
      <div><b>150+</b><span>Trained Waiters</span></div>
      <div><b>1,200+</b><span>Events Served</span></div>
      <div><b>4.9</b><span>Client Rating</span></div>
    </div>
  </div>
  <div class="hero-dots" id="heroDots">
    <button class="on" aria-label="Slide 1"></button>
    <button aria-label="Slide 2"></button>
    <button aria-label="Slide 3"></button>
  </div>
</header>

<!-- ======== STATS ======== -->
<section class="stats">
  <div class="wrap">
    <div class="stats-g">
      <div><b><span class="count" data-to="1200">0</span>+</b><span>Events Catered</span></div>
      <div><b><span class="count" data-to="150">0</span>+</b><span>Uniformed Waiters</span></div>
      <div><b><span class="count" data-to="14">0</span>+</b><span>Years In Service</span></div>
      <div><b><span class="count" data-to="100">0</span>%</b><span>Hygiene Compliance</span></div>
    </div>
  </div>
</section>

<!-- ======== ABOUT ======== -->
<section class="sec" id="about">
  <div class="wrap about">
    <div class="about-pics reveal">
      <div class="big"><img src="https://images.pexels.com/photos/36242484/pexels-photo-36242484.jpeg?auto=compress&cs=tinysrgb&w=900" alt="Aman Catering chefs preparing meals in a professional kitchen"></div>
      <div class="small"><img src="https://images.pexels.com/photos/8921559/pexels-photo-8921559.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Guests being served at a table by a waiter in a black suit"></div>
      <div class="about-badge"><b>14+</b><span>Years of<br>Hospitality</span></div>
    </div>
    <div class="reveal">
      <span class="eyebrow">About Aman Catering</span>
      <h2 class="h-sec">A Family Kitchen With A <em>Hotel-Grade</em> Service Team</h2>
      <p>Aman Catering began in 2011 as a small family kitchen cooking for neighbourhood weddings. Word travelled — not only because of the food, but because of how our staff carried themselves. Today we handle events from intimate 50-guest gatherings to 2,000-plate weddings, and we still run on the same principle: cook honestly, serve gracefully.</p>
      <p>Every menu is planned with the host, cooked fresh on the day, and served by a team that has been trained in banquet etiquette, portion discipline and guest handling. Our waiters arrive in pressed black suits with white shirts, groomed and briefed on your run-sheet before the first guest walks in.</p>
      <ul class="about-list">
        <li><svg viewBox="0 0 24 24"><path d="M9 16.2 4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4z"/></svg><span>FSSAI-compliant kitchen &amp; hygiene protocol</span></li>
        <li><svg viewBox="0 0 24 24"><path d="M9 16.2 4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4z"/></svg><span>Pure-veg &amp; non-veg kitchens kept separate</span></li>
        <li><svg viewBox="0 0 24 24"><path d="M9 16.2 4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4z"/></svg><span>Background-verified, uniformed service staff</span></li>
        <li><svg viewBox="0 0 24 24"><path d="M9 16.2 4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4z"/></svg><span>Transparent per-plate &amp; per-waiter pricing</span></li>
        <li><svg viewBox="0 0 24 24"><path d="M9 16.2 4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4z"/></svg><span>On-site captain for every 12 guest tables</span></li>
        <li><svg viewBox="0 0 24 24"><path d="M9 16.2 4.8 12l-1.4 1.4L9 19 21 7l-1.4-1.4z"/></svg><span>Complete setup, service &amp; clearing included</span></li>
      </ul>
      <div class="sign">
        <div><b>Aman Ji</b><span>Founder &amp; Head of Operations</span></div>
      </div>
    </div>
  </div>
</section>

<!-- ======== SERVICES ======== -->
<section class="sec sec--off" id="services">
  <div class="wrap">
    <div class="center reveal">
      <span class="eyebrow">What We Offer</span>
      <h2 class="h-sec">Catering Services, <em>End To End</em></h2>
      <p class="lead">Food, staff, setup and clearing — arranged as one package so you are never chasing three different vendors on the morning of your event.</p>
    </div>
    <div class="svc-g">
      <article class="svc reveal">
        <div class="svc-img"><span class="svc-no">01</span><img src="https://images.pexels.com/photos/31837830/pexels-photo-31837830.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Wedding reception table with floral decor and place settings"></div>
        <div class="svc-b">
          <h3>Wedding Catering</h3>
          <p>Full wedding-season catering across mehndi, sangeet, reception and next-day breakfast, with menus planned around both families' tastes.</p>
          <div class="svc-tags"><span>Multi-day</span><span>Live counters</span><span>Sweet stalls</span></div>
        </div>
      </article>
      <article class="svc reveal">
        <div class="svc-img"><span class="svc-no">02</span><img src="https://images.pexels.com/photos/15120599/pexels-photo-15120599.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Assorted appetizers arranged on a corporate catering buffet table"></div>
        <div class="svc-b">
          <h3>Corporate &amp; Office Events</h3>
          <p>Conferences, product launches, annual days and office lunches served on a strict schedule so your agenda never slips.</p>
          <div class="svc-tags"><span>Punctual</span><span>Invoiced</span><span>Bulk plates</span></div>
        </div>
      </article>
      <article class="svc reveal">
        <div class="svc-img"><span class="svc-no">03</span><img src="https://images.pexels.com/photos/7245480/pexels-photo-7245480.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Buffet table with salads, fruits and appetizers on white linen"></div>
        <div class="svc-b">
          <h3>Buffet &amp; Live Counters</h3>
          <p>Chaat, tandoor, pasta, dosa and dessert counters with dedicated attendants, replenished continuously through the evening.</p>
          <div class="svc-tags"><span>Chaat</span><span>Tandoor</span><span>Continental</span></div>
        </div>
      </article>
      <article class="svc reveal">
        <div class="svc-img"><span class="svc-no">04</span><img src="https://images.pexels.com/photos/8921549/pexels-photo-8921549.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Waiter in formal black suit serving a seated guest"></div>
        <div class="svc-b">
          <h3>Waiter &amp; Steward Staffing</h3>
          <p>Need only service staff? Hire our uniformed waiters, captains and bartenders on their own — for your venue or your own caterer.</p>
          <div class="svc-tags"><span>Per-waiter</span><span>Half/full day</span><span>Captains</span></div>
        </div>
      </article>
      <article class="svc reveal">
        <div class="svc-img"><span class="svc-no">05</span><img src="https://images.pexels.com/photos/26904273/pexels-photo-26904273.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Champagne glasses on a tray for beverage service at an event"></div>
        <div class="svc-b">
          <h3>Beverage &amp; Mocktail Service</h3>
          <p>Welcome drinks, fresh juice bars, mocktail stations and tray-passed beverages handled by trained beverage stewards.</p>
          <div class="svc-tags"><span>Welcome drinks</span><span>Juice bar</span><span>Bar staff</span></div>
        </div>
      </article>
      <article class="svc reveal">
        <div class="svc-img"><span class="svc-no">06</span><img src="https://images.pexels.com/photos/19870048/pexels-photo-19870048.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Dining tables set under an outdoor canopy for an event"></div>
        <div class="svc-b">
          <h3>Event Setup &amp; Clearing</h3>
          <p>Tables, linen, crockery, chafing dishes and counter dressing laid out before guests arrive — then cleared down completely after.</p>
          <div class="svc-tags"><span>Linen</span><span>Crockery</span><span>Full clearing</span></div>
        </div>
      </article>
    </div>
  </div>
</section>

<!-- ======== CATERING WAITERS EXPLAINER ======== -->
<section class="sec sec--dark" id="catering-waiters">
  <div class="wrap">
    <div class="cw-top">
      <div class="cw-img reveal"><img src="https://images.pexels.com/photos/15761510/pexels-photo-15761510.jpeg?auto=compress&cs=tinysrgb&w=900" alt="Catering waiter carrying a tray of glasses through an event"></div>
      <div class="reveal">
        <span class="eyebrow">Service Explained</span>
        <h2 class="h-sec">What Exactly Is A <em>Catering Waiter?</em></h2>
        <p>A catering waiter — also called a service steward or banquet server — is the trained hospitality professional who looks after your guests for the duration of an event. Unlike a restaurant server tied to one floor, a catering waiter works at your venue: a banquet hall, farmhouse, lawn, hotel terrace or home.</p>
        <p>They arrive before the guests, set the service areas, then run the entire guest-facing side of the meal: welcoming, seating, pouring, serving, clearing and quietly fixing anything that goes wrong before you ever notice it. A good waiter is measured by what the host <em>didn't</em> have to worry about.</p>
        <div class="cw-quote">"The host should be a guest at their own event. That is the entire job of a catering waiter."</div>
        <a href="#contact" class="btn btn--gold">Request Waiter Staff</a>
      </div>
    </div>

    <div class="center reveal" style="margin-bottom:46px">
      <span class="eyebrow">Duties &amp; Responsibilities</span>
      <h2 class="h-sec">What Our Catering Waiters <em>Do</em></h2>
    </div>

    <div class="cw-g">
      <div class="cw-c reveal">
        <div class="cw-ico"><svg viewBox="0 0 24 24"><path d="M11 2h2v3.1a7 7 0 0 1 6 6.9H5a7 7 0 0 1 6-6.9V2zM3 14h18v2H3v-2zm2 4h14l-1.2 3a1.5 1.5 0 0 1-1.4 1H7.6a1.5 1.5 0 0 1-1.4-1L5 18z"/></svg></div>
        <h4>Table Service</h4>
        <p>Silver service, plated service or family-style — laying covers, presenting dishes from the correct side, refilling water and bread, and keeping every table clean and unhurried all evening.</p>
      </div>
      <div class="cw-c reveal">
        <div class="cw-ico"><svg viewBox="0 0 24 24"><path d="M12 3a9 9 0 0 1 9 9H3a9 9 0 0 1 9-9zm-10 11h20v2a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-2zm10-8.8V3.6h0zM7 8.6a5.2 5.2 0 0 1 5-3.3v1.4a3.8 3.8 0 0 0-3.6 2.4L7 8.6z"/></svg></div>
        <h4>Food Serving &amp; Buffet Attending</h4>
        <p>Manning chafing dishes and live counters, portioning correctly so food lasts the full service, rotating fresh trays from the kitchen, and holding hot food at safe serving temperature.</p>
      </div>
      <div class="cw-c reveal">
        <div class="cw-ico"><svg viewBox="0 0 24 24"><path d="M16 11a4 4 0 1 0-4-4 4 4 0 0 0 4 4zm-8 0a4 4 0 1 0-4-4 4 4 0 0 0 4 4zm0 2c-3 0-6 1.5-6 4.5V21h8v-3.5A5.3 5.3 0 0 1 10.4 13 12 12 0 0 0 8 13zm8 0a13 13 0 0 0-3 .4A5.4 5.4 0 0 1 14 17.5V21h8v-3.5c0-3-3-4.5-6-4.5z"/></svg></div>
        <h4>Guest Coordination</h4>
        <p>Greeting arrivals with welcome drinks, guiding guests to seating, answering menu and allergen questions, looking after elders and children first, and handling special requests discreetly.</p>
      </div>
      <div class="cw-c reveal">
        <div class="cw-ico"><svg viewBox="0 0 24 24"><path d="M3 4h18v2H3V4zm2 4h14v3H5V8zm-2 5h18v7a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-7zm4 2v3h10v-3H7z"/></svg></div>
        <h4>Event Setup Support</h4>
        <p>Arriving early to lay tables and linen, polish glassware and cutlery, dress the buffet counters, position service stations, and run a final walk-through with the captain before doors open.</p>
      </div>
      <div class="cw-c reveal">
        <div class="cw-ico"><svg viewBox="0 0 24 24"><path d="M6 2h12l-1 6a5 5 0 0 1-4 4.9V17h3v2H8v-2h3v-4.1A5 5 0 0 1 7 8L6 2zm2.4 2 .6 3.6A3 3 0 0 0 12 11a3 3 0 0 0 3-3.4L15.6 4H8.4z"/></svg></div>
        <h4>Beverage &amp; Tray Service</h4>
        <p>Tray-passing canapés and drinks through the crowd, running the juice and mocktail station, pouring at the table, and keeping glassware cleared, replaced and never left half-empty.</p>
      </div>
      <div class="cw-c reveal">
        <div class="cw-ico"><svg viewBox="0 0 24 24"><path d="M4 4h16v2H4V4zm2 5h12l-1.3 11.1a1 1 0 0 1-1 .9H8.3a1 1 0 0 1-1-.9L6 9zm2.2 2 1 8h5.6l1-8H8.2z"/></svg></div>
        <h4>Clearing &amp; Closing Down</h4>
        <p>Continuous clearing so no table ever looks abandoned, sorting crockery and linen for the kitchen, packing leftovers as the host directs, and leaving the venue tidy before signing off.</p>
      </div>
    </div>

    <div class="cw-note reveal">
      <div>
        <h4>How many waiters will your event need?</h4>
        <p>As a working guide we deploy one waiter for every 20–25 guests on buffet service, one for every 10–12 on plated table service, plus a captain for every 12 tables. Tell us your guest count and format and we'll give you an exact staffing plan.</p>
      </div>
      <a href="#contact" class="btn btn--gold">Get A Staffing Plan</a>
    </div>
  </div>
</section>

<!-- ======== OUR WAITERS ======== -->
<section class="sec" id="waiters">
  <div class="wrap">
    <div class="center reveal">
      <span class="eyebrow">Our Waiters</span>
      <h2 class="h-sec">The Team In <em>Black Suits &amp; White Shirts</em></h2>
      <p class="lead">Every waiter on our roster is background-verified, trained in banquet etiquette and turns out in a pressed black suit with a crisp white shirt, black tie and polished black shoes. Same standard, every single event.</p>
    </div>
    <div class="team-g">
      <article class="tm reveal">
        <div class="tm-img">
          <img src="https://images.pexels.com/photos/33290971/pexels-photo-33290971.jpeg?auto=compress&cs=tinysrgb&w=700" alt="Rajesh Kumar, head steward at Aman Catering, in a black suit and white shirt">
          <span class="tm-yrs">14 Years</span>
          <span class="tm-uni"><i></i>Black suit · White shirt · Black tie</span>
        </div>
        <div class="tm-b">
          <h3>Rajesh Kumar</h3>
          <span class="tm-role">Head Steward</span>
          <p>Our most senior floor man. Fourteen years across five-star banquets and large Punjabi weddings — Rajesh can read a hall of 800 guests and redeploy his team before a single table runs dry.</p>
          <div class="tm-sk"><span>Silver service</span><span>Team briefing</span><span>VIP tables</span></div>
        </div>
      </article>
      <article class="tm reveal">
        <div class="tm-img">
          <img src="https://images.pexels.com/photos/20097456/pexels-photo-20097456.jpeg?auto=compress&cs=tinysrgb&w=700" alt="Sandeep Singh, banquet captain, in formal black suit and white shirt">
          <span class="tm-yrs">11 Years</span>
          <span class="tm-uni"><i></i>Black suit · White shirt · Black tie</span>
        </div>
        <div class="tm-b">
          <h3>Sandeep Singh</h3>
          <span class="tm-role">Banquet Captain</span>
          <p>Sandeep runs the run-sheet. He coordinates kitchen timings with the stage programme so the main course lands exactly when the host wants it — not ten minutes into a speech.</p>
          <div class="tm-sk"><span>Timing control</span><span>Guest relations</span><span>Buffet flow</span></div>
        </div>
      </article>
      <article class="tm reveal">
        <div class="tm-img">
          <img src="https://images.pexels.com/photos/33644335/pexels-photo-33644335.jpeg?auto=compress&cs=tinysrgb&w=700" alt="Vikram Mehta, senior waiter, wearing a black suit with white shirt">
          <span class="tm-yrs">9 Years</span>
          <span class="tm-uni"><i></i>Black suit · White shirt · Black tie</span>
        </div>
        <div class="tm-b">
          <h3>Vikram Mehta</h3>
          <span class="tm-role">Senior Waiter</span>
          <p>Specialist in plated fine-dining service and corporate sit-downs. Precise with covers, quietly attentive, and the man we send to head tables and formal dinners.</p>
          <div class="tm-sk"><span>Plated service</span><span>Table setting</span><span>Corporate</span></div>
        </div>
      </article>
      <article class="tm reveal">
        <div class="tm-img">
          <img src="https://images.pexels.com/photos/36232657/pexels-photo-36232657.jpeg?auto=compress&cs=tinysrgb&w=700" alt="Harpreet Singh, service steward, in black suit and white shirt">
          <span class="tm-yrs">8 Years</span>
          <span class="tm-uni"><i></i>Black suit · White shirt · Black tie</span>
        </div>
        <div class="tm-b">
          <h3>Harpreet Singh</h3>
          <span class="tm-role">Service Steward</span>
          <p>Outdoor and lawn-event specialist. Harpreet handles long buffet lines with genuine warmth — guests routinely ask for him by name at repeat family functions.</p>
          <div class="tm-sk"><span>Buffet counters</span><span>Outdoor events</span><span>Guest care</span></div>
        </div>
      </article>
      <article class="tm reveal">
        <div class="tm-img">
          <img src="https://images.pexels.com/photos/29133442/pexels-photo-29133442.jpeg?auto=compress&cs=tinysrgb&w=700" alt="Arun Sharma, floor supervisor, in an elegant black suit and white shirt">
          <span class="tm-yrs">12 Years</span>
          <span class="tm-uni"><i></i>Black suit · White shirt · Black tie</span>
        </div>
        <div class="tm-b">
          <h3>Arun Sharma</h3>
          <span class="tm-role">Floor Supervisor</span>
          <p>Arun trains our new intake. Grooming checks, tray-carrying drills, service sequence and hygiene discipline all pass through him before a waiter is cleared for events.</p>
          <div class="tm-sk"><span>Staff training</span><span>Hygiene audit</span><span>Setup lead</span></div>
        </div>
      </article>
      <article class="tm reveal">
        <div class="tm-img">
          <img src="https://images.pexels.com/photos/14468286/pexels-photo-14468286.jpeg?auto=compress&cs=tinysrgb&w=700" alt="Mohit Verma, beverage steward, dressed in black suit and white shirt">
          <span class="tm-yrs">7 Years</span>
          <span class="tm-uni"><i></i>Black suit · White shirt · Black tie</span>
        </div>
        <div class="tm-b">
          <h3>Mohit Verma</h3>
          <span class="tm-role">Beverage Steward</span>
          <p>Runs welcome-drink lines and mocktail counters. Fast on tray service through a crowded hall, and meticulous about clean, chilled, correctly-placed glassware.</p>
          <div class="tm-sk"><span>Tray service</span><span>Mocktails</span><span>Glassware</span></div>
        </div>
      </article>
    </div>

    <div class="uniform-strip reveal">
      <div class="swatches">
        <span class="sw b">Suit</span>
        <span class="sw w">Shirt</span>
        <span class="sw g">Detail</span>
      </div>
      <div>
        <h4>One Uniform Standard — No Exceptions</h4>
        <p>Black two-piece suit, white full-sleeve shirt, black tie, black formal shoes, clean-shaven or neatly trimmed, short nails, no strong fragrance, name badge on the left lapel. Our supervisor runs a grooming check on site before every event begins.</p>
      </div>
      <a href="#contact" class="btn btn--gold">Hire Our Team</a>
    </div>
  </div>
</section>

<!-- ======== WHY ======== -->
<section class="sec sec--off">
  <div class="wrap">
    <div class="center reveal">
      <span class="eyebrow">Why Aman Catering</span>
      <h2 class="h-sec">Reasons Hosts Keep <em>Coming Back</em></h2>
    </div>
    <div class="why-g">
      <div class="why reveal">
        <div class="why-ico"><svg viewBox="0 0 24 24"><path d="M12 2 4 5v6c0 5 3.4 9.7 8 11 4.6-1.3 8-6 8-11V5l-8-3zm-1 14-3.5-3.5 1.4-1.4L11 13.2l4.7-4.7 1.4 1.4L11 16z"/></svg></div>
        <h4>Hygiene First</h4>
        <p>FSSAI-compliant kitchen, gloved handling, covered transport and temperature-checked holding at the venue.</p>
      </div>
      <div class="why reveal">
        <div class="why-ico"><svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 1 0 0 20 10 10 0 0 0 0-20zm1 5v5.6l4.3 2.5-1 1.7L11 13.6V7h2z"/></svg></div>
        <h4>On Time, Always</h4>
        <p>Staff on site three hours before service, food dispatched to a written timeline, courses served on your cue.</p>
      </div>
      <div class="why reveal">
        <div class="why-ico"><svg viewBox="0 0 24 24"><path d="M20 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/></svg></div>
        <h4>Clear Pricing</h4>
        <p>Written per-plate and per-waiter quotes. No service charge surprises, no hidden setup or clearing fees.</p>
      </div>
      <div class="why reveal">
        <div class="why-ico"><svg viewBox="0 0 24 24"><path d="M12 2 15.1 8.3 22 9.3l-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg></div>
        <h4>Trained Staff</h4>
        <p>Every waiter is verified, uniformed and put through in-house service training before they ever face a guest.</p>
      </div>
    </div>
  </div>
</section>

<!-- ======== GALLERY ======== -->
<section class="sec" id="gallery">
  <div class="wrap">
    <div class="center reveal">
      <span class="eyebrow">Gallery</span>
      <h2 class="h-sec">Moments From <em>Our Events</em></h2>
      <p class="lead">A look at the food we plate, the tables we lay and the team that carries it all.</p>
    </div>
    <div class="gal-f" id="galFilter">
      <button class="on" data-f="all">All</button>
      <button data-f="setup">Event Setup</button>
      <button data-f="food">Food</button>
      <button data-f="service">Service &amp; Staff</button>
      <button data-f="drinks">Beverages</button>
    </div>
    <div class="gal-g" id="galGrid">
      <figure class="gi tall" data-cat="setup"><img src="https://images.pexels.com/photos/29040997/pexels-photo-29040997.jpeg?auto=compress&cs=tinysrgb&w=900" alt="Banquet hall laid with round tables for a wedding reception"><figcaption class="gi-ov"><span>Event Setup</span><b>Banquet Hall Layout</b></figcaption></figure>
      <figure class="gi" data-cat="service"><img src="https://images.pexels.com/photos/8921574/pexels-photo-8921574.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Waiter in a black suit serving food from a silver tray"><figcaption class="gi-ov"><span>Service</span><b>Tray Service</b></figcaption></figure>
      <figure class="gi" data-cat="food"><img src="https://images.pexels.com/photos/7245480/pexels-photo-7245480.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Buffet table with salad and fresh fruit on white linen"><figcaption class="gi-ov"><span>Food</span><b>Buffet Spread</b></figcaption></figure>
      <figure class="gi wide" data-cat="food"><img src="https://images.pexels.com/photos/30507463/pexels-photo-30507463.jpeg?auto=compress&cs=tinysrgb&w=1200" alt="Chef plating a fine dining dish with precision"><figcaption class="gi-ov"><span>Food</span><b>Plating Detail</b></figcaption></figure>
      <figure class="gi" data-cat="drinks"><img src="https://images.pexels.com/photos/16408/pexels-photo-16408.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Flute glasses arranged on a black serving tray"><figcaption class="gi-ov"><span>Beverages</span><b>Welcome Drinks</b></figcaption></figure>
      <figure class="gi" data-cat="setup"><img src="https://images.pexels.com/photos/38502557/pexels-photo-38502557.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Outdoor wedding tables decorated under a canopy"><figcaption class="gi-ov"><span>Event Setup</span><b>Lawn Reception</b></figcaption></figure>
      <figure class="gi" data-cat="service"><img src="https://images.pexels.com/photos/15761510/pexels-photo-15761510.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Server carrying a tray of wine glasses at an event"><figcaption class="gi-ov"><span>Service</span><b>Floor Service</b></figcaption></figure>
      <figure class="gi" data-cat="food"><img src="https://images.pexels.com/photos/15120599/pexels-photo-15120599.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Variety of appetizers displayed on a catering buffet"><figcaption class="gi-ov"><span>Food</span><b>Appetizer Counter</b></figcaption></figure>
      <figure class="gi" data-cat="setup"><img src="https://images.pexels.com/photos/19870048/pexels-photo-19870048.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Table set for a wedding reception under an outdoor pergola"><figcaption class="gi-ov"><span>Event Setup</span><b>Table Covers</b></figcaption></figure>
      <figure class="gi" data-cat="service"><img src="https://images.pexels.com/photos/8921559/pexels-photo-8921559.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Guests at a table being served by a uniformed waiter"><figcaption class="gi-ov"><span>Service</span><b>Guest Attention</b></figcaption></figure>
      <figure class="gi" data-cat="drinks"><img src="https://images.pexels.com/photos/26904273/pexels-photo-26904273.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Champagne glasses and bottles arranged on a tray"><figcaption class="gi-ov"><span>Beverages</span><b>Beverage Station</b></figcaption></figure>
      <figure class="gi" data-cat="food"><img src="https://images.pexels.com/photos/8580978/pexels-photo-8580978.jpeg?auto=compress&cs=tinysrgb&w=800" alt="Close up of a gourmet plated dish with greens and grains"><figcaption class="gi-ov"><span>Food</span><b>Signature Plate</b></figcaption></figure>
    </div>
  </div>
</section>

<!-- LIGHTBOX -->
<div class="lb" id="lb">
  <button class="lb-btn lb-x" id="lbX" aria-label="Close">&times;</button>
  <button class="lb-btn lb-p" id="lbP" aria-label="Previous">&#8249;</button>
  <img src="" alt="" id="lbImg">
  <button class="lb-btn lb-n" id="lbN" aria-label="Next">&#8250;</button>
  <div class="lb-cap" id="lbCap"></div>
</div>

<!-- ======== TESTIMONIALS ======== -->
<section class="sec sec--dark" id="testimonials">
  <div class="wrap">
    <div class="center reveal" style="margin-bottom:40px">
      <span class="eyebrow">Testimonials</span>
      <h2 class="h-sec">What Our <em>Hosts Say</em></h2>
    </div>
    <div class="tst reveal">
      <div class="tst-q">&ldquo;</div>
      <div class="tst-track" id="tstTrack">
        <div class="tst-item on">
          <div class="stars"><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg></div>
          <p>We had 700 guests and I genuinely did not have to stand up once. The waiters were in proper black suits, spotless white shirts, and they moved like a hotel team. Three relatives asked me for Aman Ji's number before the night ended.</p>
          <div class="tst-who"><img src="https://images.pexels.com/photos/4121033/pexels-photo-4121033.jpeg?auto=compress&cs=tinysrgb&w=200" alt="Ravinder and Simran, wedding clients"><span><b>Ravinder &amp; Simran</b><span>Wedding Reception · Ludhiana</span></span></div>
        </div>
        <div class="tst-item">
          <div class="stars"><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg></div>
          <p>We hired only the waiter staff for our annual day since the venue had its own kitchen. Twenty-two waiters arrived two and a half hours early, set every table, and served 400 people in under forty minutes. Complete professionals.</p>
          <div class="tst-who"><img src="https://images.pexels.com/photos/20097456/pexels-photo-20097456.jpeg?auto=compress&cs=tinysrgb&w=200" alt="Corporate client portrait"><span><b>Naveen Arora</b><span>Corporate Annual Day · Mohali</span></span></div>
        </div>
        <div class="tst-item">
          <div class="stars"><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg></div>
          <p>My mother is diabetic and my nephew has a nut allergy. Their captain noted both on arrival and personally walked those plates to our table separately. That kind of attention is why we've now used them for four family functions.</p>
          <div class="tst-who"><img src="https://images.pexels.com/photos/31761979/pexels-photo-31761979.jpeg?auto=compress&cs=tinysrgb&w=200" alt="Anniversary celebration clients"><span><b>Meenakshi Bansal</b><span>25th Anniversary · Jalandhar</span></span></div>
        </div>
        <div class="tst-item">
          <div class="stars"><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg><svg viewBox="0 0 24 24"><path d="M12 2l3.1 6.3 6.9 1-5 4.9 1.2 6.8L12 17.8 5.8 21l1.2-6.8-5-4.9 6.9-1L12 2z"/></svg></div>
          <p>Rain moved our lawn function indoors ninety minutes before guests arrived. Their team re-laid the entire buffet inside without one word of complaint and we still started on time. Honest quote, honest people.</p>
          <div class="tst-who"><img src="https://images.pexels.com/photos/10138896/pexels-photo-10138896.jpeg?auto=compress&cs=tinysrgb&w=200" alt="Engagement function clients"><span><b>Gurpreet &amp; Family</b><span>Engagement Function · Amritsar</span></span></div>
        </div>
      </div>
      <div class="tst-dots" id="tstDots"></div>
    </div>
    <div class="logos reveal">
      <span>Grand Palace Banquets</span>
      <span>The Royal Lawns</span>
      <span>Hotel Sunview</span>
      <span>Orchid Resorts</span>
      <span>Heritage Farmhouse</span>
    </div>
  </div>
</section>

<!-- ======== FAQ ======== -->
<section class="sec">
  <div class="wrap">
    <div class="center reveal">
      <span class="eyebrow">Good To Know</span>
      <h2 class="h-sec">Frequently Asked <em>Questions</em></h2>
    </div>
    <div class="faq-g">
      <details class="reveal"><summary>How far in advance should I contact you?</summary><p>For weddings and large functions, four to eight weeks is comfortable — peak wedding season fills earlier. For smaller gatherings and waiter-only staffing we can often arrange things within a week. A quick call to Aman Ji on +91 98141 71748 will confirm availability for your date immediately.</p></details>
      <details class="reveal"><summary>Can I hire only waiters, without food?</summary><p>Yes. Waiter-only staffing is one of our most requested services. You can hire waiters, captains, buffet attendants or beverage stewards on a half-day or full-day basis for your own venue, your own kitchen, or alongside another caterer.</p></details>
      <details class="reveal"><summary>Do you serve pure-vegetarian and Jain menus?</summary><p>We do. Pure-veg and Jain food is prepared in a separately maintained kitchen section with dedicated utensils and staff, and is served from clearly marked counters by designated waiters so there is no cross-handling at the buffet.</p></details>
      <details class="reveal"><summary>What is included in your per-plate price?</summary><p>Our standard per-plate quote includes food, cooking, transport, chafing dishes and serving equipment, crockery and cutlery, table linen, service staff, and full clearing after the event. Anything outside that — extra live counters, décor, premium crockery — is listed separately so you can see exactly what you're paying for.</p></details>
      <details class="reveal"><summary>How do your waiters dress?</summary><p>A black two-piece suit with a white full-sleeve shirt, black tie and black formal shoes, with a name badge on the left lapel. Grooming standards are checked on site by our supervisor before the event begins, and we carry spare shirts and ties to every function.</p></details>
      <details class="reveal"><summary>Which areas do you cover?</summary><p>We regularly serve dinanagar, Amritsar, tanda , pathankot and surrounding towns. For venues further out we're happy to travel — travel and stay costs are quoted upfront with no markup.</p></details>
    </div>
  </div>
</section>

<!-- ======== CONTACT ======== -->
<section class="sec sec--off" id="contact">
  <div class="wrap">
    <div class="center reveal">
      <span class="eyebrow">Contact &amp; Enquire</span>
      <h2 class="h-sec">Tell Us About <em>Your Event</em></h2>
      <p class="lead">Share a few details and we'll come back with a menu suggestion, a staffing plan and a clear written quote. No obligation, no pushy follow-ups.</p>
    </div>
    <div class="ct-g">
      <div class="ct-card reveal">
        <h3>Speak To Us Directly</h3>
        <p>The quickest way to get an answer is a phone call — Aman Ji handles enquiries personally.</p>
        <div class="ct-row">
          <div class="ct-ico"><svg viewBox="0 0 24 24"><path d="M6.6 10.8c1.4 2.8 3.8 5.1 6.6 6.6l2.2-2.2c.3-.3.7-.4 1-.2 1.1.4 2.3.6 3.6.6.6 0 1 .4 1 1V20c0 .6-.4 1-1 1-9.4 0-17-7.6-17-17 0-.6.4-1 1-1h3.5c.6 0 1 .4 1 1 0 1.2.2 2.4.6 3.6.1.4 0 .7-.2 1l-2.3 2.2z"/></svg></div>
          <div><small>Call / WhatsApp</small><b class="big"><a href="tel:+919814171748">+91 98141 71748</a></b><b style="font-size:.86rem;color:#a8a8a8">Aman Ji — Founder &amp; Head of Operations</b></div>
        </div>
        <div class="ct-row">
          <div class="ct-ico"><svg viewBox="0 0 24 24"><path d="M20 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/></svg></div>
          <div><small>Email</small><b><a href="mailto:hello@amancatering.in">hello@amancatering.in</a></b></div>
        </div>
        <div class="ct-row">
          <div class="ct-ico"><svg viewBox="0 0 24 24"><path d="M12 2a7 7 0 0 0-7 7c0 5.2 7 13 7 13s7-7.8 7-13a7 7 0 0 0-7-7zm0 9.5A2.5 2.5 0 1 1 12 6.5a2.5 2.5 0 0 1 0 5z"/></svg></div>
          <div><small>Service Area</small><b>gurdaspur · pathankot · Amritsar<br>dinanagar · Batala · tanda</b></div>
        </div>
        <div class="ct-row">
          <div class="ct-ico"><svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 1 0 0 20 10 10 0 0 0 0-20zm1 5v5.6l4.3 2.5-1 1.7L11 13.6V7h2z"/></svg></div>
          <div><small>Enquiry Hours</small><b>Mon – Sun · 8:00 AM – 10:00 PM</b></div>
        </div>
        <a href="https://wa.me/919814171748?text=Hello%20Aman%20Catering%2C%20I%20would%20like%20to%20enquire%20about%20catering%20and%20waiter%20service%20for%20my%20event." class="wa" target="_blank" rel="noopener">
          <svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 0 0-8.5 15.2L2 22l4.9-1.4A10 10 0 1 0 12 2zm5.3 14.1c-.2.6-1.2 1.2-1.7 1.2-.5.1-1 .1-1.7-.1-.4-.1-1-.3-1.7-.6-2.9-1.3-4.8-4.3-5-4.5-.1-.2-1.2-1.5-1.2-2.9s.7-2 1-2.3c.2-.3.5-.3.7-.3h.5c.2 0 .4 0 .6.5l.8 2c.1.2.1.3 0 .5l-.4.6c-.1.1-.3.3-.1.6.1.3.6 1.1 1.3 1.7.9.8 1.6 1 1.9 1.2.2.1.4.1.6-.1l.8-.9c.2-.2.4-.1.6 0l1.9.9c.2.1.4.2.4.3.1.2.1.8-.1 1.2z"/></svg>
          Chat On WhatsApp
        </a>
      </div>

      <form id="enqForm" class="reveal" novalidate>
        <h3>Send An Enquiry</h3>
        <p>Fill this in and we'll respond within a few hours during enquiry hours.</p>
        <div class="f-g">
          <div class="f"><label for="nm">Your Name *</label><input type="text" id="nm" name="name" placeholder="e.g. Harman Sidhu" required></div>
          <div class="f"><label for="ph">Phone Number *</label><input type="tel" id="ph" name="phone" placeholder="+91 XXXXX XXXXX" required></div>
          <div class="f"><label for="em">Email</label><input type="email" id="em" name="email" placeholder="you@example.com"></div>
          <div class="f"><label for="dt">Event Date</label><input type="date" id="dt" name="date"></div>
          <div class="f"><label for="ev">Event Type</label>
            <select id="ev" name="event">
              <option>Wedding / Reception</option>
              <option>Engagement / Roka</option>
              <option>Corporate Event</option>
              <option>Birthday / Anniversary</option>
              <option>Waiter Staff Only</option>
              <option>Other</option>
            </select>
          </div>
          <div class="f"><label for="gs">Guest Count</label>
            <select id="gs" name="guests">
              <option>Under 100</option>
              <option>100 – 250</option>
              <option>250 – 500</option>
              <option>500 – 1000</option>
              <option>1000+</option>
            </select>
          </div>
          <div class="f full"><label for="ct">Venue / City</label><input type="text" id="ct" name="city" placeholder="Venue name and city"></div>
          <div class="f full"><label for="ms">Requirements</label><textarea id="ms" name="message" placeholder="Menu preferences, veg / non-veg, number of waiters needed, service style (buffet or plated), timings…"></textarea></div>
        </div>
        <button type="submit" class="btn btn--gold" style="width:100%">Send Enquiry</button>
        <p class="f-note">Prefer to talk? Call Aman Ji on +91 98141 71748.</p>
        <div class="ok" id="okMsg"></div>
      </form>
    </div>
  </div>
</section>

<!-- ======== FOOTER ======== -->
<footer class="foot">
  <div class="wrap">
    <div class="foot-g">
      <div>
        <a href="#home" class="logo">
          <span class="logo-mark">A</span>
          <span class="logo-txt"><strong>Aman Catering</strong><span>Fine Catering &amp; Service</span></span>
        </a>
        <p>Premium catering and professionally trained waitstaff for weddings, corporate events and private celebrations across Punjab. Serving with care since 2011.</p>
        <div class="foot-social">
          <a href="#contact" aria-label="Facebook"><svg viewBox="0 0 24 24"><path d="M15 3h-3a5 5 0 0 0-5 5v3H5v4h2v6h4v-6h3l1-4h-4V8a1 1 0 0 1 1-1h3V3z"/></svg></a>
          <a href="#contact" aria-label="Instagram"><svg viewBox="0 0 24 24"><path d="M12 2c2.7 0 3.1 0 4.1.06 1.1.05 1.8.22 2.4.47.6.24 1.1.56 1.6 1.05.5.5.8 1 1.05 1.6.25.6.42 1.3.47 2.4.06 1 .06 1.4.06 4.1s0 3.1-.06 4.1c-.05 1.1-.22 1.8-.47 2.4-.25.6-.55 1.1-1.05 1.6-.5.5-1 .8-1.6 1.05-.6.25-1.3.42-2.4.47-1 .06-1.4.06-4.1.06s-3.1 0-4.1-.06c-1.1-.05-1.8-.22-2.4-.47-.6-.25-1.1-.55-1.6-1.05-.5-.5-.8-1-1.05-1.6-.25-.6-.42-1.3-.47-2.4C2 15.1 2 14.7 2 12s0-3.1.06-4.1c.05-1.1.22-1.8.47-2.4.25-.6.55-1.1 1.05-1.6.5-.5 1-.8 1.6-1.05.6-.25 1.3-.42 2.4-.47C8.9 2 9.3 2 12 2zm0 5a5 5 0 1 0 0 10 5 5 0 0 0 0-10zm0 2a3 3 0 1 1 0 6 3 3 0 0 1 0-6zm5.5-3.3a1.2 1.2 0 1 0 0 2.4 1.2 1.2 0 0 0 0-2.4z"/></svg></a>
          <a href="https://wa.me/919814171748" aria-label="WhatsApp"><svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 0 0-8.5 15.2L2 22l4.9-1.4A10 10 0 1 0 12 2zm5.3 14.1c-.2.6-1.2 1.2-1.7 1.2-.5.1-1 .1-1.7-.1-.4-.1-1-.3-1.7-.6-2.9-1.3-4.8-4.3-5-4.5-.1-.2-1.2-1.5-1.2-2.9s.7-2 1-2.3c.2-.3.5-.3.7-.3h.5c.2 0 .4 0 .6.5l.8 2c.1.2.1.3 0 .5l-.4.6c-.1.1-.3.3-.1.6.1.3.6 1.1 1.3 1.7.9.8 1.6 1 1.9 1.2.2.1.4.1.6-.1l.8-.9c.2-.2.4-.1.6 0l1.9.9c.2.1.4.2.4.3.1.2.1.8-.1 1.2z"/></svg></a>
        </div>
      </div>
      <div>
        <h5>Quick Links</h5>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#gallery">Gallery</a></li>
          <li><a href="#testimonials">Testimonials</a></li>
          <li><a href="#contact">Contact &amp; Enquire</a></li>
        </ul>
      </div>
      <div>
        <h5>Our Services</h5>
        <ul>
          <li><a href="#catering-waiters">Catering Waiters</a></li>
          <li><a href="#waiters">Waiter Staffing</a></li>
          <li><a href="#services">Wedding Catering</a></li>
          <li><a href="#services">Corporate Events</a></li>
          <li><a href="#services">Buffet &amp; Live Counters</a></li>
          <li><a href="#services">Beverage Service</a></li>
        </ul>
      </div>
      <div>
        <h5>Get In Touch</h5>
        <p><b style="color:#e3c675;font-weight:500">Aman Ji</b><br><a href="tel:+919814171748">+91 98141 71748</a></p>
        <p><a href="mailto:hello@amancatering.in">hello@amancatering.in</a></p>
        <div style="margin-top:20px">
          <div class="foot-hrs"><span>Mon – Fri</span><span>8 AM – 10 PM</span></div>
          <div class="foot-hrs"><span>Sat – Sun</span><span>8 AM – 10 PM</span></div>
          <div class="foot-hrs" style="border:0"><span>Events</span><span>All days</span></div>
        </div>
      </div>
    </div>
    <div class="foot-bot">
      <span>&copy; <span id="yr">2026</span> Aman Catering. All rights reserved.</span>
      <span>FSSAI Compliant Kitchen · Background-Verified Staff · <a href="#admin" id="adminLink">Admin Login</a></span>
    </div>
  </div>
</footer>

<!-- FLOATERS -->
<a href="https://wa.me/919814171748" class="float f-wa" target="_blank" rel="noopener" aria-label="WhatsApp">
  <svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 0 0-8.5 15.2L2 22l4.9-1.4A10 10 0 1 0 12 2zm5.3 14.1c-.2.6-1.2 1.2-1.7 1.2-.5.1-1 .1-1.7-.1-.4-.1-1-.3-1.7-.6-2.9-1.3-4.8-4.3-5-4.5-.1-.2-1.2-1.5-1.2-2.9s.7-2 1-2.3c.2-.3.5-.3.7-.3h.5c.2 0 .4 0 .6.5l.8 2c.1.2.1.3 0 .5l-.4.6c-.1.1-.3.3-.1.6.1.3.6 1.1 1.3 1.7.9.8 1.6 1 1.9 1.2.2.1.4.1.6-.1l.8-.9c.2-.2.4-.1.6 0l1.9.9c.2.1.4.2.4.3.1.2.1.8-.1 1.2z"/></svg>
</a>
<button class="float f-top" id="toTop" aria-label="Back to top"><svg viewBox="0 0 24 24"><path d="M12 6l8 8-1.4 1.4L12 8.8l-6.6 6.6L4 14z"/></svg></button>

<!-- ======== ADMIN ======== -->
<div class="admin" id="admin">
  <!-- LOGIN -->
  <div class="ad-login" id="adLogin">
    <div class="ad-vis">
      <img src="https://images.pexels.com/photos/8921574/pexels-photo-8921574.jpeg?auto=compress&cs=tinysrgb&w=1200" alt="Waiter in black suit serving at an Aman Catering event">
      <div class="ad-vis-txt">
        <span class="eyebrow" style="color:#e3c675">Staff Area</span>
        <h2>Aman Catering<br>Management Console</h2>
        <p>Review incoming enquiries, monitor event volume and manage your service roster from one place.</p>
      </div>
    </div>
    <div class="ad-form-side">
      <div class="ad-box">
        <a href="#home" class="logo" id="adLogoLink">
          <span class="logo-mark">A</span>
          <span class="logo-txt"><strong>Aman Catering</strong><span>Admin Panel</span></span>
        </a>
        <h3>Admin Login</h3>
        <p>Authorised personnel only. Please sign in to continue.</p>
        <div class="ad-err" id="adErr">Invalid username or password. Please try again.</div>
        <form id="adForm" novalidate>
          <div class="f"><label for="adU">Username</label><input type="text" id="adU" autocomplete="username" placeholder="Enter username" required></div>
          <div class="f"><label for="adP">Password</label><input type="password" id="adP" autocomplete="current-password" placeholder="Enter password" required></div>
          <button type="submit" class="btn btn--gold">Sign In</button>
        </form>
        <div class="ad-hint">Demo credentials — <b>ansh</b> / <b>Ansh#6283</b></div>
        <a href="#home" class="ad-back" id="adBack">&larr; Back to website</a>
      </div>
    </div>
  </div>

  <!-- DASHBOARD -->
  <div class="ad-panel" id="adPanel">
    <div class="ad-bar">
      <div class="logo">
        <span class="logo-mark">A</span>
        <span class="logo-txt"><strong>Aman Catering</strong><span>Admin Dashboard</span></span>
      </div>
      <div class="ad-bar-r">
        <span style="font-size:.78rem;color:#a8a8a8">Signed in as <b style="color:#e3c675;font-weight:500">ansh</b></span>
        <button class="btn btn--ghost" id="expBtn">Export CSV</button>
        <button class="btn btn--ghost" id="clrBtn">Clear All</button>
        <button class="btn btn--gold" id="outBtn">Log Out</button>
      </div>
    </div>
    <div class="ad-body">
      <h3 style="margin-bottom:22px">Overview</h3>
      <div class="ad-kpi">
        <div class="kpi"><b id="kTotal">0</b><span>Total Enquiries</span></div>
        <div class="kpi"><b id="kNew">0</b><span>Received Today</span></div>
        <div class="kpi"><b id="kWed">0</b><span>Wedding Enquiries</span></div>
        <div class="kpi"><b id="kStaff">0</b><span>Waiter-Only Requests</span></div>
      </div>
      <h3>Enquiry Inbox</h3>
      <div id="inbox"></div>
    </div>
  </div>
</div>

<script>
(function(){
  'use strict';
  var $  = function(s,c){return (c||document).querySelector(s);};
  var $$ = function(s,c){return Array.prototype.slice.call((c||document).querySelectorAll(s));};

  /* ---- YEAR ---- */
  $('#yr').textContent = new Date().getFullYear();

  /* ---- NAV ---- */
  var nav=$('#nav'), burger=$('#burger'), menu=$('#menu');
  window.addEventListener('scroll',function(){
    nav.classList.toggle('small', window.scrollY>60);
    $('#toTop').classList.toggle('on', window.scrollY>600);
  });
  burger.addEventListener('click',function(){
    burger.classList.toggle('x'); menu.classList.toggle('open');
  });

  $$('#menu a').forEach(function(a){
    a.addEventListener('click',function(){burger.classList.remove('x');menu.classList.remove('open');});
  });
  $('#toTop').addEventListener('click',function(){window.scrollTo({top:0,behavior:'smooth'});});

  /* ---- REVEAL ---- */
  var ro=new IntersectionObserver(function(es){
    es.forEach(function(e){ if(e.isIntersecting){e.target.classList.add('in'); ro.unobserve(e.target);} });
  },{threshold:.12,rootMargin:'0px 0px -60px 0px'});

  $$('.reveal').forEach(function(el){ro.observe(el);});

  /* ---- COUNTERS ---- */
  var co=new IntersectionObserver(function(es){
    es.forEach(function(e){
      if(!e.isIntersecting) return;
      var el=e.target, to=+el.dataset.to, t0=null;
      function step(ts){
        if(!t0) t0=ts;
        var p=Math.min((ts-t0)/1600,1);
        el.textContent=Math.floor((1-Math.pow(1-p,3))*to).toLocaleString('en-IN');
        if(p<1) requestAnimationFrame(step);
      }
      requestAnimationFrame(step); co.unobserve(el);
    });
  },{threshold:.5});

  $$('.count').forEach(function(el){co.observe(el);});

  /* ---- HERO SLIDER ---- */
  var hs=$$('.hero-slide'), hd=$$('#heroDots button'), hi=0, ht;
  function goHero(i){
    hs[hi].classList.remove('on'); hd[hi].classList.remove('on');
    hi=(i+hs.length)%hs.length;
    hs[hi].classList.add('on'); hd[hi].classList.add('on');
  }
  function heroAuto(){ ht=setInterval(function(){goHero(hi+1);},6000); }
  hd.forEach(function(b,i){ b.addEventListener('click',function(){clearInterval(ht);goHero(i);heroAuto();}); });
  heroAuto();

  /* ---- GALLERY FILTER ---- */

  $$('#galFilter button').forEach(function(b){
    b.addEventListener('click',function(){

      $$('#galFilter button').forEach(function(x){x.classList.remove('on');});
      b.classList.add('on');
      var f=b.dataset.f;

      $$('#galGrid .gi').forEach(function(g){
        g.classList.toggle('hide', f!=='all' && g.dataset.cat!==f);
      });
    });
  });

  /* ---- LIGHTBOX ---- */
  var lb=$('#lb'), lbImg=$('#lbImg'), lbCap=$('#lbCap'), li=0;
  function shots(){ return $$('#galGrid .gi').filter(function(g){return !g.classList.contains('hide');}); }
  function openLb(i){
    var s=shots(); if(!s.length) return;
    li=(i+s.length)%s.length;
    var im=$('img',s[li]);
    lbImg.src=im.src.replace(/w=\d+/,'w=1600'); lbImg.alt=im.alt;
    lbCap.textContent=$('b',s[li]).textContent+' — '+$('span',s[li]).textContent;
    lb.classList.add('on'); document.body.style.overflow='hidden';
  }
  function closeLb(){ lb.classList.remove('on'); document.body.style.overflow=''; }

  $$('#galGrid .gi').forEach(function(g){
    g.addEventListener('click',function(){ openLb(shots().indexOf(g)); });
  });
  $('#lbX').addEventListener('click',closeLb);
  $('#lbP').addEventListener('click',function(e){e.stopPropagation();openLb(li-1);});
  $('#lbN').addEventListener('click',function(e){e.stopPropagation();openLb(li+1);});
  lb.addEventListener('click',function(e){ if(e.target===lb) closeLb(); });
  document.addEventListener('keydown',function(e){
    if(!lb.classList.contains('on')) return;
    if(e.key==='Escape') closeLb();
    if(e.key==='ArrowLeft') openLb(li-1);
    if(e.key==='ArrowRight') openLb(li+1);
  });

  /* ---- TESTIMONIALS ---- */
  var ti=$$('.tst-item'), td=$('#tstDots'), tc=0, tt;
  ti.forEach(function(_,i){
    var b=document.createElement('button');
    b.setAttribute('aria-label','Review '+(i+1));
    if(i===0) b.classList.add('on');
    b.addEventListener('click',function(){clearInterval(tt);goT(i);tAuto();});
    td.appendChild(b);
  });
  var tdb=$$('button',td);
  function goT(i){
    ti[tc].classList.remove('on'); tdb[tc].classList.remove('on');
    tc=(i+ti.length)%ti.length;
    ti[tc].classList.add('on'); tdb[tc].classList.add('on');
  }
  function tAuto(){ tt=setInterval(function(){goT(tc+1);},7000); }
  tAuto();

  /* ---- ENQUIRY FORM ---- */
  var KEY='aman_enquiries_v1';
  function load(){ try{ return JSON.parse(localStorage.getItem(KEY))||[]; }catch(e){ return []; } }
  function save(a){ try{ localStorage.setItem(KEY,JSON.stringify(a)); }catch(e){} }

  $('#enqForm').addEventListener('submit',function(e){
    e.preventDefault();
    var f=e.target;
    if(!f.name.value.trim()||!f.phone.value.trim()){
      alert('Please enter your name and phone number so we can reach you.'); return;
    }
    var all=load();
    all.unshift({
      id:Date.now(),
      name:f.name.value.trim(), phone:f.phone.value.trim(),
      email:f.email.value.trim()||'—', date:f.date.value||'—',
      event:f.event.value, guests:f.guests.value,
      city:f.city.value.trim()||'—', message:f.message.value.trim()||'—',
      at:new Date().toLocaleString('en-IN')
    });
    save(all);
    var ok=$('#okMsg');
    ok.innerHTML='<b>Thank you, '+f.name.value.trim().split(' ')[0]+'.</b> Your enquiry has been received. Aman Ji will call you on '+f.phone.value.trim()+' shortly. For anything urgent, reach us directly on +91 98141 71748.';
    ok.classList.add('on');
    f.reset();
    ok.scrollIntoView({behavior:'smooth',block:'center'});
    setTimeout(function(){ok.classList.remove('on');},14000);
  });

  /* ---- ADMIN ---- */
  var admin=$('#admin'), adLogin=$('#adLogin'), adPanel=$('#adPanel');
  var USER='ansh', PASS='Ansh#6283', SESS='aman_admin_session';

  function showAdmin(){
    admin.classList.add('on'); document.body.style.overflow='hidden';
    if(sessionStorage.getItem(SESS)==='1'){ enterPanel(); }
    else { adLogin.style.display='grid'; adPanel.classList.remove('on'); }
  }
  function hideAdmin(){
    admin.classList.remove('on'); document.body.style.overflow='';
    $('#adErr').classList.remove('on'); $('#adForm').reset();
    if(location.hash==='#admin'){ history.replaceState(null,'',location.pathname+location.search+'#home'); }
  }
  function enterPanel(){
    adLogin.style.display='none'; adPanel.classList.add('on'); render();
  }

  function render(){
    var all=load(), today=new Date().toLocaleDateString('en-IN');
    $('#kTotal').textContent=all.length;
    $('#kNew').textContent=all.filter(function(r){return (r.at||'').indexOf(today)===0;}).length;
    $('#kWed').textContent=all.filter(function(r){return /Wedding|Engagement/i.test(r.event);}).length;
    $('#kStaff').textContent=all.filter(function(r){return /Waiter/i.test(r.event);}).length;

    var box=$('#inbox');
    if(!all.length){
      box.innerHTML='<div class="empty">No enquiries yet. Submissions from the website Contact form will appear here automatically.</div>';
      return;
    }
    var esc=function(s){ return String(s).replace(/[&<>"]/g,function(c){return {'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c];}); };
    var rows=all.map(function(r){
      return '<tr>'+
        '<td style="white-space:nowrap">'+esc(r.at)+'</td>'+
        '<td><b style="color:#fff">'+esc(r.name)+'</b><br><span style="color:#a8a8a8;font-size:.8rem">'+esc(r.email)+'</span></td>'+
        '<td style="white-space:nowrap"><a href="tel:'+esc(r.phone)+'" style="color:#e3c675">'+esc(r.phone)+'</a></td>'+
        '<td>'+esc(r.event)+'<br><span style="color:#a8a8a8;font-size:.8rem">'+esc(r.guests)+' guests</span></td>'+
        '<td style="white-space:nowrap">'+esc(r.date)+'</td>'+
        '<td>'+esc(r.city)+'</td>'+
        '<td style="max-width:280px">'+esc(r.message)+'</td>'+
        '<td><button class="del" data-id="'+r.id+'">Delete</button></td>'+
      '</tr>';
    }).join('');
    box.innerHTML='<div class="tbl-wrap"><table><thead><tr><th>Received</th><th>Name / Email</th><th>Phone</th><th>Event</th><th>Event Date</th><th>Venue</th><th>Requirements</th><th></th></tr></thead><tbody>'+rows+'</tbody></table></div>';

    $$('.del',box).forEach(function(b){
      b.addEventListener('click',function(){
        save(load().filter(function(x){return String(x.id)!==b.dataset.id;}));
        render();
      });
    });
  }

  $('#adForm').addEventListener('submit',function(e){
    e.preventDefault();
    if($('#adU').value.trim()===USER && $('#adP').value===PASS){
      sessionStorage.setItem(SESS,'1');
      $('#adErr').classList.remove('on');
      enterPanel();
    } else {
      $('#adErr').classList.add('on');
      $('#adP').value='';
    }
  });
  $('#outBtn').addEventListener('click',function(){
    sessionStorage.removeItem(SESS);
    adPanel.classList.remove('on'); adLogin.style.display='grid';
    $('#adForm').reset(); hideAdmin();
  });
  $('#clrBtn').addEventListener('click',function(){
    if(confirm('Delete all stored enquiries? This cannot be undone.')){ save([]); render(); }
  });
  $('#expBtn').addEventListener('click',function(){
    var all=load();
    if(!all.length){ alert('There are no enquiries to export.'); return; }
    var cols=['at','name','phone','email','event','guests','date','city','message'];
    var csv=['Received,Name,Phone,Email,Event,Guests,Event Date,Venue,Requirements'];
    all.forEach(function(r){
      csv.push(cols.map(function(c){ return '"'+String(r[c]||'').replace(/"/g,'""')+'"'; }).join(','));
    });
    var url=URL.createObjectURL(new Blob([csv.join('\n')],{type:'text/csv'}));
    var a=document.createElement('a');
    a.href=url; a.download='aman-catering-enquiries.csv'; a.click();
    URL.revokeObjectURL(url);
  });

  $('#adminLink').addEventListener('click',function(e){ e.preventDefault(); location.hash='#admin'; showAdmin(); });
  $('#adBack').addEventListener('click',function(e){ e.preventDefault(); hideAdmin(); });
  $('#adLogoLink').addEventListener('click',function(e){ e.preventDefault(); hideAdmin(); });
  window.addEventListener('hashchange',function(){ location.hash==='#admin' ? showAdmin() : hideAdmin(); });
  if(location.hash==='#admin') showAdmin();
})();
</script>
</body>
</html>
