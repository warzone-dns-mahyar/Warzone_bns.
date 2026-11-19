# Warzone_bns.
WARZONE DNS Website
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WARZONE DNS</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 15px;
    font-family: Tahoma, Arial, sans-serif;
    background:
        linear-gradient(rgba(4,10,22,.80), rgba(4,10,22,.90)),
        url("https://cdn.cloudflare.steamstatic.com/steam/apps/1962663/header.jpg");
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-color: #071321;
    color: white;
}

header {
    text-align: center;
    padding: 30px 10px;
}

h1 {
    color: #35cfff;
    font-size: 38px;
    text-shadow: 0 0 15px #13b9e8;
}

.subtitle {
    color: #d2eaff;
}

.creator {
    color: #35cfff;
    font-size: 13px;
}

.card {
    background: rgba(10,25,45,.92);
    border: 1px solid #41617f;
    border-radius: 15px;
    padding: 20px;
    margin: 20px auto;
    max-width: 950px;
    box-shadow: 0 5px 25px #0008;
    backdrop-filter: blur(8px);
}

h2 {
    color: #35cfff;
    text-align: center;
}

/* بخش خیریه */
.charity {
    background: linear-gradient(135deg, #10243e, #183d63);
    border: 2px solid #35cfff;
    border-radius: 18px;
    padding: 20px;
    margin: 20px auto;
    max-width: 950px;
    text-align: center;
    box-shadow: 0 0 20px #13b9e833;
    backdrop-filter: blur(8px);
}

.charity h2 {
    color: #ffd166;
    font-size: 25px;
}

.charity img {
    width: 100%;
    max-height: 300px;
    object-fit: cover;
    border-radius: 14px;
    margin: 12px 0;
}

.charity p {
    color: white;
    line-height: 2.2;
    font-size: 15px;
}

.charity .love {
    color: #ff9eb1;
    font-weight: bold;
}

.charity button {
    background: #ffcc55;
    color: #17243a;
    border: none;
    border-radius: 12px;
    padding: 13px 25px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
}

.charity button:hover {
    background: #ffe08a;
}

.charity .notice {
    color: #ffd166;
    font-size: 12px;
    line-height: 1.9;
}

.games {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(150px,1fr));
    gap: 15px;
}

.game {
    background: #192b46;
    border-radius: 12px;
    overflow: hidden;
    text-align: center;
    transition: .3s;
}

.game:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 15px #13b9e8;
}

.game img {
    width: 100%;
    height: 100px;
    object-fit: cover;
}

.game strong {
    display: block;
    padding: 13px 5px;
    font-size: 13px;
}

.platforms {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 10px;
    margin-top: 15px;
}

.platform {
    background: linear-gradient(135deg,#182b49,#253e60);
    border-radius: 12px;
    padding: 25px 5px;
    text-align: center;
    font-size: clamp(12px,3vw,19px);
    font-weight: bold;
    animation: float 5s ease-in-out infinite;
}

@keyframes float {
    0%,100% {transform:translateY(0);}
    50% {transform:translateY(-6px);}
}

input {
    width: 100%;
    padding: 13px;
    margin: 7px 0;
    border: 1px solid #41617f;
    border-radius: 9px;
    font-size: 15px;
    background: #192b46;
    color: white;
    outline: none;
}

input:focus {
    border-color: #35cfff;
    box-shadow: 0 0 8px #13b9e855;
}

input::placeholder {
    color: #aabbd0;
}

button {
    background: #13b9e8;
    color: #071321;
    border: 0;
    border-radius: 8px;
    padding: 11px 16px;
    font-weight: bold;
    margin: 5px 3px;
    cursor: pointer;
    transition: .2s;
}

button:hover {
    background: #55d6ff;
    transform: translateY(-2px);
}

.delete {
    background: #e74c5b;
    color: white;
}

.delete:hover {
    background: #ff6978;
}

.dns {
    background: #253b55;
    padding: 12px;
    border-radius: 9px;
    margin-top: 10px;
    overflow-wrap: anywhere;
    border: 1px solid #41617f;
}

.dns p {
    direction: ltr;
    text-align: left;
}

.small {
    color: #b9c9dc;
    font-size: 13px;
    line-height: 1.8;
}

.empty {
    text-align: center;
    color: #b9c9dc;
    padding: 20px;
}

footer {
    text-align: center;
    color: #829bb5;
    padding: 25px 5px;
    font-size: 12px;
}

@media(max-width:400px) {
    .platforms {
        grid-template-columns: 1fr;
    }

    body {
        padding: 10px;
    }

    .charity {
        padding: 13px;
    }

    .charity h2 {
        font-size: 21px;
    }

    .charity p {
        font-size: 14px;
    }
}
</style>
</head>

<body>

<header>
    <h1>WARZONE DNS</h1>
    <p class="subtitle">مرکز نمایش DNS بازی‌ها</p>
    <p class="creator">سازنده و مدیر سایت: مهیار دوست محمدی</p>
</header>

<!-- بخش خیریه -->
<section class="charity">
    <h2>💝 خیریه | کمک به انسان‌ها و حیوانات</h2>

    <img src="charity-dog.jpg" alt="سگ کوچولو در برف">

    <p>
        سلام به گیمرای گلم ❤️<br>
        ما تصمیم گرفتیم برای آدم های توی خیابان یا حیوانات توی خیابان کمک کنیم.<br>
        اگر دوس داشتین هر مبلغی دوس داشتین بزنید تا شما هم در کار خیر شریک با شید 🫠💝
    </p>

    <p class="love">
      شماره کارت 6219861458178307بنام مهیار دوست محمدی   با مهربونی می‌تونیم دنیا رو قشنگ‌تر کنیم ❤️
    </p>

    <p>🐶 کمک به حیوانات | ❤️ کمک به انسان‌ها</p>

    <button onclick="donationMessage()">
        💝 مشارکت در کار خیر
    </button>

    <p class="notice">
        این دکمه پرداخت واقعی انجام نمی‌دهد. برای کمک مالی،
        از درگاه رسمی یک خیریه معتبر و با نظارت یک بزرگسال استفاده کنید.
    </p>
</section>

<section class="card">
    <h2>🎮 بازی‌های معروف</h2>

    <div class="games">

        <div class="game">
            <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/1962663/header.jpg" alt="Warzone">
            <strong>CALL OF DUTY WARZONE</strong>
        </div>

        <div class="game">
            <img src="https://placehold.co/600x350/192b46/55d6ff?text=FORTNITE" alt="Fortnite">
            <strong>FORTNITE</strong>
        </div>

        <div class="game">
            <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/730/header.jpg" alt="CS2">
            <strong>COUNTER STRIKE 2</strong>
        </div>

        <div class="game">
            <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/578080/header.jpg" alt="PUBG">
            <strong>PUBG</strong>
        </div>

        <div class="game">
            <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/2357570/header.jpg" alt="Overwatch">
            <strong>OVERWATCH 2</strong>
        </div>

        <div class="game">
            <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/252490/header.jpg" alt="Rust">
            <strong>RUST</strong>
        </div>

        <div class="game">
            <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/570/header.jpg" alt="Dota 2">
            <strong>DOTA 2</strong>
        </div>

        <div class="game">
            <img src="https://cdn.cloudflare.steamstatic.com/steam/apps/271590/header.jpg" alt="GTA V">
            <strong>GTA V</strong>
        </div>

    </div>
</section>

<section class="card">
    <h2>🕹️ پلتفرم‌های بازی</h2>

    <div class="platforms">
        <div class="platform">STEAM</div>
        <div class="platform">PLAYSTATION</div>
        <div class="platform">XBOX</div>
    </div>
</section>

<section class="card">
    <h2>🌐 بازی‌ها و DNSها</h2>

    <input id="search" type="search"
           placeholder="جستجوی نام بازی...">

    <div id="gamesList"></div>
</section>

<section class="card">
    <h2>🔐 مدیریت DNS</h2>

    <p class="small">
        DNSهای اضافه‌شده در همین مرورگر ذخیره می‌شوند.
    </p>

    <form id="dnsForm">

        <input id="game" type="text"
               placeholder="نام بازی" maxlength="60" required>

        <input id="dns1" type="text"
               placeholder="DNS اصلی" maxlength="100">

        <input id="dns2" type="text"
               placeholder="DNS جایگزین" maxlength="100">

        <button type="submit">➕ افزودن DNS</button>

    </form>

    <p class="small" id="message" aria-live="polite"></p>
</section>

<footer>
    WARZONE DNS | تمام حقوق محفوظ است
</footer>

<script>
"use strict";

const STORAGE_KEY = "warzoneDNS";

const area = document.getElementById("gamesList");
const form = document.getElementById("dnsForm");
const search = document.getElementById("search");
const message = document.getElementById("message");

let records = [];

function createId() {
    return crypto.randomUUID
        ? crypto.randomUUID()
        : Date.now() + "-" + Math.random().toString(36).slice(2);
}

function loadRecords() {
    try {
        const saved = localStorage.getItem(STORAGE_KEY);
        const data = JSON.parse(saved || "[]");

        if (!Array.isArray(data)) return [];

        return data
            .filter(r =>
                r &&
                typeof r.game === "string" &&
                typeof r.dns1 === "string" &&
                typeof r.dns2 === "string"
            )
            .map(r => ({
                id: r.id || createId(),
                game: r.game,
                dns1: r.dns1,
                dns2: r.dns2
            }));

    } catch (error) {
        console.error(error);
        return [];
    }
}

function saveRecords() {
    try {
        localStorage.setItem(
            STORAGE_KEY,
            JSON.stringify(records)
        );

        render();

    } catch (error) {
        showMessage("ذخیره اطلاعات انجام نشد!");
    }
}

function showMessage(text) {
    message.textContent = text;
}

function createDNSBox(record) {
    const box = document.createElement("div");
    box.className = "dns";

    const title = document.createElement("h3");
    title.textContent = record.game;
    box.appendChild(title);

    const dnsValues = [
        ["DNS اصلی", record.dns1],
        ["DNS جایگزین", record.dns2]
    ];

    dnsValues.forEach(([label, value]) => {
        if (!value) return;

        const p = document.createElement("p");

        const text = document.createElement("span");
        text.textContent = label + ": " + value;

        const copy = document.createElement("button");
        copy.textContent = "کپی";
        copy.onclick = () => copyDNS(value);

        p.appendChild(text);
        p.appendChild(copy);
        box.appendChild(p);
    });

    const del = document.createElement("button");
    del.className = "delete";
    del.textContent = "حذف";
    del.onclick = () => deleteDNS(record.id);

    box.appendChild(del);

    return box;
}

function render() {
    area.replaceChildren();

    const keyword = search.value.trim().toLowerCase();

    const filtered = records.filter(r =>
        r.game.toLowerCase().includes(keyword)
    );

    if (filtered.length === 0) {
        const empty = document.createElement("div");
        empty.className = "empty";
        empty.textContent = keyword
            ? "بازی موردنظر پیدا نشد."
            : "هنوز DNS اضافه نشده است.";

        area.appendChild(empty);
        return;
    }

    filtered.forEach(record => {
        area.appendChild(createDNSBox(record));
    });
}

form.addEventListener("submit", function(event) {
    event.preventDefault();

    const game = document.getElementById("game").value.trim();
    const dns1 = document.getElementById("dns1").value.trim();
    const dns2 = document.getElementById("dns2").value.trim();

    if (!game || (!dns1 && !dns2)) {
        showMessage("نام بازی و حداقل یک DNS وارد کن.");
        return;
    }

    records.push({
        id: createId(),
        game,
        dns1,
        dns2
    });

    saveRecords();
    form.reset();

    showMessage("DNS با موفقیت اضافه شد.");
});

function deleteDNS(id) {
    if (!confirm("آیا از حذف این DNS مطمئن هستی؟")) {
        return;
    }

    records = records.filter(r => r.id !== id);

    saveRecords();
    showMessage("DNS حذف شد.");
}

async function copyDNS(value) {
    try {
        if (navigator.clipboard && window.isSecureContext) {
            await navigator.clipboard.writeText(value);
        } else {
            const textarea = document.createElement("textarea");
            textarea.value = value;
            textarea.style.position = "fixed";
            textarea.style.opacity = "0";

            document.body.appendChild(textarea);
            textarea.select();

            const success = document.execCommand("copy");
            textarea.remove();

            if (!success) throw new Error("Copy failed");
        }

        showMessage("DNS با موفقیت کپی شد.");

    } catch (error) {
        showMessage("کپی خودکار انجام نشد؛ DNS را دستی کپی کن.");
    }
}

/* پیام دکمه خیریه */
function donationMessage() {
    alert(
        "ممنون از مهربونی شما ❤️\n" +
        "این دکمه فعلاً پرداخت واقعی انجام نمی‌دهد.\n" +
        "برای کمک مالی، از درگاه رسمی یک خیریه معتبر و با نظارت یک بزرگسال اقدام کنید."
    );
}

search.addEventListener("input", render);

records = loadRecords();
render();

</script>

</body>
</html>
