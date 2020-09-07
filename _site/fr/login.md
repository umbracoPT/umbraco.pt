
<style>

  .form-signin {
    max-width: 330px;
    padding: 15px;
    margin: auto;
  }
  
  .form-signin .form-signin-heading,
  .form-signin .checkbox {
    margin-bottom: 10px;
  }
  
  .form-signin .checkbox {
    font-weight: normal;
  }
  
  .form-signin .form-control {
    position: relative;
    height: auto;
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
    padding: 10px;
    font-size: 16px;
  }
  
  .form-signin .form-control:focus {
    z-index: 2;
  }
  
  .form-signin input[type="email"] {
    margin-bottom: -1px;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0;
  }
  
  .form-signin input[type="password"] {
    margin-bottom: 10px;
    border-top-left-radius: 0;
    border-top-right-radius: 0;
  }
  
</style>

<div>

  <form class="form-signin">
    <h2 class="form-signin-heading">Login credentials</h2>
    <br>
    
    <label for="inputEmail" class="sr-only">Email address</label>
    <input type="username" id="inputUser" class="form-control" placeholder="Username" required autofocus>
    
    <label for="inputPassword" class="sr-only">Password</label>
    <input type="password" id="inputPassword" class="form-control" placeholder="Password" required>
    
    <div class="checkbox">
      <label>
        <input type="checkbox" value="remember-me"> Remember me
      </label>
    </div>
    
    <br>
    
    <button class="btn btn-lg btn-primary btn-block" type="submit">Sign in</button>
    
    <br>   
  </form>

    <br>

</div>
    