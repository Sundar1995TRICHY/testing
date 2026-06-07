<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>General English - Semester I</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700&family=Poppins:wght@300;400;600&display=swap');

*{margin:0;padding:0;box-sizing:border-box}
body{
    font-family:Poppins,sans-serif;
    background:linear-gradient(135deg,#090909,#141e30,#243b55);
    color:#f5f5f5;
    overflow-x:hidden;
}
.hero{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:40px;
    background:radial-gradient(circle at center,rgba(255,215,0,.15),transparent 60%);
}
.hero h1{
    font-family:Cinzel,serif;
    font-size:4rem;
    text-shadow:0 0 20px gold;
}
.hero p{max-width:800px;margin-top:20px;font-size:1.1rem}
.glow{
    animation:pulse 3s infinite;
}
@keyframes pulse{
    0%,100%{text-shadow:0 0 10px gold}
    50%{text-shadow:0 0 30px gold,0 0 60px orange}
}
.section{
    width:min(1100px,92%);
    margin:40px auto;
    padding:30px;
    background:rgba(255,255,255,.08);
    backdrop-filter:blur(12px);
    border-radius:20px;
    box-shadow:0 0 30px rgba(255,215,0,.15);
}
h2{
    color:#ffd700;
    margin-bottom:15px;
}
.card{
    margin:15px 0;
    padding:15px;
    border-left:4px solid gold;
    background:rgba(255,255,255,.05);
    border-radius:10px;
}
ul{padding-left:20px}
footer{
    text-align:center;
    padding:30px;
    color:#ccc;
}
.star{
    position:fixed;
    width:2px;height:2px;
    background:white;
    border-radius:50%;
    animation:twinkle 4s infinite;
}
@keyframes twinkle{
    50%{opacity:.2}
}
</style>
</head>
<body>

<div class="hero">
    <h1 class="glow">GENERAL ENGLISH</h1>
    <h2>First Year • Semester I</h2>
    <p>A cinematic and aesthetically designed syllabus page highlighting learning outcomes, literary texts, grammar, and language skills.</p>
</div>

<section class="section">
<h2>Programme Specific Outcomes</h2>
<ul>
<li>Identify and use English grammar structures effectively.</li>
<li>Develop vocabulary for writing and communication.</li>
<li>Practice spoken and written expression of ideas.</li>
<li>Engage in real-life communication and composition.</li>
</ul>
</section>

<section class="section">
<h2>Learning Objectives</h2>
<div class="card">Self-awareness and positive thinking.</div>
<div class="card">Empathy and social understanding.</div>
<div class="card">Creative and critical thinking.</div>
<div class="card">Basic grammar proficiency.</div>
<div class="card">Development of LSRW skills.</div>
</section>

<section class="section">
<h2>Unit I – Self Awareness & Positive Thinking</h2>
<ul>
<li>Chapter 1 – I Am Malala</li>
<li>Autobiography of M.K. Gandhi (Ch.1–3)</li>
<li>Where the Mind is Without Fear – Rabindranath Tagore</li>
<li>Love Cycle – Chinua Achebe</li>
</ul>
</section>

<section class="section">
<h2>Unit II – Empathy</h2>
<ul>
<li>Nine Gold Medals – David Roth</li>
<li>Alice Fell or Poverty – William Wordsworth</li>
<li>The School for Sympathy – E.V. Lucas</li>
<li>Barn Burning – William Faulkner</li>
</ul>
</section>

<section class="section">
<h2>Unit III – Critical & Creative Thinking</h2>
<ul>
<li>The Things That Haven't Been Done Before – Edgar Guest</li>
<li>Stopping by Woods on a Snowy Evening – Robert Frost</li>
<li>The Magic Brocade – A Tale of China</li>
<li>Three Sideways Stories from Wayside School – Louis Sachar</li>
</ul>
</section>

<section class="section">
<h2>Unit IV – Parts of Speech</h2>
<p>Articles, Nouns, Pronouns, Verbs, Adverbs, Adjectives and Prepositions.</p>
</section>

<section class="section">
<h2>Unit V – Writing Skills</h2>
<p>Descriptive, Expository, Persuasive and Narrative Writing along with Reading Comprehension.</p>
</section>

<section class="section">
<h2>Course Outcomes</h2>
<ul>
<li>Develop self-awareness and positive thinking.</li>
<li>Demonstrate empathy.</li>
<li>Apply creative and critical thinking.</li>
<li>Use grammar effectively.</li>
<li>Integrate Listening, Speaking, Reading and Writing skills.</li>
</ul>
</section>

<footer>
Designed with cinematic aesthetics ✨
</footer>

<script>
for(let i=0;i<120;i++){
 let s=document.createElement('div');
 s.className='star';
 s.style.left=Math.random()*100+'vw';
 s.style.top=Math.random()*100+'vh';
 s.style.animationDuration=(2+Math.random()*5)+'s';
 document.body.appendChild(s);
}
</script>

</body>
</html>
