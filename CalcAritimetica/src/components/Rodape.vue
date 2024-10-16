<template>
    <footer class="text-center mt-5 animate-fade-in">
        <div>
            <ul class="list-unstyled d-flex justify-content-center align-items-center fs-3 mt-4 mb-3">
                <li class="mx-3">
                    <a href="https://www.linkedin.com/in/jean-pablo-alves-gon%C3%A7alves-a82477212/" target="_blank">
                    <i class="bi bi-linkedin vibrant-text"></i>
                    </a>
                </li>
                <li class="mx-3">
                    <a href="https://github.com/JeanAlves00" target="_blank">
                    <i class="bi bi-github vibrant-text"></i>
                    </a>
                </li>
            </ul>
            <p class="text-black mb-3 vibrant-text">
            &copy; {{ new Date().getFullYear() }} - Jean Pablo Alves Gonçalves - Todos os direitos reservados.
            </p>
        </div>
    </footer>
</template>

<style scoped>

    .vibrant-text {
        color: #ff5733;
        transition: color 0.3s ease, transform 0.3s ease;
    }
  
    .vibrant-text:hover {
        color: #000000;
        
    }

    @keyframes fadeIn {
        0% {
            opacity: 0;
            transform: translateY(20px);
        }
        100% {
            opacity: 1;
            transform: translateY(0);
        }
    }
  
    .animate-fade-in {
        animation: fadeIn 1s ease-in-out;
    }   
  
    a {
        text-decoration: none;
    }
  
    li:hover {
    transform: scale(1.2);
    }
</style>
  