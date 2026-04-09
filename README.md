# pratica-sem-ntica-html
um mini projeto de HTML básico para habilidades futuras

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="root.css">
    <link rel="stylesheet" href="login.css">
    <title>Meu Logint</title>
</head>

<body>
    <header>
        <nav>
            <h1>Minha Loja</h1>
        </nav>
    </header>
    <section class="login-section">

        <div class="container">
            <div class="login-card">
                <h2 class="titulo-login">Logo</h2>
                <h3>Faça Loggin da sua conta.</h3>

                <form class="login-form" novalidate>
                    <div class="input group">
                        <label for="user">Usuario</label>
                        <input type="text" id="user" name="user" placeholder="digite seu usuario"
                            class="input-field" required autocomplete="username">
                        <span class="input-error"></span>
                    </div>
                    <div class="input-group">
                        <label for="password">Senha</label>
                        <input type="password" id="password" name="password" placeholder="digite sua senha"
                            class="input-field" required autocomplete="current-password">
                        <span class="input-error"></span>
                    </div>
                    <button class="button-enter" type="submit">
                        <span class="button-text">Entrar</span>
                        <span></span>
                    </button>
                </form>
                <div class="login-footer">
                    <a href="#" class="link-forgot">Esqueceu sua senha?</a>
                    <p class="login-help">Não tem conta? <a href="#" class="link-register" >Cadastre-se</a></p>
                </div>
            </div>
        </div>

    </section>

    <!--FOOTER-->
   <footer>
    <p>&copy MinhaLoja - Todos os direitos reservados</p>
    <p>Webcreate by Jeff</p>
   </footer>
</body>

</html>

