<!DOCTYPE html>
<html lan="pt-br">

<head>
    <title>Pré-matrícula</title>
</head>

<body>

        <div id="current_date">
        </p>
        <script>
            date = new Date();
            year = date.getFullYear();
            month = date.getMonth() + 1;
            day = date.getDate();
            document.getElementById("current_date").innerHTML = day + "/" + month + "/" + year;
        </script>
        <script>
            window.alert('Página de teste')
            
        </script>
        

            <p>

                <font color="black"><i>
                        <font size="45"> Sistema de pré-matrícula do ensino fundamental</font>
                    </i></font>
            </p><br>

	     	

            <body background="https://thumbs.dreamstime.com/z/quadro-de-papelaria-escolar-sobre-fundo-branco-espa%C3%A7o-visualiza%C3%A7%C3%A3o-cima-plano-para-texto-volta-ao-conceito-226729453.jpg">

                               

            </body>

                                  
            <style>
                .modal-container .mostrar {
                    width: 100vw;
                    height: 100vh;
                    background: rgba(0, 0, 0, 5);
                    position: fixed;
                    top: 0px;
                    left: 0px;
                    z-index: 2000;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                }

                .modal-container .mostrar {
                    display: flex;
                }

                .modal {
                    background: rgb(162, 184, 155);
                    width: 10%;
                    min-width: 400px;
                    padding: 20px;
                    border: 2px solid #988b7a;
                    box-shadow: 0 0 0 10px white;
                    position: relative;
                }

                @keyframes modal {
                    from {
                        opacity: 0;
                        transform: translate3d(0, 60px, 0);
                    }

                    to {
                        opacity: 1;
                        transform: translate3d(0, 0, 0);
                    }
                }

                .fechar {
                    position: absolute;
                    top: 0px;
                    right: 0px;
                    width: 50px;
                    height: 50px;
                    border-radius: 50%;
                    border: 4px solid white;
                    background: #988b7a;
                    color: white;
                    font-family: "PT Mono", monospace;
                    cursor: pointer;
                    box-shadow: 0 4px 0 rgba(0, 0, 0, 3);
                }
            </style>


            <div id="Iniciar inscrição" class="modal-contanier">
                <div class="modal">
                    <h3 class="subtitulo"><i><font size="5">Faça sua inscrição no botão abaixo</font></i></h3>
                    
                </div>
		<p>Preencha o formulário

                <a href='form.html'>clicando aqui</a>

            </p>
</body>

</html>

