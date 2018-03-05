## <center>女生节快乐！</center>



<html>
<head>
<center>
<title>这是一个表白</title>
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
var butong_net = new Array('我是你的蛙儿子，照片每天寄给妈','女神节快乐','今年横幅特别小，钱都拿去买礼物了','关注材51公众号“材吾伊”，你会更漂亮！','我是个野路子，偏偏被你制服','51女神我爱你，爱你爱你最爱你','这是一个表白，我……'); 
var butong_net2 = Math.floor(Math.random() * butong_net.length); 
var text = document.getElementById("text");
text.firstChild.nodeValue = butong_net[butong_net2];
}
window.onload = content;
</script>
</center>
</head>
<body>
<p id="text">这是一个表白</p>
</body>
</html>
