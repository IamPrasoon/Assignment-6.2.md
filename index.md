1. index.html


<!DOCTYPE html>
<html>
<head>
    <title>Card Designs</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Our Plans</h1>
    <div class="card basic">
        <h2>Basic</h2>
        <p>Basic features</p>
        <button>Choose</button>
    </div>
    <div class="card standard">
        <h2>Standard</h2>
        <p>More features</p>
        <button>Choose</button>
    </div>
    <div class="card premium">
        <h2>Premium</h2>
        <p>All features</p>
        <button>Choose</button>
    </div>
    <p class="block">Block Element</p>
    <span class="inline">Inline Element</span>
    <span class="inline-block">Inline Block</span>
</body>
</html>

2. style.css


.card {
    display: inline-block;
    width: 200px;
    max-width: 100%;
    height: 180px;
    padding: 15px;
    margin: 10px;
    border-radius: 12px;
    text-align: center;
}
.basic {
    background: lightblue;
    border: 2px solid blue;
}
.standard {
    background: lightgreen;
    border: 2px solid green;
}
.premium {
    background: lightyellow;
    border: 2px solid orange;
}
button {
    padding: 8px 15px;
    border-radius: 6px;
}
.block { display: block; }
.inline { display: inline; }
.inline-block { display: inline-block; }