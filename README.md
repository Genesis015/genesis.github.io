<!DOCTYPE html>

<head>
    <meta name="viewport" content="width=device-width intial-scaling=1">
    <style>
        form {
            margin: 15px;
            padding: 5px;
            border-spacing: 10px;
            font-size: 25px;
        }
        
        fieldset {
            width: 20%;
            text-align: center;
            border-radius: 5px;
            box-shadow: 2px;
            margin-left: 40%;
            margin-top: 10%;
        }
        
        a:hover {
            color: rgb(253, 27, 27);
        }
        
    </style>
</head>
<fieldset>
    <form action="H" method="POST">
        <p>Sign In</p>
        <label>Email Address</label><br>
        <input type="email" placeholder="Email" required><br><br>
        <label>Password</label><br>
        <input type="password" placeholder="Password" required><br><br>
        <button type="submit">Login</button><br>
        <label><a href="H">Don't have an Account</a></label>
    </form>

</fieldset>


</html>
