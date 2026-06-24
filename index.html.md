<!DOCTYPE html>  
<html lang="ru">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Ремонт квартир под ключ</title>  
  
<style>  
*{  
    margin:0;  
    padding:0;  
    box-sizing:border-box;  
    font-family: Arial, sans-serif;  
}  
  
html{  
    scroll-behavior:smooth;  
}  
  
body{  
    background:#f7f8fb;  
    color:#222;  
    line-height:1.6;  
}  
  
.container{  
    width:90%;  
    max-width:1200px;  
    margin:auto;  
}  
  
header{  
    position:sticky;  
    top:0;  
    background:#fff;  
    box-shadow:0 2px 10px rgba(0,0,0,0.08);  
    z-index:1000;  
}  
  
.nav{  
    display:flex;  
    justify-content:space-between;  
    align-items:center;  
    padding:15px 0;  
}  
  
.logo{  
    font-size:22px;  
    font-weight:bold;  
    color:#0d2b5c;  
}  
  
.menu{  
    display:flex;  
    gap:20px;  
}  
  
.menu a{  
    text-decoration:none;  
    color:#333;  
    transition:.3s;  
}  
  
.menu a:hover{  
    color:#0d2b5c;  
}  
  
.hero{  
    min-height:90vh;  
    display:flex;  
    align-items:center;  
    padding:60px 0;  
}  
  
.hero-content{  
    display:grid;  
    grid-template-columns:1fr 420px;  
    gap:40px;  
    align-items:center;  
}  
  
.hero h1{  
    font-size:56px;  
    color:#0d2b5c;  
    margin-bottom:20px;  
}  
  
.hero p{  
    font-size:22px;  
    margin-bottom:30px;  
}  
  
.btn{  
    display:inline-block;  
    background:#0d2b5c;  
    color:#fff;  
    padding:15px 30px;  
    border:none;  
    border-radius:10px;  
    text-decoration:none;  
    cursor:pointer;  
    transition:.3s;  
}  
  
.btn:hover{  
    opacity:.9;  
}  
  
.form-box{  
    background:#fff;  
    padding:30px;  
    border-radius:20px;  
    box-shadow:0 10px 30px rgba(0,0,0,0.08);  
}  
  
.form-box h3{  
    margin-bottom:20px;  
    color:#0d2b5c;  
}  
  
input{  
    width:100%;  
    padding:14px;  
    margin-bottom:15px;  
    border:1px solid #ddd;  
    border-radius:10px;  
}  
  
section{  
    padding:80px 0;  
}  
  
.section-title{  
    text-align:center;  
    font-size:36px;  
    margin-bottom:40px;  
    color:#0d2b5c;  
}  
  
.cards{  
    display:grid;  
    grid-template-columns:repeat(3,1fr);  
    gap:25px;  
}  
  
.card{  
    background:#fff;  
    padding:30px;  
    text-align:center;  
    border-radius:20px;  
    box-shadow:0 5px 20px rgba(0,0,0,0.06);  
}  
  
.card .icon{  
    font-size:48px;  
    margin-bottom:15px;  
}  
  
.pricing{  
    display:grid;  
    grid-template-columns:repeat(3,1fr);  
    gap:25px;  
}  
  
.price-card{  
    background:#fff;  
    border-radius:20px;  
    padding:30px;  
    text-align:center;  
    box-shadow:0 5px 20px rgba(0,0,0,0.06);  
}  
  
.price-card h3{  
    color:#0d2b5c;  
    margin-bottom:15px;  
}  
  
.price{  
    font-size:32px;  
    font-weight:bold;  
    margin-bottom:15px;  
}  
  
footer{  
    background:#0d2b5c;  
    color:#fff;  
    padding:40px 0;  
    text-align:center;  
}  
  
footer a{  
    color:#fff;  
    text-decoration:none;  
    margin:0 10px;  
}  
  
@media(max-width:900px){  
  
    .hero-content{  
        grid-template-columns:1fr;  
    }  
  
    .hero h1{  
        font-size:40px;  
    }  
  
    .cards,  
    .pricing{  
        grid-template-columns:1fr;  
    }  
  
    .menu{  
        gap:12px;  
        font-size:14px;  
    }  
}  
  
@media(max-width:600px){  
  
    .nav{  
        flex-direction:column;  
        gap:10px;  
    }  
  
    .hero h1{  
        font-size:32px;  
    }  
  
    .hero p{  
        font-size:18px;  
    }  
  
    .section-title{  
        font-size:28px;  
    }  
}  
</style>  
</head>  
<body>  
  
<header>  
    <div class="container nav">  
        <div class="logo">Ремонт квартир</div>  
        <nav class="menu">  
            <a href="#hero">Главная</a>  
            <a href="#advantages">Почему мы</a>  
            <a href="#prices">Цены</a>  
            <a href="#footer">Контакты</a>  
        </nav>  
    </div>  
</header>  
  
<section class="hero" id="hero">  
    <div class="container hero-content">  
        <div>  
            <h1>Ремонт квартир под ключ</h1>  
            <p>Сделаем всё за 30 дней</p>  
            <a href="#form" class="btn">Рассчитать стоимость</a>  
        </div>  
  
        <div class="form-box" id="form">  
            <h3>Оставьте заявку</h3>  
            <form id="leadForm">  
                <input type="text" placeholder="Ваше имя" required>  
                <input type="tel" placeholder="Ваш телефон" required>  
                <button type="submit" class="btn" style="width:100%;">Отправить заявку</button>  
            </form>  
        </div>  
    </div>  
</section>  
  
<section id="advantages">  
    <div class="container">  
        <h2 class="section-title">Почему мы</h2>  
  
        <div class="cards">  
            <div class="card">  
                <div class="icon">🛡️</div>  
                <h3>Гарантия 3 года</h3>  
                <p>Отвечаем за качество выполненных работ.</p>  
            </div>  
  
            <div class="card">  
                <div class="icon">📋</div>  
                <h3>Фиксированная смета</h3>  
                <p>Стоимость не изменится в процессе ремонта.</p>  
            </div>  
  
            <div class="card">  
                <div class="icon">💰</div>  
                <h3>Без предоплаты</h3>  
                <p>Оплата по факту выполненных этапов.</p>  
            </div>  
        </div>  
    </div>  
</section>  
  
<section id="prices">  
    <div class="container">  
        <h2 class="section-title">Цены</h2>  
  
        <div class="pricing">  
            <div class="price-card">  
                <h3>Косметический</h3>  
                <div class="price">от 3 500 ₽/м²</div>  
                <p>Обновление отделки, покраска, обои, ламинат.</p>  
            </div>  
  
            <div class="price-card">  
                <h3>Капитальный</h3>  
                <div class="price">от 7 500 ₽/м²</div>  
                <p>Полная замена коммуникаций и отделки.</p>  
            </div>  
  
            <div class="price-card">  
                <h3>Дизайнерский</h3>  
                <div class="price">от 12 000 ₽/м²</div>  
                <p>Индивидуальный проект и премиальная отделка.</p>  
            </div>  
        </div>  
    </div>  
</section>  
  
<footer id="footer">  
    <div class="container">  
        <p>Адрес: г. [ТВОЙ ГОРОД], ул. Строителей, 10</p>  
        <p>Телефон: +7 (999) 123-45-67</p>  
        <br>  
        <a href="#">Telegram</a>  
        <a href="#">VK</a>  
        <a href="#">WhatsApp</a>  
    </div>  
</footer>  
  
<script>  
document.getElementById('leadForm').addEventListener('submit', function(e){  
    e.preventDefault();  
    alert('Спасибо, мы свяжемся с вами!');  
    this.reset();  
});  
</script>  
  
</body>  
</html>  
