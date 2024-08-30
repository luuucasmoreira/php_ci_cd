# php_ci_cd
Estudos de Pipeline CI/CD
Foco desse projeto é treinar o fluxo basico de uma pipeline.

Inicialmente utilizaremos as seguintes tecnologia
PHP
Nginx
MariaDB
Docker
Jenkins

Fluxo
 *Push em QA
 *Jenkins - Build
 *Jenkins - Test
 *Jenkins - atualiza o GIT em QA
 *Testou em QA Manualmente, Merge no Main (produção)
 *Jenkins atualiza o MAIN passando novamente por outro teste
 *Deploy em Produção
