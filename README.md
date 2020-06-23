# kestrelhelloworld

nginx, kestrel ve docker-compose kullanarak helloworld seviyesinde bir .net core projesinin tek bir komutla deploy edilmesini sağlayan bir PoC.
kestrel+uygulamanin bulundugu container'ı edinmek icin "docker pull mantislogic/hell0c0rew0rld"


prerequisites
1. docker
2. docker compose
3. proje uzerinde gelistirme yapilmak istenirse (.net sdk ve runtime 2.1)

Ayaga kaldirmak icin
1. clone ile repoyu lokalinize aldiktan sonra projenin root dizininde "docker-compose up" komutu calistirilir.
2. localhost:80'den browse edilir.
