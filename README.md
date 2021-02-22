# Estudo básico do terminal Windows (Powershell) - Linux
  * Windows Prompt de Comando ***não*** incluído. O estudo é feito a partir do ***Powershell***, apesar de que alguns comandos do prompt de comando funcionem (os chamados *cmdlets*).

## **Windows**

**Sumário**

- [Estudo básico do terminal Windows (Powershell) - Linux](#estudo-básico-do-terminal-windows-powershell---linux)
  - [**Windows**](#windows)
    - [Comandos e informações básicas](#comandos-e-informações-básicas)
    - [Trabalhando com pastas](#trabalhando-com-pastas)
    - [Trabalhando com arquivos](#trabalhando-com-arquivos)

### Comandos e informações básicas
* Powershell ***não*** é case sensitive.
* Powershell tem auto complete de comandos, basta apertar *TAB*
* Limpando terminal: `cls` (cmdlet) ou `clear` ou `clear-host`
* Sair do terminal: `exit`
* Obter dados sobre o powershell: `get-host`
* Para atualizar a ajuda que o powershell te tá com o `get-host`, utilize `update-help`, com isso quaisquer novidades serão baixadas.
* Quem eu sou: `whoami`
* Histórico de comandos: Se apertar a seta do teclado para cima ele mostrará os ultimos comandos usados.
* Mostrar todos os comandos do Powershell: `get-command -commandtype all`
* Mostrar todos os comandos cmdlet `get-command -commandtype cmdlet`
* Mostrar todos os comandos de um outro tipo `get-command -commandtype tipoDeComando` (usar o tab mostrará os tipos existentes)
* Mostrar todos os comandos (de uma maneira mais gráfica): `show-command`
* 

### Trabalhando com pastas

* Cada pasta é separada por uma contra barra, exemplo: `C:\Users\Bruno>`
   * Isso significa que estamos no diretório *Bruno*, que está dentro da pasta *Users*, que está dentro da pasta *C:*.
* Mostar o diretório atual: `pwd`
* Navegando entre diretórios: `cd pathDoArquivo`
* Voltando uma pasta: `cd ..` (cmdlet)
* Voltando a pasta raiz do seu computador `cd\` (cmdlet)
* Visualizando arquivos dentro das pastas: `dir` (cmdlet) ou `ls`
* Criando uma pasta: `mkdir nomeDaPasta`

### Trabalhando com arquivos

* Criando um arquivo: `ni nomeDoArquivo.extensao`
* Renomeando um arquivo e mudando a extensão dele: `rni nomeDoArquivo.extensao novoNome.extensao`


