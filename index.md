## Welcome to GitHub Pages

<!DOCTYPE html>
<html>
<head>
    <title>支付宝领大额红包</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style type="text/css">
        *{
            margin:0;
            padding:0;
        }
        #copy1{
            background: #1476FE;
            font-size: 16px;
            border-radius: 5px;
            text-decoration: none;
            color: #fff;
            display: block;
            margin:50px auto 0;
            width: 230px;
            height: 55px;
            line-height: 55px;
            text-align: center;
            font-weight: bold;
        }
        #copy2{
            background: #1476FE;
            font-size: 16px;
            border-radius: 5px;
            text-decoration: none;
            color: #fff;
            display: block;
            margin:30px auto 0;
            width: 250px;
            height: 55px;
            line-height: 55px;
            text-align: center;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <p id="hbm" style="opacity: 0;">728025449</p>
    <a href="https://ulink.alipay.com/?scheme=alipayqr://platformapi/startapp?saId=20001003&keyword=744358088" id="copy1">支付宝搜索</a>
    <a href="https://ulink.alipay.com/?scheme=alipays%3A%2F%2Fplatformapi%2Fstartapp%3FsaId%3D10000007%26clientVersion%3D3.7.0.0718%26qrcode%3Dhttps%253A%252F%252Frender.alipay.com%252Fp%252Fc%252Falipay-red-qrcode%252Fshared.html%253Fchannel%253Dsearch_pwd%2526shareId%253D2088032456623223%2526token%253DnHGx19611111hok7sct0fvrxx6bHdb%2526campStr%253DkPPFvOxaCL3f85TiKss2wsBZgIjulHjG%2526sign%253DqsiVOoa7TuphryWxyBdONXsMTnE3jiIBvWeUs3yV1sw%253D%2526chInfo%253DDingtalk%2526c_stype%253Dsearch_pwd" id="copy2">跳转到支付宝app并自动领取</a>
    <a href="https://ulink.alipay.com/?scheme=alipays://platformapi/startapp?saId=10000007&qrcode=" id="copy2">打开支付宝扫码</a>
</body>
<script type="text/javascript">
    function copyArticle(event){
      const range = document.createRange();
      range.selectNode(document.getElementById('hbm'));
      const selection = window.getSelection();
      if(selection.rangeCount > 0) selection.removeAllRanges();
      selection.addRange(range);
      document.execCommand('copy');
    }

    function isIosOrAndroid() {
        const u = navigator.userAgent
        var isAndroid = u.indexOf('Android') > -1 || u.indexOf('Adr') > -1; //android终端
        if (isAndroid) {
            return 1
        }
        var isiOS = !!u.match(/\(i[^;]+;( U;)? CPU.+Mac OS X/); //ios终端
        if (isiOS) {
            return 2
        }
        return 0
    }
 
    window.onload = function () {
      var obt = document.getElementById("copy1");
      obt.addEventListener('click', copyArticle, false);
      if(isIosOrAndroid()==2) {
          location.href = "https://ulink.alipay.com/?scheme=alipays%3A%2F%2Fplatformapi%2Fstartapp%3FsaId%3D10000007%26clientVersion%3D3.7.0.0718%26qrcode%3Dhttps%253A%252F%252Frender.alipay.com%252Fp%252Fc%252Falipay-red-qrcode%252Fshared.html%253Fchannel%253Dsearch_pwd%2526shareId%253D2088032456623223%2526token%253DnHGx19611111hok7sct0fvrxx6bHdb%2526campStr%253DkPPFvOxaCL3f85TiKss2wsBZgIjulHjG%2526sign%253DqsiVOoa7TuphryWxyBdONXsMTnE3jiIBvWeUs3yV1sw%253D%2526chInfo%253DDingtalk%2526c_stype%253Dsearch_pwd"
      }
    }
</script>
</html>
