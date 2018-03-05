## 女生节快乐！

<html>
<head>
<style>
#text {
border: 1px solid #FA9150;
width: 300px;
background: #FEF1E9;
color: #000000;
line-height: 50px;
text-align: center;
font-size: 14px;
font-weight: bold;
}
</style>
<script>
function content() {
var butong_net = new Array('大家好，我是马鹿野郎','国庆节快乐','不停的好奇，不停的学习','公众号野鹿志','我是个野路子','我喜欢大幂幂','这是一个测试'); 
var butong_net2 = Math.floor(Math.random() * butong_net.length); 
var text = document.getElementById("text");
text.firstChild.nodeValue = butong_net[butong_net2];
}
window.onload = content;
</script>
</head>
<body>
</body>
</html>
