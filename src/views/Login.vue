<template>
  <div id="login">  

    <h1> LOG IN </h1>
      <form @submit.prevent="login">
          Username: <input type="text" id="txtUsername" v-model='username'><br>
          Password: <input type="password" id="txtPassword" v-model='password'><br>
          <input type="submit" value="LOGIN">
      </form>
  </div>
</template>>
