# Desafio DIO - Criação de Instância de Banco de Dados no Azure

## 📚 Resumo

Este repositório foi criado como parte do desafio da DIO para praticar a configuração de uma instância de Banco de Dados no Microsoft Azure.

## 🛠️ Tecnologias Utilizadas

- Microsoft Azure
- Azure SQL Database / Instância Gerenciada
- Git e GitHub
- Markdown

## 📝 Passo a Passo da Criação da Instância de Banco de Dados

1. **Login no Azure**  
   Acessar o portal do Azure: [https://portal.azure.com](https://portal.azure.com)

2. **Criar um novo recurso**  
   - Clicar em "**Criar um recurso**"
   - Buscar por "**Instância Gerenciada do SQL**" ou "**Banco de Dados SQL**", conforme o desafio.

3. **Configuração básica da instância**  
   - **Nome do servidor**: `exemplo-sql`
   - **Admin Login**: definir usuário administrador
   - **Senha**: definir senha segura
   - **Grupo de recursos**: criar ou selecionar um existente
   - **Região**: selecionar a mais próxima (ex: South Brazil)

4. **Configurações adicionais**  
   - **Escolher plano**: Escalabilidade e performance conforme orçamento.
   - **Configurar acesso**: Liberar IPs que poderão se conectar (inclusive o seu).
   - **Habilitar** ou **desabilitar firewall** conforme necessidade.

5. **Revisar e criar**  
   - Conferir todas as informações.
   - Clicar em "**Criar**".

6. **Conectar à instância**  
   - Usar ferramentas como Azure Data Studio ou SQL Server Management Studio (SSMS).
   - Conectar usando o nome do servidor, login e senha definidos.

## 💡 Dicas Importantes

- **Libere seu IP** no firewall da instância para conseguir conectar.
- **Anote o nome do servidor** na hora da criação (fundamental para conexão).
- **Cuidado com o preço**: escolha performance e armazenamento compatíveis com o uso.
- **Use grupos de recursos** separados para facilitar a organização e possíveis exclusões futuras.
- **Ative backup automático** para segurança dos dados.

## 📷 Prints (opcional)

As imagens do processo estão disponíveis na pasta `/images`.

## 📖 Documentação Oficial

- [Criar uma instância gerenciada do Azure SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/managed-instance-quickstart)
- [Documentação do GitHub](https://docs.github.com/pt)
- [Guia de Markdown GitHub](https://docs.github.com/pt/github/writing-on-github/getting-started-with-writing-and-formatting-on-github)

---

> Projeto criado como parte do desafio de formação da DIO.
