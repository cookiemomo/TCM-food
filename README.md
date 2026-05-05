<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>抗敏飲食指南｜過敏性鼻炎的飲食對策</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700;900&family=Noto+Serif+TC:wght@400;500;700;900&family=LXGW+WenKai+TC&display=swap" rel="stylesheet">
<style>
  :root{
    --cream:#F4EBDE;
    --cream-deep:#EADFCE;
    --paper:#FBF6EC;
    --ink:#2A1A10;
    --ink-soft:#4A3A2E;
    --orange:#E86A2C;
    --orange-deep:#C84E12;
    --red:#B83A2A;
    --red-deep:#8E2818;
    --red-soft:#FAE3DC;
    --green:#5C7A3D;
    --green-deep:#3F5628;
    --green-soft:#E5EDD8;
    --teal:#3F7A6A;
    --brown:#7A4A28;
    --brown-soft:#F0E2CE;
    --gold:#C8973C;
    --mustard:#E8B547;
    --yellow-soft:#FBE9B6;
    --pink:#D89B8E;
    --blue:#5B7A9C;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    font-family:'Noto Sans TC',sans-serif;
    background:var(--cream);
    color:var(--ink);
    line-height:1.75;
    overflow-x:hidden;
    background-image:
      radial-gradient(circle at 20% 10%, rgba(232,181,71,0.10) 0%, transparent 40%),
      radial-gradient(circle at 80% 60%, rgba(184,58,42,0.06) 0%, transparent 40%);
  }
  body::before{
    content:'';position:fixed;inset:0;pointer-events:none;z-index:1;
    background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='3'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.35'/%3E%3C/svg%3E");
    opacity:0.15;mix-blend-mode:multiply;
  }
  .container{max-width:1240px;margin:0 auto;padding:0 32px;position:relative;z-index:2;}

  /* TOP BAR */
  .topbar{
    border-bottom:1.5px solid var(--ink);
    padding:14px 0;
    font-size:13px;
    background:var(--paper);
    position:relative;z-index:3;
  }
  .topbar-inner{display:flex;justify-content:space-between;align-items:center;gap:24px;flex-wrap:wrap;}
  .topbar .logo{font-weight:700;font-size:15px;}
  .topbar .logo span{color:var(--orange);}
  .topbar .meta{display:flex;gap:24px;font-size:12px;opacity:0.7;}

  /* HERO */
  .hero{
    border-bottom:1.5px solid var(--ink);
    padding:60px 0 80px;
    position:relative;
    overflow:hidden;
  }
  .hero-grid{
    display:grid;
    grid-template-columns:1.1fr 1fr;
    gap:60px;
    align-items:center;
  }
  .eyebrow{
    font-size:14px;
    color:var(--red);
    margin-bottom:18px;
    display:flex;align-items:center;gap:14px;
    font-weight:700;
    letter-spacing:0.08em;
  }
  .eyebrow::before{content:'';width:50px;height:1.5px;background:var(--red);}
  h1.title{
    font-family:'Noto Serif TC',serif;
    font-weight:900;
    font-size:clamp(44px,6.5vw,86px);
    line-height:1.05;
    letter-spacing:-0.01em;
    margin-bottom:28px;
  }
  h1.title .nose{color:var(--ink);}
  h1.title .allergy{color:var(--orange);}
  h1.title .food{color:var(--green);display:block;}
  h1.title .x{color:var(--red);font-style:italic;margin:0 4px;}
  .hero-subtitle{
    font-family:'LXGW WenKai TC',serif;
    font-size:19px;
    line-height:1.8;
    color:var(--ink-soft);
    margin-bottom:32px;
    max-width:520px;
  }
  .hero-subtitle .pos{color:var(--green-deep);font-weight:700;}
  .hero-subtitle .neg{color:var(--red);font-weight:700;}
  .hero-tags{display:flex;flex-wrap:wrap;gap:10px;}
  .hero-tag{
    padding:8px 16px;
    background:var(--paper);
    border:1.5px solid var(--ink);
    border-radius:30px;
    font-size:14px;
    font-weight:500;
  }
  .hero-tag.dark{background:var(--ink);color:var(--paper);border-color:var(--ink);}
  .hero-tag.gold{background:var(--mustard);}

  /* Hero illustration */
  .hero-illust{
    position:relative;
    aspect-ratio:1;
    display:flex;
    align-items:center;
    justify-content:center;
    max-width:520px;
    margin-left:auto;
  }
  .hero-img-wrap{position:relative;width:100%;height:100%;display:flex;align-items:center;justify-content:center;}
  .hero-img-frame{
    position:relative;
    width:92%;
    aspect-ratio:1;
    border:2px solid var(--ink);
    border-radius:8px;
    overflow:hidden;
    background:var(--paper);
    box-shadow:12px 12px 0 var(--ink);
    transform:rotate(-1.5deg);
    transition:transform 0.5s cubic-bezier(0.16,1,0.3,1);
  }
  .hero-img-frame:hover{transform:rotate(0deg) scale(1.02);}
  .hero-img{width:100%;height:100%;object-fit:cover;display:block;}

  .speech-bubble{
    position:absolute;
    top:-15px;
    right:-30px;
    background:var(--paper);
    border:2px solid var(--ink);
    padding:18px 24px;
    border-radius:24px;
    box-shadow:5px 5px 0 var(--orange);
    max-width:240px;
    z-index:5;
    transform:rotate(3deg);
    animation:bobble 5s ease-in-out infinite;
    font-family:'Noto Serif TC',serif;
  }
  .speech-bubble::after{
    content:'';position:absolute;bottom:-14px;left:30px;
    width:0;height:0;border:14px solid transparent;
    border-top-color:var(--ink);border-bottom:0;border-left:0;
  }
  .speech-bubble::before{
    content:'';position:absolute;bottom:-10px;left:33px;
    width:0;height:0;border:11px solid transparent;
    border-top-color:var(--paper);border-bottom:0;border-left:0;z-index:1;
  }
  .speech-bubble .l1{display:block;font-size:15px;font-weight:700;color:var(--ink);}
  .speech-bubble .l2{display:block;font-size:17px;font-weight:900;color:var(--orange);margin-top:2px;}
  .speech-bubble .heart{color:var(--red);}
  @keyframes bobble{
    0%,100%{transform:rotate(3deg) translateY(0);}
    50%{transform:rotate(-2deg) translateY(-6px);}
  }

  .floating-tag{
    position:absolute;
    background:var(--paper);
    border:1.5px solid var(--ink);
    padding:9px 18px;
    font-size:14px;
    font-weight:700;
    border-radius:30px;
    box-shadow:3px 3px 0 var(--ink);
    z-index:3;
    white-space:nowrap;
  }
  .ftag-1{bottom:8%;left:-6%;background:var(--red);color:var(--paper);border-color:var(--ink);animation:float 4s ease-in-out infinite;}
  .ftag-2{top:42%;left:-10%;background:var(--mustard);animation:float-alt 4.5s ease-in-out infinite;}
  @keyframes float{0%,100%{transform:translateY(0) rotate(-3deg);}50%{transform:translateY(-8px) rotate(3deg);}}
  @keyframes float-alt{0%,100%{transform:translateY(0) rotate(3deg);}50%{transform:translateY(-10px) rotate(-2deg);}}

  /* INTRO PARAGRAPH */
  .intro-section{
    padding:70px 0 30px;
    border-bottom:1.5px solid var(--ink);
  }
  .intro-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:24px;
  }
  .intro-card{
    background:var(--paper);
    border:2px solid var(--ink);
    padding:32px 28px;
    box-shadow:6px 6px 0 var(--ink);
    position:relative;
  }
  .intro-card.bad{background:#FCE8E0;}
  .intro-card.good{background:#E8F0DA;}
  .intro-card .ico{
    display:inline-flex;align-items:center;justify-content:center;
    width:48px;height:48px;border-radius:50%;
    border:1.5px solid var(--ink);
    font-size:22px;font-weight:900;
    margin-bottom:14px;
  }
  .intro-card.bad .ico{background:var(--red);color:var(--paper);}
  .intro-card.good .ico{background:var(--green);color:var(--paper);}
  .intro-card h3{
    font-family:'Noto Serif TC',serif;
    font-weight:900;font-size:24px;
    margin-bottom:10px;
  }
  .intro-card p{
    font-family:'LXGW WenKai TC',serif;
    font-size:16.5px;
    color:var(--ink-soft);
    line-height:1.75;
  }
  .intro-card .arrow{
    display:inline-block;margin:0 6px;
    color:var(--ink);font-weight:900;
  }
  .intro-card.bad .arrow{color:var(--red);}
  .intro-card.good .arrow{color:var(--green);}

  /* SECTION HEADER */
  .section-header{
    text-align:center;
    padding:80px 0 40px;
  }
  .section-header .badge{
    display:inline-flex;align-items:center;gap:10px;
    padding:10px 22px;
    border:1.5px solid var(--ink);
    border-radius:40px;
    font-size:14px;font-weight:700;
    margin-bottom:20px;
    background:var(--paper);
  }
  .section-header.green .badge{background:var(--green);color:var(--paper);border-color:var(--green);}
  .section-header.red .badge{background:var(--red);color:var(--paper);border-color:var(--red);}
  .section-header h2{
    font-family:'Noto Serif TC',serif;
    font-weight:900;
    font-size:clamp(34px,4.5vw,56px);
    line-height:1.15;
    margin-bottom:16px;
  }
  .section-header.green h2 .accent{color:var(--green);}
  .section-header.red h2 .accent{color:var(--red);}
  .section-header p{
    font-family:'LXGW WenKai TC',serif;
    font-size:17px;
    color:var(--ink-soft);
    max-width:640px;
    margin:0 auto;
  }

  /* NUTRIENT CARDS (大卡片型) */
  .nutrient-list{
    display:flex;
    flex-direction:column;
    gap:24px;
  }
  .nutrient-card{
    background:var(--paper);
    border:2px solid var(--ink);
    box-shadow:8px 8px 0 var(--ink);
    overflow:hidden;
    display:grid;
    grid-template-columns:200px 1fr;
    transition:all 0.3s ease;
  }
  .nutrient-card:hover{transform:translate(-2px,-2px);box-shadow:10px 10px 0 var(--ink);}
  .nut-side{
    background:var(--green);
    color:var(--paper);
    padding:32px 24px;
    display:flex;
    flex-direction:column;
    justify-content:space-between;
    border-right:2px solid var(--ink);
  }
  .nut-side .num{
    font-family:'Noto Serif TC',serif;
    font-size:64px;
    font-weight:900;
    line-height:1;
    margin-bottom:12px;
  }
  .nut-side .icon-circle{
    width:72px;height:72px;
    background:var(--paper);
    color:var(--green);
    border:2px solid var(--ink);
    border-radius:50%;
    display:flex;align-items:center;justify-content:center;
    font-size:36px;
    margin-bottom:14px;
    box-shadow:3px 3px 0 var(--ink);
  }
  .nut-side .tagline{
    font-size:15px;
    line-height:1.5;
    opacity:0.95;
    font-family:'LXGW WenKai TC',serif;
  }
  .nut-body{padding:32px 36px;}
  .nut-body h3{
    font-family:'Noto Serif TC',serif;
    font-weight:900;
    font-size:30px;
    margin-bottom:8px;
    line-height:1.2;
  }
  .nut-body h3 .en{
    font-size:18px;
    color:var(--green);
    margin-left:10px;
    font-style:italic;
    font-weight:700;
  }
  .nut-body .subtitle{
    display:inline-block;
    background:var(--green-soft);
    color:var(--green-deep);
    padding:5px 14px;
    border-radius:20px;
    font-size:14px;
    font-weight:700;
    margin-bottom:18px;
  }
  .nut-body .mechanism{
    font-size:15.5px;
    line-height:1.85;
    color:var(--ink-soft);
    margin-bottom:20px;
  }
  .nut-body .mechanism strong{color:var(--ink);background:var(--yellow-soft);padding:0 4px;}
  .food-label{
    font-size:13px;
    font-weight:700;
    color:var(--ink);
    margin-bottom:10px;
    display:flex;align-items:center;gap:8px;
  }
  .food-label::before{
    content:'';
    display:inline-block;
    width:18px;height:2px;
    background:var(--green);
  }
  .food-chips{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:14px;}
  .food-chips:last-child{margin-bottom:0;}
  .food-chip{
    background:var(--cream);
    border:1.5px solid var(--ink);
    padding:6px 14px;
    border-radius:20px;
    font-size:14px;
    font-weight:500;
    transition:all 0.2s ease;
  }
  .food-chip:hover{
    background:var(--green);
    color:var(--paper);
    border-color:var(--green);
    transform:translateY(-2px);
  }

  /* Sub-vitamin layout */
  .vit-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:14px;
    margin-top:8px;
  }
  .vit-block{
    background:var(--cream);
    border:1.5px solid var(--ink);
    padding:16px 14px;
    border-radius:8px;
  }
  .vit-block .vlabel{
    font-family:'Noto Serif TC',serif;
    font-weight:900;
    font-size:18px;
    color:var(--green-deep);
    margin-bottom:6px;
    display:flex;align-items:center;gap:8px;
  }
  .vit-block .vlabel .vico{
    width:26px;height:26px;background:var(--green);color:var(--paper);
    border-radius:50%;display:flex;align-items:center;justify-content:center;
    font-size:12px;font-weight:900;
  }
  .vit-block .vdesc{font-size:13px;line-height:1.55;color:var(--ink-soft);margin-bottom:10px;}
  .vit-block .vfoods{font-size:12.5px;color:var(--ink);font-family:'LXGW WenKai TC',serif;}
  .vit-block .vfoods strong{color:var(--green-deep);}

  /* GUT HIGHLIGHT box */
  .gut-highlight{
    background:linear-gradient(135deg,var(--mustard) 0%,#F0C56C 100%);
    border:2px dashed var(--ink);
    padding:16px 20px;
    margin:14px 0 18px;
    border-radius:10px;
    display:flex;align-items:center;gap:14px;
  }
  .gut-num{
    font-family:'Noto Serif TC',serif;
    font-weight:900;
    font-size:42px;
    color:var(--ink);
    line-height:1;
    flex-shrink:0;
  }
  .gut-num small{font-size:20px;}
  .gut-text{
    font-size:14.5px;
    line-height:1.6;
    color:var(--ink);
    font-family:'LXGW WenKai TC',serif;
  }
  .gut-text strong{color:var(--red);font-weight:700;}

  /* TCM food rows */
  .tcm-foods{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:14px;
  }
  .tcm-food{
    background:var(--cream);
    border:1.5px solid var(--ink);
    padding:16px;
    border-radius:8px;
    text-align:center;
  }
  .tcm-food .tico{font-size:34px;line-height:1;margin-bottom:10px;display:block;}
  .tcm-food h4{
    font-family:'Noto Serif TC',serif;
    font-weight:900;font-size:18px;
    color:var(--green-deep);
    margin-bottom:6px;
  }
  .tcm-food p{font-size:12.5px;color:var(--ink-soft);line-height:1.55;}

  /* RED VARIANT */
  .nutrient-card.red-card .nut-side{background:var(--red);}
  .nutrient-card.red-card .nut-side .icon-circle{color:var(--red);}
  .nutrient-card.red-card .nut-body h3 .en{color:var(--red);}
  .nutrient-card.red-card .nut-body .subtitle{background:var(--red-soft);color:var(--red-deep);}
  .nutrient-card.red-card .food-label::before{background:var(--red);}
  .nutrient-card.red-card .food-chip:hover{background:var(--red);border-color:var(--red);}
  .nutrient-card.red-card .nut-body .mechanism strong{background:#FCD9CF;}

  /* BAD foods specific list */
  .bad-list{display:flex;flex-direction:column;gap:10px;}
  .bad-row{
    display:flex;align-items:flex-start;gap:14px;
    padding:12px 14px;
    background:var(--cream);
    border:1.5px solid var(--ink);
    border-radius:8px;
  }
  .bad-row .bemo{font-size:24px;flex-shrink:0;line-height:1.4;}
  .bad-row .btxt{font-size:14.5px;line-height:1.6;color:var(--ink);}
  .bad-row .btxt strong{color:var(--red-deep);font-weight:900;}

  /* INTERACTIVE CHECKER */
  .checker-section{padding:80px 0;border-top:1.5px solid var(--ink);background:var(--cream);}
  .checker{
    border:2px solid var(--ink);
    background:var(--paper);
    padding:48px 40px;
    box-shadow:8px 8px 0 var(--mustard);
    position:relative;
  }
  .checker-badge{
    position:absolute;top:-18px;left:32px;
    background:var(--mustard);border:1.5px solid var(--ink);
    padding:6px 16px;font-size:13px;font-weight:700;
    border-radius:30px;
  }
  .checker-header{
    display:flex;align-items:flex-start;justify-content:space-between;
    gap:20px;flex-wrap:wrap;
    margin-bottom:32px;
    border-bottom:1.5px dashed var(--ink);
    padding-bottom:24px;
  }
  .checker-header h3{font-family:'Noto Serif TC',serif;font-weight:900;font-size:30px;margin-bottom:6px;}
  .checker-header .sub{font-family:'LXGW WenKai TC',serif;font-size:15px;color:var(--ink-soft);}
  .score-display{font-size:13px;text-align:right;font-weight:600;}
  .score-num{display:block;font-family:'Noto Serif TC',serif;font-size:52px;font-weight:900;color:var(--red);line-height:1;}
  .score-num.healthy{color:var(--green);}
  .checker-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(140px,1fr));gap:10px;}
  .check-pill{
    border:1.5px solid var(--ink);background:transparent;
    padding:10px 14px;font-family:inherit;font-size:14px;
    cursor:pointer;border-radius:28px;transition:all 0.2s ease;
    color:var(--ink);
  }
  .check-pill:hover{transform:translateY(-2px);box-shadow:2px 2px 0 var(--ink);}
  .check-pill.bad.active{background:var(--red);color:var(--paper);border-color:var(--red);}
  .check-pill.good.active{background:var(--green);color:var(--paper);border-color:var(--green);}
  .verdict{
    margin-top:28px;padding:22px 26px;
    background:var(--cream);
    border-left:4px solid var(--ink);
    font-family:'LXGW WenKai TC',serif;
    font-size:16.5px;line-height:1.75;
    min-height:60px;transition:all 0.3s ease;
  }

  /* TAKEAWAY */
  .takeaway{
    padding:90px 0 100px;
    background:var(--ink);
    color:var(--paper);
    position:relative;
    overflow:hidden;
  }
  .takeaway::before{
    content:'天然 · 抗發炎 · 養腸道';
    position:absolute;
    bottom:-20px;right:-20px;
    font-family:'Noto Serif TC',serif;
    font-size:180px;font-weight:900;
    color:rgba(244,235,222,0.04);
    letter-spacing:0.08em;line-height:1;
    pointer-events:none;
  }
  .takeaway-inner{max-width:920px;margin:0 auto;text-align:center;}
  .takeaway-label{
    display:inline-block;
    background:var(--mustard);color:var(--ink);
    padding:8px 20px;border-radius:30px;
    font-size:13px;font-weight:700;
    margin-bottom:24px;
    letter-spacing:0.08em;
  }
  .takeaway h2{
    font-family:'Noto Serif TC',serif;
    font-weight:900;
    font-size:clamp(30px,4.5vw,52px);
    line-height:1.3;
    margin-bottom:32px;
  }
  .takeaway h2 .hl{color:var(--mustard);}
  .takeaway h2 .red-hl{color:#FF8A6E;}

  .summary-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:18px;
    margin-top:48px;
  }
  .summary-item{
    background:rgba(244,235,222,0.05);
    border:1.5px solid rgba(244,235,222,0.3);
    padding:22px 18px;
    text-align:center;
    transition:all 0.3s ease;
    border-radius:8px;
  }
  .summary-item:hover{
    background:var(--mustard);color:var(--ink);
    transform:translateY(-4px);
    border-color:var(--mustard);
  }
  .summary-item .sico{font-size:32px;display:block;margin-bottom:10px;}
  .summary-item h4{
    font-family:'Noto Serif TC',serif;
    font-size:16px;font-weight:900;
    margin-bottom:4px;
  }
  .summary-item p{font-size:12.5px;opacity:0.8;line-height:1.55;}
  .summary-item:hover p{opacity:1;}

  /* FOOTER */
  footer{
    background:var(--paper);
    color:var(--ink-soft);
    padding:50px 0 30px;
    border-top:1.5px solid var(--ink);
  }
  .footer-grid{display:grid;grid-template-columns:2fr 1fr;gap:40px;margin-bottom:30px;}
  footer h4{
    font-size:13px;font-weight:700;color:var(--orange);
    letter-spacing:0.08em;margin-bottom:12px;
  }
  footer p{font-size:13.5px;line-height:1.7;}
  footer p strong{color:var(--ink);}
  .footer-bottom{
    border-top:1px solid rgba(42,26,16,0.15);padding-top:20px;
    display:flex;justify-content:space-between;flex-wrap:wrap;gap:16px;
    font-size:12px;opacity:0.6;
  }

  /* RESPONSIVE */
  @media(max-width:900px){
    .hero-grid{grid-template-columns:1fr;}
    .hero-illust{max-width:380px;margin:0 auto;}
    .nutrient-card{grid-template-columns:1fr;}
    .nut-side{
      flex-direction:row;align-items:center;justify-content:flex-start;
      border-right:none;border-bottom:2px solid var(--ink);
      padding:20px 24px;gap:18px;
    }
    .nut-side .num{margin-bottom:0;font-size:48px;}
    .nut-side .icon-circle{width:54px;height:54px;font-size:26px;margin-bottom:0;}
    .nut-side .tagline{flex:1;}
    .nut-body{padding:24px 26px;}
    .vit-grid{grid-template-columns:1fr;}
    .tcm-foods{grid-template-columns:1fr;}
    .intro-grid{grid-template-columns:1fr;}
    .summary-grid{grid-template-columns:repeat(2,1fr);}
    .footer-grid{grid-template-columns:1fr;}
    .speech-bubble{right:0;top:-25px;}
  }
  @media(max-width:560px){
    .container{padding:0 20px;}
    .topbar .meta{display:none;}
    .checker{padding:32px 22px;}
    .summary-grid{grid-template-columns:1fr;}
    .nut-body h3{font-size:24px;}
    .nut-body h3 .en{font-size:14px;display:block;margin-left:0;margin-top:4px;}
  }

  .reveal{opacity:0;transform:translateY(30px);transition:all 0.8s cubic-bezier(0.16,1,0.3,1);}
  .reveal.in{opacity:1;transform:translateY(0);}
</style>
</head>
<body>

<!-- TOP BAR -->
<div class="topbar">
  <div class="container topbar-inner">
    <div class="logo">抗敏飲食指南<span>.</span></div>
    <div class="meta">
      <span>過敏性鼻炎照護</span>
      <span>飲食營養衛教</span>
    </div>
  </div>
</div>

<!-- HERO -->
<section class="hero">
  <div class="container">
    <div class="hero-grid">
      <div class="reveal">
        <div class="eyebrow">過敏性鼻炎 × 飲食對策</div>
        <h1 class="title">
          飲食<span class="x">×</span>免疫<br>
          <span class="food">打造抗敏體質</span>
        </h1>
        <p class="hero-subtitle">
          不當飲食會<span class="neg">刺激黏膜、加劇發炎</span>；<br>
          正確營養則能從根本<span class="pos">調節免疫、達到治本</span>。
        </p>
        <div class="hero-tags">
          <span class="hero-tag dark">天然原型食物</span>
          <span class="hero-tag gold">抗發炎 · 抗敏</span>
          <span class="hero-tag">養好腸道菌叢</span>
        </div>
      </div>

      <div class="hero-illust reveal">
        <div class="hero-img-wrap">
          <div class="hero-img-frame">
            <img src="data:image/jpeg;base64,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" alt="小男孩在思考食物選擇" class="hero-img"/>
          </div>
          <div class="speech-bubble">
            <span class="l1">從飲食開始</span>
            <span class="l2">建立抗敏防護網<span class="heart">❤</span></span>
          </div>
          <div class="floating-tag ftag-1">🤧 鼻子更穩定</div>
          <div class="floating-tag ftag-2">飲食 = 體質</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- INTRO -->
<section class="intro-section">
  <div class="container">
    <div class="intro-grid reveal">
      <div class="intro-card bad">
        <span class="ico">✕</span>
        <h3>吃錯了，發炎更嚴重</h3>
        <p>不當飲食 <span class="arrow">→</span> 刺激鼻黏膜 <span class="arrow">→</span> 引發或加劇身體發炎反應，使打噴嚏、流鼻水、鼻塞更難緩解。</p>
      </div>
      <div class="intro-card good">
        <span class="ico">✓</span>
        <h3>吃對了，免疫會穩定</h3>
        <p>對的營養素 <span class="arrow">→</span> 從體內調節免疫系統 <span class="arrow">→</span> 達到「抗敏」與「治本」的長期效果，讓鼻子不再頻繁過敏。</p>
      </div>
    </div>
  </div>
</section>

<!-- 🟢 GOOD NUTRIENTS SECTION -->
<section>
  <div class="container">
    <div class="section-header green reveal">
      <span class="badge">🟢 建議多吃</span>
      <h2>五大<span class="accent">抗敏營養素</span></h2>
      <p>從天然食物中攝取這些關鍵營養素，幫助身體建立穩定的抗敏防護網。</p>
    </div>

    <div class="nutrient-list">

      <!-- 01 槲皮素 -->
      <div class="nutrient-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">01</div>
            <div class="icon-circle">🍎</div>
          </div>
          <div class="tagline">天然的<br>抗組織胺</div>
        </div>
        <div class="nut-body">
          <h3>槲皮素 <span class="en">Quercetin</span></h3>
          <span class="subtitle">★ 天然抗組織胺</span>
          <p class="mechanism">
            槲皮素能<strong>抑制免疫細胞分泌組織胺</strong>，減少局部組織的發炎浸潤，有效減輕打噴嚏、流鼻水等過敏症狀。是天然食物中最受研究關注的抗敏成分之一。
          </p>
          <div class="food-label">推薦食物</div>
          <div class="food-chips">
            <span class="food-chip">🍎 帶皮蘋果</span>
            <span class="food-chip">🧅 紅洋蔥</span>
            <span class="food-chip">🌿 青蔥</span>
            <span class="food-chip">🍅 番茄</span>
            <span class="food-chip">🥦 花椰菜</span>
            <span class="food-chip">🫑 青椒</span>
            <span class="food-chip">🌱 蘆筍</span>
            <span class="food-chip">🫐 莓果類</span>
          </div>
        </div>
      </div>

      <!-- 02 Omega-3 -->
      <div class="nutrient-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">02</div>
            <div class="icon-circle">🐟</div>
          </div>
          <div class="tagline">強效<br>抗發炎</div>
        </div>
        <div class="nut-body">
          <h3>Omega-3 不飽和脂肪酸 <span class="en">Omega-3</span></h3>
          <span class="subtitle">★ 強效抗發炎</span>
          <p class="mechanism">
            Omega-3 在體內能代謝成<strong>具有抗發炎作用的物質</strong>，幫助改善呼吸道與皮膚屏障功能，抑制過敏發炎因子的產生，從源頭降低過敏反應。
          </p>
          <div class="food-label">推薦食物</div>
          <div class="food-chips">
            <span class="food-chip">🐟 鮭魚</span>
            <span class="food-chip">🐟 鯖魚</span>
            <span class="food-chip">🐟 秋刀魚</span>
            <span class="food-chip">🐟 沙丁魚</span>
            <span class="food-chip">🌾 亞麻仁油</span>
            <span class="food-chip">🌰 核桃</span>
          </div>
        </div>
      </div>

      <!-- 03 益生菌與益生元 -->
      <div class="nutrient-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">03</div>
            <div class="icon-circle">🦠</div>
          </div>
          <div class="tagline">養好<br>腸道免疫力</div>
        </div>
        <div class="nut-body">
          <h3>益生菌與益生元 <span class="en">Probiotics &amp; Prebiotics</span></h3>
          <span class="subtitle">★ 腸道是免疫核心</span>

          <div class="gut-highlight">
            <div class="gut-num">70<small>%</small></div>
            <div class="gut-text">
              人體有 <strong>70% 以上的免疫細胞</strong>位於腸道，<br>
              維持腸道微生態平衡，是調節過敏的關鍵。
            </div>
          </div>

          <p class="mechanism">
            膳食纖維（益生元）會被腸道細菌發酵成<strong>「短鏈脂肪酸」（如丁酸）</strong>，這對調節皮膚與肺部的過敏反應至關重要。每天攝取多元發酵食品與膳食纖維，能讓腸道菌叢更健康。
          </p>

          <div class="food-label">益生元（膳食纖維）</div>
          <div class="food-chips">
            <span class="food-chip">🧅 洋蔥</span>
            <span class="food-chip">🧄 大蒜</span>
            <span class="food-chip">🌱 蘆筍</span>
            <span class="food-chip">🥬 地瓜葉</span>
            <span class="food-chip">🍄 黑木耳</span>
            <span class="food-chip">🌾 全穀雜糧</span>
          </div>

          <div class="food-label">益生菌（發酵食品）</div>
          <div class="food-chips">
            <span class="food-chip">🥛 優格</span>
            <span class="food-chip">🥬 泡菜</span>
            <span class="food-chip">🍲 味噌</span>
            <span class="food-chip">🍶 天然發酵食品</span>
          </div>
        </div>
      </div>

      <!-- 04 維生素 CDE -->
      <div class="nutrient-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">04</div>
            <div class="icon-circle">☀️</div>
          </div>
          <div class="tagline">調節免疫<br>抗氧化</div>
        </div>
        <div class="nut-body">
          <h3>維生素 C、D、E <span class="en">Vitamins</span></h3>
          <span class="subtitle">★ 三大抗氧化夥伴</span>
          <p class="mechanism">
            這三種維生素分工合作：<strong>C 清除自由基</strong>、<strong>D 平衡免疫</strong>、<strong>E 抗發炎</strong>，是構成抗敏體質不可或缺的營養基礎。
          </p>

          <div class="vit-grid">
            <div class="vit-block">
              <div class="vlabel"><span class="vico">C</span>維生素 C</div>
              <div class="vdesc">清除自由基、協助分解組織胺、減緩發炎反應。</div>
              <div class="vfoods"><strong>來源</strong>：芭樂、奇異果、柑橘類、草莓</div>
            </div>
            <div class="vit-block">
              <div class="vlabel"><span class="vico">D</span>維生素 D</div>
              <div class="vdesc">充足攝取可降低過敏性鼻炎的風險與嚴重度。</div>
              <div class="vfoods"><strong>來源</strong>：日曬乾香菇、黑木耳、雞蛋、鮭魚</div>
            </div>
            <div class="vit-block">
              <div class="vlabel"><span class="vico">E</span>維生素 E</div>
              <div class="vdesc">具抗發炎功效，是脂溶性的天然抗氧化劑。</div>
              <div class="vfoods"><strong>來源</strong>：黑芝麻、花生、杏仁、酪梨</div>
            </div>
          </div>
        </div>
      </div>

      <!-- 05 中醫食療 -->
      <div class="nutrient-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">05</div>
            <div class="icon-circle">🌿</div>
          </div>
          <div class="tagline">中醫<br>食療食材</div>
        </div>
        <div class="nut-body">
          <h3>中醫食療推薦食材 <span class="en">TCM</span></h3>
          <span class="subtitle">★ 從體質根本調理</span>
          <p class="mechanism">
            中醫認為過敏性鼻炎與「肺氣不足、脾虛、體寒」有關。以下三種食材，是溫和又常見的<strong>日常調理首選</strong>。
          </p>

          <div class="tcm-foods">
            <div class="tcm-food">
              <span class="tico">🫚</span>
              <h4>生薑</h4>
              <p>含薑辣素，可驅寒、提高新陳代謝、緩和鼻塞。</p>
            </div>
            <div class="tcm-food">
              <span class="tico">🪷</span>
              <h4>蓮藕</h4>
              <p>富含黏液素，避免鼻黏膜過於乾燥，舒緩不適。</p>
            </div>
            <div class="tcm-food">
              <span class="tico">🍊</span>
              <h4>柚皮素食物</h4>
              <p>柳丁、橘子、葡萄柚的果皮含柚皮素，可抑制過敏細胞激素。</p>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- 🔴 BAD FOODS SECTION -->
<section>
  <div class="container">
    <div class="section-header red reveal">
      <span class="badge">🔴 應避開</span>
      <h2>四大<span class="accent">地雷食物</span></h2>
      <p>這些食物可能正在悄悄加劇你的過敏症狀，是體質敏感者的飲食紅燈區。</p>
    </div>

    <div class="nutrient-list">

      <!-- 01 高組織胺 -->
      <div class="nutrient-card red-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">01</div>
            <div class="icon-circle">🦐</div>
          </div>
          <div class="tagline">高組織胺<br>促發炎食物</div>
        </div>
        <div class="nut-body">
          <h3>高組織胺與促發炎食物</h3>
          <span class="subtitle">⚠ 直接誘發過敏反應</span>
          <p class="mechanism">
            魚肉變質後，細菌會使其轉變成耐熱的<strong>「組織胺」</strong>，成為誘發過敏的主因；帶殼海鮮本身也容易引發過敏反應。部分蔬菜雖然偏寒卻富含組織胺，食用後易使流鼻水加劇。
          </p>
          <div class="bad-list">
            <div class="bad-row">
              <div class="bemo">🐟</div>
              <div class="btxt"><strong>不新鮮的魚類</strong>：變質產生的組織胺耐熱，烹調後依然存在。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🦞</div>
              <div class="btxt"><strong>帶殼海鮮</strong>：蝦、蟹、蚵仔等本身就是常見過敏原。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🥬</div>
              <div class="btxt"><strong>特定蔬菜</strong>：竹筍、白菜、白蘿蔔——偏寒且富含組織胺。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🍶</div>
              <div class="btxt"><strong>醃漬品與酒精</strong>：含較高組織胺，容易誘發症狀。</div>
            </div>
          </div>
        </div>
      </div>

      <!-- 02 精緻糖加工食品 -->
      <div class="nutrient-card red-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">02</div>
            <div class="icon-circle">🍬</div>
          </div>
          <div class="tagline">精緻糖與<br>加工食品</div>
        </div>
        <div class="nut-body">
          <h3>精緻糖與加工食品</h3>
          <span class="subtitle">⚠ 加重慢性發炎</span>
          <p class="mechanism">
            甜點、手搖飲中的高糖分，以及含有<strong>色素、香料、防腐劑、人工甘味劑</strong>的加工食品（如香腸、罐頭），會加重身體的慢性發炎反應，使黏膜充血與過敏症狀更嚴重。
          </p>
          <div class="bad-list">
            <div class="bad-row">
              <div class="bemo">🥤</div>
              <div class="btxt"><strong>含糖手搖飲</strong>、甜點、糖果——高糖促發炎。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🌭</div>
              <div class="btxt"><strong>香腸、火腿、培根</strong>——添加物多，刺激呼吸道。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🥫</div>
              <div class="btxt"><strong>罐頭與即食食品</strong>——人工添加物會加劇過敏反應。</div>
            </div>
          </div>
        </div>
      </div>

      <!-- 03 寒涼食物與發物 -->
      <div class="nutrient-card red-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">03</div>
            <div class="icon-circle">🧊</div>
          </div>
          <div class="tagline">生冷寒涼<br>與發物</div>
        </div>
        <div class="nut-body">
          <h3>生冷寒涼食物與「發物」</h3>
          <span class="subtitle">⚠ 中醫角度的禁忌</span>
          <p class="mechanism">
            從中醫角度，冰品與寒性蔬果會<strong>刺激氣管收縮、損害脾胃</strong>，直接傷害鼻黏膜。同時應避免「發物」——即可能誘發舊疾或刺激特殊體質的食物。
          </p>
          <div class="bad-list">
            <div class="bad-row">
              <div class="bemo">🧊</div>
              <div class="btxt"><strong>冰水、冰品</strong>——直接刺激氣管與鼻黏膜。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🍉</div>
              <div class="btxt"><strong>寒性蔬果</strong>：冬瓜、苦瓜、西瓜、柚子、生菜沙拉。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🥭</div>
              <div class="btxt"><strong>「發物」類</strong>：芒果、荔枝、榴槤、花生——易誘發舊疾。</div>
            </div>
          </div>
        </div>
      </div>

      <!-- 04 交叉過敏原 -->
      <div class="nutrient-card red-card reveal">
        <div class="nut-side">
          <div>
            <div class="num">04</div>
            <div class="icon-circle">📓</div>
          </div>
          <div class="tagline">隱藏的<br>交叉過敏原</div>
        </div>
        <div class="nut-body">
          <h3>隱藏的交叉過敏原</h3>
          <span class="subtitle">⚠ 因人而異，需要觀察</span>
          <p class="mechanism">
            部分食物可能與呼吸道過敏存在<strong>交叉反應</strong>。建議透過「飲食日記」記錄每日攝取與症狀變化，若發現特定食物會加重症狀，應盡量避免。
          </p>
          <div class="bad-list">
            <div class="bad-row">
              <div class="bemo">🥛</div>
              <div class="btxt"><strong>牛奶</strong>——部分人會產生黏液增加感。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🥚</div>
              <div class="btxt"><strong>蛋類</strong>——常見的兒童交叉過敏原。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🌰</div>
              <div class="btxt"><strong>堅果</strong>——體質特殊者可能出現呼吸道反應。</div>
            </div>
            <div class="bad-row">
              <div class="bemo">🌾</div>
              <div class="btxt"><strong>小麥麩質</strong>——對麩質敏感者會加重發炎。</div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- INTERACTIVE CHECKER -->
<section class="checker-section">
  <div class="container">
    <div class="checker reveal">
      <span class="checker-badge">★ 互動小工具</span>
      <div class="checker-header">
        <div>
          <h3>🍽️ 你今天的鼻子加分卡</h3>
          <p class="sub">點選你今天吃過的食物，看看你的鼻子今天過得如何～</p>
        </div>
        <div class="score-display">
          <small>今日鼻子指數</small>
          <span class="score-num" id="scoreNum">—</span>
          <small id="scoreLabel">尚未開始</small>
        </div>
      </div>

      <div class="checker-grid" id="checkerGrid">
        <button class="check-pill bad" data-type="bad">🧊 冰飲</button>
        <button class="check-pill bad" data-type="bad">🦐 帶殼海鮮</button>
        <button class="check-pill bad" data-type="bad">🌭 香腸</button>
        <button class="check-pill bad" data-type="bad">🥤 手搖飲</button>
        <button class="check-pill bad" data-type="bad">🍦 冰淇淋</button>
        <button class="check-pill bad" data-type="bad">🥒 生菜沙拉</button>
        <button class="check-pill bad" data-type="bad">🥭 芒果</button>
        <button class="check-pill bad" data-type="bad">🥫 罐頭食品</button>
        <button class="check-pill good" data-type="good">🍎 帶皮蘋果</button>
        <button class="check-pill good" data-type="good">🐟 鮭魚</button>
        <button class="check-pill good" data-type="good">🥛 優格</button>
        <button class="check-pill good" data-type="good">🥬 地瓜葉</button>
        <button class="check-pill good" data-type="good">🧅 紅洋蔥</button>
        <button class="check-pill good" data-type="good">🥝 奇異果</button>
        <button class="check-pill good" data-type="good">🌰 核桃</button>
        <button class="check-pill good" data-type="good">🫚 生薑</button>
      </div>

      <div class="verdict" id="verdict">
        👀 點選你今天吃過的東西，我來告訴你今天的鼻子可能過得怎麼樣～
      </div>
    </div>
  </div>
</section>

<!-- TAKEAWAY -->
<section class="takeaway">
  <div class="container">
    <div class="takeaway-inner reveal">
      <span class="takeaway-label">★ 重點總結</span>
      <h2>
        以<span class="hl">「天然原型食物」</span>為主，<br>
        從體內打造<span class="red-hl">抗敏防護網</span>。
      </h2>

      <div class="summary-grid">
        <div class="summary-item">
          <span class="sico">🥗</span>
          <h4>多吃抗發炎蔬果</h4>
          <p>槲皮素、維生素 C、E</p>
        </div>
        <div class="summary-item">
          <span class="sico">🐟</span>
          <h4>多吃深海魚</h4>
          <p>補充 Omega-3</p>
        </div>
        <div class="summary-item">
          <span class="sico">🦠</span>
          <h4>養好腸道菌叢</h4>
          <p>益生菌＋膳食纖維</p>
        </div>
        <div class="summary-item">
          <span class="sico">🚫</span>
          <h4>避開冰冷加工</h4>
          <p>遠離高糖與組織胺</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="container">
    <div class="footer-grid">
      <div>
        <h4>關於本指南</h4>
        <p>
          本衛教內容由<strong>中國醫藥大學 健康照護學院 健康照護科學研究所</strong>製作，
          作為研究計畫之教育素材，僅供健康教育與學術研究使用。
        </p>
      </div>
      <div>
        <h4>免責聲明</h4>
        <p>
          內容僅供參考，不可取代專業醫療建議。如有過敏症狀困擾，請尋求醫師或營養師之專業協助。
        </p>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© 中國醫藥大學 健康照護學院</span>
      <span>飲食營養衛教 · 過敏性鼻炎</span>
    </div>
  </div>
</footer>

<script>
  const io = new IntersectionObserver((entries)=>{
    entries.forEach(e=>{
      if(e.isIntersecting){e.target.classList.add('in');io.unobserve(e.target);}
    });
  },{threshold:0.1});
  document.querySelectorAll('.reveal').forEach(el=>io.observe(el));

  const pills = document.querySelectorAll('.check-pill');
  const scoreNum = document.getElementById('scoreNum');
  const scoreLabel = document.getElementById('scoreLabel');
  const verdict = document.getElementById('verdict');

  function updateScore(){
    const badCount = document.querySelectorAll('.check-pill.bad.active').length;
    const goodCount = document.querySelectorAll('.check-pill.good.active').length;
    const total = badCount + goodCount;
    if(total === 0){
      scoreNum.textContent = '—';scoreNum.className = 'score-num';scoreNum.style.color='';
      scoreLabel.textContent = '尚未開始';
      verdict.innerHTML = '👀 點選你今天吃過的東西，我來告訴你今天的鼻子可能過得怎麼樣～';
      verdict.style.borderLeftColor = 'var(--ink)';
      return;
    }
    const score = Math.max(0, Math.min(100, 50 + goodCount*12 - badCount*15));
    scoreNum.textContent = score;
    if(score >= 75){
      scoreNum.className = 'score-num healthy';scoreNum.style.color='';
      scoreLabel.textContent = '鼻子很開心';
      verdict.innerHTML = '🌿 <strong>太棒了！</strong>你今天攝取了很多抗敏營養素——抗組織胺的槲皮素、抗發炎的 Omega-3、養腸道的益生菌都到位了。繼續保持！';
      verdict.style.borderLeftColor = 'var(--green)';
    }else if(score >= 50){
      scoreNum.className = 'score-num';scoreNum.style.color = 'var(--gold)';
      scoreLabel.textContent = '尚可，可以更好';
      verdict.innerHTML = '🤔 <strong>還算 OK，</strong>但有進步空間。試著減少一兩樣加工或寒涼食物，再多加一份深海魚、發酵食品或帶皮水果，鼻子會更感謝你。';
      verdict.style.borderLeftColor = 'var(--gold)';
    }else{
      scoreNum.className = 'score-num';scoreNum.style.color = 'var(--red)';
      scoreLabel.textContent = '鼻子可能在抗議';
      verdict.innerHTML = '🤧 <strong>注意一下！</strong>你今天的飲食對敏感鼻子壓力有點大。組織胺、加工添加物、寒涼食物可能正在加劇發炎，建議下一餐換成溫熱原型食物。';
      verdict.style.borderLeftColor = 'var(--red)';
    }
  }
  pills.forEach(p=>{p.addEventListener('click',()=>{p.classList.toggle('active');updateScore();});});
</script>

</body>
</html>
