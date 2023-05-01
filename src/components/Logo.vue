<template>
  <a href="" class="logo">
  <h1>Bank</h1>
    <svg
      width="30"
      height="25"
      viewBox="0 0 36 33"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M18 0L22.0413 12.4377H35.119L24.5389 20.1246L28.5801 32.5623L18 24.8754L7.41987 32.5623L11.4611 20.1246L0.880983 12.4377H13.9587L18 0Z"
        fill="#9FC733"
      />
    </svg>
  </a>
 
    
  
</template>


<script>
export default {
  name: "Logo",
};
</script>

<style scope>

.logo {
  font-family: Arial, Helvetica, sans-serif;
  display: flex;
  align-items: center;
}
a{
  text-decoration: none;
}
h1 {
  text-transform: uppercase;
  color: black;
}

.logo:hover h1{
  color: #005b94;
  transition: 300ms;
}
</style>
