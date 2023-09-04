

<template>
  <div class="wrapper">
    <div class="left">
      <img src="../assets/frame.png" />
    </div>
    <div class="right">
      <LoginForm />

      <div>
      <button class="shop">Login to shopper</button>
      <p>Please enter login information</p>
      <form>
        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="Email" />
        <label for="password">Password</label>
        <input type="password" id="password" name="password" placeholder="Password" />
        <p>Forgot your password?</p>
        <button class="submit-btn" type="submit">Login with email</button>
      <p>You do not have an account ? </p>
      <a href="#about">Create an account</a>
      </form>
    </div>

    </div>
  </div>
</template>
<style>
.wrapper {
  width: 100%;
  display: flex;
  flex-direction: row;
}
.left {
  width: 50%;
}
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
</style>
