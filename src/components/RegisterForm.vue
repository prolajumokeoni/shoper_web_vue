<template>
  <div class="register">
    <button class="shop">Create a shopper account</button>
    <p>Please enter register information</p>
    <form>
      <label for="First name">First Name</label>
      <input type="first name" id="First name" name="first name" placeholder="First name" />
      <label for="Last name">Register</label>
      <input type="Lastname" id="Last name" name="Last name" placeholder="Last name" />
      <label for="register">Register</label>
      <input type="register" id="register" name="register" placeholder="Register" />
      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Email" />
      <label for="email">Company</label>
      <input type="company" id="company" name="company" placeholder="Company" />
      <label for="password">Phone number</label>

      <input type="phone number" id="phone number" name="phone number" placeholder="Password" />
      <!-- <div class="main-box">
        <div class="box">
          <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike" />
          <label for="vehicle1"> I am a subscriber</label><br />
        </div>
        <div class="box">
          <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike" />
          <label for="vehicle1"> I am a subscriber</label><br />
        </div>
      </div> -->
      <p>Forgot your password?</p>
      <button class="submit-btn" type="submit">Continue</button>
      <div class="account">
        <p>You do not have an account ?</p>
        <a href="#table">Create an account</a>
				<!-- <router-link to="/login">Go to Home</router-link> -->
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
}
.shop {
  border: 1px solid black;
  border-radius: 25px;
  padding: 10px;
  color: black;
  background: white;
	text-align: center;
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
.text-small {
  text-align: center;
}
.main-box {
  border: 1px solid red;
  display: flex;
  flex-direction: row;
}
/* .box {
	width: 50px;
} */
.account {
	display: flex;
	align-items: center;
	gap: 5px;
}
</style>