# Atividade-Semana-2

# Relatório Técnico - Configuração de EC2 na AWS

## Introdução
Este relatório detalha a configuração de uma instância EC2 na AWS e sua conexão via SSH. O processo foi documentado usando commits no GitHub.

## Objetivo
O propósito deste relatório é demonstrar o processo de criação, configuração e acesso a uma máquina EC2, demonstrando o conhecimento do uso do SSH.

## Materiais
- Conta AWS
- PuTTY (SSH)
- Git e GitHub

## Método Chave PEM

1. Entrar no AWS Academy
2. Clicar nos seguintes hiperlinks dentro da AWS Academy: Cursos -> AWS Academy Learner Lab -> Módulos -> Laboratório de Aprendizagem 
3. Dentro do laboratório, iniciar o o laboratório através do hiperlink "Start Lab" e aguardar iniciar o console da AWS
4. Acesso ao console da AWS e inicio de configuração de uma instância EC2.
5. Configurei as opções de segurança, tipo de instância e outras configurações relevantes.
6. Criação de uma chave pem
7. Iniciar conexão SSH através do comando "ssh -i "chavasemana2.pem" ec2-54-234-15-12.compute-1.amazonaws.com", utilizando o "DNS IPv4 público" fornecido pela AWS


## Resultados (Metódo chave PEM)


### Criação da Instância EC2
![Alt text](image-1.png) 
![Alt text](image-3.png) 
![Alt text](image-4.png) 
![Alt text](image-5.png)  
![Alt text](image.png) 

### Criando chaves com IP 
![Alt text](image-7.png) 

### Iniciando AWS
![Alt text](image-8.png) 

### Criando chave pem
![Alt text](image-9.png) 

### Chave pem criada
![Alt text](image-10.png) 

### Print do powershell para mostrar que estou no mesmo diretório da chave
![Alt text](image-11.png) 

### Tentativa de criação com chave pem negada por falta de permissão
![Alt text](image-12.png) 

Não foi possível iniciar a comunicação, não estou com acesso liberado e não sei o motivo. Talvez um dos motivos seja o fato de que estou com o computador do Inteli emprestado e posso ter alguma permissão mais restrita. Porém, realizei o mesmo procedimentos que meus colegar e tive resultados diferentes.

## Método Chave PPK
1. Download Putty


## Resultados (Metódo chave PPK)

### Download Putty
![Alt text](image-6.png) 

### Criação chave ppk

![Alt text](image-13.png)

### Criação instânicia com chave ppk

![Alt text](image-14.png)

### Configuração Putty

![Alt text](image-15.png)

### Configuração Putty

![Alt text](image-16.png)

### Resultado prompt de comando

![Alt text](image-17.png)

Não foi possível iniciar a comunicação, não consegui fazer a transformação da chave não sei por quais motivos.
---



