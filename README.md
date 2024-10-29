portofolio website zahra dengan frame work Bootstap HTML dan CSS
berisi tentang saya, Project dan Contact 
terimakasih 

tedapat js untuk membuat navbar berubah saat di scroll

  <script>
        // navbar
        const navbar = document.getElementsByTagName('nav')[0];
        window.addEventListener('scroll', function () {
            console.log(window.scrollY);
            if (window.scrollY > 1) {
                navbar.classList.replace('berubah', 'nav-color');
            } else if (this.window.scrollY <= 0) {
                navbar.classList.replace('nav-color', 'berubah')
            }
        });

    </script>

pemanggilan berdasarkan Class yaitu nav yang apabila di scroll Y(kebawah) jika iya maka akan berubah warna dan jika kembali di scroll ke atas akan kembali ke warna smeula yaitu ada di class Berubah 
