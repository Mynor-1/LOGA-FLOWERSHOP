// Ejemplo simple: Cambia la imagen de Navidad cada 5 segundos (puedes personalizar)
const navidadImg = document.querySelector('#navidad img');
const images = ['images/navidad1.jpg', 'images/navidad2.jpg', 'images/poinsettias.jpg'];
let currentIndex = 0;

setInterval(() => {
    currentIndex = (currentIndex + 1) % images.length;
    navidadImg.src = images[currentIndex];
}, 5000);