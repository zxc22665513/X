<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>曜妍能量 X 運動輕食｜今日守護水晶測驗</title>

<!-- LINE LIFF SDK -->
<script src="https://static.line-scdn.net/liff/edge/2/sdk.js"></script>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:"Noto Sans TC",sans-serif;
}

body{
    min-height:100vh;
    background:
    linear-gradient(135deg,#f8d7ff,#ffdfe7,#fff3e8);
    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px;
}

.container{
    width:100%;
    max-width:420px;
}

.card{
    background:rgba(255,255,255,0.25);
    backdrop-filter:blur(16px);
    -webkit-backdrop-filter:blur(16px);

    border:1px solid rgba(255,255,255,0.4);

    border-radius:28px;
    padding:28px;
    box-shadow:
    0 8px 32px rgba(0,0,0,.12);
}

.logo{
    text-align:center;
    margin-bottom:12px;
}

.logo h1{
    font-size:24px;
    color:#6b3f7d;
}

.logo p{
    color:#666;
    margin-top:8px;
}

.page{
    display:none;
}

.page.active{
    display:block;
}

.welcome-title{
    text-align:center;
    font-size:30px;
    color:#5a3472;
    margin-bottom:16px;
}

.nickname{
    text-align:center;
    color:#7b4f8f;
    font-weight:bold;
    margin-bottom:20px;
}

.desc{
    text-align:center;
    line-height:1.7;
    color:#555;
    margin-bottom:25px;
}

.btn{
    width:100%;
    border:none;
    border-radius:999px;
    padding:16px;
    font-size:16px;
    font-weight:bold;
    cursor:pointer;

    background:linear-gradient(
    135deg,
    #d88cff,
    #ff9bb6
    );

    color:white;

    box-shadow:
    0 8px 18px rgba(216,140,255,.35);

    transition:.25s;
}

.btn:active{
    transform:scale(.96);
}

.progress{
    width:100%;
    height:10px;
    background:rgba(255,255,255,.4);
    border-radius:999px;
    overflow:hidden;
    margin-bottom:24px;
}

.progress-bar{
    height:100%;
    width:0%;
    background:linear-gradient(
    90deg,
    #d88cff,
    #ffb4c8
    );
    transition:.4s;
}

.question-title{
    font-size:22px;
    color:#5b3d72;
    margin-bottom:20px;
    line-height:1.5;
}

.option{
    width:100%;
    margin-bottom:12px;
    padding:15px;

    border-radius:18px;

    background:white;
    border:none;
    cursor:pointer;

    font-size:15px;

    box-shadow:
    0 5px 12px rgba(0,0,0,.08);

    transition:.25s;
}

.option:hover{
    transform:translateY(-2px);
}

.result-title{
    text-align:center;
    color:#5a3472;
    margin-bottom:15px;
}

.result-content{
    background:white;
    border-radius:18px;
    padding:18px;
    margin-bottom:18px;
    line-height:1.8;
}

.recommend{
    background:rgba(255,255,255,.7);
    border-radius:18px;
    padding:18px;
    margin-bottom:20px;
}

.recommend h3{
    color:#5a3472;
    margin-bottom:10px;
}

.recommend ul{
    padding-left:20px;
    line-height:1.8;
}

.shop-btn{
    display:block;
    text-decoration:none;
    text-align:center;
}

.small{
    text-align:center;
    margin-top:15px;
    color:#666;
    font-size:13px;
}

@media(max-width:480px){

    .card{
        padding:22px;
    }

    .welcome-title{
        font-size:26px;
    }

    .question-title{
        font-size:20px;
    }

}
</style>
</head>

<body>

<div class="container">

    <!-- 歡迎頁 -->
    <div class="card page active" id="welcomePage">

        <div class="logo">
            <h1>曜妍能量 X 運動輕食</h1>
        </div>

        <div class="nickname" id="userName">
            嗨！能量探索者 👋
        </div>

        <h2 class="welcome-title">
            測測你的今日守護水晶
        </h2>

        <p class="desc">
            只需 30 秒，找出你目前最需要的能量支持，
            並獲得專屬水晶與課程推薦。
        </p>

        <button class="btn" onclick="startQuiz()">
            開始測驗
        </button>

    </div>

    <!-- 測驗頁 -->
    <div class="card page" id="quizPage">

        <div class="progress">
            <div class="progress-bar" id="progressBar"></div>
        </div>

        <h2 class="question-title" id="questionText"></h2>

        <div id="optionsContainer"></div>

    </div>

    <!-- 結果頁 -->
    <div class="card page" id="resultPage">

        <h2 class="result-title">
            你的專屬能量結果
        </h2>

        <div class="nickname" id="resultNickname"></div>

        <div class="result-content">
            <h3 id="resultName"></h3>
            <p id="resultDescription"></p>
        </div>

        <div class="recommend">
            <h3>🎁 專屬推薦</h3>

            <ul id="recommendList"></ul>
        </div>

        <a
            href="https://yourshop.com"
            target="_blank"
            class="btn shop-btn"
        >
            領取限定優惠並前往商城
        </a>

        <div class="small">
            曜妍能量 X 運動輕食
        </div>

    </div>

</div>

<script>

/* ===========================
   LINE LIFF 初始化
   =========================== */

/*
   修改方式：

   將 YOUR_LIFF_ID
   改成你在 LINE Developers
   建立好的 LIFF ID

   範例：
   liff.init({
      liffId:"2001234567-ABCDEFG"
   })
*/

let displayName = "能量探索者";

async function initializeLiff(){

    try{

        await liff.init({
            liffId:"YOUR_LIFF_ID"
        });

        if(liff.isLoggedIn()){

            const profile = await liff.getProfile();

            displayName = profile.displayName;

            document.getElementById("userName").innerHTML =
            `嗨！${displayName} 👋`;

        }

    }catch(error){

        console.log("LIFF初始化失敗",error);

    }

}

initializeLiff();


/* ===========================
   題目資料
   =========================== */

const questions = [

{
question:"Q1：每天早上起床，你通常是什麼心情？",
options:[
{ text:"A. 期待新的一天", value:"career"},
{ text:"B. 好累不想動", value:"healing"},
{ text:"C. 焦慮今天的工作", value:"protect"}
]
},

{
question:"Q2：面對突如其來的挑戰，你直覺會怎麼做？",
options:[
{ text:"A. 正面迎擊", value:"career"},
{ text:"B. 想躲起來", value:"healing"},
{ text:"C. 心跳加速不知所措", value:"protect"}
]
},

{
question:"Q3：現在的你，最渴望得到哪種力量？",
options:[
{ text:"A. 財富與事業", value:"career"},
{ text:"B. 內心的平靜", value:"healing"},
{ text:"C. 滿滿的活力", value:"protect"}
]
}

];


/* ===========================
   結果資料
   =========================== */

const resultMap = {

healing:{
title:"💗 你需要粉晶與紫水晶的療癒",
description:
"近期的你可能承受較多壓力與情緒消耗，需要被理解、被照顧與恢復安全感。粉晶有助於愛與關係能量，紫水晶則能協助穩定思緒與放鬆身心。",
recommend:[
"粉晶 × 紫水晶能量手鍊",
"越式頭療舒壓課程",
"七脈輪能量檢測"
]
},

career:{
title:"💰 你需要黃水晶與鈦晶的助攻",
description:
"你對未來有企圖心，也渴望突破現況。黃水晶象徵財富與自信，鈦晶則能提升行動力與目標感，幫助你朝夢想前進。",
recommend:[
"黃水晶財富手鍊",
"鈦晶事業能量手鍊",
"越式頭療能量重啟課程"
]
},

protect:{
title:"🛡️ 你需要綠幽靈與黑曜石的守護",
description:
"最近容易受到外界影響，需要補充正能量並遠離負面干擾。綠幽靈有助於成長與恢復活力，黑曜石則能提升保護與穩定感。",
recommend:[
"綠幽靈守護手鍊",
"黑曜石能量手鍊",
"越式頭療深層放鬆課程"
]
}

};


/* ===========================
   測驗邏輯
   =========================== */

let currentQuestion = 0;

let scores = {
healing:0,
career:0,
protect:0
};

function startQuiz(){

    switchPage("quizPage");

    showQuestion();

}

function showQuestion(){

    const q = questions[currentQuestion];

    document.getElementById("questionText").innerText =
    q.question;

    const container =
    document.getElementById("optionsContainer");

    container.innerHTML = "";

    q.options.forEach(option=>{

        const btn =
        document.createElement("button");

        btn.className = "option";

        btn.innerText = option.text;

        btn.onclick = ()=>{

            scores[option.value]++;

            currentQuestion++;

            if(currentQuestion < questions.length){

                showQuestion();

            }else{

                showResult();

            }

        };

        container.appendChild(btn);

    });

    const percent =
    ((currentQuestion + 1) / questions.length) * 100;

    document.getElementById("progressBar").style.width =
    percent + "%";

}

function showResult(){

    switchPage("resultPage");

    let resultType =
    Object.keys(scores).reduce((a,b)=>
    scores[a] > scores[b] ? a : b
    );

    const result =
    resultMap[resultType];

    document.getElementById("resultNickname").innerHTML =
    `嗨！${displayName}，你專屬的能量結果是：`;

    document.getElementById("resultName").innerText =
    result.title;

    document.getElementById("resultDescription").innerText =
    result.description;

    const list =
    document.getElementById("recommendList");

    list.innerHTML = "";

    result.recommend.forEach(item=>{

        const li =
        document.createElement("li");

        li.innerText = item;

        list.appendChild(li);

    });

}

function switchPage(pageId){

    document.querySelectorAll(".page")
    .forEach(page=>{

        page.classList.remove("active");

    });

    document.getElementById(pageId)
    .classList.add("active");

}

</script>

</body>
</html>
