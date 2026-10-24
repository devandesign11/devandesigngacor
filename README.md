<meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta charset="UTF-8">
  <title>DEVAN DESIGN</title>
  <style>
    *{box-sizing:border-box}
    body{margin:0;background:#080808;color:white;font-family:Arial,sans-serif}
    header{text-align:center;padding:28px 15px;background:radial-gradient(circle,#493b00,#111 70%);border-bottom:2px solid #ffe000}
    .brand{font-size:34px;font-weight:900;font-style:italic;color:#ffe000;letter-spacing:2px}
    .sub{font-size:12px;color:#ddd;margin-top:8px}
    .admin{display:inline-block;margin-top:14px;border:1px solid #ffe000;padding:8px 13px;border-radius:25px;color:#ffe000;font-weight:bold;font-size:12px}
    main{max-width:850px;margin:auto;padding:16px}
    .panel{background:#151515;border:1px solid #383838;border-radius:12px;padding:16px;margin-bottom:18px}
    h2{color:#ffe000;font-size:20px}
    label{display:block;font-size:13px;margin:12px 0 6px}
    input{width:100%;padding:13px;border-radius:7px;border:1px solid #777;font-size:15px;background:#fff;color:#111}
    .hint{color:#aaa;font-size:12px;line-height:1.6}
    .grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:12px}
    .card{background:#151515;border:1px solid #645500;border-radius:10px;padding:9px;min-width:0}
    .art{height:145px;border-radius:7px;border:1px solid #655500;background:radial-gradient(circle at 50% 35%,#514200,#151515 70%);display:flex;align-items:center;justify-content:center;flex-direction:column;text-align:center;overflow:hidden}
    .symbol{font-size:43px;text-shadow:0 0 15px #ffe000}
    .art strong{font-size:15px;color:#ffe000;font-style:italic;text-shadow:1px 2px black}
    .card h3{font-size:15px;margin:12px 0 7px}
    .desc{font-size:12px;line-height:1.6;color:#ccc}
    .price{font-weight:900;color:#ffe000;font-size:18px;margin:12px 0}
    button,.btn{display:block;width:100%;padding:13px 8px;border:0;border-radius:8px;background:#ffe000;color:#111;text-align:center;text-decoration:none;font-size:14px;font-weight:bold;cursor:pointer;margin-top:12px}
    .green{background:#13a34a;color:white}
    .gray{background:#333;color:white}
    .hidden{display:none!important}
    .detail-art{height:205px}
    .detail-desc{font-size:14px;line-height:1.8;color:#ddd}
    .bigprice{text-align:center;border:1px solid #ffe000;background:#292300;padding:20px;border-radius:8px;margin-top:20px;color:#ffe000;font-weight:900;font-size:25px}
    .closing{text-align:center;color:#ffe000;font-weight:bold;letter-spacing:1px;margin-top:24px;padding:15px 4px}
    footer{text-align:center;padding:20px;color:#aaa;font-size:12px;border-top:1px solid #333}
    @media(min-width:650px){.grid{grid-template-columns:repeat(2,minmax(0,1fr))}.art{height:190px}}
  </style>
</head>
<body>

<header>
  <div class="brand">DEVAN DESIGN</div>
  <div class="sub">CREATIVE DIGITAL DESIGN • LOGO • POSTER</div>
  <div class="admin">● ADMIN FAST RESPON</div>
  <p class="sub">Logo anti pasaran, dibuat sesuai request kamu.</p>
</header>

<main>
  <section id="home">
    <div class="panel">
      <h2>✦ FORMAT PEMESANAN</h2>
      <p class="hint">Isi nama dan nomor WhatsApp terlebih dahulu sebelum memilih produk.</p>
      <form id="buyerForm">
        <label for="buyerName">Nama pembeli</label>
        <input id="buyerName" type="text" maxlength="60" placeholder="Masukkan nama kamu" required>

        <label for="buyerPhone">Nomor WhatsApp kamu</label>
        <input id="buyerPhone" type="tel" maxlength="20" placeholder="Contoh: 6281234567890" required>

        <button type="submit">SIMPAN FORMAT</button>
      </form>
      <p id="formStatus" class="hint">Data hanya digunakan di halaman ini untuk menyusun pesan order.</p>
    </div>

    <h2>⚡ PILIH LAYANAN</h2>
    <div class="grid">

      <article class="card">
        <div class="art">
          <div class="symbol">♛</div>
          <strong>LOGO MASCOT</strong>
          <span class="hint">CUSTOM CHARACTER</span>
        </div>
        <h3>Logo Mascot</h3>
        <p class="desc">Logo mascot adalah sebuah gambar yang dilengkapi anatomi manusia dengan berbagai macam pose yang bisa di request, dan juga pakaian.</p>
        <div class="price">HARGA 40K</div>
        <button type="button" onclick="openDetail(0)">LIHAT & ORDER →</button>
      </article>

      <article class="card">
        <div class="art">
          <div class="symbol">♟</div>
          <strong>LOGO CHIBI</strong>
          <span class="hint">MINI CHARACTER</span>
        </div>
        <h3>Logo Chibi FF</h3>
        <p class="desc">Logo chibi ff adalah sebuah karakter yang memiliki badan mini bisa req karakter dari game, atau dari anime.</p>
        <div class="price">HARGA 10K–20K</div>
        <button type="button" onclick="openDetail(1)">LIHAT & ORDER →</button>
      </article>

      <article class="card">
        <div class="art">
          <div class="symbol">♛</div>
          <strong>LOGO NAMA</strong>
          <span class="hint">NAME MONOGRAM</span>
        </div>
        <h3>Logo Nama</h3>
        <p class="desc">Logo nama adalah sebuah gambar seperti monogram atau sebuah teks yang di ubah menjadi terlihat lebih keren mengikuti nama jb/nama yang di req.</p>
        <div class="price">HARGA 10K–20K</div>
        <button type="button" onclick="openDetail(2)">LIHAT & ORDER →</button>
      </article>

      <article class="card">
        <div class="art">
          <div class="symbol">▣</div>
          <strong>POSTER</strong>
          <span class="hint">PROMOTION DESIGN</span>
        </div>
        <h3>Poster</h3>
        <p class="desc">Poster promosi JB maupun non-JB, seperti testimoni, poster jual makanan, poster sekolah, dan lain-lain.</p>
        <div class="price">HARGA 7K</div>
        <button type="button" onclick="openDetail(3)">LIHAT & ORDER →</button>
      </article>
    </div>
  </section>

  <section id="detail" class="hidden">
    <div class="panel">
      <button class="gray" onclick="goHome()">← KEMBALI KE KATALOG</button>
      <h2 id="detailTitle">DETAIL PRODUK</h2>

      <div class="art detail-art" id="detailArt">
        <div class="symbol" id="detailSymbol">♛</div>
        <strong id="detailArtTitle">LOGO</strong>
        <span class="hint">DEVAN DESIGN • CUSTOM ART</span>
      </div>

      <p class="detail-desc" id="detailDesc"></p>
      <div class="bigprice" id="detailPrice"></div>

      <p class="hint">Pastikan nama dan nomor WhatsApp sudah diisi pada halaman awal.</p>
      <button class="green" onclick="orderHub()">☏ ORDER HUB — WHATSAPP</button>

      <div class="closing">✦ TEKAN JIKA NIAT ORDER ✦</div>
    </div>
  </section>
</main>

<footer>© DEVAN DESIGN • CREATIVE DIGITAL SERVICES</footer>

<script>
  const products = [
    {
      name: "Logo Mascot",
      symbol: "♛",
      artwork: "LOGO MASCOT",
      description: "Logo mascot adalah sebuah gambar yang dilengkapi anatomi manusia dengan berbagai macam pose yang bisa di request, dan juga pakaian.",
      price: "HARGA 40K",
      phone: "6285117516599"
    },
    {
      name: "Logo Chibi FF",
      symbol: "♟",
      artwork: "LOGO CHIBI",
      description: "Logo chibi ff adalah sebuah karakter yang memiliki badan mini bisa req karakter dari game, atau dari anime.",
      price: "HARGA 10K–20K SESUAI KESULITAN",
      phone: "6285117694372"
    },
    {
      name: "Logo Nama",
      symbol: "♛",
      artwork: "LOGO NAMA",
      description: "Logo nama adalah sebuah gambar seperti monogram atau sebuah teks yang di ubah menjadi terlihat lebih keren mengikuti nama jb/nama yang di req.",
      price: "HARGA 10K–20K SESUAI KESULITAN",
      phone: "6285117694372"
    },
    {
      name: "Poster",
      symbol: "▣",
      artwork: "POSTER",
      description: "Poster adalah sebuah gambar yang memiliki sebuah teks yang bisa membuat orang yang melihatnya bisa lebih memahami apa yang anda sedang produksikan, dan apa yang sedang anda promosikan. Poster yang disediakan ada dua, poster jb seperti testi dan lain-lain, ada juga poster non jb seperti poster jual makanan, poster sekolah, dan lain-lain.",
      price: "HARGA 7K",
      phone: "6285117694372"
    }
  ];

  let selectedProduct = null;
  let buyer = { name: "", phone: "" };

  const form = document.getElementById("buyerForm");

  form.addEventListener("submit", function(event) {
    event.preventDefault();

    const name = document.getElementById("buyerName").value.trim();
    const phone = document.getElementById("buyerPhone").value.trim();

    if (!name) {
      alert("Masukkan nama kamu.");
      return;
    }

    // Hanya menerima angka, spasi, +, tanda kurung, dan strip.
    if (!/^[0-9+\s()-]{8,20}$/.test(phone)) {
      alert("Masukkan nomor WhatsApp yang valid.");
      return;
    }

    const digits = phone.replace(/\D/g, "");
    if (digits.length < 9 || digits.length > 15) {
      alert("Periksa kembali nomor WhatsApp kamu.");
      return;
    }

    buyer = { name: name, phone: digits };
    document.getElementById("formStatus").textContent =
      "Format pembeli tersimpan. Pilih produk untuk melanjutkan.";
    alert("Format berhasil disimpan. Silakan pilih produk.");
  });

  function openDetail(index) {
    if (!buyer.name || !buyer.phone) {
      alert("Isi nama dan nomor WhatsApp terlebih dahulu!");
      document.getElementById("buyerName").focus();
      return;
    }

    selectedProduct = products[index];

    document.getElementById("home").classList.add("hidden");
    document.getElementById("detail").classList.remove("hidden");

    document.getElementById("detailTitle").textContent = selectedProduct.name;
    document.getElementById("detailSymbol").textContent = selectedProduct.symbol;
    document.getElementById("detailArtTitle").textContent = selectedProduct.artwork;
    document.getElementById("detailDesc").textContent = selectedProduct.description;
    document.getElementById("detailPrice").textContent = selectedProduct.price;

    window.scrollTo(0, 0);
  }

  function goHome() {
    document.getElementById("detail").classList.add("hidden");
    document.getElementById("home").classList.remove("hidden");
    window.scrollTo(0, 0);
  }

  function orderHub() {
    if (!selectedProduct || !buyer.name || !buyer.phone) {
      alert("Lengkapi format pembeli dan pilih produk terlebih dahulu.");
      return;
    }

    const message =
      "HALO ADMIN DEVAN DESIGN, SAYA INGIN ORDER.\n\n" +
      "SESEORANG YANG BERNAMA: " + buyer.name + "\n" +
      "NOMOR WHATSAPP PEMBELI: " + buyer.phone + "\n" +
      "DIA MENGORDER PRODUK: " + selectedProduct.name + "\n" +
      "HARGA: " + selectedProduct.price + "\n\n" +
      "Mohon info proses pemesanan selanjutnya. Terima kasih.";

    const url = "https://wa.me/" + selectedProduct.phone +
      "?text=" + encodeURIComponent(message);

    window.location.href = url;
  }
</script>
</body>
</html>
