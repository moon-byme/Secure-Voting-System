# Minha contribuição para o Sistema de Votação Seguro

Este repositório é um **fork** do projeto desenvolvido em equipe, onde atuei como desenvolvedora Backend. O objetivo principal foi criar um sistema de eleições com garantia de segurança, integridade e sigilo dos votos utilizando Java e Spring Boot.

## 🎯 Meu Foco e Responsabilidades
Neste projeto, minha atuação foi concentrada no **Backend e infraestrutura Spring Boot**, com destaque para:
* **Cadastro e Autenticação de Usuários:** Implementação de fluxos para eleitores e administradores.
* **Segurança e Criptografia:** Integração do **BCrypt** para proteção de credenciais e hash de senhas.
* **Gestão de Votações:** Desenvolvimento da lógica para criação, gerenciamento e registro de votos.
* **Arquitetura:** Estruturação inicial do projeto e integração de dependências via Maven.

---

## 📑 Sobre o Projeto Geral

Este sistema visa simular uma urna eletrônica com foco total em segurança avançada.

### Objetivos
* Votação segura e simples.
* Proteção criptográfica completa (votos e senhas).
* Simulação de urna eletrônica auditável e transparente.

### 🛠️ Tecnologias e Ferramentas

| Categoria | Tecnologia | Versão | Propósito |
| :--- | :--- | :--- | :--- |
| **Linguagem** | Java | 21 | Linguagem principal |
| **Framework** | Spring Boot | 3.x | Backend e Injeção de Dependência |
| **Interface** | JavaFX | 21.0.2 | Interface Desktop nativa |
| **Banco de Dados** | MySQL | - | Persistência de dados |
| **Segurança** | BCrypt / AES-256 | - | Criptografia e Integridade |
| **Utilitários** | Lombok / Maven | - | Produtividade e Gestão |

### 🔒 Estratégia de Segurança
1. **Confidencialidade (AES-256):** Protege o sigilo dos resultados parciais diretamente no banco de dados.
2. **Integridade (HMAC-SHA256):** Garante que o registro do voto não foi modificado através de um selo único.
3. **Autenticação (BCrypt):** Protege as credenciais de acesso contra vazamentos.

### 🚀 Como Executar
1. Certifique-se de usar o **JDK 21 LTS**.
2. Gere as chaves utilizando a classe `KeyGenerator` no pacote `Util`.
3. Configure as chaves e o banco de dados no arquivo `application.properties`.
4. Para detalhes de banco e interface, consulte o arquivo `SETUP.MD`.
5. Execute a classe `ExecutorSistemaVotacaoApplication`.

---

### 👥 Autores e Colaboradores
Projeto desenvolvido em equipe por:
* [@georiSamuel](https://github.com/georiSamuel) (Lead/Original)
* [@Horlanlacerda](https://github.com/Horlanlacerda)
* [@moon-byme](https://github.com/moon-byme) (Backend & Security)
* [@SuelleMaciel](https://github.com/SuelleMaciel)
