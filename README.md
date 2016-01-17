<h1># OmarDocker</h1>
<h2>Dependencias:</h2>
<p>docker, docker-machine, docker-compose</p>
<h2>Para ejecutar:</h2>
<p>docker-machine create --driver virtualbox dev</p>
<p>eval "$(docker-machine env dev)"</p>
<p>docker-compose up -d</p>
<p># Cuando realizamos cambios en los ficheros ejecutamos</p>
<p>docker-compose build</p>
<p>docker-compose up -d</p>
<p>...</p>
