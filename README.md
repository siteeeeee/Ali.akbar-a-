
                lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"><title>حسینیه حضرت علی اکبر | مجتمع آسمان</title><meta name="description" content="وب‌سایت حسینیه حضرت علی اکبر علیه السلام - مجتمع آسمان">
<meta name="theme-color" content="#090909"><style>

@import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800;900&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:'Vazirmatn',Tahoma,sans-serif;
    background:#080909;
    color:#f4f4f4;
    line-height:1.9;
    overflow-x:hidden;
}

a{
    text-decoration:none;
    color:inherit;
}

.container{
    width:min(1150px,92%);
    margin:auto;
}

/* ================= HEADER ================= */

header{
    position:fixed;
    top:0;
    right:0;
    left:0;
    z-index:1000;
    background:rgba(8,9,9,.82);
    backdrop-filter:blur(18px);
    border-bottom:1px solid rgba(255,255,255,.06);
}

.nav{
    height:75px;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.brand{
    display:flex;
    align-items:center;
    gap:12px;
    font-weight:800;
}

.brand-mark{
    width:43px;
    height:43px;
    border-radius:14px;
    display:flex;
    align-items:center;
    justify-content:center;
    background:linear-gradient(145deg,#651818,#230707);
    border:1px solid rgba(190,150,70,.35);
    box-shadow:0 8px 30px rgba(80,0,0,.25);
    font-size:20px;
}

.brand-text{
    display:flex;
    flex-direction:column;
    line-height:1.3;
}

.brand-text strong{
    font-size:14px;
}

.brand-text span{
    color:#999;
    font-size:10px;
    font-weight:400;
}

.nav-links{
    display:flex;
    gap:25px;
    color:#aaa;
    font-size:13px;
}

.nav-links a{
    transition:.3s;
}

.nav-links a:hover{
    color:#d8b76a;
}

.eitaa-nav{
    padding:9px 16px;
    border-radius:10px;
    background:#123b2b;
    color:#cce9dc !important;
    border:1px solid rgba(80,180,130,.25);
}

/* ================= HERO ================= */

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
    position:relative;
    overflow:hidden;
    padding-top:80px;
}

.hero::before{
    content:"";
    position:absolute;
    width:650px;
    height:650px;
    background:radial-gradient(circle,rgba(105,16,16,.30),transparent 68%);
    top:-220px;
    right:-180px;
}

.hero::after{
    content:"";
    position:absolute;
    width:550px;
    height:550px;
    background:radial-gradient(circle,rgba(10,75,49,.20),transparent 70%);
    bottom:-250px;
    left:-180px;
}

.hero-content{
    position:relative;
    z-index:2;
    max-width:760px;
}

.bismillah{
    color:#b99953;
    font-size:15px;
    margin-bottom:28px;
    letter-spacing:1px;
}

.hero h1{
    font-size:clamp(38px,7vw,78px);
    line-height:1.25;
    font-weight:900;
    margin-bottom:15px;
}

.hero h1 span{
    display:block;
    color:#a92727;
}

.hero-sub{
    color:#a8a8a8;
    max-width:650px;
    font-size:16px;
    margin-bottom:35px;
}

.hero-buttons{
    display:flex;
    gap:12px;
    flex-wrap:wrap;
}

.btn{
    padding:13px 23px;
    border-radius:13px;
    font-size:13px;
    font-weight:700;
    transition:.3s;
    display:inline-flex;
    align-items:center;
    justify-content:center;
}

.btn-red{
    background:#771d1d;
    border:1px solid #922828;
    box-shadow:0 12px 30px rgba(100,0,0,.20);
}

.btn-red:hover{
    transform:translateY(-3px);
    background:#902323;
}

.btn-dark{
    background:#101313;
    border:1px solid #252929;
    color:#bbb;
}

.btn-dark:hover{
    transform:translateY(-3px);
    border-color:#555;
}

/* ================= STATS ================= */

.stats{
    position:relative;
    z-index:5;
    margin-top:-70px;
}

.stats-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:12px;
}

.stat{
    background:rgba(18,20,20,.82);
    border:1px solid rgba(255,255,255,.06);
    border-radius:18px;
    padding:22px;
    text-align:center;
    backdrop-filter:blur(12px);
}

.stat strong{
    display:block;
    font-size:24px;
    color:#d4b76c;
}

.stat span{
    color:#888;
    font-size:12px;
}

/* ================= SECTIONS ================= */

section{
    padding:110px 0;
}

.section-title{
    margin-bottom:45px;
}

.section-title small{
    color:#a92727;
    font-weight:700;
    font-size:12px;
}

.section-title h2{
    font-size:32px;
    margin-top:7px;
}

.section-title p{
    color:#777;
    font-size:13px;
    margin-top:8px;
}

/* ================= ABOUT ================= */

.about-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:25px;
}

.about-card{
    background:#101212;
    border:1px solid #1e2222;
    border-radius:22px;
    padding:32px;
}

.about-card h3{
    margin-bottom:15px;
    font-size:21px;
}

.about-card p{
    color:#999;
    font-size:14px;
}

.quote{
    margin-top:22px;
    padding:17px;
    border-right:3px solid #791d1d;
    background:#0b0d0d;
    color:#c7c7c7;
    border-radius:10px;
    font-size:13px;
}

/* ================= PROGRAM ================= */

.programs{
    background:#0b0d0d;
    border-top:1px solid #111;
    border-bottom:1px solid #111;
}

.program-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:18px;
}

.program{
    background:#111414;
    border:1px solid #202525;
    border-radius:20px;
    padding:25px;
    transition:.3s;
}

.program:hover{
    transform:translateY(-5px);
    border-color:#552020;
}

.program-icon{
    width:45px;
    height:45px;
    display:flex;
    align-items:center;
    justify-content:center;
    border-radius:13px;
    background:#321212;
    color:#d2b56c;
    margin-bottom:18px;
    font-size:19px;
}

.program h3{
    font-size:17px;
    margin-bottom:8px;
}

.program p{
    color:#858585;
    font-size:12px;
}

/* ================= EITAA ================= */

.eitaa{
    position:relative;
}

.eitaa-box{
    background:
        linear-gradient(135deg,rgba(21,65,48,.55),rgba(11,16,14,.85));
    border:1px solid rgba(67,145,107,.22);
    border-radius:28px;
    padding:55px 35px;
    text-align:center;
    overflow:hidden;
}

.eitaa-box::before{
    content:"";
    position:absolute;
    width:250px;
    height:250px;
    background:radial-gradient(circle,rgba(42,130,87,.16),transparent 70%);
    top:-100px;
    right:-80px;
}

.eitaa-box h2{
    font-size:30px;
    margin-bottom:10px;
}

.eitaa-box p{
    color:#9baca5;
    max-width:600px;
    margin:0 auto 25px;
    font-size:13px;
}

.eitaa-btn{
    display:inline-flex;
    padding:13px 25px;
    border-radius:12px;
    background:#176344;
    border:1px solid #28815b;
    color:#e4fff1;
    font-weight:700;
    font-size:13px;
    transition:.3s;
}

.eitaa-btn:hover{
    transform:translateY(-3px);
    background:#1d7650;
}

/* ================= CONTACT ================= */

.contact-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:20px;
}

.contact-card{
    background:#101212;
    border:1px solid #1d2121;
    border-radius:20px;
    padding:25px;
}

.contact-item{
    padding:17px 0;
    border-bottom:1px solid #1d2020;
}

.contact-item:last-child{
    border-bottom:0;
}

.contact-item span{
    display:block;
    color:#777;
    font-size:11px;
    margin-bottom:3px;
}

.contact-item strong{
    color:#ddd;
    font-size:13px;
}

/* ================= FOOTER ================= */

footer{
    padding:35px 0;
    border-top:1px solid #171919;
    background:#060707;
}

.footer{
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:20px;
}

.footer p{
    color:#666;
    font-size:11px;
}

.footer a{
    color:#a99763;
    font-size:11px;
}

/* ================= MOBILE ================= */

@media(max-width:800px){

    .nav-links{
        display:none;
    }

    .brand-text strong{
        font-size:12px;
    }

    .hero{
        min-height:90vh;
    }

    .hero h1{
        font-size:43px;
    }

    .hero-sub{
        font-size:14px;
    }

    .stats-grid{
        grid-template-columns:1fr;
    }

    .stats{
        margin-top:-35px;
    }

    .about-grid,
    .contact-grid{
        grid-template-columns:1fr;
    }

    .program-grid{
        grid-template-columns:1fr;
    }

    section{
        padding:80px 0;
    }

    .section-title h2{
        font-size:27px;
    }

    .eitaa-box{
        padding:40px 20px;
    }

    .footer{
        flex-direction:column;
        text-align:center;
    }
}

</style></head><body><header>
    <div class="container nav">    <a href="#" class="brand">

        <div class="brand-mark">ع</div>

        <div class="brand-text">
            <strong>حسینیه حضرت علی اکبر</strong>
            <span>علیه السلام</span>
        </div>

    </a>

    <nav class="nav-links">
        <a href="#about">درباره حسینیه</a>
        <a href="#programs">برنامه‌ها</a>
        <a href="#contact">ارتباط</a>
        <a class="eitaa-nav" href="https://eitaa.com/hoseinieealiakbar" target="_blank">
            ایتا
        </a>
    </nav>

</div>

</header><main><!-- HERO --><section class="hero"><div class="container">

    <div class="hero-content">

        <div class="bismillah">
            بِسْمِ اللهِ الرَّحْمٰنِ الرَّحِیمِ
        </div>

        <h1>
            حسینیه
            <span>حضرت علی اکبر</span>
        </h1>

        <p class="hero-sub">
            پایگاه فرهنگی و مذهبی حسینیه حضرت علی اکبر علیه السلام
            در مجتمع آسمان؛ جایی برای گردهمایی محبان اهل‌بیت علیهم‌السلام.
        </p>

        <div class="hero-buttons">

            <a
                href="https://eitaa.com/hoseinieealiakbar"
                target="_blank"
                class="btn btn-red"
            >
                مشاهده کانال ایتا
            </a>

            <a href="#programs" class="btn btn-dark">
                مشاهده برنامه‌ها
            </a>

        </div>

    </div>

</div>

</section><!-- STATS --><div class="stats"><div class="container">

    <div class="stats-grid">

        <div class="stat">
            <strong>۵۷۲+</strong>
            <span>دنبال‌کننده در ایتا</span>
        </div>

        <div class="stat">
            <strong>۲۷۰۰+</strong>
            <span>تصویر در کانال</span>
        </div>

        <div class="stat">
            <strong>۳۲۹+</strong>
            <span>ویدیو</span>
        </div>

    </div>

</div>

</div><!-- ABOUT --><section id="about"><div class="container">

    <div class="section-title">
        <small>ABOUT US</small>
        <h2>درباره حسینیه</h2>
        <p>خانه‌ای برای عشق به اهل‌بیت علیهم‌السلام</p>
    </div>

    <div class="about-grid">

        <div class="about-card">

            <h3>حسینیه حضرت علی اکبر</h3>

            <p>
                حسینیه حضرت علی اکبر علیه السلام یکی از پایگاه‌های
                فرهنگی و مذهبی مجتمع آسمان است که با برگزاری مراسم،
                مجالس مذهبی و برنامه‌های فرهنگی میزبان محبان اهل‌بیت
                علیهم‌السلام است.
            </p>

            <div class="quote">
                «اَلسَّلامُ عَلَیْکَ یا عَلِیَّ بْنَ الْحُسَیْنِ»
            </div>

        </div>


        <div class="about-card">

            <h3>آخرین اطلاع‌رسانی</h3>

            <p>
                آخرین اخبار، تصاویر، ویدیوها و اطلاعیه‌های مراسم
                حسینیه را می‌توانید از طریق کانال رسمی ایتا دنبال کنید.
            </p>

            <div class="quote">
                کانال رسمی حسینیه حضرت علی اکبر در ایتا
                <br>
                @hoseinieealiakbar
            </div>

        </div>

    </div>

</div>

</section><!-- PROGRAMS --><section id="programs" class="programs"><div class="container">

    <div class="section-title">
        <small>PROGRAMS</small>
        <h2>برنامه‌های حسینیه</h2>
        <p>فضایی برای مراسم و فعالیت‌های فرهنگی و مذهبی</p>
    </div>

    <div class="program-grid">

        <div class="program">

            <div class="program-icon">﷽</div>

            <h3>مراسم مذهبی</h3>

            <p>
                برگزاری مراسم و مجالس مذهبی در مناسبت‌های مختلف.
            </p>

        </div>


        <div class="program">

            <div class="program-icon">✦</div>

            <h3>برنامه‌های فرهنگی</h3>

            <p>
                فعالیت‌های فرهنگی و اجتماعی با محوریت معارف اهل‌بیت.
            </p>

        </div>


        <div class="program">

            <div class="program-icon">♡</div>

            <h3>خدمت به محبان اهل‌بیت</h3>

            <p>
                ایجاد فضایی صمیمی برای حضور خانواده‌ها و دوستداران اهل‌بیت.
            </p>

        </div>

    </div>

</div>

</section><!-- EITAA --><section class="eitaa"><div class="container">

    <div class="eitaa-box">

        <h2>همراه حسینیه در ایتا</h2>

        <p>
            برای اطلاع از مراسم‌ها، تصاویر، ویدیوها و آخرین اطلاعیه‌ها
            عضو کانال رسمی حسینیه حضرت علی اکبر شوید.
        </p>

        <a
            href="https://eitaa.com/hoseinieealiakbar"
            target="_blank"
            class="eitaa-btn"
        >
            ورود به کانال رسمی ایتا
        </a>

    </div>

</div>

</section><!-- CONTACT --><section id="contact"><div class="container">

    <div class="section-title">
        <small>CONTACT</small>
        <h2>ارتباط با حسینیه</h2>
        <p>راه‌های ارتباطی و دسترسی</p>
    </div>

    <div class="contact-grid">

        <div class="contact-card">

            <div class="contact-item">
                <span>کانال رسمی ایتا</span>
                <strong>@hoseinieealiakbar</strong>
            </div>

            <div class="contact-item">
                <span>ارتباط با مدیر</span>
                <strong>@AdminHosseiniealiakbr</strong>
            </div>

        </div>


        <div class="contact-card">

            <div class="contact-item">
                <span>مکان</span>
                <strong>مجتمع آسمان</strong>
            </div>

            <div class="contact-item">
                <span>آدرس</span>
                <strong>
                    اتوبان خرازی، میدان دریاچه،
                    خیابان جوزانی غربی،
                    خیابان هراز
                </strong>
            </div>

        </div>

    </div>

</div>

</section></main><footer><div class="container footer">

    <p>
        © ۱۴۰۵ حسینیه حضرت علی اکبر علیه السلام
    </p>

    <a
        href="https://eitaa.com/hoseinieealiakbar"
        target="_blank"
    >
        کانال رسمی ایتا
    </a>

</div>

</footer></body>
</html>
