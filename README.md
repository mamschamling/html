<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login form</title>

    <style>
        *{
            margin: 20px;
            padding: 10px;
            box-sizing: border-box;
            font-family: 'poppins',sans-serif;
            font-size: 16px;
        }
        body{
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .container{
            width: 400px;
            padding: 30px;
            border: 1px solid gray;
            box-shadow: 0,0,10px blue;
        }
        p{
            font-size: 30px;
            margin-bottom: 30px;
            font-weight: bold;
        }
        input{
            width: 100%;
            height: 50px;
            padding: 10px;
            margin-top: 10px;
            border: none;
            outline: none;
            background-color: rgb(209, 214, 218);
        }
        button{
            border: none;
            padding: 8px 25px;
            background-color: aqua;
            color: aliceblue;
            cursor: progress;
        }
        button:hover{
            background-color: orange;

        }

    </style>

</head>
<body>
    <div class="container">
        <p> Sign Up</p>
        <input type="text"
        placeholder="Name">
        <input type="Email"
        placeholder="Email">
        <input type="password"
        placeholder="Password">
        <input type="Confirm password">
        <button
        type="submit"> Sign up</button>
            
        </button>
    </div>
    
</body>
</html>
