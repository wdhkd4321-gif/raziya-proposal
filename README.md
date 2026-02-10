# raziya-proposal
Proposal 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For Razia ❤️</title>
<style>
    body {
        margin: 0;
        height: 100vh;
        background: linear-gradient(135deg, #ff758c, #ff7eb3);
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: 'Segoe UI', sans-serif;
        color: white;
        text-align: center;
    }

    .box {
        background: rgba(0,0,0,0.3);
        padding: 30px;
        border-radius: 20px;
        box-shadow: 0 0 20px rgba(0,0,0,0.3);
        max-width: 350px;
    }

    h1 {
        font-size: 28px;
        margin-bottom: 10px;
    }

    p {
        font-size: 18px;
        margin-bottom: 25px;
    }

    button {
        padding: 12px 30px;
        font-size: 18px;
        border: none;
        border-radius: 30px;
        cursor: pointer;
        margin: 10px;
    }

    #yes {
        background: #00ff99;
        color: #000;
    }

    #no {
        background: #ff4d4d;
        color: white;
        opacity: 0.5;
        cursor: not-allowed;
    }
</style>
</head>
<body>

<div class="box">
    <h1>Raziya ❤️</h1>
    <p>
        From the moment you came into my life,  
        everything felt complete.  
        <br><br>
        Will you be mine forever?
    </p>

    <button id="yes" onclick="accepted()">YES 💍</button>
    <button id="no" disabled>NO ❌</button>
</div>

<script>
function accepted() {
    document.body.innerHTML = `
        <div style="
            display:flex;
            justify-content:center;
            align-items:center;
            height:100vh;
            background:linear-gradient(135deg,#43e97b,#38f9d7);
            font-family:Segoe UI;
            color:#000;
            text-align:center;
        ">
            <div>
                <h1>She Said YES ❤️</h1>
                <p style="font-size:20px;">
                    My heart is yours forever, Raziya 💖
                </p>
            </div>
        </div>
    `;
}
</script>

</body>
</html>
