# Furkan-Sabiha-<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Furkan ❤️ Sabiha</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:linear-gradient(135deg,#ff4d6d,#ff8fa3);
    color:white;
    text-align:center;
    overflow-x:hidden;
}

#loading{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background:linear-gradient(135deg,#ff4d6d,#ff8fa3);
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    z-index:9999;
}

#loading h1{
    font-size:2.5rem;
    margin-bottom:20px;
}

#loading button{
    padding:15px 30px;
    border:none;
    border-radius:15px;
    font-size:18px;
    cursor:pointer;
}

.content{
    padding:40px 20px;
}

.gallery img{
    width:90%;
    max-width:700px;
    border-radius:20px;
    margin:15px auto;
    display:block;
}

.message{
    font-size:20px;
    line-height:1.8;
    margin-top:20px;
}
</style>
</head>

<body>

<div id="loading">
    <h1>❤️ Seni Seviyorum Sabiha ❤️</h1>
    <p>Bu site Furkan'dan sana özel hazırlandı.</p>
    <br>
    <button onclick="enterSite()">Siteye Gir</button>
</div>

<div class="content">
    <h1>❤️ Furkan & Sabiha ❤️</h1>

    <div class="message">
        <p>
            Seninle geçen her an benim için çok değerli.<br>
            Gülüşün, sesin ve varlığın hayatımı güzelleştiriyor.<br><br>

            Seni çok seviyorum Sabiha ❤️
        </p>
    </div>

    <!-- FOTOĞRAFLARI BURAYA EKLE -->
    <div class="gallery">
        <img src="foto1.jpg">
        <img src="foto2.jpg">
        <img src="foto3.jpg">
    </div>
</div>

<script>
function enterSite(){
    document.getElementById("loading").style.display = "none";
}
</script>

</body>
</html>
