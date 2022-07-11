## **Visão Geral**

O **java-spring-webflux-template** adiciona em uma stack a capacidade de provisionar serviços rest reativos utilizando **Java** com **Spring Boot** e **Spring Webflux**.


## **Uso**

### **Pré-requisitos**

Para utilizar esse template você precisa utilizar o `CLI` do `StackSpot` que você pode baixar [**aqui**](https://stackspot.com/).
- Java 11 LTS ou superior.


### **Instalação**
Para fazer o download do **java-spring-webflux-template**, siga os passos abaixo:

**Passo 1.** Copie e cole a URL abaixo no seu navegador/terminal:
```
https://github.com/community-studio/java-spring-webflux-template.git
```

## **Implementação**

### **Inputs**

Os inputs necessários para utilizar o template são:  

| **Campo** | **Valor** | **Descrição** |
| :--- | :--- | :--- |
| group_id| ex.: com.stackspot | Group id |
| artifact_id| ex.: my-demo-app | Artifact id |


Os inputs opcionais para utilizar o template são:

| **Campo** | **Valor** | **Descrição** |
| :--- | :--- | :--- |
| versao_java| default: 11 | Versão do Java  |
| versao_spring_boot| default: 2.7.1 | Versão Spring Boot  |
| nome_projeto| ex.: My Project | Nome do projeto |
| version | ex.: 0.0.1-SNAPSHOT | Versão |
| descricao_projeto | ex.: A simple demo | Descricao do projeto |


## Execução do projeto criado

Após criar o projeto, acesse o diretório em que foi criado e execute o seguinte comando:

Para realizar a compilação do projeto, execute o comando abaixo:

```bash
    ./mvnw package
```

Realize a execução dos testes unitários e de integração. Execute o seguinte comando:

```bash
    ./mvnw test
```

Para executar a aplicação em modo dev, execute o seguinte comando:

```bash
    ./mvnw spring-boot:run
```

