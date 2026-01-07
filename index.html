<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CrazyModz - Unlock</title>

<style>
*{
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    margin:0;
    min-height:100vh;
    background:radial-gradient(circle at top, #0b2a33, #05070b);
    display:flex;
    justify-content:center;
    align-items:center;
    color:#fff;
}

.container{
    width:100%;
    max-width:380px;
    padding:20px;
    text-align:center;
}

.logo{
    width:70px;
    height:70px;
    margin:auto;
    border-radius:18px;
    background:linear-gradient(135deg,#00e5ff,#ff2db2);
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:32px;
}

.title{
    margin-top:15px;
    font-size:35px;
    font-weight:bold;
    background:linear-gradient(90deg,#00e5ff,#ff2db2);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

.card{
    position: relative;
    margin-top:30px;
    background:rgba(20,20,20,0.88);
    border-radius:20px;
    padding:25px 18px;
    z-index:1;
}

/* BORDE NEÓN ANIMADO */
.card::before{
    content:"";
    position:absolute;
    inset:-2px;
    border-radius:22px;
    background:linear-gradient(
        270deg,
        #7f00ff,
        #00e5ff,
        #ff2db2,
        #7f00ff
    );
    background-size:600% 600%;
    animation:neonBorder 6s ease infinite;
    z-index:-1;
    filter:blur(6px);
    opacity:0.9;
}

.card::after{
    content:"";
    position:absolute;
    inset:-1.5px;
    border-radius:22px;
    background:linear-gradient(
        270deg,
        #7f00ff,
        #00e5ff,
        #ff2db2,
        #7f00ff
    );
    background-size:600% 600%;
    animation:neonBorder 6s linear infinite;
    z-index:-1;
}

/* ANIMACIÓN */
@keyframes neonBorder{
    0%{ background-position:0% 50%; }
    50%{ background-position:100% 50%; }
    100%{ background-position:0% 50%; }
}

.task{
    background:#2a2a2a;
    border-radius:12px;
    padding:14px;
    margin-bottom:12px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    cursor:pointer;
}

.task.done{
    background:#1f3d32;
}

.check{
    color:#2dff88;
    font-size:18px;
    display:none;
}

.task.done .check{
    display:block;
}

.progress-text{
    font-size:13px;
    margin:10px 0 6px;
    color:#9aa4b2;
}

.progress-bar{
    width:100%;
    height:6px;
    background:#1f2937;
    border-radius:10px;
    overflow:hidden;
}

.progress{
    width:0%;
    height:100%;
    background:#2dff88;
    transition:0.3s;
}

.unlock-btn{
    margin-top:20px;
    width:100%;
    padding:15px;
    border:none;
    border-radius:16px;
    background:#0f3d34;
    color:#2dff88;
    font-size:16px;
    font-weight:bold;
    display:none;
    cursor:pointer;
}
</style>
</head>

<body>

<div class="container">

    <div class="logo">🚀</div>
    <div class="title">Starlux Mods</div>

    <div class="card">

        <h2>Area de descarga</h2>
        <p>Complete the actions and unlock the link</p>

        <div class="task" onclick="startTask(1)">
            <span>▶️ Subscribe on YouTube</span>
            <span class="check">✔</span>
        </div>

        <div class="task" onclick="startTask(2)">
            <span>👍 Like on Video</span>
            <span class="check">✔</span>
        </div>

        <div class="progress-text" id="progressText">unlock progress 0/2</div>
        <div class="progress-bar">
            <div class="progress" id="progressBar"></div>
        </div>

        <button class="unlock-btn" id="unlockBtn" onclick="goLink()">
            🔓 Ir al enlace
        </button>

    </div>

</div>

<script>
const totalTasks = 2;

// 🔗 LINKS DE CADA BOTÓN
const links = {
    1: "https://youtu.be/JwCkzm4JjMo?si=ADXhHjQGz5dzmpgL",
    2: "https://youtu.be/JwCkzm4JjMo?si=ADXhHjQGz5dzmpgL"
};

// ⏱️ SEGUNDOS QUE DEBE ESPERAR PARA VALIDAR
const waitSeconds = 2;

// 🔥 REINICIO SOLO AL ENTRAR DESDE CERO
if (!sessionStorage.getItem("sessionStarted")) {
    localStorage.removeItem("completedTasks");
    localStorage.removeItem("pendingTask");
    sessionStorage.setItem("sessionStarted", "true");
}

// Estado
let completed = JSON.parse(localStorage.getItem("completedTasks")) || {};
let pendingTask = localStorage.getItem("pendingTask");

// Al cargar
window.onload = () => {
    updateUI();

    // Si vuelve del link
    if (pendingTask) {
        setTimeout(() => {
            completed[pendingTask] = true;
            localStorage.removeItem("pendingTask");
            localStorage.setItem("completedTasks", JSON.stringify(completed));
            updateUI();
        }, waitSeconds * 1000);
    }
};

function startTask(taskId){
    if (completed[taskId]) return;

    // Guardar tarea pendiente
    localStorage.setItem("pendingTask", taskId);

    // Abrir link
    window.location.href = links[taskId];
}

function updateUI(){
    let doneCount = 0;
    const tasks = document.getElementsByClassName("task");

    for (let i = 1; i <= totalTasks; i++) {
        if (completed[i]) {
            tasks[i-1].classList.add("done");
            doneCount++;
        } else {
            tasks[i-1].classList.remove("done");
        }
    }

    let percent = (doneCount / totalTasks) * 100;
    document.getElementById("progressBar").style.width = percent + "%";
    document.getElementById("progressText").innerText =
        "unlock progress " + doneCount + "/" + totalTasks;

    document.getElementById("unlockBtn").style.display =
        doneCount === totalTasks ? "block" : "none";
}

function goLink(){
    window.location.href =
    "https://www.mediafire.com/file/2ogz3wb5rq8yx4e/Painel_pared_invertida_v5.7z/file";
}
</script>

</body>
</html>