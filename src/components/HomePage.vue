<template>
  <div class="home-container">
    <div class="welcome-text">
      <h1>Welcome to IE Bank</h1>
      <p>Your Trusted Banking Partner</p>
    </div>
    <div class="action-buttons">
      <router-link to="/skull" class="btn">
        Test Connection
      </router-link>
      <router-link to="/accounts" class="btn">
        View Accounts
      </router-link>
    </div>
  </div>
</template>

<style>
.home-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: #f0f0f0; /* Set your desired background color */
  color: #333; /* Set your desired text color */
}

.welcome-text {
  text-align: center;
  margin-bottom: 20px;
}

.action-buttons {
  display: flex;
  gap: 20px;
}

.btn {
  padding: 10px 20px;
  background-color: #007BFF; /* Set your desired button color */
  color: #fff;
  text-decoration: none;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.btn:hover {
  background-color: #0056b3; /* Set your desired button color on hover */
}
</style>
