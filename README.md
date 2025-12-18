# pousadinha-thymeleaf
Aplicação exemplo para gerenciar uma pousada, construída com Spring Boot e Thymeleaf.

**Descrição:**
- Projeto demonstrativo para estudo e desenvolvimento de um sistema simples de gestão de pousada (reservas, quartos, clientes), usando Java 21, Spring Boot e Thymeleaf.

**Tecnologias**
- Java 21
- Spring Boot
- Thymeleaf
- Maven
- (Opcional) Eclipse / Spring Tools Suite

**Requisitos**
- Java 21 instalado
- Maven 3.8+
- Eclipse com suporte a Maven (m2e) ou outra IDE compatível

**Como executar (local)**
1. Importar como projeto Maven na sua IDE (Eclipse: File > Import > Existing Maven Projects).
2. Ajustar a JDK do projeto para Java 21.
3. Rodar a aplicação pela classe `main` do Spring Boot (ex: `Application`) ou via terminal:

```bash
mvn spring-boot:run
```

4. Acesse: http://localhost:8080

**Build e execução do artefato**

```bash
mvn clean package
java -jar target/*.jar
```

**Testes**

```bash
mvn test
```

**Instruções rápidas para GitHub Codespaces**
- Abra o repositório no Codespaces (GitHub → Code → Open with Codespaces).
- Certifique-se que o ambiente use Java 21 (configurar `devcontainer.json` se necessário).
- No terminal do Codespace execute `mvn spring-boot:run` e exponha a porta 8080.

**Importar no Eclipse**
- File > Import > Maven > Existing Maven Projects > selecione a raiz do repositório.
- Ajuste a JRE do projeto para Java 21 em `Project > Properties > Java Build Path`.

**Contribuindo**
- Faça forks e branches com nomes descritivos, abra pull requests para `main`.

**Licença**
- Este repositório serve para estudo. Adicione uma licença se desejar colaborar formalmente.
