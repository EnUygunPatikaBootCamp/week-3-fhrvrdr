
## Symfony kullanmanın avantajları nedir?

* Belirli standartlar üzerine kod yazıldığı için proje daha hızlı geliştirilir.
* Daha güvenli bir yazılım oluşturulmasına yardımcı olur.
* Daha kolay bakım yapılabilmesini sağlar.

### Symfony ile environment (ortam) ayarlaması nasıl yapılır?
* Proje klasöründe ".env" isimli dosya içersinden yapılır.

### Yeni bir Symfony projesi oluşturmak için kullanılan composer komutu nedir? Alternatif bir komutla Symfony projesi oluşturabilir miyiz?

* Composer aracılığı ile Symfony projesi oluşturmak için aşağıdaki komutu kullanırız:

      composer create-project symfony/skeleton:"^5.4" my_project_directory

* Alternatif olarak Symfonu CLI üzerinden aşağıdaki komut ile proje oluşturabiliz:

      symfony new my_project_directory --version=5.4 --webapp

### Laravel framework ve Symfony framework arasındaki temel farklardan iki tanesini yazınız.

* Laravel view kısmında Blade template kullanırken, Symfony Twig template kullanır.
* Laravel database işlemlerinde Eloquent ORM kullanırken, Symfony database işlemerinde Doctrine ORM kullanır.