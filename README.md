COMANDOS GIT

- git init (iniciar um projeto git)
- git status (verificar os arquivos ja adicionados)
- git add . (deixar todos os arquivos prontos para o git)
- git commit -m "" (commitar e adicionar mensagem nos "")
- git branch -M main (criar uma branch main)
- git remote add origin <LINK> (referenciar qual repositório remoto irá o seu projeto)
- git push -u origin main (para subir todos os arquivos adicionados a branch main)
- git config --local user.name <NOME> (adicionar o user name ao seu projeto)
- git config --local user.email <EMAIL> (adicionar o email do seu git remoto no projeto)
- git clone --branch <LINK DA BRANCH PARA BAIXAR> (para baixar o projeto do git remoto para seu local)
- git checkout -b <NOME BRANCH NOVA> (para criar uma nova branch)
- git branch -m novo-nome-do-branch (renomear a branch atual)
- git branch -m nome-antigo-do-branch novo-nome-do-branch (renomear uma branch diferente da atual)
- git fetch (atualiza os dadaos do repositório remoto)
- docker-compose -f devops/docker-compose-mysql.yaml up -d
- docker ps -a (status dos conteiners)
- docker stop (parar o conteiner)
- mvn package -DskipTests (empacota meu projeto java, arquivo .war) 
- mvn -U clean install -DskipTests
- sh deploy-dev.sh (fazer um deploy)

glpat--UmAE6Z4q8WHsmJ8WKgZ

sgts-datasource = ddl auto update
___________________________________________________________________________________________________________

- java 8 zulu
- maven 3.6.0

MXbK56wcZ_CP!NB^-UJk4U6DpAeHe%*y

___________________________________________________________________________________________________________

## NOVA INFRA LOCAL
s3.accesskey=AKIA3TQUHNH7M7IPXLXZ
s3.secret       key=OBGLQkgFPBr                  khyreQiWyJ5c5wsB5Qn1m+JCtXG46
s3.domain=https://portal-parcerias-dev-piracicaba.s3.us-east-1.amazonaws.com
s3.bucket=portal-parcerias-dev-piracicaba
s3.region=us-east-1
api.arquivos.baseurl=http://localhost:8081/api-arquivos
api.arquivos.files=/files
api.arquivos.upload=/upload
api.arquivos.download=/download
api.arquivos.show=/show
api.arquivos.zip=/zip
app.address=http://localhost:8080/sgts
db.name=entidadesonline
jdbc.c3p0.jdbcUrl=jdbc:mysql://localhost:3306/entidadesonline?autoreconnect=true&useUnicode=true&characterEncoding=UTF-8
jdbc.c3p0.user=root
jdbc.c3p0.password=MXbK56wcZ_CP!NB^-UJk4U6DpAeHe%*y

Evoc@inova@1910
___________________________________________________________________________________________________________
TOMCAT VM options
-Duser.language=pt
-Duser.country=BR
-Ddb.name=entidadesonline
-Drds.instance=localhost
-Dapp.address=http://localhost:8080/demo_portaldasparcerias_war_exploded
-Djdbc.c3p0.user=root
-Djdbc.c3p0.password=MXbK56wcZ_CP!NB^-UJk4U6DpAeHe%*y
-Ds3.bucket=portal-parcerias-dev-piracicaba
-Ds3.accesskey=AKIA3TQUHNH7M7IPXLXZ
-Ds3.secret         key=OBGLQkgFPBrkhyreQiWyJ5c5        wsB5Qn1m+JCtXG46
-Ds3.region=us-east-1
-Dapi.arquivos.baseurl=http://localhost:8081/api-arquivos
