# Desafio Dio - Rodando sua aplicação Java no Kubernetes Do deploy ao debug sem medo!



Neste projeto você terá o desafio  Construir um ambiente Kubernetes local para aprender a tecnologia sem medo de errar. Criar os recursos necessários para executar uma aplicação Java, bem como entender como fazer o deploy, o debug e a escalabilidade da aplicação. Construir um ambiente **Kubernetes** local para que criar os recursos necessários para fazer o **deploy** no cluster e configurar nossa aplicação a fim de fazer debug enquanto ela está rodando no Kubernetes.



###  Rodar a aplicação local
---

Há alguns scripts que podem ajudar na instalação das ferramentas de desenvolvimento: `https://github.com/sandrogiacom/k8s`.

### **Construindo a aplicação**

```bash
$ cd java-kubernetes
$ mvn clean install
```

**Iniciando o banco de dados**
```bash
$ make run-db
```

**Executando a aplicação**
```bash
$ java --enable-preview -jar target/java-kubernetes.jar
```

Após executar o comando acima, os seguintes endereços da API estarão disponíveis:
```
http://localhost:8080/app/users

http://localhost:8080/app/hello
```



Rodando sua aplicação Java no Kubernetes. Do deploy ao debug sem medo



### **DEFININDO:**

- Estruturando o Projeto

- **DOCUMENTANDO (DOCUMENTAÇÃO)**

- Definindo Modelos, Serviços e Lógica de Negócios

- Integrando e Testando

  

## **Descrição**

O sistema desenvolvido neste projeto é um ambiente Kubernetes local que permite aos desenvolvedores rodar suas aplicações Java sem medo de errar. O sistema inclui os seguintes recursos:

- Um cluster Kubernetes local criado usando o minikube
- Um namespace para a aplicação
- Um deployment para a aplicação
- Um service para a aplicação
- Um pod para o debugger
- Documentação sobre como usar o sistema

O sistema é fácil de usar e pode ser personalizado para atender às necessidades específicas de cada projeto.



## **Requisitos:**

- Docker

- Kubernetes

- Maven

- IntelliJ IDEA

- MySQL;

- Kubernetes (minikube e kubectl).

  

## **Implementação:**

1. Crie um cluster Kubernetes local usando o minikube.
2. Crie um namespace para sua aplicação.
3. Crie um deployment para sua aplicação.
4. Crie um service para sua aplicação.
5. Faça o deploy da sua aplicação.
6. Faça o debug da sua aplicação.
7. Escale a sua aplicação.



## Documentação

Este guia fornece um guia passo a passo abrangente sobre como implantar e depurar uma aplicação Java no Kubernetes. Ao seguir as etapas descritas neste guia, você poderá implantar e depurar sua aplicação com confiança.

**Apêndice**

O apêndice contém informações adicionais sobre os seguintes tópicos:

- Recursos do Kubernetes

- Comandos do Docker

- Ferramentas de depuraçã

  

## **Aprendizado:**

O desenvolvimento deste projeto proporcionará um aprendizado valioso sobre os seguintes tópicos:

- Como projetar e implementar um sistema de software em Kubernetes
- Como usar as tecnologias Java, Docker e Kubernetes
- Como testar e depurar um sistema de software em Kubernetes



## **Conclusão:**

Este projeto é uma ótima maneira de aprender sobre Kubernetes e como rodar aplicações Java nele. O sistema desenvolvido é fácil de usar e pode ser personalizado para atender às necessidades específicas de cada projeto. Este guia fornece um guia passo a passo abrangente sobre como implantar e depurar uma aplicação Java no Kubernetes. Ao seguir as etapas descritas neste guia, você poderá implantar e depurar sua aplicação com confiança.



## **Aplicabilidade prática:**

O sistema desenvolvido neste projeto pode ser usado para rodar qualquer aplicação Java em Kubernetes. Isso permite que os desenvolvedores implantem e gerenciem suas aplicações de forma mais eficiente e escalável. Construir um ambiente Kubernetes local para que os desenvolvedores possam aprender a tecnologia sem medo de errar.  É oprtunidade  de criar os recursos necessários para executar uma aplicação Java, bem como entender como fazer o deploy, o debug e a escalabilidade da aplicação.   

