# Decrement-increment
<body style="text-align:center;font-family:sans-serif;padding-top:100px">
<h1 id="c">0</h1>
<button>Decrement</button><button>Reset</button><button>Increment</button>
<script>
let n=0,c=document.getElementById('c'),b=document.querySelectorAll('button');
b[0].onclick=()=>c.innerText=--n; b[1].onclick=()=>c.innerText=n=0; b[2].onclick=()=>c.innerText=++n;
</script>
</body>
