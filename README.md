
<html>
<head>
    <link rel="shortcut icon" type="image/x-icon" href="../logoUkril.ico" />

<title> For Cahcahh <33 </title>

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

<style>
   body {
    background-color: whitesmoke;
   }

.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  cursor: pointer;
}

.button1 {  border-radius: 8px;
            background-color: #f44336;
}

.button2 {  border-radius: 8px;
            background-color: #4CAF50;

}

img {
  max-width: 60%;
  height: auto;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

#footer {
    position: fixed;
    bottom: 0;
    width: 100%;
}
#center {
    width: 500px;
    margin: 0 auto;
}


</style>

<script type="text/javascript">
flag=1



function show_modal(e)
{
    console.log (e.href);
    $("#image_modal").attr("src", e.href);
    $('#myModal').modal('show');
    return false;
}



function f()
{
    if(flag==1)
        {
            Bn.style.top=200
            Bn.style.left=370
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=450
            Bn.style.left=350
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=390
            Bn.style.left=250
            flag=1
        }
}
</script>

</head>
<body>
<h1 align="center" style="color:black;"> cahhcahh maafin aku yaaa ? <h1>
<img alt="EvilicaCell" src="https://c.tenor.com/QKzh5mKU4JIAAAAi/milk-and-mocha-cute.gif" height="200" style="display:block; margin:auto;" />
<h1 align="center"  style="color:black;">plisplisplis</h1>

<div id="By" style="position:absolute; left:150; top:400px; width:210px;
height:210px; margin-right: 30px" >
<input type="button" value=" yesyesyes " class="button button2" onclick="return show_modal(this);"/>
</div>

<div ID="Bn" style="position:absolute; left:270; top:400px; width:210px; height:210px;">
<input type="button" value=" nononono " class="button button1" onMouseOver="f()" />
</div>



<div class="modal fade" id="myModal" role="dialog">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal">&times;</button>
                <h3 class="modal-title">yeyeyeyeyeyey dimaafin cahcahh :></h3>
            </div>
            <div class="modal-body">
                <img id="image_modal" src="https://c.tenor.com/O0L78rE1EZQAAAAd/milk-and-mocha-cute.gif" ></img>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Tutup</button>
            </div>
        </div>
    </div>
</div>

    <div id="footer">
        <div id="center">

            Total kunjungan: 26942            
        </div>
    </div>


<audio autoplay>
    <source src="romance.ogg" type="audio/mp3">
</audio>

</body>
</html>
