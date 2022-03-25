# hostel-app-gcva

<!---Esses são exemplos. Veja https://shields.io para outras pessoas ou para personalizar este conjunto de escudos. Você pode querer incluir dependências, status do projeto e informações de licença aqui--->

![GitHub repo size](https://img.shields.io/github/repo-size/iuricode/README-template?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/iuricode/README-template?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/iuricode/README-template?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/iuricode/README-template?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/iuricode/README-template?style=for-the-badge)

<img src="https://s.tmimgcdn.com/scr/1200x750/57600/hostel-modelo-de-site-html5-de-varias-paginas-de-viagens_57677-2-original.jpg" alt="exemplo imagem">

> Web Application em desenvolvimento para gerenciamente de clientes por parte dos funcionário do Host Sparkling Water


## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:
<!---Estes são apenas requisitos de exemplo. Adicionar, duplicar ou remover conforme necessário--->
#### Tenha instalado:
* WSL (Windows Subsystem for Linux) [for Windows only] :heavy_check_mark:
* docker v20.10.0+ :heavy_check_mark:
* docker-compose v1.29.0+ :heavy_check_mark:
* gnu-make v4.2.0+ :heavy_check_mark:
* JDK 8+ :heavy_check_mark:
* Apache Maven v3+ :heavy_check_mark:

## 🚀 Getting started

Para instalar o hostel-app-gcva, siga estas etapas:

1. Faça download do repositório remoto
```
git clone https://github.com/celso-patiri/hostel-app-gcva.git
```
2. Dentro do diretório em que o repositório foi iniciado, execute na primeira vez (isso inicia os containers mysql e payara-server):
```
make init
```
3. Inicie um connection pool (necessário para que o backend funcione)
```
make set_connection_pool
```
4. Faça o deploy de tudo no Payara Server Docker
```
make deploy_all
```
5. Depois do deploy, tende ver o resultado em: http://localhost:8080/frontend
> #### Observações: 
> 1. A primeira vez tende a ser demorada, pois é necessário download de diversar dependências
> 2. Se estiver em uma distro linux, e houver erro de permissão, tente adicionar `sudo` aos comandos `make`, exemplo:
> 
> Ao invés de:
> 
> `make init`
> 
> Tente: 
> 
> `sudo make init`

## 📫 Contribuindo hostel-app-gcva

<!---Se o seu README for longo ou se você tiver algum processo ou etapas específicas que deseja que os contribuidores sigam, considere a criação de um arquivo CONTRIBUTING.md separado--->
Para contribuir com hostel-app-gcva, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_branch>`
5. Crie a solicitação de pull dentro do GitHub.

Como alternativa, consulte a documentação do GitHub
em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
.

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img width=100 src="https://avatars.githubusercontent.com/u/87735654?v=4" width="100px;" alt="Foto do Iuri Silva no GitHub"/><br>
        <sub>
          <b>Caio Eduardo</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img width=100 src="https://avatars.githubusercontent.com/u/56320155?v=4" width="100px;" alt="Foto do Mark Zuckerberg"/><br>
        <sub>
          <b>Celso Patiri</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img width=100 src="https://avatars.githubusercontent.com/u/94006884?v=4" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Rafael Bittar</b>
        </sub>
      </a>
    </td>
    <td align="center">
          <a href="#">
            <img width=100 src="https://avatars.githubusercontent.com/u/81968354?v=4" width="100px;" alt="Foto do Steve Jobs"/><br>
            <sub>
              <b>Guilherme Gouveia</b>
            </sub>
          </a>
        </td>
    <td align="center">
          <a href="#">
            <img width=100 src="https://avatars.githubusercontent.com/u/61283617?v=4" alt="Foto do Steve Jobs"/><br>
            <sub>
              <b>João Fonseca</b>
            </sub>
          </a>
        </td>
    <td align="center">
          <a href="#">
            <img width=100 src="https://avatars.githubusercontent.com/u/58240821?v=4" width="100px;" alt="Foto do Steve Jobs"/><br>
            <sub>
              <b>Gabriel Pereira</b>
            </sub>
          </a>
        </td>
  </tr>
</table>

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [Ainda não definido](LICENSE.md) para mais detalhes.

[⬆ Voltar ao topo](#nome-do-projeto)<br>
