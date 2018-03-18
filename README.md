# hello-world

Aplicatia pentru invatat

------------------cum luam sursele de pe github 

git clone https://github.com/Ammonaton01/hello-world

------------------ cum adaugam surse in staging
git add readme.md

------------------ cum comitem sursele in staging
git commit readme.md

------------------ cum trimitem datele catre server
git push

------------------cum pornim un docker container

docker build -t friendlyhello .

------------------cum rulam aplicatia

docker run -p 4000:80 friendlyhello
