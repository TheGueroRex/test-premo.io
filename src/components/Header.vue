<template>
  <div>
    <header>
      <div class="brand">
        <Logo />
      </div>

      <nav>
        <ul>
          <li>
            <a href="">Home</a>
          </li>
          <li>
            <a href="">Productos</a>
            <svg
              width="12"
              height="8"
              viewBox="0 0 12 8"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0.276203 0.651245C0.634498 0.306731 1.20424 0.317902 1.54875 0.676197L6 5.4015L10.4513 0.676197C10.7958 0.317903 11.3655 0.306731 11.7238 0.651245C12.0821 0.995759 12.0933 1.5655 11.7487 1.92379L6.64875 7.32379C6.47907 7.50026 6.24482 7.6 6 7.6C5.75519 7.6 5.52093 7.50026 5.35125 7.32379L0.251251 1.92379C-0.0932627 1.5655 -0.0820913 0.995759 0.276203 0.651245Z"
                fill="#005B94"
                fill-opacity="0.75"
              />
            </svg>
          </li>
          <li>
            <a href="">Nosotros</a>
            <svg
              width="12"
              height="8"
              viewBox="0 0 12 8"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0.276203 0.651245C0.634498 0.306731 1.20424 0.317902 1.54875 0.676197L6 5.4015L10.4513 0.676197C10.7958 0.317903 11.3655 0.306731 11.7238 0.651245C12.0821 0.995759 12.0933 1.5655 11.7487 1.92379L6.64875 7.32379C6.47907 7.50026 6.24482 7.6 6 7.6C5.75519 7.6 5.52093 7.50026 5.35125 7.32379L0.251251 1.92379C-0.0932627 1.5655 -0.0820913 0.995759 0.276203 0.651245Z"
                fill="#005B94"
                fill-opacity="0.75"
              />
            </svg>
          </li>
          <li>
            <a href="">Precios</a>
            <svg
              width="12"
              height="8"
              viewBox="0 0 12 8"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0.276203 0.651245C0.634498 0.306731 1.20424 0.317902 1.54875 0.676197L6 5.4015L10.4513 0.676197C10.7958 0.317903 11.3655 0.306731 11.7238 0.651245C12.0821 0.995759 12.0933 1.5655 11.7487 1.92379L6.64875 7.32379C6.47907 7.50026 6.24482 7.6 6 7.6C5.75519 7.6 5.52093 7.50026 5.35125 7.32379L0.251251 1.92379C-0.0932627 1.5655 -0.0820913 0.995759 0.276203 0.651245Z"
                fill="#005B94"
                fill-opacity="0.75"
              />
            </svg>
          </li>
        </ul>
      </nav>

      <div class="button">
        <button>
          Acceder
          <svg
            width="18"
            height="18"
            viewBox="0 0 18 18"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M14.4831 15.1644C13.2278 13.5077 11.2389 12.4375 9 12.4375C6.76114 12.4375 4.77223 13.5077 3.51692 15.1644M14.4831 15.1644C16.1807 13.6533 17.25 11.4515 17.25 9C17.25 4.44365 13.5563 0.75 9 0.75C4.44365 0.75 0.75 4.44365 0.75 9C0.75 11.4515 1.81929 13.6533 3.51692 15.1644M14.4831 15.1644C13.0255 16.4618 11.1048 17.25 9 17.25C6.89518 17.25 4.97446 16.4618 3.51692 15.1644M11.75 6.9375C11.75 8.45628 10.5188 9.6875 9 9.6875C7.48122 9.6875 6.25 8.45628 6.25 6.9375C6.25 5.41872 7.48122 4.1875 9 4.1875C10.5188 4.1875 11.75 5.41872 11.75 6.9375Z"
              stroke="white"
              stroke-width="1.5"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>
        </button>
      </div>
    </header>
  </div>
</template>

<script>
import Logo from './Logo.vue';
export default {
  name: "Header",
  components: {
    Logo
    
  }
};
</script>

<style scoped>

header {
  
  width: 100%;
  height: 80px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-bottom: 1px solid #9c9c9c6e;
}

nav {
  width: 70%;
  height: 100%;
}

ul {
  display: flex;
  width: 70%;
  height: 70%;
  justify-content: start;
  align-items: center;
  gap: 10%;
}

li {
  list-style: none;
  width: 15%;
  height: 70%;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10%;
  
}
a {
  font-size: 1.1em;
  color: #005b94;
  text-decoration: none;
}

li:hover a{
  font-weight: 600;
  
}
li:nth-child(1):hover {
  border-bottom: 3px solid #005b94;
}

.button,
.brand {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 10%;
  height: 80%;
}
button {
  background: #005b94;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10%;
  width: 9em;
  height: 3em;
  border: none;
  border-radius: 5px;
  color: white;
}

button:hover{
  cursor: pointer;
  background: #014570;
  transition: 300ms;
}

</style>
