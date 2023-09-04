<template>
	<div>

<button class="shop">Create Password</button>
<p>Please enter your login information</p>
<form>
 <label for="email">Email</label>
 <input type="email" id="email" name="email" placeholder="Email" />
 <label for="password">Password</label>
 <input type="password" id="password" name="password" placeholder="Password" />
 
 <button class="submit-btn" type="submit">Login with email</button>
 <div class="account">
	 <p>You do not have an account ? </p>
	 <a href="#about">Create an account</a>
	</div>
</form>
</div>
</template>
<style>
.right {
 width: 50%;
 display: flex;
 justify-content: center;
 align-items: center;
 flex-direction: column;
 text-align: center;
}
.shop {
 border: 1px solid black;
 border-radius: 25px;
 padding: 10px;
 color: black;
 background: white;
}
form {
 display: flex;
 flex-direction: column;
 gap: 10px;
}

input {
 padding: 16px;
 border-radius: 12px;
 border: 1px solid #a3a3a3;
 width: 375px;
}
.submit-btn {
 border-radius: 12px;
 background: #000;
 height: 50px;
 color: white;
}
.account {
	display: flex;
	align-items: center;
	gap: 5px;
}
</style>