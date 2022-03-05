
<h1>👨‍💻👩‍💻Principais comandos linux</h1>
Saber usar o terminal é uma grande mão na roda para qualquer desenvolvedor, por isso, nesse documento você verá os principais comandos linux para quem está iniciando.
caso queria se aprofundar mais recomendo o [vídeo do DioLinux](https://www.youtube.com/watch?v=JEhVB4VHsTI) sobre comandos linux.

<h1> Antes de iniciarmos quero alertalos de algumas coisas </h1>

<p> Quando nos exemplos aparecer o sinal de maior e de menor,siguinifica que dentro dele tem que ser inserido o conteúdo que está descrito, e que esses sinais não devem ser colocados na hora de escrever o comando. Exemplo </p>

```console
  < meunome >
```
<p>  Equivale à:  </p> 

```console
  thalles
```
<p> Ou </p>

```console
  < nomedoseucomputador >
```
<p>  Equivale à:</p> 

```console
  root
```

<p>Agora um exemplo com um comando: </p>

```console
  cd <nomeDaSuaÁreaDeTrabalhor>
```

<p> Equivale à: </p>

```console
  cd Desktop
```
<p> ou </p>

```console
  cd "Área de trabalho"
```

<h1> Agora vamos ao que interessa </h1>


O primeiro comando básico é o pwd, ele mostra sua licalização no diretório atual; lembrando que diretorio são as pastas e que cada pasta está inserida dentro de outra que está inserida dentro de outra. Por isso o comando pwd vai mostrar a arquitetura dos diretórios. Mas não é um comando muito usado, pois o próprio terminal do linux já mostra por padrão essa raiz.

<h1>pwd</h1>

```console
 pwd
```
<p>

<h1>ls</h1>

O ls mostra todos os dieretórios e arquivos que estão presentes no seu diretório atual. Ele também não necessita de parâmetro.

</p>

```console
 ls
```

<p>Você pode também listar arquivos ou pastas ocultas com o parâmetro < -a > </p>

```console
  ls -a
 ```

<h1>clear</h1>

<p>Ao usar continuamente o terminal sua tela enche de informações que não serão mais úteis, para limpar o terminal basta usar o comando clear, fiquem traquilos, ele só vai limpar o terminal é não vai apagar nada no seu computador.</p>

```console
  clear
```

<h1>cd</h1>

<p>
cd:
  O cd tem a função de entra ou sai de um diretório (pastas)
  para entrar basta digitar o < cd > logo em seguida, como parâmetro basta digitar o < nome-do-diretório > que deseja entrar
</p>


<p> Para ENTRAR em um diretório </p>

```console
 cd < nome-do-diretório-de-interesse >
```
<p>Você pode usar o comando < l > para ver os diretórios. Quando executado os diretórios vai ficar com uma barra ( / ) na frente, siguinificam que são pastas e podem ser acessados com o comando < cd >  </p>

<p> Para VOLTAR para o diretório anterior </p>

```console
  cd ../
```

<p>Você pode voltar vários diretórios de uma vez com somente repetindo o < ../ > varárias vezes. Exemplo. </p>

```console
  cd ../../../
```
<p> Nesse caso ele voltou três vezes pois foi a quantidade de repetições dos ../ </p>

<h1>mkdir</h1>

<p> O mkdir cria diretórios (pastas), escrever o comando e na sua frente você deve passar o nome que deseja dar para a sua pasta. Lembre se de que se o nome da pasta tiver espaço você deve colocar o aspas < ' > entre o nome da pasta. Caso você não faça isso, ele vai criar várias pastas simutâneas</p>

```console
  mkdir '< nome-da-pasta >'
```

```console
  mkdir 'Minhas fotos'
```

<p> Agora caso você realmente queira cirar várias pastas, não cessecita usar as aspas, esse exemplo abaixo cria quatro pastas de uma única vez.</p>

```console
  mkdir Photos Vídeos Músicas Documentos
```


<h1> touch </h1>

<p>O comando touch serve para criar arquivos de qualquer extensão basta passar após o comando < touch > o nome do arquivo com ponto < . > e depois a extensão.</p>

```console
  touch < nome-do-arquivo.extensão >
```

<p>Exemplo:<p>

```console
  touch index.html
```

```console
  touch meutexto.txt
```


```console
  touch main.py
```

<h1> ⚠️ rm</h1>

<p>Caso você tenha criado pastas ou arquivos que não estavam no seu interesse, você também consegue removelas pelo terminal, basta colocar o < sudo > para dar permição para remover e depois o < rm > com a flag < -r > e o nome da pasta, so tome cuidado ao remover algo que seja do seu interesse.</p>

```console
  sudo rm -r Photos
```
<p>Ou</p>

```console
  sudo rm -r Vídeos
```

<p>Eele provavelmente vai pedir senha do computador basta você digitar e dar um enter no final</p>


<h3> ☠️ Cuidado com o comnando abaixo !!! </h3>

<p> Caso queira remover todos os arquivos dentro de um diretório basta digitar depois do comando rm o sinal de asterisco < * >, mas tome cuidado para não remover arquivos do seu interesse. Qual quer coisa de um < ls >  antes para listar todos os arqivos e pastas para ver o que vai ser removido </p>

```console
  sudo rm -r *
```

<h1>code . </h1>

<p>Esse comando é usado para quem já tem o editor de text visual stúdio code instalado, função é abrir o visual studio no seu diretório atual.
</p>

```console
  code .
```

<h1> top </h1>

<p>
  Esse comando mostra informações de uso e processos do hardware do seu computador como memória, porcessador...
</p>

```console
  top
```
<p>
  para encerrar o processo basta usar o atalho < ctrl + c >
</p>

# Agora vamos falar de comandos do teclado no terminal
<h1> ctrl + c </h1>
<p>Encerra um processo que está em execução</p>

<h1> ctrl + shift (⬆️) + c </h1>
<p>Copia um texto que foi selecionado no terminal</p>


<h1> ctrl + shift (⬆️) + v </h1>
<p>Cola cola um texto no terminal que foi copidado </p>


<h1> Tab </h1>
<p>Completa o nome de um diretorio ou de um arquivo quando as iniciais dele for único </p>
