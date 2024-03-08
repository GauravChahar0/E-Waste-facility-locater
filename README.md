<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LOGIN PAGE</title>
</head>
<body style="background-color: aliceblue;background-image:url(Setting\ Sun\ 4\ -\ 夜明け\ 4.jpg);background-size: cover;">
    <h1 style="text-align: center;color: white;text-shadow: 2px 2px 5px white;font-family: cursive;">LOGIN</h1>
<form style ="border:solid;width:320px;height:400px;border-radius: 30px;margin:auto;border-width: 5px;">
    <div style="text-align: center;font-size:medium; font-family: cursive;line-height: 50px;margin-top: 40px;">
    <label for="FIRST NAME">FIRST NAME</label>
    <input type="text" name="FIRST NAME"><br>
    </div>
    <div style="text-align: center;margin: 20;font-size: medium;font-family: cursive;line-height: 70px;">
    <label for="s">LAST NAME</label>
    <input type="text" name="s"><br>
    </div>
    <div style="font-family: cursive;text-align: center;line-height: 60px;">
        <label for="sex">Sex:</label>
        <input type="radio" name="sex" id="male" value="male">
        <label for="male">Male</label>
        <input type="radio" name="sex" id="female" value="female">
        <label for="female">Female</label> <br>
    </div>
    <div style="text-align:center;font-family:cursive;line-height: 30px;">
        <label for="country">Country: </label>
        <select name="country" id="country">
        <option>Select an option</option>
        <option value="nepal">Nepal</option>
        <option value="usa">USA</option>
        <option value="australia">Australia</option>
        <option value="INDIA">India</option>
        <option value="Netherlands">Netherlands</option>
    </select><br><br>
    </div>
    <div style="text-align:center;font-family:cursive;line-height:40px;">
        <label for="k">LOG IN</label>
        <input type="submit",id="k">
    </div>
</form>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 2em;
    margin: 0;
}

main {
    padding: 20px;
}

.hero {
    text-align: center;
    margin-bottom: 20px;
}

.hero img {
    width: 70%;
    height: 600px;
    display: block;
    margin: 0 auto;
}

.hero p {
    margin-top: 10px;
    font-size: 1.2em;
}

.hero button {
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 20px;
}

.about {
    border-top: 1px solid #ddd;
    padding-top: 20px;
}

footer {
    background-color: #f2f2f2;
    text-align: center;
    padding: 10px;
}



