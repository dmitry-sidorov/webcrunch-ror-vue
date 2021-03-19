<template>
  <div class="max-w-sm m-auto my-8">
    <div class="border p-10 border-grey-light shadow rounded">
      <h3 class="text-2xl mb-6 text-grey-darkest">Sign In</h3>
      <form @submit.prevent="signin">
        <div class="text-red" v-if="error">{{ error }}</div>
        
        <div class="mb-6">
          <label for="email" class="label">E-mail Adress</label>
          <input type="email" v-model="email" class="input" id="email" placeholder="example@gmail.com">
        </div>

        <div class="mb-6">
          <label for="password" class="label">Password</label>
          <input type="password" v-model="password" class="input" id="password">
        </div>



      </form>
    </div>
  </div>
</template>

<script>

</script>
