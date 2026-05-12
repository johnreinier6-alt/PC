<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8" />

<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>PromoConnect Sign Up</title>



<style>

    body {

        margin: 0;

        font-family: Arial, sans-serif;

        background: #0b0f1a;

        color: #ffffff;

    }



    :root{

        --blue:#3b82f6;

        --blue-dark:#2563eb;

        --card:#111827;

        --border:#1f2937;

    }



    .layout{

        display:flex;

        min-height:100vh;

    }



    

    .left{

        flex:1;

        background:linear-gradient(135deg,#0f172a,#0b0f1a);

        display:flex;

        flex-direction:column;

        justify-content:center;

        padding:60px;

        border-right:1px solid var(--border);

    }



    .brand-logo{

        width:80px;

        height:80px;

        border-radius:20px;

        background:var(--blue);

        display:flex;

        align-items:center;

        justify-content:center;

        margin-bottom:20px;

    }



    .brand-title{

        font-size:36px;

        font-weight:800;

        margin:0;

    }



    .brand-title span{

        color:var(--blue);

    }



    .brand-text{

        color:#94a3b8;

        margin-top:10px;

        max-width:400px;

        line-height:1.5;

    }



   

    .right{

        flex:1;

        display:flex;

        align-items:center;

        justify-content:center;

        padding:20px;

    }



    .container {

        width:100%;

        max-width:420px;

        background: var(--card);

        padding: 22px;

        border-radius: 16px;

        border: 1px solid var(--border);

        box-shadow: 0 10px 30px rgba(0,0,0,0.5);

    }



    h2 {

        margin: 10px 0 5px;

        font-size: 20px;

    }



    .subtitle{

        color:#94a3b8;

        font-size:13px;

        margin-bottom:15px;

    }



  

    .tabs{

        display:flex;

        gap:10px;

        margin-bottom:15px;

    }



    .tab{

        flex:1;

        text-align:center;

        padding:10px;

        border-radius:10px;

        cursor:pointer;

        font-weight:bold;

        background:#0f172a;

        border:1px solid var(--border);

        color:#94a3b8;

    }



    .tab.active{

        background:var(--blue);

        color:white;

    }



    input, select {

        width: 100%;

        padding: 12px;

        margin: 8px 0;

        border-radius: 10px;

        border: 1px solid var(--border);

        background: #0f172a;

        color: #ffffff;

        outline: none;

    }



    input::placeholder {

        color: #64748b;

    }



    .btn {

        background: var(--blue);

        color: white;

        padding: 12px;

        border: none;

        width: 100%;

        border-radius: 25px;

        margin-top: 10px;

        cursor: pointer;

        font-weight: bold;

    }



    .btn:hover {

        background: var(--blue-dark);

    }



    .hidden { display:none; }



    /* MOBILE */

    @media(max-width:900px){

        .layout{flex-direction:column;}

        .left{padding:30px; text-align:center;}

<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8" />

<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>PromoConnect Sign Up</title>



<style>

    body {

        margin: 0;

        font-family: Arial, sans-serif;

        background: #0b0f1a;

        color: #ffffff;

    }



    :root{

        --blue:#3b82f6;

        --blue-dark:#2563eb;

        --card:#111827;

        --border:#1f2937;

    }



    .layout{

        display:flex;

        min-height:100vh;

    }



    

    .left{

        flex:1;

        background:linear-gradient(135deg,#0f172a,#0b0f1a);

        display:flex;

        flex-direction:column;

        justify-content:center;

        padding:60px;

        border-right:1px solid var(--border);

    }



    .brand-logo{

        width:80px;

        height:80px;

        border-radius:20px;

        background:var(--blue);

        display:flex;

        align-items:center;

        justify-content:center;

        margin-bottom:20px;

    }



    .brand-title{

        font-size:36px;

        font-weight:800;

        margin:0;

    }



    .brand-title span{

        color:var(--blue);

    }



    .brand-text{

        color:#94a3b8;

        margin-top:10px;

        max-width:400px;

        line-height:1.5;

    }



   

    .right{

        flex:1;

        display:flex;

        align-items:center;

        justify-content:center;

        padding:20px;

    }



    .container {

        width:100%;

        max-width:420px;

        background: var(--card);

        padding: 22px;

        border-radius: 16px;

        border: 1px solid var(--border);

        box-shadow: 0 10px 30px rgba(0,0,0,0.5);

    }



    h2 {

        margin: 10px 0 5px;

        font-size: 20px;

    }



    .subtitle{

        color:#94a3b8;

        font-size:13px;

        margin-bottom:15px;

    }



  

    .tabs{

        display:flex;

        gap:10px;

        margin-bottom:15px;

    }



    .tab{

        flex:1;

        text-align:center;

        padding:10px;

        border-radius:10px;

        cursor:pointer;

        font-weight:bold;

        background:#0f172a;

        border:1px solid var(--border);

        color:#94a3b8;

    }



    .tab.active{

        background:var(--blue);

        color:white;

    }



    input, select {

        width: 100%;

        padding: 12px;

        margin: 8px 0;

        border-radius: 10px;

        border: 1px solid var(--border);

        background: #0f172a;

        color: #ffffff;

        outline: none;

    }



    input::placeholder {

        color: #64748b;

    }



    .btn {

        background: var(--blue);

        color: white;

        padding: 12px;

        border: none;

        width: 100%;

        border-radius: 25px;

        margin-top: 10px;

        cursor: pointer;

        font-weight: bold;

    }



    .btn:hover {

        background: var(--blue-dark);

    }



    .hidden { display:none; }



    /* MOBILE */

    @media(max-width:900px){

        .layout{flex-direction:column;}

        .left{padding:30px; text-align:center;}

        .brand-text{margin:auto;}

    }

</style>

</head>



<body>



<div class="layout">



    <!-- LEFT BRAND -->

    <div class="left">

        <div class="brand-logo">

            <svg width="40" height="40" viewBox="0 0 24 24" fill="none">

                <path d="M6 6H4" stroke="white" stroke-width="2"/>

                <path d="M4 6L6 14C6.5 16 8 17 10 17H16C18 17 19.5 16 20 14L22 8H6" stroke="white" stroke-width="2"/>

                <path d="M9 21C9.5 21 10 20.5 10 20C10 19.5 9.5 19 9 19C8.5 19 8 19.5 8 20C8 20.5 8.5 21 9 21Z" stroke="white"/>

                <path d="M17 21C17.5 21 18 20.5 18 20C18 19.5 17.5 19 17 19C16.5 19 16 19.5 16 20C16 20.5 16.5 21 17 21Z" stroke="white"/>

                <path d="M12 8V4M12 4L10 6M12 4L14 6" stroke="white"/>

            </svg>

        </div>



        <h1 class="brand-title">Promo<span>Connect</span></h1>

        <p class="brand-text">

            Discover promos, grow your business, and connect customers with exclusive deals in real time.

        </p>

    </div>



    

    <div class="right">



        <div class="container">



            <div class="tabs">

                <div class="tab active" onclick="show('customer')" id="tabCustomer">Customer</div>

                <div class="tab" onclick="show('business')" id="tabBusiness">Admin</div>

            </div>



            <!-- CUSTOMER -->

            <div id="customer">

                <h2>Create Customer Account</h2>

                <div class="subtitle">Join promos and earn rewards instantly</div>



                <input type="text" placeholder="Full Name" />

                <input type="email" placeholder="Email Address" />

                <input type="password" placeholder="Password" />



                <select>

                    <option>Preferred Category</option>

                    <option>Food</option>

                    <option>Drinks</option>

                    <option>Coffee</option>

                </select>



                <button class="btn" onclick="register('customer')">

                    Create Customer Account

                </button>

            </div>



            <!-- ADMIN -->

            <div id="business" class="hidden">

                <h2>Create Admin Account</h2>

                <div class="subtitle">Promote your shop and attract customers</div>



                <input type="text" placeholder="Business Name" />

                <input type="text" placeholder="Owner Name" />

                <input type="email" placeholder="Business Email" />

                <input type="password" placeholder="Password" />

                <input type="text" placeholder="Business Address" />



                <select>

                    <option>Business Category</option>

                    <option>Restaurant</option>

                    <option>Cafe</option>

                    <option>Retail Shop</option>

                </select>



                <button class="btn" onclick="register('admin')">

                    Create Admin Account

                </button>

            </div>



        </div>



    </div>



</div>



<script>

function show(type){

    document.getElementById('customer').classList.add('hidden');

    document.getElementById('business').classList.add('hidden');



    document.getElementById('tabCustomer').classList.remove('active');

    document.getElementById('tabBusiness').classList.remove('active');



    if(type==='customer'){

        document.getElementById('customer').classList.remove('hidden');

        document.getElementById('tabCustomer').classList.add('active');

    } else {

        document.getElementById('business').classList.remove('hidden');

        document.getElementById('tabBusiness').classList.add('active');

    }

}





function register(type){

    if(type === 'customer'){

        window.location.href = "customer.html";

    } 

    else if(type === 'admin'){

        window.location.href = "admin.html";

    }

}

</script>



</body>

</html>        .brand-text{margin:auto;}

    }

</style>

</head>



<body>



<div class="layout">



    <!-- LEFT BRAND -->

    <div class="left">

        <div class="brand-logo">

            <svg width="40" height="40" viewBox="0 0 24 24" fill="none">


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>PromoConnect Customer</title>
<style>
:root{
    --bg:#f6f3ee;
    --surface:#ffffff;
    --surface-2:#fff8ec;
    --ink:#1f2937;
    --muted:#687385;
    --line:#eadfce;
    --brand:#b83226;
    --brand-2:#f2a900;
    --brand-dark:#8f241c;
    --green:#0f9f7a;
    --blue:#2563eb;
    --shadow:0 18px 45px rgba(73,43,24,.14);
}

*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

body{
    min-height:100vh;
    font-family:Arial,Helvetica,sans-serif;
    background:
        radial-gradient(circle at 15% 8%, rgba(242,169,0,.22), transparent 30%),
        radial-gradient(circle at 90% 18%, rgba(184,50,38,.13), transparent 28%),
        var(--bg);
    color:var(--ink);
}

button,
input,
textarea,
select{
    font:inherit;
}

button{
    border:0;
    cursor:pointer;
}

.app{
    width:min(100%,480px);
    min-height:100vh;
    margin:auto;
    background:var(--surface);
    box-shadow:var(--shadow);
    position:relative;
    overflow:hidden;
}

.topbar{
    position:sticky;
    top:0;
    z-index:10;
    background:rgba(255,255,255,.92);
    backdrop-filter:blur(18px);
    border-bottom:1px solid var(--line);
    padding:16px 18px 14px;
}

.top-row{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:12px;
}

.brand{
    display:flex;
    align-items:center;
    gap:10px;
    font-weight:900;
}

.brand-mark{
    width:38px;
    height:38px;
    border-radius:14px;
    background:linear-gradient(135deg,var(--brand),var(--brand-2));
    color:#fff;
    display:grid;
    place-items:center;
    font-weight:900;
    box-shadow:0 10px 22px rgba(184,50,38,.28);
}

.route{
    margin-top:2px;
    color:var(--muted);
    font-size:12px;
    font-weight:800;
    letter-spacing:.08em;
    text-transform:uppercase;
}

.icon-btn{
    width:42px;
    height:42px;
    border-radius:50%;
    display:grid;
    place-items:center;
    background:var(--surface-2);
    color:var(--brand);
    border:1px solid var(--line);
    position:relative;
}

.icon-btn svg{
    width:20px;
    height:20px;
}

.badge{
    position:absolute;
    top:7px;
    right:7px;
    width:9px;
    height:9px;
    border-radius:50%;
    background:var(--green);
    border:2px solid #fff;
}

.container{
    padding:16px 18px 96px;
}

.screen{
    display:none;
    animation:fade .18s ease both;
}

.screen.active{
    display:block;
}

@keyframes fade{
    from{opacity:0;transform:translateY(8px)}
    to{opacity:1;transform:translateY(0)}
}

.hero{
    color:#fff;
    border-radius:24px;
    padding:20px;
    min-height:180px;
    background:
        linear-gradient(115deg, rgba(40,26,15,.82), rgba(184,50,38,.72)),
        url("https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=900&q=80") center/cover;
    display:flex;
    flex-direction:column;
    justify-content:space-between;
    overflow:hidden;
}

.hero h1{
    max-width:310px;
    font-size:29px;
    line-height:1.05;
    letter-spacing:0;
}

.hero p{
    max-width:300px;
    margin-top:8px;
    color:rgba(255,255,255,.86);
    font-size:14px;
    line-height:1.45;
}

.hero-actions{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:10px;
    margin-top:20px;
}

.points-pill{
    display:inline-flex;
    align-items:center;
    gap:8px;
    min-height:38px;
    padding:0 13px;
    border-radius:999px;
    background:rgba(255,255,255,.18);
    color:#fff;
    font-weight:900;
    border:1px solid rgba(255,255,255,.22);
}

.btn{
    min-height:42px;
    border-radius:999px;
    padding:0 16px;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    gap:8px;
    color:#fff;
    background:var(--brand);
    font-weight:900;
    transition:.16s ease;
}

.btn:hover{
    background:var(--brand-dark);
}

.btn:active,
.nav-btn:active,
.promo-card:active,
.shop-card:active{
    transform:scale(.98);
}

.btn.secondary{
    color:var(--ink);
    background:#fff;
}

.btn.soft{
    color:var(--brand);
    background:#fbe9df;
}

.btn.dark{
    color:#fff;
    background:var(--ink);
}

.btn.full{
    width:100%;
}

.btn:disabled{
    opacity:.48;
    cursor:not-allowed;
}

.section-head{
    margin:24px 0 12px;
    display:flex;
    align-items:end;
    justify-content:space-between;
    gap:12px;
}

.section-head h2{
    font-size:18px;
    letter-spacing:0;
}

.section-head span,
.section-head button{
    color:var(--muted);
    background:transparent;
    font-size:13px;
    font-weight:800;
}

.search{
    min-height:48px;
    display:flex;
    align-items:center;
    gap:10px;
    padding:0 14px;
    background:#fbf7f1;
    border:1px solid var(--line);
    border-radius:18px;
}

.search svg{
    width:18px;
    height:18px;
    color:var(--muted);
}

.search input{
    width:100%;
    min-width:0;
    border:0;
    outline:0;
    background:transparent;
    color:var(--ink);
}

.filters{
    display:flex;
    gap:8px;
    overflow-x:auto;
    padding:12px 0 2px;
    scrollbar-width:none;
}

.filters::-webkit-scrollbar,
.horizontal::-webkit-scrollbar{
    display:none;
}

.chip{
    flex:0 0 auto;
    min-height:34px;
    border-radius:999px;
    padding:0 13px;
    background:#fbf7f1;
    color:var(--muted);
    border:1px solid var(--line);
    font-size:13px;
    font-weight:900;
}

.chip.active{
    background:var(--ink);
    color:#fff;
    border-color:var(--ink);
}

.horizontal{
    display:grid;
    grid-auto-flow:column;
    grid-auto-columns:78%;
    gap:12px;
    overflow-x:auto;
    scrollbar-width:none;
    padding:2px 0 4px;
}

.promo-card,
.shop-card,
.panel,
.reward-card,
.profile-card{
    background:var(--surface);
    border:1px solid var(--line);
    border-radius:12px;
    overflow:hidden;
}

.promo-card{
    min-height:132px;
    padding:16px;
    color:#fff;
    border:0;
    display:flex;
    flex-direction:column;
    justify-content:space-between;
    background:linear-gradient(135deg,var(--brand),#df7d24);
    box-shadow:0 12px 24px rgba(184,50,38,.18);
}

.promo-card:nth-child(2){
    background:linear-gradient(135deg,#a1261d,#f2a900);
}

.promo-card:nth-child(3){
    background:linear-gradient(135deg,#165e54,#f2a900);
}

.promo-card h3{
    font-size:19px;
    line-height:1.15;
}

.promo-card p{
    margin-top:6px;
    font-size:13px;
    color:rgba(255,255,255,.82);
}

.tag{
    width:max-content;
    min-height:25px;
    border-radius:999px;
    padding:0 9px;
    display:inline-flex;
    align-items:center;
    background:#fff;
    color:var(--brand);
    font-size:11px;
    font-weight:900;
}

.shop-list{
    display:grid;
    gap:12px;
}

.shop-card{
    display:grid;
    grid-template-columns:86px 1fr;
    min-height:96px;
    text-align:left;
    color:inherit;
    width:100%;
}

.shop-card img{
    width:86px;
    height:100%;
    object-fit:cover;
}

.shop-body{
    padding:12px;
}

.shop-body h3,
.reward-card h3,
.profile-card h3{
    font-size:15px;
    line-height:1.2;
}

.meta{
    margin-top:5px;
    color:var(--muted);
    font-size:12px;
    line-height:1.35;
}

.shop-foot{
    margin-top:10px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:8px;
}

.small-link{
    color:var(--brand);
    font-size:12px;
    font-weight:900;
}

.detail{
    display:none;
    margin-top:12px;
    padding:16px;
    border-radius:12px;
    background:var(--surface-2);
    border:1px solid var(--line);
}

.detail.active{
    display:block;
}

.detail h3{
    font-size:18px;
}

.detail p{
    margin-top:7px;
    color:var(--muted);
    font-size:13px;
    line-height:1.45;
}

.points-card{
    border-radius:24px;
    padding:20px;
    color:#fff;
    background:linear-gradient(135deg,var(--brand),var(--brand-2));
    box-shadow:0 14px 28px rgba(184,50,38,.2);
}

.points-card p{
    color:rgba(255,255,255,.84);
    font-size:13px;
}

.points-value{
    margin:8px 0;
    font-size:58px;
    line-height:.95;
    font-weight:900;
}

.progress{
    height:10px;
    margin-top:10px;
    border-radius:999px;
    background:rgba(255,255,255,.28);
    overflow:hidden;
}

.progress span{
    display:block;
    width:var(--value);
    height:100%;
    border-radius:inherit;
    background:#fff;
}

.tabs{
    margin:14px 0;
    padding:5px;
    border-radius:999px;
    background:#fbf7f1;
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:5px;
}

.tab{
    min-height:36px;
    border-radius:999px;
    background:transparent;
    color:var(--muted);
    font-size:12px;
    font-weight:900;
}

.tab.active{
    color:var(--ink);
    background:#fff;
    box-shadow:0 8px 16px rgba(73,43,24,.08);
}

.reward-list{
    display:grid;
    gap:10px;
}

.reward-card{
    padding:14px;
    display:grid;
    grid-template-columns:48px 1fr auto;
    align-items:center;
    gap:12px;
}

.reward-icon,
.list-icon{
    width:48px;
    height:48px;
    border-radius:16px;
    display:grid;
    place-items:center;
    color:#fff;
    background:var(--brand);
    font-weight:900;
}

.reward-card:nth-child(2) .reward-icon{
    background:var(--green);
}

.reward-card:nth-child(3) .reward-icon{
    background:var(--blue);
}

.mini-btn{
    min-height:34px;
    border-radius:999px;
    padding:0 12px;
    background:var(--ink);
    color:#fff;
    font-size:12px;
    font-weight:900;
}

.mini-btn:disabled{
    opacity:.45;
}

.panel{
    margin-top:12px;
}

.list-row{
    width:100%;
    min-height:72px;
    padding:14px;
    background:#fff;
    color:inherit;
    text-align:left;
    display:grid;
    grid-template-columns:46px 1fr auto;
    align-items:center;
    gap:12px;
    border-bottom:1px solid var(--line);
}

.list-row:last-child{
    border-bottom:0;
}

.list-icon{
    width:46px;
    height:46px;
    border-radius:15px;
}

.list-row:nth-child(2) .list-icon{
    background:var(--green);
}

.list-row:nth-child(3) .list-icon{
    background:var(--brand-2);
    color:#1f2937;
}

.chev{
    color:var(--muted);
    font-size:21px;
}

.form-panel{
    display:none;
    margin-top:12px;
    padding:15px;
    border:1px solid var(--line);
    border-radius:12px;
    background:#fff;
}

.form-panel.active{
    display:block;
}

.field{
    margin-bottom:12px;
}

.field label{
    display:block;
    margin-bottom:6px;
    color:var(--muted);
    font-size:12px;
    font-weight:900;
}

.field input,
.field textarea,
.field select{
    width:100%;
    border:1px solid var(--line);
    border-radius:15px;
    background:#fbf7f1;
    padding:12px;
    outline:0;
}

.field textarea{
    min-height:88px;
    resize:none;
    line-height:1.45;
}

.chat{
    min-height:220px;
    max-height:260px;
    overflow-y:auto;
    display:flex;
    flex-direction:column;
    gap:9px;
    padding-right:2px;
}

.bubble{
    width:fit-content;
    max-width:82%;
    border-radius:18px;
    padding:10px 12px;
    background:#fbf7f1;
    color:var(--ink);
    font-size:13px;
    line-height:1.4;
}

.bubble.me{
    margin-left:auto;
    color:#fff;
    background:var(--brand);
}

.compose{
    display:grid;
    grid-template-columns:1fr 44px;
    gap:8px;
    margin-top:12px;
}

.profile-card{
    padding:16px;
}

.profile-top{
    text-align:center;
}

.avatar{
    width:88px;
    height:88px;
    margin:0 auto 14px;
    border-radius:50%;
    background:linear-gradient(135deg,var(--brand),var(--brand-2));
    color:#fff;
    display:grid;
    place-items:center;
    font-size:34px;
    font-weight:900;
    box-shadow:0 12px 24px rgba(184,50,38,.18);
}

.stats{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:10px;
}

.stat{
    border:1px solid var(--line);
    border-radius:12px;
    padding:14px;
    background:#fff;
}

.stat strong{
    display:block;
    font-size:24px;
}

.setting{
    min-height:60px;
    padding:14px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:12px;
    border-bottom:1px solid var(--line);
}

.setting:last-child{
    border-bottom:0;
}

.switch{
    position:relative;
    width:48px;
    height:28px;
    flex:0 0 auto;
}

.switch input{
    opacity:0;
}

.slider{
    position:absolute;
    inset:0;
    border-radius:999px;
    background:#d9d0c2;
    transition:.16s ease;
}

.slider:before{
    content:"";
    position:absolute;
    width:22px;
    height:22px;
    top:3px;
    left:3px;
    border-radius:50%;
    background:#fff;
    box-shadow:0 4px 10px rgba(31,41,55,.2);
    transition:.16s ease;
}

.switch input:checked + .slider{
    background:var(--green);
}

.switch input:checked + .slider:before{
    transform:translateX(20px);
}

.nav{
    position:fixed;
    left:50%;
    bottom:14px;
    transform:translateX(-50%);
    width:min(calc(100% - 28px),452px);
    min-height:76px;
    border-radius:28px;
    background:rgba(255,255,255,.94);
    border:1px solid var(--line);
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:4px;
    padding:8px;
    box-shadow:0 12px 30px rgba(73,43,24,.16);
    backdrop-filter:blur(18px);
}

.nav-btn{
    border-radius:22px;
    background:transparent;
    color:var(--muted);
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    gap:4px;
    font-size:11px;
    font-weight:900;
}

.nav-btn svg{
    width:21px;
    height:21px;
}

.nav-btn.active{
    color:var(--brand);
    background:#fbe9df;
}

.toast{
    position:fixed;
    left:50%;
    bottom:102px;
    transform:translate(-50%,12px);
    width:min(calc(100% - 44px),420px);
    min-height:46px;
    padding:11px 14px;
    border-radius:18px;
    background:rgba(31,41,55,.96);
    color:#fff;
    display:grid;
    place-items:center;
    text-align:center;
    font-size:13px;
    font-weight:900;
    opacity:0;
    pointer-events:none;
    transition:.18s ease;
    z-index:30;
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>PromoConnect Customer</title>
<style>
:root{
    --bg:#f6f3ee;
    --surface:#ffffff;
    --surface-2:#fff8ec;
    --ink:#1f2937;
    --muted:#687385;
    --line:#eadfce;
    --brand:#b83226;
    --brand-2:#f2a900;
    --brand-dark:#8f241c;
    --green:#0f9f7a;
    --blue:#2563eb;
    --shadow:0 18px 45px rgba(73,43,24,.14);
}

*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

body{
    min-height:100vh;
    font-family:Arial,Helvetica,sans-serif;
    background:
        radial-gradient(circle at 15% 8%, rgba(242,169,0,.22), transparent 30%),
        radial-gradient(circle at 90% 18%, rgba(184,50,38,.13), transparent 28%),
        var(--bg);
    color:var(--ink);
}

button,
input,
textarea,
select{
    font:inherit;
}

button{
    border:0;
    cursor:pointer;
}

.app{
    width:min(100%,480px);
    min-height:100vh;
    margin:auto;
    background:var(--surface);
    box-shadow:var(--shadow);
    position:relative;
    overflow:hidden;
}

.topbar{
    position:sticky;
    top:0;
    z-index:10;
    background:rgba(255,255,255,.92);
    backdrop-filter:blur(18px);
    border-bottom:1px solid var(--line);
    padding:16px 18px 14px;
}

.top-row{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:12px;
}

.brand{
    display:flex;
    align-items:center;
    gap:10px;
    font-weight:900;
}

.brand-mark{
    width:38px;
    height:38px;
    border-radius:14px;
    background:linear-gradient(135deg,var(--brand),var(--brand-2));
    color:#fff;
    display:grid;
    place-items:center;
    font-weight:900;
    box-shadow:0 10px 22px rgba(184,50,38,.28);
}

.route{
    margin-top:2px;
    color:var(--muted);
    font-size:12px;
    font-weight:800;
    letter-spacing:.08em;
    text-transform:uppercase;
}

.icon-btn{
    width:42px;
    height:42px;
    border-radius:50%;
    display:grid;
    place-items:center;
    background:var(--surface-2);
    color:var(--brand);
    border:1px solid var(--line);
    position:relative;
}

.icon-btn svg{
    width:20px;
    height:20px;
}

.badge{
    position:absolute;
    top:7px;
    right:7px;
    width:9px;
    height:9px;
    border-radius:50%;
    background:var(--green);
    border:2px solid #fff;
}

.container{
    padding:16px 18px 96px;
}

.screen{
    display:none;
    animation:fade .18s ease both;
}

.screen.active{
    display:block;
}

@keyframes fade{
    from{opacity:0;transform:translateY(8px)}
    to{opacity:1;transform:translateY(0)}
}

.hero{
    color:#fff;
    border-radius:24px;
    padding:20px;
    min-height:180px;
    background:
        linear-gradient(115deg, rgba(40,26,15,.82), rgba(184,50,38,.72)),
        url("https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=900&q=80") center/cover;
    display:flex;
    flex-direction:column;
    justify-content:space-between;
    overflow:hidden;
}

.hero h1{
    max-width:310px;
    font-size:29px;
    line-height:1.05;
    letter-spacing:0;
}

.hero p{
    max-width:300px;
    margin-top:8px;
    color:rgba(255,255,255,.86);
    font-size:14px;
    line-height:1.45;
}

.hero-actions{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:10px;
    margin-top:20px;
}

.points-pill{
    display:inline-flex;
    align-items:center;
    gap:8px;
    min-height:38px;
    padding:0 13px;
    border-radius:999px;
    background:rgba(255,255,255,.18);
    color:#fff;
    font-weight:900;
    border:1px solid rgba(255,255,255,.22);
}

.btn{
    min-height:42px;
    border-radius:999px;
    padding:0 16px;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    gap:8px;
    color:#fff;
    background:var(--brand);
    font-weight:900;
    transition:.16s ease;
}

.btn:hover{
    background:var(--brand-dark);
}

.btn:active,
.nav-btn:active,
.promo-card:active,
.shop-card:active{
    transform:scale(.98);
}

.btn.secondary{
    color:var(--ink);
    background:#fff;
}

.btn.soft{
    color:var(--brand);
    background:#fbe9df;
}

.btn.dark{
    color:#fff;
    background:var(--ink);
}

.btn.full{
    width:100%;
}

.btn:disabled{
    opacity:.48;
    cursor:not-allowed;
}

.section-head{
    margin:24px 0 12px;
    display:flex;
    align-items:end;
    justify-content:space-between;
    gap:12px;
}

.section-head h2{
    font-size:18px;
    letter-spacing:0;
}

.section-head span,
.section-head button{
    color:var(--muted);
    background:transparent;
    font-size:13px;
    font-weight:800;
}

.search{
    min-height:48px;
    display:flex;
    align-items:center;
    gap:10px;
    padding:0 14px;
    background:#fbf7f1;
    border:1px solid var(--line);
    border-radius:18px;
}

.search svg{
    width:18px;
    height:18px;
    color:var(--muted);
}

.search input{
    width:100%;
    min-width:0;
    border:0;
    outline:0;
    background:transparent;
    color:var(--ink);
}

.filters{
    display:flex;
    gap:8px;
    overflow-x:auto;
    padding:12px 0 2px;
    scrollbar-width:none;
}

.filters::-webkit-scrollbar,
.horizontal::-webkit-scrollbar{
    display:none;
}

.chip{
    flex:0 0 auto;
    min-height:34px;
    border-radius:999px;
    padding:0 13px;
    background:#fbf7f1;
    color:var(--muted);
    border:1px solid var(--line);
    font-size:13px;
    font-weight:900;
}

.chip.active{
    background:var(--ink);
    color:#fff;
    border-color:var(--ink);
}

.horizontal{
    display:grid;
    grid-auto-flow:column;
    grid-auto-columns:78%;
    gap:12px;
    overflow-x:auto;
    scrollbar-width:none;
    padding:2px 0 4px;
}

.promo-card,
.shop-card,
.panel,
.reward-card,
.profile-card{
    background:var(--surface);
    border:1px solid var(--line);
    border-radius:12px;
    overflow:hidden;
}

.promo-card{
    min-height:132px;
    padding:16px;
    color:#fff;
    border:0;
    display:flex;
    flex-direction:column;
    justify-content:space-between;
    background:linear-gradient(135deg,var(--brand),#df7d24);
    box-shadow:0 12px 24px rgba(184,50,38,.18);
}

.promo-card:nth-child(2){
    background:linear-gradient(135deg,#a1261d,#f2a900);
}

.promo-card:nth-child(3){
    background:linear-gradient(135deg,#165e54,#f2a900);
}

.promo-card h3{
    font-size:19px;
    line-height:1.15;
}

.promo-card p{
    margin-top:6px;
    font-size:13px;
    color:rgba(255,255,255,.82);
}

.tag{
    width:max-content;
    min-height:25px;
    border-radius:999px;
    padding:0 9px;
    display:inline-flex;
    align-items:center;
    background:#fff;
    color:var(--brand);
    font-size:11px;
    font-weight:900;
}

.shop-list{
    display:grid;
    gap:12px;
}

.shop-card{
    display:grid;
    grid-template-columns:86px 1fr;
    min-height:96px;
    text-align:left;
    color:inherit;
    width:100%;
}

.shop-card img{
    width:86px;
    height:100%;
    object-fit:cover;
}

.shop-body{
    padding:12px;
}

.shop-body h3,
.reward-card h3,
.profile-card h3{
    font-size:15px;
    line-height:1.2;
}

.meta{
    margin-top:5px;
    color:var(--muted);
    font-size:12px;
    line-height:1.35;
}

.shop-foot{
    margin-top:10px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:8px;
}

.small-link{
    color:var(--brand);
    font-size:12px;
    font-weight:900;
}

.detail{
    display:none;
    margin-top:12px;
    padding:16px;
    border-radius:12px;
    background:var(--surface-2);
    border:1px solid var(--line);
}

.detail.active{
    display:block;
}

.detail h3{
    font-size:18px;
}

.detail p{
    margin-top:7px;
    color:var(--muted);
    font-size:13px;
    line-height:1.45;
}

.points-card{
    border-radius:24px;
    padding:20px;
    color:#fff;
    background:linear-gradient(135deg,var(--brand),var(--brand-2));
    box-shadow:0 14px 28px rgba(184,50,38,.2);
}

.points-card p{
    color:rgba(255,255,255,.84);
    font-size:13px;
}

.points-value{
    margin:8px 0;
    font-size:58px;
    line-height:.95;
    font-weight:900;
}

.progress{
    height:10px;
    margin-top:10px;
    border-radius:999px;
    background:rgba(255,255,255,.28);
    overflow:hidden;
}

.progress span{
    display:block;
    width:var(--value);
    height:100%;
    border-radius:inherit;
    background:#fff;
}

.tabs{
    margin:14px 0;
    padding:5px;
    border-radius:999px;
    background:#fbf7f1;
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:5px;
}

.tab{
    min-height:36px;
    border-radius:999px;
    background:transparent;
    color:var(--muted);
    font-size:12px;
    font-weight:900;
}

.tab.active{
    color:var(--ink);
    background:#fff;
    box-shadow:0 8px 16px rgba(73,43,24,.08);
}

.reward-list{
    display:grid;
    gap:10px;
}

.reward-card{
    padding:14px;
    display:grid;
    grid-template-columns:48px 1fr auto;
    align-items:center;
    gap:12px;
}

.reward-icon,
.list-icon{
    width:48px;
    height:48px;
    border-radius:16px;
    display:grid;
    place-items:center;
    color:#fff;
    background:var(--brand);
    font-weight:900;
}

.reward-card:nth-child(2) .reward-icon{
    background:var(--green);
}

.reward-card:nth-child(3) .reward-icon{
    background:var(--blue);
}

.mini-btn{
    min-height:34px;
    border-radius:999px;
    padding:0 12px;
    background:var(--ink);
    color:#fff;
    font-size:12px;
    font-weight:900;
}

.mini-btn:disabled{
    opacity:.45;
}

.panel{
    margin-top:12px;
}

.list-row{
    width:100%;
    min-height:72px;
    padding:14px;
    background:#fff;
    color:inherit;
    text-align:left;
    display:grid;
    grid-template-columns:46px 1fr auto;
    align-items:center;
    gap:12px;
    border-bottom:1px solid var(--line);
}

.list-row:last-child{
    border-bottom:0;
}

.list-icon{
    width:46px;
    height:46px;
    border-radius:15px;
}

.list-row:nth-child(2) .list-icon{
    background:var(--green);
}

.list-row:nth-child(3) .list-icon{
    background:var(--brand-2);
    color:#1f2937;
}

.chev{
    color:var(--muted);
    font-size:21px;
}

.form-panel{
    display:none;
    margin-top:12px;
    padding:15px;
    border:1px solid var(--line);
    border-radius:12px;
    background:#fff;
}

.form-panel.active{
    display:block;
}

.field{
    margin-bottom:12px;
}

.field label{
    display:block;
    margin-bottom:6px;
    color:var(--muted);
    font-size:12px;
    font-weight:900;
}

.field input,
.field textarea,
.field select{
    width:100%;
    border:1px solid var(--line);
    border-radius:15px;
    background:#fbf7f1;
    padding:12px;
    outline:0;
}

.field textarea{
    min-height:88px;
    resize:none;
    line-height:1.45;
}

.chat{
    min-height:220px;
    max-height:260px;
    overflow-y:auto;
    display:flex;
    flex-direction:column;
    gap:9px;
    padding-right:2px;
}

.bubble{
    width:fit-content;
    max-width:82%;
    border-radius:18px;
    padding:10px 12px;
    background:#fbf7f1;
    color:var(--ink);
    font-size:13px;
    line-height:1.4;
}

.bubble.me{
    margin-left:auto;
    color:#fff;
    background:var(--brand);
}

.compose{
    display:grid;
    grid-template-columns:1fr 44px;
    gap:8px;
    margin-top:12px;
}

.profile-card{
    padding:16px;
}

.profile-top{
    text-align:center;
}

.avatar{
    width:88px;
    height:88px;
    margin:0 auto 14px;
    border-radius:50%;
    background:linear-gradient(135deg,var(--brand),var(--brand-2));
    color:#fff;
    display:grid;
    place-items:center;
    font-size:34px;
    font-weight:900;
    box-shadow:0 12px 24px rgba(184,50,38,.18);
}

.stats{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:10px;
}

.stat{
    border:1px solid var(--line);
    border-radius:12px;
    padding:14px;
    background:#fff;
}

.stat strong{
    display:block;
    font-size:24px;
}

.setting{
    min-height:60px;
    padding:14px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:12px;
    border-bottom:1px solid var(--line);
}

.setting:last-child{
    border-bottom:0;
}

.switch{
    position:relative;
    width:48px;
    height:28px;
    flex:0 0 auto;
}

.switch input{
    opacity:0;
}

.slider{
    position:absolute;
    inset:0;
    border-radius:999px;
    background:#d9d0c2;
    transition:.16s ease;
}

.slider:before{
    content:"";
    position:absolute;
    width:22px;
    height:22px;
    top:3px;
    left:3px;
    border-radius:50%;
    background:#fff;
    box-shadow:0 4px 10px rgba(31,41,55,.2);
    transition:.16s ease;
}

.switch input:checked + .slider{
    background:var(--green);
}

.switch input:checked + .slider:before{
    transform:translateX(20px);
}

.nav{
    position:fixed;
    left:50%;
    bottom:14px;
    transform:translateX(-50%);
    width:min(calc(100% - 28px),452px);
    min-height:76px;
    border-radius:28px;
    background:rgba(255,255,255,.94);
    border:1px solid var(--line);
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:4px;
    padding:8px;
    box-shadow:0 12px 30px rgba(73,43,24,.16);
    backdrop-filter:blur(18px);
}

.nav-btn{
    border-radius:22px;
    background:transparent;
    color:var(--muted);
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    gap:4px;
    font-size:11px;
    font-weight:900;
}

.nav-btn svg{
    width:21px;
    height:21px;
}

.nav-btn.active{
    color:var(--brand);
    background:#fbe9df;
}

.toast{
    position:fixed;
    left:50%;
    bottom:102px;
    transform:translate(-50%,12px);
    width:min(calc(100% - 44px),420px);
    min-height:46px;
    padding:11px 14px;
    border-radius:18px;
    background:rgba(31,41,55,.96);
    color:#fff;
    display:grid;
    place-items:center;
    text-align:center;
    font-size:13px;
    font-weight:900;
    opacity:0;
    pointer-events:none;
    transition:.18s ease;
    z-index:30;
}

.toast.show{
    opacity:1;
    transform:translate(-50%,0);
}

.empty{
    padding:18px;
    border:1px dashed var(--line);
    border-radius:12px;
    color:var(--muted);
    text-align:center;
    background:#fbf7f1;
    font-size:13px;
}

@media (min-width:700px){
    body{
        padding:28px;
        display:flex;
        align-items:center;
        justify-content:center;
    }

    .app{
        min-height:860px;
        border-radius:34px;
    }
}
</style>
</head>
<body>
<div class="app">
    <header class="topbar">
        <div class="top-row">
            <div class="brand">
                <div class="brand-mark">P</div>
                <div>
                    <div>PromoConnect</div>
                    <div class="route" id="routeLabel">Home</div>
                </div>
            </div>
            <button class="icon-btn" type="button" id="notifyBtn" aria-label="Notifications">
                <svg viewBox="0 0 24 24" fill="none" aria-hidden="true">
                    <path d="M6 9a6 6 0 1 1 12 0v5l2 3H4l2-3V9Z" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/>
                    <path d="M10 20a2 2 0 0 0 4 0" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
                </svg>
                <span class="badge"></span>
            </button>
        </div>
    </header>

    <main class="container">
        <section class="screen active" id="home">
            <article class="hero">
                <div>
                    <h1>Fresh local deals near you.</h1>
                    <p>Discover recommended promos, save offers, and earn points from small businesses.</p>
                </div>
                <div class="hero-actions">
                    <span class="points-pill"><span id="heroPoints">120</span> pts</span>
                    <button class="btn secondary" type="button" data-route="rewards">View Rewards</button>
                </div>
            </article>

            <div class="section-head">
                <h2>Recommended for you</h2>
                <span id="promoCount">0 deals</span>
            </div>

            <label class="search" aria-label="Search promotions">
                <svg viewBox="0 0 24 24" fill="none" aria-hidden="true">
                    <circle cx="11" cy="11" r="7" stroke="currentColor" stroke-width="2"/>
                    <path d="M16.5 16.5 21 21" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
                </svg>
                <input id="searchInput" type="search" placeholder="Search promotions, shops, deals" />
            </label>

            <div class="filters" id="filters"></div>
            <div class="horizontal" id="recommendedList"></div>

            <div class="detail" id="promoDetail">
                <h3 id="detailTitle">Promo detail</h3>
                <p id="detailMeta"></p>
                <p id="detailText"></p>
                <button class="btn full" type="button" id="claimDetail">Claim Promo</button>
            </div>

            <div class="section-head">
                <h2>Nearby Promotion</h2>
                <button type="button" id="sortNearby">Nearest first</button>
            </div>
            <div class="shop-list" id="nearbyList"></div>

            <div class="section-head">
                <h2>Small business shops</h2>
                <span id="shopCount">0 shops</span>
            </div>
            <div class="shop-list" id="shopList"></div>
        </section>

        <section class="screen" id="rewards">
            <article class="points-card">
                <p>Total Points:</p>
                <div class="points-value" id="pointsValue">120</div>
                <p id="tierText">Tier: Bronze Member</p>
                <div class="section-head" style="margin:16px 0 0;color:#fff">
                    <span style="color:#fff">Progress to Silver</span>
                    <span id="progressText" style="color:#fff">40%</span>
                </div>
                <div class="progress"><span id="tierBar" style="--value:40%"></span></div>
            </article>

            <div class="tabs">
                <button class="tab active" type="button" data-reward-tab="food">Food</button>
                <button class="tab" type="button" data-reward-tab="drinks">Drinks</button>
                <button class="tab" type="button" data-reward-tab="special">Special</button>
            </div>

            <div class="section-head">
                <h2 id="rewardTitle">Food Rewards</h2>
                <button type="button" id="earnPoints">Earn +15</button>
            </div>
            <div class="reward-list" id="rewardList"></div>

            <div class="section-head">
                <h2>Activity Summary</h2>
                <span id="activityCount">0 items</span>
            </div>
            <div class="panel" id="activityList"></div>
        </section>

        <section class="screen" id="inbox">
            <label class="search" aria-label="Search inbox">
                <svg viewBox="0 0 24 24" fill="none" aria-hidden="true">
                    <circle cx="11" cy="11" r="7" stroke="currentColor" stroke-width="2"/>
                    <path d="M16.5 16.5 21 21" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
                </svg>
                <input id="inboxSearch" type="search" placeholder="Search customization, feedback, chat" />
            </label>

            <div class="panel" id="inboxMenu">
                <button class="list-row" type="button" data-panel="customize">
                    <span class="list-icon">C</span>
                    <span>
                        <strong>Product Customization</strong>
                        <span class="meta">Size, flavor, sugar, add-ons</span>
                    </span>
                    <span class="chev">&gt;</span>
                </button>
                <button class="list-row" type="button" data-panel="feedback">
                    <span class="list-icon">F</span>
                    <span>
                        <strong>Business Feedback</strong>
                        <span class="meta">Rate service and promo quality</span>
                    </span>
                    <span class="chev">&gt;</span>
                </button>
                <button class="list-row" type="button" data-panel="chatbox">
                    <span class="list-icon">M</span>
                    <span>
                        <strong>Chat Box</strong>
                        <span class="meta">Message the selected business</span>
                    </span>
                    <span class="chev">&gt;</span>
                </button>
            </div>

            <form class="form-panel active" id="customizePanel">
                <div class="field">
                    <label for="orderShop">Shop</label>
                    <select id="orderShop">
                        <option>Maria's Milk Tea Shop</option>
                        <option>Local Bakery</option>
                        <option>Family Restaurant</option>
                    </select>
                </div>
                <div class="field">
                    <label for="orderSize">Size</label>
                    <select id="orderSize">
                        <option>Medium</option>
                        <option>Small</option>
                        <option>Large</option>
                    </select>
                </div>
                <div class="field">
                    <label for="sugarLevel">Sugar level</label>
                    <select id="sugarLevel">
                        <option>50%</option>
                        <option>0%</option>
                        <option>25%</option>
                        <option>75%</option>
                        <option>100%</option>
                    </select>
                </div>
                <div class="field">
                    <label for="addons">Add-ons</label>
                    <input id="addons" placeholder="Pearls, jelly, cream cheese" />
                </div>
                <button class="btn full" type="submit">Save Custom Order</button>
            </form>

            <form class="form-panel" id="feedbackPanel">
                <div class="field">
                    <label for="rating">Rating</label>
                    <select id="rating">
                        <option>5 - Excellent</option>
                        <option>4 - Good</option>
                        <option>3 - Okay</option>
                        <option>2 - Needs work</option>
                        <option>1 - Poor</option>
                    </select>
                </div>
                <div class="field">
                    <label for="feedbackText">Feedback</label>
                    <textarea id="feedbackText" placeholder="Write your feedback about the shop or promo quality"></textarea>
                </div>
                <button class="btn full" type="submit">Submit Feedback</button>
            </form>

            <div class="form-panel" id="chatboxPanel">
                <div class="chat" id="chatMessages"></div>
                <form class="compose" id="chatForm">
                    <input id="chatInput" placeholder="Type a message" />
                    <button class="btn" type="submit" aria-label="Send">Send</button>
                </form>
            </div>
        </section>

        <section class="screen" id="profile">
            <article class="profile-card profile-top">
                <div class="avatar">J</div>
                <h2>Juan Dela Cruz</h2>
                <p class="meta">juan@email.com</p>
                <p class="meta" id="profileTier">Bronze Member</p>
            </article>

            <div class="section-head">
                <h2>Loyalty Progress</h2>
                <button type="button" data-route="rewards">Rewards</button>
            </div>
            <article class="points-card">
                <p>Current progress</p>
                <div class="points-value" id="profileProgressValue">40%</div>
                <p id="profileProgressText">180 points to Silver</p>
                <div class="progress"><span id="profileBar" style="--value:40%"></span></div>
            </article>

            <div class="section-head">
                <h2>Activity Summary</h2>
                <button type="button" id="resetApp">Reset</button>
            </div>
            <div class="stats">
                <div class="stat"><strong id="statPoints">120</strong><span class="meta">Points</span></div>
                <div class="stat"><strong id="statPromos">0</strong><span class="meta">Promos</span></div>
                <div class="stat"><strong id="statMessages">0</strong><span class="meta">Messages</span></div>
                <div class="stat"><strong id="statReviews">0</strong><span class="meta">Reviews</span></div>
            </div>

            <div class="section-head">
                <h2>Settings</h2>
                <span>Account</span>
            </div>
            <div class="panel">
                <label class="setting">
                    <span>
                        <strong>Notifications</strong>
                        <span class="meta">Promo and reward alerts</span>
                    </span>
                    <span class="switch">
                        <input id="settingNotifications" type="checkbox" checked />
                        <span class="slider"></span>
                    </span>
                </label>
                <label class="setting">
                    <span>
                        <strong>Privacy</strong>
                        <span class="meta">Hide profile from public shop boards</span>
                    </span>
                    <span class="switch">
                        <input id="settingPrivacy" type="checkbox" />
                        <span class="slider"></span>
                    </span>
                </label>
                <button class="list-row" type="button" id="editProfile">
                    <span class="list-icon">E</span>
                    <span>
                        <strong>Edit Profile</strong>
                        <span class="meta">Update name, email, and preferences</span>
                    </span>
                    <span class="chev">&gt;</span>
                </button>
            </div>
        </section>
    </main>

    <nav class="nav" aria-label="Main navigation">
        <button class="nav-btn active" type="button" data-route="home">
            <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M3 11.5 12 4l9 7.5V20a1 1 0 0 1-1 1h-5v-6H9v6H4a1 1 0 0 1-1-1v-8.5Z" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/></svg>
            Home
        </button>
        <button class="nav-btn" type="button" data-route="rewards">
            <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M7 11h10v10H7V11Z" stroke="currentColor" stroke-width="2"/><path d="M5 7h14v4H5V7ZM12 7v14M8.5 7A2.5 2.5 0 1 1 12 7a2.5 2.5 0 1 1 3.5 0" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>
            Rewards
        </button>
        <button class="nav-btn" type="button" data-route="inbox">
            <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M4 5h16v11H8l-4 4V5Z" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/><path d="M8 9h8M8 12h5" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>
            Inbox
        </button>
        <button class="nav-btn" type="button" data-route="profile">
            <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 12a4 4 0 1 0 0-8 4 4 0 0 0 0 8ZM4.5 21a7.5 7.5 0 0 1 15 0" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>
            Profile
        </button>
    </nav>

    <div class="toast" id="toast" role="status" aria-live="polite"></div>
</div>

<script>
const promotions=[
    {title:"20% Off Milk Tea",tag:"Hot",shop:"Maria's Milk Tea Shop",category:"Drinks",distance:.3,points:12,detail:"Save on any classic milk tea flavor today."},
    {title:"Buy 1 Get 1 Pizza",tag:"New",shop:"Pizza Corner",category:"Food",distance:1.2,points:18,detail:"Buy one slice set and get one free for a friend."},
    {title:"Free Coffee Upgrade",tag:"Trending",shop:"Coffee Shop",category:"Drinks",distance:.5,points:10,detail:"Upgrade any regular coffee to large for free."},
    {title:"Weekend Dessert Sale",tag:"Limited",shop:"Local Bakery",category:"Bakery",distance:.9,points:14,detail:"Fresh breads, cakes, and pastries with weekend-only discounts."}
];

const shops=[
    {name:"Maria's Milk Tea Shop",type:"Drinks",rating:4.8,distance:.3,status:"Trending",img:"https://images.unsplash.com/photo-1558857563-b371033873b8?auto=format&fit=crop&w=400&q=80"},
    {name:"Coffee Shop Discount",type:"Drinks",rating:4.7,distance:.5,status:"Open now",img:"https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?auto=format&fit=crop&w=400&q=80"},
    {name:"Burger House Promo",type:"Food",rating:4.5,distance:.8,status:"Open now",img:"https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=400&q=80"},
    {name:"Local Noodle House",type:"Food",rating:4.6,distance:1.5,status:"Budget friendly",img:"https://images.unsplash.com/photo-1569718212165-3a8278d5f624?auto=format&fit=crop&w=400&q=80"},
    {name:"Family Restaurant",type:"Meals",rating:4.4,distance:1.8,status:"Family meals",img:"https://images.unsplash.com/photo-1552566626-52f8b828add9?auto=format&fit=crop&w=400&q=80"}
];

const smallBusinesses=[
    {name:"Maria's Milk Tea Shop Special",type:"Drinks",rating:4.8,distance:.3,status:"Loyalty partner",img:"https://images.unsplash.com/photo-1525385133512-2f3bdd039054?auto=format&fit=crop&w=400&q=80"},
    {name:"Local Bakery Fresh Bread Promo",type:"Bakery",rating:4.6,distance:.9,status:"Fresh today",img:"https://images.unsplash.com/photo-1509440159596-0249088772ff?auto=format&fit=crop&w=400&q=80"},
    {name:"Street Food Stall Discount Deals",type:"Food",rating:4.5,distance:1.1,status:"Budget meals",img:"https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=400&q=80"},
    {name:"Family Restaurant Budget Meals",type:"Meals",rating:4.4,distance:1.8,status:"Open now",img:"https://images.unsplash.com/photo-1552566626-52f8b828add9?auto=format&fit=crop&w=400&q=80"}
];

const rewards={
    food:[
        {name:"Free Burger Meal",cost:250,desc:"Burger, fries, and drink",code:"B"},
        {name:"Free Pizza Slice",cost:180,desc:"Any regular pizza slice",code:"P"},
        {name:"Free Noodle Bowl",cost:200,desc:"House noodle bowl",code:"N"}
    ],
    drinks:[
        {name:"Milk Tea Upgrade",cost:120,desc:"Upgrade to large",code:"M"},
        {name:"Coffee Upgrade",cost:80,desc:"Regular to large coffee",code:"C"},
        {name:"Snack Combo",cost:140,desc:"Drink plus snack",code:"S"}
    ],
    special:[
        {name:"20% Discount Voucher",cost:200,desc:"Use at partner shops",code:"V"},
        {name:"Mystery Box Reward",cost:300,desc:"Sponsored surprise reward",code:"X"},
        {name:"Double Points Pass",cost:220,desc:"Double points on next visit",code:"D"}
    ]
};

const baseState={
    points:120,
    claimed:0,
    messages:12,
    reviews:3,
    activeFilter:"All",
    selectedPromo:0,
    rewardTab:"food",
    nearestFirst:true,
    activity:["Joined as Bronze Member with 120 points"],
    chat:[
        {from:"shop",text:"Hi Juan, how can we help you today?"},
        {from:"me",text:"Do you still have the milk tea promo?"}
    ],
    settings:{notifications:true,privacy:false}
};

let state=loadState();
let toastTimer;

function loadState(){
    const saved=localStorage.getItem("promoConnectCustomerState");
    if(!saved) return structuredClone(baseState);
    try{
        return {...structuredClone(baseState),...JSON.parse(saved)};
    }catch{
        return structuredClone(baseState);
    }
}

function saveState(){
    localStorage.setItem("promoConnectCustomerState",JSON.stringify(state));
}

function showToast(message){
    const toast=document.getElementById("toast");
    toast.textContent=message;
    toast.classList.add("show");
    clearTimeout(toastTimer);
    toastTimer=setTimeout(()=>toast.classList.remove("show"),2200);
}

function addActivity(message){
    state.activity.unshift(message);
    state.activity=state.activity.slice(0,12);
    saveState();
    renderActivity();
    renderProfile();
 }

function tierInfo(){
    const next=300;
    const progress=Math.min(100,Math.round((state.points/next)*100));
    return {
        name:state.points>=300?"Silver Member":"Bronze Member",
        progress,
        remaining:Math.max(next-state.points,0)
    };
}

function setRoute(route){
    document.querySelectorAll(".screen").forEach(screen=>{
        screen.classList.toggle("active",screen.id===route);
    });
    document.querySelectorAll(".nav-btn").forEach(btn=>{
        btn.classList.toggle("active",btn.dataset.route===route);
    });
    document.getElementById("routeLabel").textContent={
        home:"Home",
        rewards:"My Reward",
        inbox:"Inbox",
        profile:"Profile"
    }[route];
}

function renderFilters(){
    const filters=["All","Food","Drinks","Bakery","Meals"];
    document.getElementById("filters").innerHTML=filters.map(filter=>`
        <button class="chip ${state.activeFilter===filter?"active":""}" type="button" data-filter="${filter}">${filter}</button>
    `).join("");
    document.querySelectorAll("[data-filter]").forEach(button=>{
        button.addEventListener("click",()=>{
            state.activeFilter=button.dataset.filter;
            saveState();
            renderHome();
        });
    });
}

function matchesSearch(item,query){
    return Object.values(item).join(" ").toLowerCase().includes(query);
}

function renderHome(){
    const query=document.getElementById("searchInput").value.trim().toLowerCase();
    const filteredPromos=promotions.filter(p=>{
        const filterMatch=state.activeFilter==="All"||p.category===state.activeFilter;
        return filterMatch&&matchesSearch(p,query);
    });

    document.getElementById("promoCount").textContent=`${filteredPromos.length} deals`;
    document.getElementById("recommendedList").innerHTML=filteredPromos.map((promo,index)=>`
        <button class="promo-card" type="button" data-promo-index="${promotions.indexOf(promo)}">
            <span class="tag">${promo.tag}</span>
            <span>
                <h3>${promo.title}</h3>
                <p>${promo.shop} - ${promo.points} bonus pts</p>
            </span>
        </button>
    `).join("")||`<div class="empty">No recommended promotions found.</div>`;

    document.querySelectorAll("[data-promo-index]").forEach(card=>{
        card.addEventListener("click",()=>{
            state.selectedPromo=Number(card.dataset.promoIndex);
            saveState();
            renderPromoDetail();
        });
    });

    const nearby=[...shops].sort((a,b)=>state.nearestFirst?a.distance-b.distance:b.rating-a.rating);
    document.getElementById("nearbyList").innerHTML=nearby.map(shop=>shopCard(shop,true)).join("");
    document.getElementById("shopCount").textContent=`${smallBusinesses.length} shops`;
    document.getElementById("shopList").innerHTML=smallBusinesses.map(shop=>shopCard(shop,false)).join("");

    document.querySelectorAll("[data-save-shop]").forEach(button=>{
        button.addEventListener("click",event=>{
            event.stopPropagation();
            state.claimed+=1;
            addActivity(`Saved offer from ${button.dataset.saveShop}`);
            showToast("Offer saved");
        });
    });

    renderFilters();
    renderPromoDetail();
}

function shopCard(shop,nearby){
    return `
        <button class="shop-card" type="button">
            <img src="${shop.img}" alt="${shop.name}" />
            <span class="shop-body">
                <h3>${shop.name}</h3>
                <span class="meta">${shop.type} - ${shop.rating} rating - ${shop.distance} km away</span>
                <span class="shop-foot">
                    <span class="tag">${shop.status}</span>
                    <span class="small-link" data-save-shop="${shop.name}">${nearby?"Claim":"Save"}</span>
                </span>
            </span>
        </button>
    `;
}

function renderPromoDetail(){
    const promo=promotions[state.selectedPromo];
    const detail=document.getElementById("promoDetail");
    detail.classList.add("active");
    document.getElementById("detailTitle").textContent=promo.title;
    document.getElementById("detailMeta").textContent=`${promo.shop} - ${promo.distance} km away - valid this week`;
    document.getElementById("detailText").textContent=promo.detail;
}

function renderRewards(){
    const info=tierInfo();
    document.getElementById("heroPoints").textContent=state.points;
    document.getElementById("pointsValue").textContent=state.points;
    document.getElementById("tierText").textContent=`Tier: ${info.name}`;
    document.getElementById("progressText").textContent=`${info.progress}%`;
    document.getElementById("tierBar").style.setProperty("--value",`${info.progress}%`);

    document.querySelectorAll("[data-reward-tab]").forEach(tab=>{
        tab.classList.toggle("active",tab.dataset.rewardTab===state.rewardTab);
    });

    const title={food:"Food Rewards",drinks:"Drinks & Snacks",special:"Special Rewards"}[state.rewardTab];
    document.getElementById("rewardTitle").textContent=title;
    document.getElementById("rewardList").innerHTML=rewards[state.rewardTab].map(reward=>{
        const canRedeem=state.points>=reward.cost;
        return `
            <article class="reward-card">
                <span class="reward-icon">${reward.code}</span>
                <span>
                    <h3>${reward.name}</h3>
                    <span class="meta">${reward.desc} - ${reward.cost} pts</span>
                </span>
                <button class="mini-btn" type="button" data-redeem="${reward.name}" data-cost="${reward.cost}" ${canRedeem?"":"disabled"}>${canRedeem?"Redeem":"Locked"}</button>
            </article>
        `;
    }).join("");

    document.querySelectorAll("[data-redeem]").forEach(button=>{
        button.addEventListener("click",()=>{
            const cost=Number(button.dataset.cost);
            if(state.points<cost) return;
            state.points-=cost;
            state.claimed+=1;
            addActivity(`Redeemed ${button.dataset.redeem} for ${cost} points`);
            renderAll();
            showToast(`${button.dataset.redeem} redeemed`);
        });
    });
}

function renderActivity(){
    const list=document.getElementById("activityList");
    document.getElementById("activityCount").textContent=`${state.activity.length} items`;
    list.innerHTML=state.activity.map(item=>`
        <div class="list-row">
            <span class="list-icon">A</span>
            <span>
                <strong>${item}</strong>
                <span class="meta">Updated just now</span>
            </span>
            <span class="chev">.</span>
        </div>
    `).join("");
}

function renderInbox(){
    const messages=document.getElementById("chatMessages");
    messages.innerHTML=state.chat.map(msg=>`
        <div class="bubble ${msg.from==="me"?"me":""}">${msg.text}</div>
    `).join("");
    messages.scrollTop=messages.scrollHeight;
}

function setInboxPanel(panel){
    ["customize","feedback","chatbox"].forEach(name=>{
        document.getElementById(`${name}Panel`).classList.toggle("active",name===panel);
    });
    if(panel==="chatbox") renderInbox();
}

function renderProfile(){
    const info=tierInfo();
    document.getElementById("profileTier").textContent=`${info.name} - ${state.points} points`;
    document.getElementById("profileProgressValue").textContent=`${info.progress}%`;
    document.getElementById("profileProgressText").textContent=info.remaining?`${info.remaining} points to Silver`:"Silver unlocked";
    document.getElementById("profileBar").style.setProperty("--value",`${info.progress}%`);
    document.getElementById("statPoints").textContent=state.points;
    document.getElementById("statPromos").textContent=state.claimed;
    document.getElementById("statMessages").textContent=state.messages;
    document.getElementById("statReviews").textContent=state.reviews;
    document.getElementById("settingNotifications").checked=state.settings.notifications;
    document.getElementById("settingPrivacy").checked=state.settings.privacy;
}

function renderAll(){
    renderHome();
    renderRewards();
    renderActivity();
    renderInbox();
    renderProfile();
}

document.querySelectorAll("[data-route]").forEach(button=>{
    button.addEventListener("click",()=>setRoute(button.dataset.route));
});

document.getElementById("searchInput").addEventListener("input",renderHome);

document.getElementById("sortNearby").addEventListener("click",()=>{
    state.nearestFirst=!state.nearestFirst;
    document.getElementById("sortNearby").textContent=state.nearestFirst?"Nearest first":"Top rated";
    saveState();
    renderHome();
});

document.getElementById("claimDetail").addEventListener("click",()=>{
    const promo=promotions[state.selectedPromo];
    state.points+=promo.points;
    state.claimed+=1;
    addActivity(`Claimed ${promo.title} and earned ${promo.points} points`);
    renderAll();
    showToast(`Promo claimed: +${promo.points} points`);
});

document.querySelectorAll("[data-reward-tab]").forEach(tab=>{
    tab.addEventListener("click",()=>{
        state.rewardTab=tab.dataset.rewardTab;
        saveState();
        renderRewards();
    });
});

document.getElementById("earnPoints").addEventListener("click",()=>{
    state.points+=15;
    addActivity("Earned 15 points from a customer check-in");
    renderAll();
    showToast("+15 points earned");
});

document.querySelectorAll("[data-panel]").forEach(button=>{
    button.addEventListener("click",()=>setInboxPanel(button.dataset.panel));
});

document.getElementById("inboxSearch").addEventListener("input",event=>{
    const query=event.target.value.trim().toLowerCase();
    document.querySelectorAll("#inboxMenu .list-row").forEach(row=>{
        row.style.display=row.textContent.toLowerCase().includes(query)?"grid":"none";
    });
});

document.getElementById("customizePanel").addEventListener("submit",event=>{
    event.preventDefault();
    const shop=document.getElementById("orderShop").value;
    const size=document.getElementById("orderSize").value;
    const sugar=document.getElementById("sugarLevel").value;
    state.messages+=1;
    state.chat.push({from:"me",text:`Custom order for ${shop}: ${size}, ${sugar} sugar.`});
    addActivity("Saved Product Customization order");
    renderInbox();
    showToast("Custom order saved");
});

document.getElementById("feedbackPanel").addEventListener("submit",event=>{
    event.preventDefault();
    const text=document.getElementById("feedbackText").value.trim();
    if(!text){
        showToast("Write feedback before submitting");
        return;
    }
    state.reviews+=1;
    document.getElementById("feedbackText").value="";
    addActivity("Submitted Business Feedback");
    showToast("Feedback submitted");
});

document.getElementById("chatForm").addEventListener("submit",event=>{
    event.preventDefault();
    const input=document.getElementById("chatInput");
    const text=input.value.trim();
    if(!text) return;
    state.messages+=1;
    state.chat.push({from:"me",text});
    state.chat.push({from:"shop",text:"Thanks. The shop will reply with availability shortly."});
    input.value="";
    addActivity("Sent a Chat Box message");
    renderInbox();
    showToast("Message sent");
});

document.getElementById("settingNotifications").addEventListener("change",event=>{
    state.settings.notifications=event.target.checked;
    saveState();
    showToast(`Notifications ${event.target.checked?"on":"off"}`);
});

document.getElementById("settingPrivacy").addEventListener("change",event=>{
    state.settings.privacy=event.target.checked;
    saveState();
    showToast(`Privacy mode ${event.target.checked?"on":"off"}`);
});

document.getElementById("notifyBtn").addEventListener("click",()=>{
    showToast("You have new nearby promotions.");
});

document.getElementById("editProfile").addEventListener("click",()=>{
    showToast("Profile editing screen placeholder opened.");
});

document.getElementById("resetApp").addEventListener("click",()=>{
    state=structuredClone(baseState);
    saveState();
    renderAll();
    setRoute("home");
    showToast("App data reset");
});

renderAll();
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>PromoConnect Admin</title>
<style>
:root{--bg:#020617;--glass:rgba(255,255,255,.08);--line:rgba(125,211,252,.24);--text:#f8fbff;--muted:#9fb3c8;--cyan:#22d3ee;--blue:#2563eb;--green:#34d399;--amber:#fbbf24;--red:#fb7185;--violet:#a78bfa}
*{box-sizing:border-box;margin:0;padding:0}
body{min-height:100vh;font-family:Inter,Arial,sans-serif;background:radial-gradient(circle at 10% 4%,rgba(34,211,238,.30),transparent 30%),radial-gradient(circle at 90% 8%,rgba(37,99,235,.28),transparent 34%),linear-gradient(160deg,#020617,#071a35 55%,#020617);color:var(--text);display:flex;justify-content:center;padding:16px}
button,input,select,textarea{font:inherit}button{border:0;cursor:pointer}
.app{width:100%;max-width:540px;min-height:calc(100vh - 32px);border:1px solid var(--line);border-radius:32px;background:linear-gradient(180deg,rgba(12,32,65,.84),rgba(3,10,25,.90));box-shadow:0 0 60px rgba(34,211,238,.18),0 30px 90px rgba(0,0,0,.55);backdrop-filter:blur(22px);overflow:hidden;position:relative}
.header{padding:22px 20px 14px;display:flex;justify-content:space-between;align-items:center;gap:12px}.brand{display:flex;gap:12px;align-items:center}.logo{width:46px;height:46px;border-radius:17px;background:linear-gradient(135deg,var(--cyan),var(--blue));display:grid;place-items:center;font-weight:900;box-shadow:0 0 28px rgba(34,211,238,.55)}h1{font-size:21px}.sub{color:var(--muted);font-size:12px;margin-top:3px}.icon{width:40px;height:40px;border-radius:15px;background:var(--glass);border:1px solid var(--line);color:#dff8ff;display:grid;place-items:center}
.content{padding:8px 20px 108px;height:calc(100vh - 104px);overflow:auto}.content::-webkit-scrollbar,.nav::-webkit-scrollbar{display:none}
.screen{display:none}.screen.active{display:block;animation:enter .18s ease both}@keyframes enter{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
.hero,.card,.item,.formbox,.chartbox,.mini{border:1px solid var(--line);background:linear-gradient(145deg,rgba(255,255,255,.11),rgba(255,255,255,.045));box-shadow:inset 0 1px 0 rgba(255,255,255,.10),0 18px 38px rgba(0,0,0,.22);backdrop-filter:blur(18px)}
.hero{border-radius:26px;padding:20px}.hero h2{font-size:28px;line-height:1.05}.hero p{margin-top:8px;color:var(--muted);font-size:14px;line-height:1.45}
.stats,.row2,.chart-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}.stats{margin-top:16px}.card{border-radius:21px;padding:15px}.card span{color:var(--muted);font-size:12px}.card strong{display:block;margin-top:7px;font-size:23px}
.head{margin:24px 0 12px;display:flex;justify-content:space-between;align-items:end;gap:10px}.head h3{font-size:17px}.head span,.link{font-size:12px;color:#7dd3fc;background:none;font-weight:900}
.list{display:grid;gap:11px}.item{min-height:74px;border-radius:21px;padding:14px;display:flex;align-items:center;justify-content:space-between;gap:12px}.title{font-weight:900;font-size:14px}.meta{margin-top:4px;color:var(--muted);font-size:12px;line-height:1.35}
.badge{padding:7px 10px;border-radius:999px;font-size:11px;font-weight:900;white-space:nowrap}.run{color:#8fffe1;background:rgba(52,211,153,.13);border:1px solid rgba(52,211,153,.32)}.soon{color:#ffe28a;background:rgba(251,191,36,.13);border:1px solid rgba(251,191,36,.32)}.low{color:#ff9bac;background:rgba(251,113,133,.13);border:1px solid rgba(251,113,133,.32)}.vip{color:#ddd6fe;background:rgba(167,139,250,.14);border:1px solid rgba(167,139,250,.34)}
.btn{width:100%;min-height:44px;border-radius:999px;background:linear-gradient(135deg,var(--cyan),var(--blue));color:white;font-weight:900;box-shadow:0 0 24px rgba(34,211,238,.28)}.btn.ghost{background:rgba(255,255,255,.09);box-shadow:none;border:1px solid var(--line)}
input,select,textarea{width:100%;margin-top:8px;padding:12px;border-radius:14px;border:1px solid var(--line);background:rgba(2,8,23,.62);color:white;outline:0}label{display:block;margin-top:13px;color:var(--muted);font-size:12px;font-weight:900}textarea{min-height:86px;resize:none}
.formbox{padding:16px;border-radius:22px}.chartbox{height:230px;border-radius:22px;padding:12px}.chartbox.tall{height:260px}.mini{border-radius:20px;padding:14px;margin-top:12px}.chart-label{margin-top:8px;color:var(--muted);font-size:12px;line-height:1.35}canvas{width:100%;height:100%}
.nav{position:absolute;left:16px;right:16px;bottom:16px;height:78px;border-radius:26px;background:rgba(255,255,255,.08);border:1px solid var(--line);display:flex;gap:6px;padding:8px;overflow-x:auto;backdrop-filter:blur(18px)}.nav button{min-width:70px;border-radius:20px;background:transparent;color:#91a7bf;font-size:10px;font-weight:900}.nav button.active{color:white;background:linear-gradient(135deg,var(--cyan),var(--blue));box-shadow:0 0 22px rgba(34,211,238,.38)}
.toast{position:fixed;left:50%;bottom:108px;transform:translate(-50%,12px);width:min(410px,calc(100% - 44px));min-height:44px;border-radius:16px;background:#eaf9ff;color:#061a36;display:grid;place-items:center;font-weight:900;font-size:13px;opacity:0;transition:.2s;z-index:5}.toast.show{opacity:1;transform:translate(-50%,0)}
@media(max-width:430px){.chart-grid,.row2{grid-template-columns:1fr}}
</style>
</head>
<body>
<main class="app">
<header class="header">
  <div class="brand"><div class="logo">PC</div><div><h1>PromoConnect Admin</h1><div class="sub" id="page">Business dashboard</div></div></div>
  <button class="icon" onclick="toast('Notifications opened')">N</button>
</header>

<section class="content">
  <div id="home" class="screen active">
    <div class="hero"><h2>Welcome back, Maria</h2><p>Modern dark dashboard for revenue, claim rate, conversion, active promos, loyalty, and customer activity.</p><div class="stats" id="dashboardStats"></div></div>
    <div class="head"><h3>Active Promotions</h3><span>Live status</span></div><div class="list" id="promoList"></div>
    <div class="head"><h3>Quick Actions</h3><span>Manage faster</span></div>
    <div class="list">
      <div class="item" onclick="show('event')"><div><div class="title">Create Campaign</div><div class="meta">Schedule promos, rules, flash timers</div></div><b>›</b></div>
      <div class="item" onclick="show('data')"><div><div class="title">View Analytics</div><div class="meta">Graphs, pie charts, ROI, behavior</div></div><b>›</b></div>
      <div class="item" onclick="show('customer')"><div><div class="title">Customer Features</div><div class="meta">Budget assistant, Barkada mode, missions</div></div><b>›</b></div>
    </div>
  </div>

  <div id="data" class="screen">
    <div class="hero"><h2>Smart Analytics</h2><p>Accurate insights based on views, claims, redemptions, sales, revenue, cost, ROI, and feedback.</p></div>
    <div class="head"><h3>Active Promotion Claims</h3><button class="link" onclick="drawCharts()">Refresh</button></div><div class="chartbox"><canvas id="promoChart"></canvas></div>
    <div class="head"><h3>Weekly Sales Revenue</h3><span>PHP revenue</span></div><div class="chartbox"><canvas id="salesChart"></canvas></div>
    <div class="head"><h3>Business Insight Pie Graphs</h3><span>Category, claims, feedback</span></div>
    <div class="chart-grid">
      <div class="chartbox tall"><canvas id="categoryPie"></canvas><div class="chart-label">Revenue share by promo category</div></div>
      <div class="chartbox tall"><canvas id="claimPie"></canvas><div class="chart-label">Claim share by campaign</div></div>
      <div class="chartbox tall"><canvas id="sentimentPie"></canvas><div class="chart-label">Customer feedback sentiment</div></div>
    </div>
    <div class="head"><h3>Accurate KPI Summary</h3><span>Auto-computed</span></div><div class="list" id="insights"></div>
  </div>

  <div id="event" class="screen">
    <div class="hero"><h2>Campaign Builder</h2><p>Create, edit, pause, schedule, and launch promotions with AI campaign assistance.</p></div>
    <form class="formbox" onsubmit="saveCampaign(event)">
      <label>Campaign Name</label><input id="cname" value="Summer Blast Promo">
      <div class="row2"><div><label>Product</label><select id="product"><option>Milk Tea</option><option>Coffee</option><option>Snacks</option><option>Burgers</option><option>Rice Meals</option></select></div><div><label>Discount Type</label><select id="dtype"><option>Percentage</option><option>Buy 1 Get 1</option><option>Fixed Price</option><option>Free Add-on</option></select></div></div>
      <div class="row2"><div><label>Discount Value</label><input id="discount" value="20% OFF"></div><div><label>Target Audience</label><select id="audience"><option>All Customers</option><option>New Customers</option><option>VIP Members</option><option>Students</option></select></div></div>
      <label>Campaign Schedule</label><div class="row2"><input id="startDate" type="date"><input id="endDate" type="date"></div>
      <label>Promo Rules</label><textarea id="rules">One redemption per customer. Valid for dine-in and pickup only.</textarea>
      <label>Flash Sale Timer</label><select id="flash"><option>Off</option><option>2 hours</option><option>6 hours</option><option>24 hours</option></select>
      <button class="btn" style="margin-top:15px" id="campaignButton">Launch Campaign</button>
      <button class="btn ghost" type="button" style="margin-top:10px" onclick="aiSuggest()">AI Campaign Assistant</button>
    </form>
    <div class="mini"><div class="title">AI Suggestion</div><div class="meta" id="aiText">Choose a product, then tap AI Campaign Assistant.</div></div>
    <div class="head"><h3>Campaign Manager</h3><span>Edit / pause</span></div><div class="list" id="campaignManager"></div>
  </div>

  <div id="loyalty" class="screen">
    <div class="hero"><h2>Loyalty Management</h2><p>Manage points, tiers, rewards, badges, streaks, and redemption rules.</p></div>
    <div class="stats" id="loyaltyStats"></div>
    <div class="head"><h3>Leaderboard</h3><button class="link" onclick="addPoints()">Add Points</button></div><div class="list" id="leaderboard"></div>
    <div class="head"><h3>Reward Rules</h3><button class="link" onclick="addReward()">Add Rule</button></div><div class="list" id="rewardRules"></div>
  </div>

  <div id="feedback" class="screen">
    <div class="hero"><h2>Ratings & Reviews</h2><p>Track customer sentiment, promo quality, shop ratings, and business responses.</p></div>
    <div class="head"><h3>Feedback Sentiment Graph</h3><button class="link" onclick="drawFeedbackChart()">Refresh</button></div>
    <div class="chartbox"><canvas id="feedbackChart"></canvas></div>
    <div class="head"><h3>Review Feed</h3><span>Positive / neutral / negative</span></div>
    <div class="list" id="reviews"></div>
    <div class="formbox" style="margin-top:14px"><label>Business Response</label><textarea id="reviewReply" placeholder="Write a response..."></textarea><button class="btn" style="margin-top:12px" onclick="respondReview()">Respond</button></div>
  </div>

  <div id="inbox" class="screen">
    <div class="hero"><h2>Business Inbox</h2><p>Customer inquiries, promo questions, product customization, and quick replies.</p></div>
    <div class="head"><h3>Messages</h3><span id="msgLabel"></span></div><div class="list" id="messageList"></div>
    <div class="formbox" style="margin-top:14px">
      <label>Quick Reply Template</label><select id="template"><option>Yes, this promo is still active.</option><option>You can customize sugar level and add-ons.</option><option>Please show your QR coupon at the counter.</option></select>
      <label>Reply</label><textarea id="reply" placeholder="Type a response..."></textarea>
      <button class="btn" style="margin-top:12px" onclick="sendReply()">Send Reply</button>
    </div>
  </div>

  <div id="profile" class="screen">
    <div class="hero"><h2>Verified Business</h2><p>Manage business profile, verification, logo, store hours, location, and trust badge.</p></div>
    <div class="formbox">
      <label>Business Name</label><input value="Maria's Milk Tea Shop">
      <label>Category</label><select><option>Food and Drinks</option><option>Retail</option><option>Services</option></select>
      <label>Store Hours</label><input value="9:00 AM - 9:00 PM">
      <label>Location</label><input value="Downtown, 0.5 km from campus">
      <div class="mini"><div class="title">Verified Business Badge</div><div class="meta">Trusted seller score: 94%. High ratings, successful redemptions, and active support.</div></div>
      <button class="btn" style="margin-top:14px" onclick="toast('Business profile saved')">Save Profile</button>
    </div>
  </div>

  <div id="customer" class="screen">
    <div class="hero"><h2>Customer Feature Hub</h2><p>AI budget deals, Barkada mode, daily missions, flash sales, reviews, verified shops, and offline saved promos.</p></div>
    <div class="head"><h3>AI Budget Assistant</h3><button class="link" onclick="budgetRecommend()">Find Deals</button></div>
    <div class="formbox"><label>Customer Budget</label><input id="budget" type="number" value="100"><div class="mini"><div class="title">Affordable Deals Near You</div><div class="meta" id="budgetResult">Tap Find Deals to recommend promos based on budget.</div></div></div>
    <div class="head"><h3>Barkada Mode</h3><button class="link" onclick="inviteFriend()">Invite</button></div><div class="item"><div><div class="title">Group Milk Tea Deal</div><div class="meta" id="groupText"></div></div><span class="badge vip">Group</span></div>
    <div class="head"><h3>Daily Missions</h3><button class="link" onclick="completeMission()">Complete</button></div><div class="list" id="missions"></div>
    <div class="head"><h3>Flash Sales</h3><span>Countdown timer</span></div><div class="item"><div><div class="title">Flash Sale: Coffee Upgrade</div><div class="meta" id="timer">Loading timer...</div></div><span class="badge soon">Limited</span></div>
    <div class="head"><h3>Saved Offline Promos</h3><button class="link" onclick="saveOfflinePromo()">Save</button></div><div class="list" id="offlineList"></div>
  </div>
</section>

<nav class="nav">
  <button class="active" data-tab="home" onclick="show('home')">Home</button>
  <button data-tab="data" onclick="show('data')">Data</button>
  <button data-tab="event" onclick="show('event')">Event</button>
  <button data-tab="loyalty" onclick="show('loyalty')">Loyalty</button>
  <button data-tab="feedback" onclick="show('feedback')">Reviews</button>
  <button data-tab="inbox" onclick="show('inbox')">Inbox</button>
  <button data-tab="profile" onclick="show('profile')">Profile</button>
  <button data-tab="customer" onclick="show('customer')">Features</button>
</nav>
</main>
<div class="toast" id="toast"></div>

<script>
const initial={
  sales:5200,msgs:5,users:120,editing:null,group:2,streak:4,offline:["20% OFF Milk Tea - Offline ready"],
  campaigns:[
    {name:"Buy 1 Get 1 Milk Tea",category:"Drinks",product:"Milk Tea",discount:"BOGO",audience:"All Customers",status:"Running",views:1840,claims:420,redemptions:318,sales:286,revenue:28600,cost:7200,rating:4.8},
    {name:"Weekend 20% Sale",category:"Food",product:"Snacks",discount:"20% OFF",audience:"Students",status:"Running",views:1320,claims:265,redemptions:188,sales:154,revenue:16940,cost:5100,rating:4.5},
    {name:"Free Add-ons Promo",category:"Drinks",product:"Milk Tea",discount:"Free Add-on",audience:"VIP Members",status:"Ending Soon",views:940,claims:126,redemptions:72,sales:61,revenue:6405,cost:2800,rating:3.9},
    {name:"Rice Meal Saver",category:"Meals",product:"Rice Meals",discount:"PHP 99 Deal",audience:"New Customers",status:"Running",views:1120,claims:310,redemptions:244,sales:229,revenue:22671,cost:4300,rating:4.7}
  ],
  customers:[{name:"Bea Cruz",points:220,tier:"VIP",badges:"Streak Master"},{name:"Juan Dela Cruz",points:120,tier:"Gold",badges:"Top Fan"},{name:"Anna Reyes",points:80,tier:"Silver",badges:"Reviewer"},{name:"Mark Santos",points:45,tier:"Bronze",badges:"Newcomer"}],
  rewards:["100 pts - Free Drink","200 pts - 20% Discount","300 pts - Mystery Box"],
  reviews:[["Juan Dela Cruz","5 Stars","Great promos and fast service.","Positive"],["Anna Reyes","4 Stars","Rewards are useful and easy.","Positive"],["Mark Santos","3 Stars","Good, but pickup can improve.","Neutral"],["Leo Garcia","2 Stars","Promo instructions were unclear.","Negative"],["Bea Cruz","5 Stars","The flash sale was easy to redeem.","Positive"]],
  messages:["Juan: Is the milk tea promo still active?","Anna: Can I customize sugar level?","Mark: How many points for a free drink?"],
  missions:[["Claim 1 promo today","Pending"],["Visit a verified business","Pending"],["Leave 1 review","Done"]]
};
let state=JSON.parse(localStorage.getItem("pcAdminCombinedV3")||JSON.stringify(initial));
let flashEnd=Date.now()+1000*60*18+1000*22;
const $=id=>document.getElementById(id);
function save(){localStorage.setItem("pcAdminCombinedV3",JSON.stringify(state))}
function toast(t){let e=$("toast");e.textContent=t;e.classList.add("show");setTimeout(()=>e.classList.remove("show"),1900)}
function cls(s){return s==="Running"||s==="Positive"||s==="Done"?"run":s==="Ending Soon"||s==="Neutral"||s==="Pending"?"soon":"low"}
function campaignROI(c){return Math.round(((c.revenue-c.cost)/c.cost)*100)}
function roiText(n){return n>=0?`+${n}%`:`${n}%`}
function metrics(){let views=state.campaigns.reduce((a,c)=>a+c.views,0),claims=state.campaigns.reduce((a,c)=>a+c.claims,0),red=state.campaigns.reduce((a,c)=>a+c.redemptions,0),sales=state.campaigns.reduce((a,c)=>a+c.sales,0),rev=state.campaigns.reduce((a,c)=>a+c.revenue,0),cost=state.campaigns.reduce((a,c)=>a+c.cost,0);return{views,claims,red,sales,rev,cost,claimRate:Math.round(claims/views*100),convRate:Math.round(sales/claims*100),redemption:Math.round(red/claims*100),roi:Math.round((rev-cost)/cost*100)}}
function show(id){document.querySelectorAll(".screen").forEach(s=>s.classList.toggle("active",s.id===id));document.querySelectorAll(".nav button").forEach(b=>b.classList.toggle("active",b.dataset.tab===id));$("page").textContent={home:"Business dashboard",data:"Smart analytics",event:"Campaign builder",loyalty:"Loyalty management",feedback:"Ratings and reviews",inbox:"Business inbox",profile:"Verified profile",customer:"Customer feature hub"}[id];if(id==="data")drawCharts();if(id==="feedback")drawFeedbackChart()}
function render(){
  let m=metrics(),best=[...state.campaigns].sort((a,b)=>campaignROI(b)-campaignROI(a))[0],low=[...state.campaigns].sort((a,b)=>campaignROI(a)-campaignROI(b))[0],top=[...state.campaigns].sort((a,b)=>b.claims-a.claims)[0];
  $("dashboardStats").innerHTML=[["Today Sales","PHP "+state.sales.toLocaleString()],["Revenue","PHP "+m.rev.toLocaleString()],["Active Promos",state.campaigns.filter(c=>c.status!=="Paused").length],["Messages",state.msgs],["Loyalty Users",state.users],["Claim Rate",m.claimRate+"%"],["Conversion",m.convRate+"%"],["Overall ROI",roiText(m.roi)]].map(x=>`<div class="card"><span>${x[0]}</span><strong>${x[1]}</strong></div>`).join("");
  $("promoList").innerHTML=state.campaigns.map(c=>`<div class="item"><div><div class="title">${c.name}</div><div class="meta">${c.claims} claims • ${c.redemptions} redemptions • ROI ${roiText(campaignROI(c))}</div></div><span class="badge ${cls(c.status)}">${c.status}</span></div>`).join("");
  $("campaignManager").innerHTML=state.campaigns.map((c,i)=>`<div class="item"><div><div class="title">${c.name}</div><div class="meta">${c.product} • ${c.discount} • ${c.audience}</div></div><div><button class="link" onclick="editCampaign(${i})">Edit</button><br><button class="link" onclick="pauseCampaign(${i})">${c.status==="Paused"?"Resume":"Pause"}</button></div></div>`).join("");
  $("insights").innerHTML=[["Total Campaign Views",m.views.toLocaleString(),"run"],["Total Claims",m.claims.toLocaleString(),"run"],["Total Revenue","PHP "+m.rev.toLocaleString(),"run"],["Average Claim Rate",m.cl
    $("loyaltyStats").innerHTML=[["Members",state.users],["VIP",state.customers.filter(c=>c.tier==="VIP").length],["Rewards",state.rewards.length],["Streak",state.streak+" days"]].map(x=>`<div class="card"><span>${x[0]}</span><strong>${x[1]}</strong></div>`).join("");
  $("leaderboard").innerHTML=[...state.customers].sort((a,b)=>b.points-a.points).map((c,i)=>`<div class="item"><div><div class="title">${i+1}. ${c.name}</div><div class="meta">${c.points} pts • ${c.tier} • ${c.badges}</div></div><span class="badge ${c.tier==="VIP"?"vip":c.tier==="Gold"?"run":c.tier==="Silver"?"soon":"low"}">${c.tier}</span></div>`).join("");
  $("rewardRules").innerHTML=state.rewards.map(r=>`<div class="item"><div><div class="title">${r}</div><div class="meta">Redemption rule active</div></div><span class="badge run">Active</span></div>`).join("");
  $("reviews").innerHTML=state.reviews.map(r=>`<div class="item"><div><div class="title">${r[0]} • ${r[1]}</div><div class="meta">${r[2]}</div></div><span class="badge ${cls(r[3])}">${r[3]}</span></div>`).join("");
  $("msgLabel").textContent=state.msgs+" open";
  $("messageList").innerHTML=state.messages.map(m=>`<div class="item"><div><div class="title">${m.split(":")[0]}</div><div class="meta">${m.split(":")[1]}</div></div><b>›</b></div>`).join("");
  $("missions").innerHTML=state.missions.map(m=>`<div class="item"><div><div class="title">${m[0]}</div><div class="meta">Daily mission • Streak ${state.streak} days</div></div><span class="badge ${cls(m[1])}">${m[1]}</span></div>`).join("");
  $("offlineList").innerHTML=state.offline.map(o=>`<div class="item"><div><div class="title">${o}</div><div class="meta">Accessible without internet</div></div><span class="badge run">Offline</span></div>`).join("");
  $("groupText").textContent=`${state.group}/5 friends joined. ${state.group>=5?"35% OFF unlocked.":"Unlock 35% OFF at 5 friends."}`;
  if($("feedback").classList.contains("active")) drawFeedbackChart();
}
function saveCampaign(e){e.preventDefault();let c={name:$("cname").value,category:$("product").value==="Milk Tea"||$("product").value==="Coffee"?"Drinks":"Food",product:$("product").value,discount:$("discount").value,audience:$("audience").value,status:"Running",views:100,claims:0,redemptions:0,sales:0,revenue:0,cost:1500,rating:0};state.campaigns.unshift(c);state.sales+=900;save();render();toast("Campaign launched");show("home")}
function editCampaign(i){let c=state.campaigns[i];$("cname").value=c.name;$("product").value=c.product;$("discount").value=c.discount;$("audience").value=c.audience;show("event")}
function pauseCampaign(i){state.campaigns[i].status=state.campaigns[i].status==="Paused"?"Running":"Paused";save();render();toast("Campaign status updated")}
function aiSuggest(){let p=$("product").value;$("discount").value=p==="Milk Tea"?"Buy 1 Get 1":p==="Coffee"?"Free Size Upgrade":"20% OFF";$("rules").value="Use peak hours, flash timer, and one redemption per customer.";$("aiText").textContent=`AI recommends ${$("discount").value} for ${p}, target students and repeat buyers, run from 5 PM to 8 PM.`;toast("AI idea generated")}
function addPoints(){state.customers[0].points+=10;save();render();toast("10 points added")}function addReward(){state.rewards.push("400 pts - VIP Bundle");save();render();toast("Reward rule added")}function respondReview(){if(!$("reviewReply").value.trim())return toast("Write a response first");$("reviewReply").value="";toast("Review response sent")}
function sendReply(){if(!$("reply").value.trim())$("reply").value=$("template").value;state.msgs=Math.max(0,state.msgs-1);$("reply").value="";save();render();toast("Reply sent")}
function budgetRecommend(){let b=Number($("budget").value||0);$("budgetResult").textContent=b>=150?"Recommended: BOGO Milk Tea, Burger Combo, Coffee Upgrade.":"Recommended: PHP 99 rice meal, PHP 80 coffee upgrade, student snack deal.";toast("Affordable deals updated")}
function inviteFriend(){state.group=Math.min(5,state.group+1);save();render();toast("Invite added")}function completeMission(){let m=state.missions.find(x=>x[1]==="Pending");if(m){m[1]="Done";state.streak++;state.customers[0].points+=15;save();render();toast("Mission complete: +15 pts")}else toast("All missions complete")}function saveOfflinePromo(){state.offline.push("Flash Coffee Upgrade - Offline ready");save();render();toast("Promo saved for offline mode")}
function tick(){let left=Math.max(0,flashEnd-Date.now()),min=Math.floor(left/60000),sec=Math.floor((left%60000)/1000);if($("timer"))$("timer").textContent=`Ends in ${min}m ${String(sec).padStart(2,"0")}s • few coupons remaining`;setTimeout(tick,1000)}
function drawLineChart(id,values,labels,color){let c=$(id),x=c.getContext("2d"),w=c.clientWidth,h=c.clientHeight,p=34,max=Math.max(...values)*1.2;c.width=w*devicePixelRatio;c.height=h*devicePixelRatio;x.setTransform(devicePixelRatio,0,0,devicePixelRatio,0,0);x.clearRect(0,0,w,h);x.strokeStyle="rgba(125,211,252,.22)";for(let i=0;i<4;i++){let y=p+i*(h-p*2)/3;x.beginPath();x.moveTo(p,y);x.lineTo(w-p,y);x.stroke()}x.strokeStyle=color;x.lineWidth=3;x.beginPath();values.forEach((v,i)=>{let px=p+i*(w-p*2)/(values.length-1),py=h-p-v/max*(h-p*2);i?x.lineTo(px,py):x.moveTo(px,py)});x.stroke();x.fillStyle="#fff";values.forEach((v,i)=>{let px=p+i*(w-p*2)/(values.length-1),py=h-p-v/max*(h-p*2);x.beginPath();x.arc(px,py,4,0,7);x.fill()});x.fillStyle="#9fb3c8";x.font="11px Arial";labels.forEach((l,i)=>{let px=p+i*(w-p*2)/(labels.length-1);x.fillText(l,px-10,h-10)})}
function drawBarChart(id,labels,values){let c=$(id),x=c.getContext("2d"),w=c.clientWidth,h=c.clientHeight,p=34,max=Math.max(...values,1)*1.25;c.width=w*devicePixelRatio;c.height=h*devicePixelRatio;x.setTransform(devicePixelRatio,0,0,devicePixelRatio,0,0);x.clearRect(0,0,w,h);let bw=(w-p*2)/values.length*.58;values.forEach((v,i)=>{let px=p+i*((w-p*2)/values.length)+bw*.35,bh=v/max*(h-p*2),py=h-p-bh,g=x.createLinearGradient(0,py,0,h-p);g.addColorStop(0,"#22d3ee");g.addColorStop(1,"#2563eb");x.fillStyle=g;x.beginPath();x.roundRect(px,py,bw,bh,8);x.fill();x.fillStyle="#f8fbff";x.font="11px Arial";x.fillText(v,px+2,py-6);x.fillStyle="#9fb3c8";x.fillText(labels[i].slice(0,6),px,h-10)})}
function drawPieChart(id,data){let c=$(id),x=c.getContext("2d"),w=c.clientWidth,h=c.clientHeight,cx=w/2,cy=h/2-10,r=Math.min(w,h)*.27,total=data.reduce((a,d)=>a+d.value,0)||1,start=-Math.PI/2,colors=["#22d3ee","#2563eb","#34d399","#fbbf24","#a78bfa","#fb7185"];c.width=w*devicePixelRatio;c.height=h*devicePixelRatio;x.setTransform(devicePixelRatio,0,0,devicePixelRatio,0,0);x.clearRect(0,0,w,h);data.forEach((d,i)=>{let a=d.value/total*Math.PI*2;x.beginPath();x.moveTo(cx,cy);x.arc(cx,cy,r,start,start+a);x.closePath();x.fillStyle=colors[i%colors.length];x.fill();start+=a});x.fillStyle="#020617";x.beginPath();x.arc(cx,cy,r*.55,0,7);x.fill();x.fillStyle="#f8fbff";x.font="bold 13px Arial";x.textAlign="center";x.fillText("Total",cx,cy-2);x.fillText(total.toLocaleString(),cx,cy+16);x.textAlign="left";x.font="11px Arial";data.forEach((d,i)=>{let lx=16,ly=h-58+i*16;x.fillStyle=colors[i%colors.length];x.fillRect(lx,ly-8,9,9);x.fillStyle="#9fb3c8";x.fillText(`${d.label}: ${d.value.toLocaleString()}`,lx+15,ly)})}
function feedbackCounts(){let counts={Positive:0,Neutral:0,Negative:0};state.reviews.forEach(r=>counts[r[3]]=(counts[r[3]]||0)+1);return counts}
function drawFeedbackChart(){let c=$("feedbackChart");if(!c)return;let x=c.getContext("2d"),w=c.clientWidth,h=c.clientHeight,p=34,counts=feedbackCounts(),labels=["Positive","Neutral","Negative"],values=labels.map(l=>counts[l]),max=Math.max(...values,1)*1.25,colors=["#34d399","#fbbf24","#fb7185"];c.width=w*devicePixelRatio;c.height=h*devicePixelRatio;x.setTransform(devicePixelRatio,0,0,devicePixelRatio,0,0);x.clearRect(0,0,w,h);x.strokeStyle="rgba(125,211,252,.22)";for(let i=0;i<4;i++){let y=p+i*(h-p*2)/3;x.beginPath();x.moveTo(p,y);x.lineTo(w-p,y);x.stroke()}let area=(w-p*2)/labels.length,bw=area*.52;values.forEach((v,i)=>{let px=p+i*area+(area-bw)/2,bh=v/max*(h-p*2),py=h-p-bh;x.fillStyle=colors[i];x.beginPath();x.roundRect(px,py,bw,bh,9);x.fill();x.fillStyle="#f8fbff";x.font="bold 13px Arial";x.textAlign="center";x.fillText(v,px+bw/2,py-8);x.fillStyle="#9fb3c8";x.font="11px Arial";x.fillText(labels[i],px+bw/2,h-10)});x.textAlign="left"}
function groupByCategoryRevenue(){let map={};state.campaigns.forEach(c=>map[c.category]=(map[c.category]||0)+c.revenue);return Object.entries(map).map(([label,value])=>({label,value}))}
function sentimentData(){let map={Positive:0,Neutral:0,Negative:0};state.reviews.forEach(r=>map[r[3]]++);return Object.entries(map).map(([label,value])=>({label,value}))}
function drawCharts(){drawBarChart("promoChart",state.campaigns.map(c=>c.name),state.campaigns.map(c=>c.claims));drawLineChart("salesChart",[11200,14800,13600,17200,15900,21400,22600],["Mon","Tue","Wed","Thu","Fri","Sat","Sun"],"#34d399");drawPieChart("categoryPie",groupByCategoryRevenue());drawPieChart("claimPie",state.campaigns.map(c=>({label:c.name.split(" ")[0],value:c.claims})));drawPieChart("sentimentPie",sentimentData())}
render();drawCharts();tick();
</script>
</body>
</html>
