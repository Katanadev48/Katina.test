<!DOCTYPE html>
<html>
<head>
<style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    body{
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .container{
        display: flex;
        flex-direction: column;
        width: 300px;
        padding: 15px;
        border: 1px solid 
         orange;
         border-radius: 5px;
    }
    input{
        margin: 5px 0px;
        height: 30px;
        padding: 7px;

    }
    button{
        height: 39px;
        margin: 5px 0px;
        background-color: bisque;
        border: none;
        border-radius: 5px;
        color: azure;
    }
    button:hover{
        background-color: beige;
        color: blanchedalmond;
    }
</style>    
</head>
<body>
    <div class="container">
        <input type="email"
        placeholder="email">
        <input type="password"
        placeholder="password">
        <button>login</button>
        <div class="remember-forgot">
        <label><input type="checkbox" remember me</label>
        <a href="#"> forgo-password? </a>
      </div>
        <button type="submit" class="btn"><login/button>
            <div class="registre-linke">
                <p>DON'T have an account?<a href="#"> registre</a></p>
            </div>

</body>
</html>
