# Angular v10 Login and Register Template by using Login html.

  
   
<div class="container" id="container">
	<div class="form-container sign-up-container">
		<form action="#">
			<h1>Create Account</h1>   
			<input type="email" placeholder="Email" />
			<input type="password" id="password" placeholder="Password" minlength="6"/>
			<input type="password" id="confirm_password" placeholder="Confirm Password" minlength="6"/>
			<div style="width: 100%;">
				<button  class="btn_black">Create</button>
			</div>
			
			<div class="div-a">
				<a href="#" id="signIn"> Already have a account?</a>	
			</div>
			
		</form>
	</div>
	<div class="form-container sign-in-container">
		<form action="#">
			<h1>Sign in</h1> 
			<input type="email" placeholder="Email" />
			<input type="password" placeholder="Password" minlength="6"  />
			<div style="width: 100%">
				<button class="btn_yellow">Login</button>
			</div>
			<div class="div-a">
				<a href="#" id="signUp">Create account</a>
			</div>
			
		</form>
	</div>
	<div class="overlay-container">
		<div class="overlay">
			<div class="overlay-panel overlay-left">
				<h1>Let's get you started</h1>
				<p>Be part of out awesome team and have fun with us</p> 
			</div>
			<div class="overlay-panel overlay-right">
				<h1>Hello, There</h1>
				<p>Don't have an account? <br/>Sign Up with us today!</p> 
			</div>
		</div>
	</div>
</div>   