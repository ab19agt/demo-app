<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-md-8">
        <div class="card">
          <div class="card-header">User Register</div>

          

          <div class="card-body">
            
            
            <router-link class="nav-link"
            data-toggle="collapse"
            :to="{name: 'login'}">
            New user?</router-link>

          </div>

          

        </div>
        
      </div>
    </div>
  </div>
</template>

<script>
//import LoginForm  from '../components/LoginForm';
export default{
    name:'Home',
    
}
</script>