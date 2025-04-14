<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web gelistirici sitesi</title>
    <link rel="stylesheet" href="LoginFrom.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
 <form action="#">
      <h1>Login</h1>
      <div>
        <label for="name">Name</label>
        </div>
        <input type="text" id="name" placeholder="name">
        <i class="fa-solid fa-user"></i>
        <div>
    </div>
      <div>
        <label for="email">Email</label>
        <input type="email" id="email" placeholder="email">
        <i class="fa-solid fa-envelope"></i>
    
      </div>
      <div>

        <label for="pass">Password</label>
        <input type="password" id="password" placeholder="password">
        <i class="fa-solid fa-key"></i>
        <div>
          
    <button type="submit">Login</button>
 </form>
      
</body>
</html>






*{
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
}

html, body{
    height: 100%;
}

body {
    font-family: sans-serif;

    display: flex;
    justify-content: center;
    align-items: center;
    color: white !important;

    background: url(image/b530b2c5507b85ce19aae7a31fa3abe4-2.jpg);
    background-size: cover;
    background-repeat: no-repeat;

}

form {
    background: rgba(0, 0, 0, 0.641);
    backdrop-filter: blur(3px);
    border-radius: 1rem;

    display: flex;
    flex-direction: column;
    gap: 2rem;
    padding: 3rem 2rem;
}

form h1 {
    text-align: center;
    text-transform: uppercase;
    letter-spacing: 5px;
    font-size: 45px;
    font-weight: bold;
}
label {
    font-size: 18px;
}
form div div {
    display: flex;
    flex-direction: column;
    align-items: center;
    line-height: 30px;
    background: transparent;
    border: none;outline: none;
    border-bottom: 1x solid white;
}
label {
    font-size: 18px;
    font-size: 20px;
}

input {
    all: unset;
    font-size: 17px;
}

input,button {
    height: 50px;
    width: 300px;

    margin-top: .5rem;
}

button {
    background: #ff884d;
    color: wheat;
    font-weight: bold;
    font-size: 20px;
    width: 100%;
    
    border: none;outline: none;
    border-radius: 5rem;
    cursor: pointer;
    transition: .15s ease-in;

}
button:hover {
    transform: scale(1.05);
}


