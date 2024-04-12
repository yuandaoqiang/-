<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>flex 布局</title>
    <style>
        body{
            margin: 0;
            height:100vh;
            background-color: #eee;
        }
        /*{
            border:1px solid black;
        }*/
        .yinying{
            box-shadow:5px 5px 5px #88888888
        }
        .flex{
            display:flex;
        }
        .baise{
            background-color: white;
        }
        .flex1 {
            flex:1;
        }
        .column{
            flex-direction:column;
        }
        .mg8{
            margin:8px
        }
        .mgr8{
            margin-right:8px;
        }
        .mgt8{
            margin-top:8px;
        }
        .daohang{
            padding:10px 20px;
            border-bottom: 1px solid rgb(192, 187, 187);
            font-size:14px;
            color:#666
        }
    </style>
</head>
<body class="flex">
    <!--侧边栏-->
    <div style="width:200px;z-index:2" class="baise yinying">
    <!--头像栏-->
    <div style="
    padding:10px;
    align-items: center;
    justify-content:center;
    border-bottom: 1px solid #999;
    " class="flex">
        <img src="https://kangwenchang.com/logo.png" width="40px" hheight="40px" alt="">
         <div style="margin-left: 10px;">康文昌</div>
    </div>
    <!--导航栏-->
    <div class="flex1">
        <div class="daohang">康老师的发家史</div>
        <div class="daohang">康老师的爱情史</div>
        <div class="daohang">康老师的伟大理想</div>
        <div class="daohang">康老师的无私奉献事迹</div>
        <div class="daohang">康老师永不言弃</div>
    </div>
    </div>
    <!--主区域-->
    <div class="flex1 flex column">
        <!--头部栏-->
        <div style="height:60px;z-index:1" class="baise yinying"></div>
        <!--内容区-->
        <div style="overflow:auto" class="flex1 flex">
            <!--左区-->
            <div style="flex:3" class="flex column mg8">
            <!--数据区-->
            <div class="flex">
                <!--数据块-->
                <div style="height:100px;" class="flex1 baise mg8 yinying"></div>
                <div style="height:100px;" class="flex1 baise mg8 yinying"></div>
                <div style="height:100px;" class="flex1 baise mg8 yinying"></div>
                <div style="height:100px;" class="flex1 baise mg8 yinying"></div>
            </div>
            <!--列表区-->
            <div class="flex column">
                <!--列表项-->
                <div style="height:160px" class="baise mgt8 yinying"></div>
                <div style="height:160px" class="baise mgt8 yinying"></div>
                <div style="height:160px" class="baise mgt8 yinying"></div>
                <div style="height:160px" class="baise mgt8 yinying"></div>
                <div style="height:160px" class="baise mgt8 yinying"></div>
                <div style="height:160px" class="baise mgt8 yinying"></div>
                <div style="height:160px" class="baise mgt8 yinying"></div>
                <div style="height:160px" class="baise mgt8 yinying"></div>
                <div style="height:160px" class="baise mgt8 yinying"></div>
                
            </div>
            </div>
            <!--右区-->
            <div style="flex:1" class="flex column mgr8 mgt8">
            <!--提示区-->
            <div style="height:150px" class="baise  yinying"></div>
            <!--消息区-->
            <div style="height:300px" class="baise mgt8 yinying"></div>
            </div>
        </div>
    </div>

</body></html>
