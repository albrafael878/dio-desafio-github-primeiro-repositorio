# Desafio de Projeto Sobre Git/GitHub da Dio
Repositório criado para o desafio de projeto. 

## Links úteis
[Sintaxe básica Markdown](https://www.markdownguide.org/basic-syntax/ )

#Lembrete (retornar para identificar o erro e desenvolver o site com mais experiência.

1º) Houve um erro com relação a ligação do Bootstrap com o HTML, meu palpite:
      a) Atualização (HTML ou do Bootstrap1), pois mesmo seguinto as aulas não consegui identificar o problema. Assim, para evitar perder muito tempo com a solução, deixarei para posterior solução.
      
    Minha desconfiança (acho que é algo aqui):
      
      "<title>Minha página</title>
    <meta charset="utf-8">
    <link rel="stylesheet" type="text/css" href="aula_bootstrap\css\bootstrap.min.css">
    <link rel="stylesheet" type="text/css" href="css2/style.css">"
    
    Dificuldade apresentada: Saber por qual motivo as palavras "quem somos", "parceiros", "serviços" ainda estão em formato HTML e não estão na mesma linha horizontal que a imagem. 
    
2º) Divisão da página. 

    Não consegui fazer e nem identificar o problema que estava me impedido de colocar as três imagens da Dio.
    
3º) 
    
Códogo-fonte:

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <title>Minha página</title>
    <meta charset="utf-8">
    <link rel="stylesheet" type="text/css" href="aula_bootstrap\css\bootstrap.min.css">
    <link rel="stylesheet" type="text/css" href="css2/style.css">
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light">
        <a class="navbar-brand" href="#">
            <img src="img/Global.png" width="120" height="100">
        </a>
        <div class="collapse navbar-collapse">
            <ul class="navbar-nav ar-auto">
                <li class="nave-item">
                    <a class="nav-link active" href="#">Quem somos</a>
                </li>
                <li class="nave-item">
                    <a class="nav-link active" href="#">Parceiros</a>
                </li>
                <li class="nave-item">
                    <a class="nav-link active" href="#">Serviços</a>
                </li>
            </ul>
        </div>
    </nav>
    <section id="quem-somos">
        <div class="container-fluid quem-somos text-center margin">
            <h3>Quem somos</h3>
            <img src="img/internet-1.jpeg" class="rounded-circle" width="400 " height="400 ">
            <h3>Somos um time comprometido com os resultados</h3>
        </div>
    </section>
    <section id="parceiros">
        <div class="container fluid text-center margin parceiros">
            <h3>Parceiros</h3>
            <div class="container">
                <div class="row">
                    <div class="col-lg-4">
                        <img src="img/digital-innovation-one.jpg" width="50%">
                    </div>
                    <div class="col-lg-4">
                        <img src="img/digital-innovation-one.jpg" width="50%">
                    </div>
                    <div class="col-lg-4">
                        <img src="img/digital-innovation-one.jpg" width="50%">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="serviços">
        <div class="container fluid text-center margin serviços">
            <h3>Serviços</h3>
            <div class="container">
                <div class="row">
                    <div class="col-lg-6">
                        <img src="img/pexels-markus-spiske-360591.jpg" width="100%">
                    </div>
                    <div class="col-lg-6">
                        <img src="img/internet-1.jpeg" width="100%">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <footer class="container-fluid text-center bg-footer">
        <img src="img/dio.svg" width="20%">
        <p>Página desenvolvida por xxxxxxxxxxxxx></p>

    </footer>


</body>

</html>
