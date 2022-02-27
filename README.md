Saber usar o terminal é uma grande mão na roda para qualquer desenvolvedor, por isso, nesse documento você verá os principais comandos linux para quem está iniciando.
caso queria se aprofundar mais recomendo o [vídeo do DioLinux](https://www.youtube.com/watch?v=JEhVB4VHsTI) sobre comandos linux.

<h1> Antes de iniciarmos quero alertalos de algumas coisas </h1>

<p> Quando eu usar o sinal de maior e de menor siguinifica que dentro dele tem que ser inserido o conteúdo que o nome está descrevendo, e que esses sinais não devem aparecer no terminal. Exemplo </p>

```console
  < meunome >
```
<p>  Equivale a:  </p> 

```console
  thalles
```
<p> Ou </p>

```console
  < nomedoseucomputador >
```
<p>  Equivale a:</p> 

```console
  root
```

<p>Agora um exemplo com um comando: </p>

```console
  cd <nomeDaSuaÁreaDeTrabalhor>
```

<p> isso equivale a: </p>

```console
  cd Desktop
```
<p> ou </p>

```console
  cd "Área de trabalho"
```

<h1> Agora vamos ao que interessa </h1>


O primeiro comando básico é o pwd que mostra os a sua licalização no diretório atual, ele não precisa de parẫmetro então pode ser passando sozinho.

<h1>pwd</h1>

```console
 pwd
```
<p>

<h1>ls</h1>

O ls mostra todos os dieretórios e arquivos que estão presentes no seu diretório atual no terminal. Ele também não necessita de parâmetro.

</p>

```console
 ls
```

<h1>clear</h1>

<p>Ao usar continuamente o terminal sua tela enche de informações que não serão mais úteis, para limpar o terminal basta usar o comando clear</p>

```console
  clear
```

<h1>cd</h1>

<p>
cd:
  O cd entra ou sai de um diretório
  para entrar basta digitar o cd logo em seguida, como parâmetro basta digitar o nome do diretório que deseja entrar
</p>


<p> Para ENTRAR em um diretório </p>

```console
 cd < nome-do-diretório-de-interesse >
```

<p> Para VOLTAR um diretório </p>

```console
  cd ../
```

<p>Você pode voltar vários diretórios de uma vez com somente repetindo o < ../ > varárias vezes. Exemplo. </p>

```console
  cd ../../../
```
<p> Nesse caso ele voltou três vezes </p>

<h1>mkdir</h1>

<p> O mkdir cria pastas basta escrevelo e na sua frente passar o nome da pasta como parâmetro. Lembrese que se o nome da pasta tiver espaço você deve colocar o aspas < ' > antes do nome dela, caso contrário ele vai criar várias pastas</p>

```console
  mkdir '< nome-da-pasta >'
```

```console
  mkdir 'Minhas fotos'
```

<p> Agora se você não vai cirar uma pasta com espaço no nome ou se quer realmente criar várias pastas, não precisa colocar aspas.</p>

```console
  mkdir Photos Vídeos Músicas Documentos
```


<h1> touch </h1>

<p>O comando touch serve para criar arquivos de qualquer extensão basta passar após o comando touch o nome do arquivo com ponto < . > e depois a extensão.</p>

```console
  touch < nome-do-arquivo.extensão >
```

<p>Exemplo:<p>

```console
  touch index.html
```

```console
  touch metexto.txt
```


```console
  touch main.py
```

<h1> ⚠️ rm</h1>

<p>Caso você tenha criado pastas que não estavam no seu interesse, você também consegue removelas pelo terminal, basta colocar o < sudo > para dar permição para remover e depois o < rm > com a flag < -r > e o nome da pasta, so tome cuidado ao remover algo que seja do seu interesse.</p>

```console
  sudo rm -r Photos
```
<p> caso o sistema não de permisão para remover basta digitar um sudo na frente do comando </p>

```console
  sudo rm -r Vídeos
```

<p>Eele provavelmente vai pedir senha do computador basta você digitar e dar um enter no final</p>


<h3> ☠️ Cuidado com o comnando abaixo !!! </h3>

<p> Caso queira remover todos os arquivos dentro de um diretório basta digitar depois do comando rm o sinal de asterisco < * >, mas tome cuidado para não remover arquivos do seu interesse. </p>

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
  Esse comando mostra informações de uso e processos do hardwar do seu computador como memória, porcessador...
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