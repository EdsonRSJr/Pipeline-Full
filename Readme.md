Projeto para validação do processo completo de CICD contemplando:
 - Build da imagem
 - Upload
 - Scan de vuln da Imagem
 - Preparação do ambiente K8S
 - Scan de vuln da Aplicação

Variaveis denifidas:
 - DOCKERHUB_USERNAME

Secrets definidas:
 - Tenable_ACCESS_KEY
 - Tenable_SECRET_KEY
 - AWS_ACCESS_KEY_ID
 - AWS_SECRET_ACCESS_KEY
 - DOCKERHUB_TOKEN