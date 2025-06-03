# 💰 Conversor de Moedas (Console)

<div align="center">
  <h3>Transformando valores monetários com a agilidade do Java e APIs em tempo real!</h3>
</div>

## Badges

![Java](https://img.shields.io/badge/Java-Orientado%20a%20Objetos-007396?logo=java&logoColor=white)
![GSON](https://img.shields.io/badge/GSON-JSON%20Parsing-E05B44?logo=json&logoColor=white)
![REST API](https://img.shields.io/badge/API%20REST-Integração-007ACC?logo=openjdk&logoColor=white)
![Terminal](https://img.shields.io/badge/Terminal-Interface%20Console-4D4D4D?logo=powershell&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=flat)

---

## Descrição do Projeto

Este projeto é um **Conversor de Moedas** desenvolvido em **Java**, focado na interação via console. Ele permite ao usuário converter valores entre diferentes moedas com base em cotações **em tempo real**, obtidas através de uma API externa.

Criado como parte de um desafio prático de back-end, este programa demonstra o uso de conceitos fundamentais de Java, como:

* **Consumo de APIs RESTful**: Integração com serviços externos para obter dados dinâmicos.
* **Processamento de JSON**: Utilização da biblioteca `GSON` para desserializar respostas da API.
* **Tratamento de Exceções**: Robustez na manipulação de erros de entrada e falhas de rede.
* **Estruturas de Controle**: Loops e condicionais para navegação no menu e lógica de conversão.

---

## Funcionalidades

O conversor oferece um menu interativo no console com as seguintes opções de conversão:

* Dólar (USD) ➡️ Real (BRL)
* Real (BRL) ➡️ Dólar (USD)
* Euro (EUR) ➡️ Real (BRL)
* Real (BRL) ➡️ Euro (EUR)
* Libra Esterlina (GBP) ➡️ Real (BRL)
* Real (BRL) ➡️ Libra Esterlina (GBP)
* Opção para sair do programa

Após a seleção da moeda, o usuário informa o valor a ser convertido e o programa exibe o resultado final com a cotação atualizada.

---

## Tecnologias Utilizadas

* **Java 11+**: Linguagem de programação principal.
* **Exchange Rate API**: API gratuita para obter taxas de câmbio em tempo real.
* **GSON**: Biblioteca Java para serialização/desserialização de objetos Java para/de JSON.
* **Java HTTP Client**: Módulo `java.net.http` para realizar requisições HTTP.

---

## Como Configurar e Rodar

Siga estes passos para ter o projeto funcionando em sua máquina:

### Pré-requisitos

* **Java Development Kit (JDK) 11 ou superior** instalado.
* Uma IDE Java (como **IntelliJ IDEA**, Eclipse ou VS Code com extensões Java).
* Uma **chave de API** da [Exchange Rate API](https://www.exchangerate-api.com/). Cadastre-se no site para obter sua chave gratuita.

### Instalação e Execução

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO/NomeDoSeuRepositorio.git](https://github.com/SEU_USUARIO/NomeDoSeuRepositorio.git)
    cd NomeDoSeuRepositorio
    ```
    (Lembre-se de substituir `SEU_USUARIO` e `NomeDoSeuRepositorio` pelo seu próprio nome de usuário e nome do repositório no GitHub.)

2.  **Adicione a Biblioteca GSON:**
    * Baixe o arquivo `gson-X.Y.Z.jar` (onde X.Y.Z é a versão mais recente) em [Maven Central Repository - GSON](https://mvnrepository.com/artifact/com.google.code.gson/gson).
    * No IntelliJ IDEA: Vá em `File > Project Structure... > Libraries`. Clique no `+` e adicione o JAR baixado.

3.  **Configure a Chave da API:**
    * Abra o arquivo `src/Main.java`.
    * Encontre a linha:
        ```java
        private static final String API_KEY = "SUA_CHAVE_AQUI";
        ```
    * **Substitua `"SUA_CHAVE_AQUI"` pela sua chave real da Exchange Rate API.**

4.  **Execute o Programa:**
    * **Via IDE (IntelliJ IDEA):** Abra `src/Main.java`, clique no ícone de "play" verde ao lado do método `main` e selecione "Run 'Main'".
    * **Via Terminal (após build do JAR):**
        ```bash
        # Navegue até a pasta 'out/artifacts/ConversorDeMoedasAPI_jar/' (ou similar)
        java -jar ConversorDeMoedasAPI.jar
        ```

---

## Próximos Passos (Possíveis Evoluções)

* **Interface Gráfica (GUI):** Implementar uma interface mais amigável usando JavaFX ou Swing.
* **Histórico de Conversões:** Armazenar e exibir as últimas conversões realizadas.
* **Log de Operações:** Registrar as conversões em um arquivo de log com data e hora.
* **Mais Moedas:** Expandir o menu para incluir outras moedas suportadas pela API.
* **Criação de Executável (JAR):** Empacotar a aplicação em um arquivo JAR executável para distribuição.

---

## Contribuições

Sinta-se à vontade para explorar, testar e sugerir melhorias! Se encontrar algum problema ou tiver uma ideia de funcionalidade, abra uma [Issue](https://github.com/SEU_USUARIO/NomeDoSeuRepositorio/issues) ou envie um [Pull Request](https://github.com/SEU_USUARIO/NomeDoSeuRepositorio/pulls).

---

## Desenvolvedor

**Amaro Netto**
* [Amaro Netto](https://www.linkedin.com/in/amaro-netto) (Desenvolvedor Principal)

---

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
