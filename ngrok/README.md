<p text-align="center">
  <h1>ngrok</h1>
</p>



Já pensou você deixar seu conteudo HTML disponível na internet sem precisar hospedar ele em algum servidor? Com essa ferramenta chamada ngrok é possível.

O ngrok não é nada mais nada menos do que um "túnel", onde a função dele é redirecionar conexões externas para o seu localhost. Ou seja, você consegue com ele, rodar aquele teu projeto php ou html que está em localhost na rede externa e mostrar para as outras pessoas.


### 1º Passo: Instalar o ngrok

A partir do site https://ngrok.com/download você pode fazer o download do ngrok. Extraia o arquivo para a pagina de destino.

.

### 3º passo: criar servidor local.

Nesse passo irei utilizar o servidor do python mas qualquer outro como o apache do linux pode funcionar. 
Comando: execute no cmd ou terminal python -m http.server 3000. (estamos ultizando um modulo do python chamado http.server na porta 3000).


### 4º Passo: Execute o ngrok.

Agora com outra janela do cmd execute o ngrok na pasta que criou o arquivo.

Comando: ngrok.exe http 3000. (execute na mesma porta que abriu no servidor local.)

Irá aparecer uma url criada pelo ngrok, quando você entrar no navegador com essa url o ngrok irá fazer o túnel com o seu computador. Assim voce pode mandar a url gerada para qualquer pessoa, que vão conseguir acessar seu site.

[Passo a passo nesse pdf](https://github.com/valtercioj/amostras_pessoais/blob/master/ngrok/tutorial_ngrok.pdf)
