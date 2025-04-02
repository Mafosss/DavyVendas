<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Davy Vendas</title>
    <link rel="stylesheet" href="DavyBonito.css">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background: #333;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        section {
            padding: 20px;
        }
        .produto {
            border: 1px solid #ddd;
            padding: 20px;
            margin: 20px auto;
            width: 300px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
        }
        .produto img {
            width: 100%;
            border-radius: 10px;
        }
        .preco {
            color: red;
            font-size: 22px;
            font-weight: bold;
            margin: 10px 0;
        }
        .botao {
            display: inline-block;
            padding: 10px 20px;
            background: green;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            background: #333;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        form {
            margin-top: 20px;
        }
        input, textarea {
            display: block;
            width: 80%;
            margin: 10px auto;
            padding: 10px;
        }
        button {
            padding: 10px 20px;
            background: blue;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        Davy Vendas, a diferença de uma microimpresa para uma Industria!
    </header>
    <section>
        <h2>Confira nossos produtos</h2>
    
        <!-- Container dos produtos -->
        <div class="produtos-container">
            <!-- Produto 1 -->
            <div class="produto">
                <img src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1623730/ss_1e47bb8bbfaaaf3282bfb5d253378832b55c4e56.1920x1080.jpg?t=1742869326" alt="Palworld">
                <h2>Todos os Pals</h2>
                <p>Agora você poderá ter todos os pals em sua casa!</p>
                <ul>
                    <li>Grandes</li>
                    <li>Fortes</li>
                    <li>Armados</li>
                    <li>Muito loucos</li>
                </ul>
                <p class="preco">R$ 88,90</p>
                <a href="#" class="botao">Comprar</a>
            </div>
    
            <!-- Produto 2 -->
            <div class="produto">
                <img src="https://m.media-amazon.com/images/I/71O2bDUtv+L._AC_SL1500_.jpg" alt="Fone de Ouvido">
                <h2>Fone Gamer</h2>
                <p>Som incrível para você curtir seus jogos com imersão total.</p>
                <ul>
                    <li>Áudio 3D</li>
                    <li>Cancelamento de Ruído</li>
                    <li>Confortável para longas horas</li>
                    <li>Microfone de alta qualidade</li>
                </ul>
                <p class="preco">R$ 299,90</p>
                <a href="#" class="botao">Comprar</a>
            </div>
        </div>
    </section>
    <section>
        <h2>Entre em Contato com Mafos</h2>
        <img src="https://yt3.googleusercontent.com/OJozi6MLakeevdixOD8iJjKLKucdp1E8glDQOYm_YQgs4PVz02qhkI1akoZs2uxrqklkpQFJ6A=s900-c-k-c0x00ffffff-no-rj" 
     alt="Dava Jonas"
     style="width: 150px; height: 150px; border-radius: 50%;">

     <form method="post" action="#">
        <input type="text" name="nome" placeholder="Seu Nome" required>
        <input type="email" name="email" placeholder="Seu E-mail" required>
        <textarea name="mensagem" placeholder="Sua Mensagem" rows="5" required></textarea>
        <button type="submit">Enviar</button>
    </form>
    
    </section>
    <footer>
        &copy; 2025 Davy Vendas. by Mafos.
    </footer>
</body>
</html>
