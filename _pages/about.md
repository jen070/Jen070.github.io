---
permalink: /
title: "恶人名单"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

网站属于测试阶段

邪恶之人必将遭到审判

<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<title>QQ查询</title>
</head>
<body>

<h2>QQ号查询</h2>

<input type="text" id="searchInput" placeholder="输入QQ号">
<button onclick="searchQQ()">搜索</button>

<p id="result"></p>

<script>
let qqList = ["123456","888888","999999","456789"];

function searchQQ() {
  let input = document.getElementById("searchInput").value;
  let result = document.getElementById("result");

  if (qqList.includes(input)) {
    result.innerText = "⚠️ 存在风险";
  } else {
    result.innerText = "✅ 未发现";
  }
}
</script>

</body>
</html>
