<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" type="image/x-icon" href="../logoUkril.ico" />
    <title>For Cahcahh <33</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    <style>
        body {
            background-color: whitesmoke;
            text-align: center;
        }
        .button {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 20px;
            cursor: pointer;
            border-radius: 8px;
        }
        .button1 { background-color: #f44336; }
        .button2 { background-color: #4CAF50; }
        img {
            max-width: 60%;
            height: auto;
            display: block;
            margin: auto;
        }
        #footer {
            position: fixed;
            bottom: 0;
            width: 100%;
            background: #f1f1f1;
            padding: 10px 0;
        }
        #center {
            width: 500px;
            margin: 0 auto;
        }
        #By, #Bn {
            position: absolute;
            width: 210px;
            height: 210px;
        }
        #By {
            left: 150px;
            top: 400px;
        }
        #Bn {
            left: 270px;
            top: 400px;
        }
    </style>
    <script>
        let flag = 1;
        function f() {
            const Bn = document.getElementById('Bn');
            if (flag == 1) {
                Bn.style.top = "200px";
                Bn.style.left = "370px";
                flag = 2;
            } else if (flag == 2) {
                Bn.style.top = "450px";
                Bn.style.left = "350px";
                flag = 3;
            } else {
                Bn.style.top = "390px";
                Bn.style.left = "250px";
                flag = 1;
            }
        }
    </script>
</head>
<body>
    <h1 style="color:black;">Cahcahh maafin aku yaaa?</h1>
    <img src="https://c.tenor.com/QKzh5mKU4JIAAAAi/milk-and-mocha-cute.gif" alt="Cute GIF" height="200" />
    <h1 style="color:black;">Plisplisplis</h1>
    <div id="By">
        <button class="button button2" data-toggle="modal" data-target="#myModal">yesyesyes</button>
    </div>
    <div id="Bn">
        <button class="button button1" onMouseOver="f()">nononono</button>
    </div>
    <div class="modal fade" id="myModal" role="dialog">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal">&times;</button>
                    <h3 class="modal-title">yeyeyeyeyeyey dimaafin cahcahh :></h3>
                </div>
                <div class="modal-body">
                    <img src="https://c.tenor.com/O0L78rE1EZQAAAAd/milk-and-mocha-cute.gif" alt="Cute GIF" />
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-default" data-dismiss="modal">Tutup</button>
                </div>
            </div>
        </div>
    </div>
    <div id="footer">
        <div id="center">Total kunjungan: 26942</div>
    </div>
    <audio autoplay loop>
        <source src="romance.mp3" type="audio/mpeg">
    </audio>
</body>
</html>
