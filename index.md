
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>不二情书</title>
    <style>
        * {
            margin:0;
            padding:0;
        }
        a {
            text-decoration: none;
        }
        input,button{
            background: transparent;
            border: none;
            outline: none;
        }
        body{
            height:100vh;
            background:linear-gradient(#141e30,#243b55);
            display:flex;
            justify-content: center;
            align-items: center;
            font-size: 16px;
            color:#03e9f4;
            }
        .loginBox{
            width:400px;
            height:364px;
            background: rgba(0,0,0,0.5);
            box-shadow: 0 15px 25px 0 rgba(0,0,0,0.6);
            padding:40px;
            box-sizing: border-box;
        }
        h2{
            text-align: center;
            color:#fff;
            margin-bottom: 30px;
        }
        .item{
            height:45px;
            border-bottom: 1px solid #ffffff;
            margin-bottom: 40px;
            position:relative;
        }
        .item input{
            width:100%;
            height:100%;
            color:#ffffff;
            padding-top: 20px;
            box-sizing: border-box;
        }
        .item input:focus+label,.item input:valid+label{
            top:0;
            font-size: 12px;
        }
        .item label{
            position:absolute;
            left:0;
            top:12px;
            transition: all 0.5s linear;
        }
        .btn{
            padding:10px 20px;
           overflow: hidden;
            margin-top: 30px;
            color:#03e9f4;
            position: relative;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        .btn:hover{
            background: #03e9f4;
          border-radius: 5px;
          color:#ffffff;
            box-shadow:0 0 5px 0 #03e9f4,
                       0 0 25px 0 #03e9f4,
                       0 0 50px 0 #03e9f4,
                       0 0 100px 0 #03e9f4;
        }
        .btn>span{
            position: absolute;
        }
        .btn>span:nth-child(1){
           width:100%;
            height:2px;
            background:-webkit-linear-gradient(left,transparent,#03e9f4);
            left:-100%;
            top:0px;
            animation: line1 1s linear infinite;
        }
        @keyframes line1 {
            50%,100%{
                left:100%;
            }
        }
        .btn>span:nth-child(2){
            width:2px;
            height:100%;
            background:-webkit-linear-gradient(top,transparent,#03e9f4);
            right:0%;
            top:100%;
            animation: line2 1s 0.25s linear infinite;
        }
        @keyframes line2 {
            50%,100%{
                top:100%;
            }
        .btn>span:nth-child(3){
            width:100%;
            height:2px;
            background:-webkit-linear-gradient(left,#03e9f4,transparent);
            left:100%;
            bottom:0;
            animation: line3 1s 0.5s linear infinite;
        }
        @keyframes line3 {
            50%,100%{
                left:100%;
            }
        .btn>span:nth-child(4){
            width:2px;
            height:100%;
            background:-webkit-linear-gradient(top,#03e9f4,transparent);
            left:0;
            bottom:100%;
            animation: line4 1s 0.75s linear infinite;
        }
        @keyframes line4 {
            50%,100%{
                top:-100%;
            }
    </style>

    </head>
    <body>
       <div class="loginBox">
           <h2>Login</h2>
           <form action=""><div class="item">
               <input type="text" required>
               <label for="">UserName</label>
           </div>
               <div class="item">
                   <input type="password" required>
                   <label for="">PassWord</label>
               </div>
               <button class="btn"><a href="https://hllovecyk.github.io/yklovell/">SUBMIT</a>
               <span></span>
               <span></span>
               <span></span>
               <span></span>
               </button>
           </form>

               <audio src="./energy.mp3" controls="controls" autoplay="autopaly" loop="loop">
</audiom>
</body>
</html>
