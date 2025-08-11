<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<title>کارت‌های کار</title>
<style>
  body {
    font-family: sans-serif;
    direction: rtl;
    background-color: #eef2f3;
    padding: 20px
  }
  .box {
    display: flex
    flex-wrap: wrap;
    gap: 15px;
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    max-width: 600px;
    margin: auto;
  }
  .card {
    flex: 1 1 calc(33% - 15px);
    min-width: 120px;
    background-color: #3498db;
    color: white;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
    transition: transform 0.3s ease, background 0.3s ease;
  }
  .card:hover {
    background-color: #2980b9;
    transform: translateY(-5px);
  }
</style>
</head>
<body>

<div class="box">
  <div class="card">کار شماره ۱</div>
  <div class="card">کار شماره ۲</div>
  <div class="card">کار شماره ۳</div>
  <div class="card">کار شماره ۴</div>
  <div class="card">کار شماره ۵</div>
  <div class="card">کار شماره ۶</div>
</div>

</body>
</html>
