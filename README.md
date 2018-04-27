Comandos Linux

ls - lista
ls -al - Lista arquivo oculto.
clear - limpa a tela.
mkdir - criaq pasta
cd nomedapasta - entra no diretorio
cd .. - sai da pasta
rm -r nomedapasta - deleta o diretório
touch - cria arquivo
cp - copia a pasta ou diretório
mv - move o arquivos e pastas para o diretório
pwd - mostra o caminho atual
echo - escreve dentro do arquivo
cat nomedoarquivo - mostra o que dentro do arquivo

Comandos Git

git config --global http.proxy http://10.1.118.254:3128 - permissão de proxy para usar no Senai.


git init - inicia o repositório
git status - verifiar arquivos não comitados
git add - adiciona arquivo para comitar
git commit -m - "
git remote add origin https://github.com/Jailsondsouza/comando_basico.git aponta para o arquivo externo
git push -u - envia o arquivo para o master
git diff nomedoarquivo - mostra as modificações do arquivo

Comandos Rails 
rails new blog
cd blog

rails g controller Home index about

rails g scaffold Post title:string body:text

rails generate devise User

rails destroy devise:views
rails generate devise:views users
rake db:migrate
rake db:migrate
rake routes
rails g migration AddNameToUsers name:string "Corrige banco de dados"

Comandos Git 
git status
git checkout config/secrets.yml
git checkout config/database.yml

Vamos criar uma nova branch para desenvolvimento
git checkout -B  dev 
git branch - lista as branchs 
git push origin dev 
git config --global http.proxy http://10.1.118.254:3128    →  Acesso do proxy



Comandos Linux 

touch app/views/layouts/_header.html.erb

Comando Extras
@set PATH=C:\RailsInstaller\Ruby2.2.0\bin;%PATH%
set http_proxy=http://10.1.118.254:3128




Comando do Projeto:
rails new app-game
