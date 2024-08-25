# CODSOFT
New Repo for CODSOFT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="cal.css">
</head>
<body>
    <form name="form_design">
        <input type="text" name="display" id="display">
        <div class="button_design">
            <input type="button" value="AC" onclick="form_design. display.value= '' ">
            <input type="button" value="DEL" onclick="form_design. display.value=form_design.display.value.slice(0,-1)">
            <input type="button" value="%" onclick="form_design. display.value+='%'">
            <input type="button" value="/" onclick="form_design. display.value+='/'">

            <input type="button" value="7" onclick="form_design. display.value+='7'">
            <input type="button" value="8" onclick="form_design. display.value+='8'">
            <input type="button" value="9" onclick="form_design. display.value+='9'">
            <input type="button" value="*" onclick="form_design. display.value+='*'">

            <input type="button" value="4" onclick="form_design. display.value+='4'">
            <input type="button" value="5" onclick="form_design. display.value+='5'">
            <input type="button" value="6" onclick="form_design. display.value+='6'">
            <input type="button" value="-" onclick="form_design. display.value+='-'">

            <input type="button" value="1" onclick="form_design. display.value+='1'">
            <input type="button" value="2" onclick="form_design. display.value+='2'">
            <input type="button" value="3" onclick="form_design. display.value+='3'">
            <input type="button" value="+" onclick="form_design. display.value+='+'">

            <input type="button" value="0" onclick="form_design. display.value+='0'">
            <input type="button" value="00" onclick="form_design. display.value+='00'">
            <input type="button" value="." onclick="form_design. display.value+='.'"> 
            <input type="button" value="=" onclick="form_design. display.value= eval(form_design.display.value)">

        </div>
    </form>
</body>
</html>
