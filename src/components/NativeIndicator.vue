<template>
  <div class="border">
    <h1>Browser default visual focus indicator</h1>
  
    <div>
        <button class="button primary" >Primary <span aria-hidden="true" >Button</span></button>
        <button class="button secondary" >Secondary <span aria-hidden="true">Button</span></button>
        <button class="button tertiary" >Tertiary <span aria-hidden="true">Button</span></button>
    </div>
  </div>
</template>
<script>
export default{
    data(){
        return {
            
        }
    },
    methods: {
    
    }
}
</script>
<style scoped>
.border {
  background-color: rgb(243, 241, 241);
  padding: 10px;
  margin: 20px;
}
.button {
  display: inline-block;
  padding: 10px 20px;
  margin: 5px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  font-size: 16px;
  transition: background-color 0.3s;
}
.primary {
  background-color: #007bff;
  color: #fff;
}
.secondary {
  background-color: #6c757d;
  color: #fff;
}
.tertiary {
  background-color: #f8f9fa;
  color: #212529;
  border: 1px solid #ccc;
}
</style>