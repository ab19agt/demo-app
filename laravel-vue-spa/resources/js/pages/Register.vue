<template>
    <div class="container">
        <div class="row justify-content-center">

            <h1 class="justify-content">Register</h1><br>
            <div class="form-group">
              
                    
                
                    <input type="text" class="form-control" v-model="name" placeholder="name" required>
                 
                    
                    <input type="email" v-model="email" class="form-control" placeholder="email" required >
                    
                    <input type="password" v-model="password" class="form-control" placeholder="password" required>
                    <input type="submit" class="btn btn-primary" @click='submitting'>
            
            </div>
        </div>
    </div>
</template>

<script>

export default{
    name:'Register',

    data:{
        onclick: false,
        name: "",
        email:"",
        password:""


    },

    methods:
    {
        submitting(){
            
        }
        
    }

}
</script>
