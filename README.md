<h1>Bookstore Website</h1>

<p>Repositório destinado ao estudo de PHP para aplicações web.
     O foco desse repositório a princípio foi o de desenvolver 
     um e-commerce de uma livraria. Dessa maneira o php foi utilizado 
     com o auxílio do composer, que é a nova maneira de realizar projetos em php. </p>

<p>
    Alguns links úteis:
    <ul>
        <li><a href="https://getcomposer.org/">https://getcomposer.org/</a></li>
        <li><a href="https://github.com/feulf/raintpl">https://github.com/feulf/raintpl</a></li>
        <li><a href="https://github.com/PHPMailer/PHPMailer">https://github.com/PHPMailer/PHPMailer</a></li>
        <li><a href="http://www.slimframework.com/">http://www.slimframework.com/</a></li>
        <li><a href="https://www.digitalocean.com/community/tutorials/como-instalar-o-mysql-no-ubuntu-18-04-pt">https://www.digitalocean.com/community/tutorials/como-instalar-o-mysql-no-ubuntu-18-04-pt</a></li>
        <li><a href="https://chartio.com/resources/tutorials/how-to-grant-all-privileges-on-a-database-in-mysql/">https://chartio.com/resources/tutorials/how-to-grant-all-privileges-on-a-database-in-mysql/</a></li>
        <li><a href="https://www.digitalocean.com/community/tutorials/como-criar-um-novo-usuario-e-conceder-permissoes-no-mysql-pt">https://www.digitalocean.com/community/tutorials/como-criar-um-novo-usuario-e-conceder-permissoes-no-mysql-pt</a></li>
    </ul>
</p>

<h3>Aparência da home</h3>

<img src="imgs/fig1.png">
<img src="imgs/fig2.png">

<h3>Organização da base de dados</h3>

<img src="imgs/fig3.png">

<h3> Algumas instruções...</h3>

<p><b>1-Composer</b>:</p>
<p> Três códigos importantes</p>
<p><code>composer install</code></p>
<p><code>composer dump-autoload</code></p>
<p><code>composer update</code></p>

<p><b>2-Mysql connection</b></p>
<p>Para instalar e conectar um usuário ao mysql</p>
<p><code>sudo apt update</code></p>
<p><code>sudo apt install mysql-server</code></p>
<p><code>mysql_secure_installation</code></p>
<p><code>sudo mysql -u root -p</code></p>
<p><code>USE mysql;</code></p>
<p><code>CREATE USER 'novousuario'@'localhost' IDENTIFIED BY 'password';</code></p>
<p><code>GRANT ALL PRIVILEGES ON * . * TO 'novousuario'@'localhost';</code></p>
<p><code>FLUSH PRIVILEGES;</code></p>

<p><b>3-Start no Xampp</b></p>
<p>Primeiro acesse o terminal linux e escreva</p>
<p><code>cd /opt/lampp</code></p>
<p><code>ls</code></p>
<p><code>sudo ./manager-linux-x64.run</code></p>

<p>OBS: não se esqueça de verificar as portas. 
    O MySQL costuma rodar na porta 3306. 
    Se existir outra instância nessa porta ele pode gerar erro. 
    Neste caso direcione para outra porta, por exemplo a 3307.</p>






