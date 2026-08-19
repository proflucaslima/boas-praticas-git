# boas-praticas-git



funcao login(usuario, senha) {

    usuarioBanco = buscarUsuarioNoBanco(usuario)

    se usuarioBanco nao existe {
        retornar falso
    }

    se usuarioBanco.senha == senha {
        retornar verdadeiro
    }

    validarToken(usuario);
    
    retornar falso
}