<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Calculator </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1> Calculator </h1>
    <div class="card">

    <div class="calc-head">
        <input type="text" id="result" maxlength="10">
    </div>
    <div class="calc-body">
        <div>
            <input type="button" class="btn" value="C">
            <input type="button" class="btn" value="+/-">
            <input type="button" class="btn" value="%">
            <input type="button" class="btn btn-style" value="/">

        </div>

        <div>
            <input type="button" class="btn" value="7">
            <input type="button" class="btn" value="8">
            <input type="button" class="btn" value="9">
            <input type="button" class="btn btn-style" value="X">

        </div>


        <div>
            <input type="button" class="btn" value="4">
            <input type="button" class="btn" value="5">
            <input type="button" class="btn" value="6">
            <input type="button" class="btn btn-style" value="-">

        </div>


        <div>
            <input type="button" class="btn" value="1">
            <input type="button" class="btn" value="2">
            <input type="button" class="btn" value="3">
            <input type="button" class="btn btn-style" value="+">

        </div>

        <div>
            <input type="button" class="btn" value="0">
            <input type="button" class="btn" value=".">
            <input type="button" class="btn" value="DEL">
            <input type="button" class="btn" style="background-color: orange;" value="=">

        </div>

    </div>
    </div>
    

</body>
</html>
*{
    margin: 0;
    padding: 0;
}

h1{
    text-align: center;
    color: rebeccapurple;
}

.card{
    margin: 0 auto;
    max-width: 350px;
    text-align: center;
    margin-top: 10px;
    box-shadow: 0 4px 8px 0  rgba(0,0,0,0,2);
    transition: 0.3s;
    font-size: 0;
}

.card:hover{
    box-shadow: 0 16px 32px 0 rgb(0,0,0,0,2);
}

.calc-head #result{
    width: 335px;
    height: 100px;
    font-size: 32px;
    text-align: right;
    padding: 0 5px ;
    letter-spacing: 2px;

}

.btn{
    width: 87px;
    height: 70px;
    font-weight: bold;
    font-size: 16px;
    background-color: #1f2326;
    color: white;
}

.btn-style{


    background-color: #5F4BB6;
}

.btn:hover{
    background-color: pink;
}






