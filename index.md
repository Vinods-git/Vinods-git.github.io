
<html>

<head>

    <head>
        <title>Assignment</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet"
            href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
            <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    </head>

    <style>
        body {
            font-family: "Lato", sans-serif;
        }

        .sidenav {
            height: 100%;
            width: 100px;
            position: fixed;
            z-index: 1;
            top: 0;
            left: 0;
            background-color: #fff;
            overflow-x: hidden;
           
        }

        .sidenav div {
           display: flex;
           justify-content: center;
           align-items: center;
           height: 75px;
        }
        .sidenav .logo{
           display: flex;
           justify-content: center;
           align-items: center;
           max-height: 100px;
        }

        .logo img{
            height: 100%;width: 100%;
        }
        .sidenav div:hover {
            background-color: #b7d5f4;
            border-left-style: solid;
            border-color: #2351fc;
        }
        .upload-container{
            margin-top: 100px;
            margin-left: 100px;
            background-color: #f1f1f1;
            height: 100vh;
            padding: 40px;
        }
        .upload-container a{text-decoration: none; color: #404040    ;}

        .upload-container h5{
        text-align: center; margin-top: 40px;

        }
        .input{
            width: 70%;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }

        input{
            height:30px;width: 100%;border:0 ;border-radius:5px;
        }
        .upload-button{
            display: flex;
          align-items: center;
          justify-content: center;
          width: 150px; height: 150px;margin-left: auto;margin-right: auto;
        }


    </style>
</head>

<body>

    <div class="sidenav shadow-lg ">
        <div  class=" logo"><a href=""><img src="images/logo.png" alt="logo"></a></div>
        <div><i class="fa fa-user"></i></div>
        <div><i class="fa fa-book"></i></div>
        <div><i class="fa fa-cog"></i></div>
    </div>

    <div class="upload-container" >
        <a href="" ><i class="fa fa-caret-left p-2"></i><b>Videos</b></a>
        <div class="input">
        <div ><input  type="text"></div>
        <h5 >or</h5>
        <button class="bg-white border-0 " >
            <div class="upload-button" ><b>Upload</b></div>
        </button></div>
    </div>

    

</body>

</html>
