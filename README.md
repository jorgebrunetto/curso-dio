# Desafio DIO - Criação de Máquina Virtual no Azure

## 📚 Resumo

Este repositório foi criado como parte do desafio da DIO para praticar a criação e configuração de uma máquina virtual (VM) na plataforma Microsoft Azure.

## 🛠️ Tecnologias Utilizadas

- Microsoft Azure
- Portal Azure Web
- Git e GitHub
- Markdown

## 📝 Passo a Passo da Criação da Máquina Virtual

1. **Login no Azure**  
   Acessar o portal do Azure: [https://portal.azure.com](https://portal.azure.com)

2. **Criar um novo recurso**  
   - Clicar em "**Criar um recurso**"
   - Escolher "**Máquina Virtual**"

3. **Configuração básica da VM**  
   - **Nome da máquina**: `exemplo-vm`
   - **Região**: Escolher a mais próxima (Ex: South Brazil)
   - **Imagem**: Windows Server 2019 ou Ubuntu 20.04
   - **Tipo de Tamanho**: Padrão B1s ou conforme a necessidade
   - **Usuário e senha**: Definir

4. **Configuração de rede**  
   - Criar nova **Rede Virtual** (se necessário)
   - Deixar regras de firewall abertas para RDP ou SSH (dependendo do sistema operacional)

5. **Revisar e criar**  
   - Revisar as configurações
   - Clicar em "**Criar**"

6. **Acessar a VM**  
   - Pelo IP público fornecido
   - Usar RDP (Windows) ou SSH (Linux)

## 💡 Dicas Importantes

- Sempre selecione a **região mais próxima** para menor latência.
- Use **naming convention** para organizar recursos (ex: `vm-dev-01`).
- Configure o **auto shutdown** para não gastar créditos desnecessariamente.
- Crie **grupos de recursos** específicos para manter tudo organizado.
- Tire **prints de tela** de cada etapa para documentação e provas de execução.

## 📷 Prints (opcional)

As imagens do processo estão disponíveis na pasta `/images`.

## 📖 Documentação Oficial

- [Criar uma máquina virtual do Windows no Portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [Documentação do GitHub](https://docs.github.com/pt)
- [Guia de Markdown GitHub](https://docs.github.com/pt/github/writing-on-github/getting-started-with-writing-and-formatting-on-github)

---

> Projeto criado como parte do desafio de formação da DIO.
