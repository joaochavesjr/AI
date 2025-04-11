## Laboratório DIO - Azure Cognitive Search
### Utilizando AI Search para indexação e consulta de dados

- Objetivo é avaliar o atendimento de todas as lojas de uma rede de café

-> Dica: Excluir todos os recursos criados na Nuvem depois de finalizar o laboratório.

- Inicialmente serão criados 3 recursos no Azure:

1 - AI Search:

    - Selecionar assinatura;
    - Selecionar o nome do resource group;
    - Definir uma nome de serviço exclusivo;
    - Location EAST US;
    - Selecionar nível básico (pricing tier);
    - Review + Create.
    
2 - Azure AI services:

    - Selecionar assinatura;
    - Selecionar o nome do resource group;
    - Definir uma nome de serviço exclusivo;
    - Location EAST US;
    - Pricing tier: Standard S0;
    - Review + Create.
    
3 - Conta de Armazenamento:

    - Selecionar assinatura;
    - Selecionar o nome do resource group;
    - Nome da conta de armazenamento (único de 3 a 24 caracteres);
    - Location EAST US;
    - Performance: Standard Recommended for most scenarios (conta propósito geral v2);
    - Redundancy: Local-redundant storage (LRS);
    - Review + Create.
    
    Após a criação do recurso é necessário ajustar uma configuração de segurança:
    - Allow Block anonymous access -> Enable
    
    Salvar as alterações!
    

- Em Data storage, criar um novo container com acesso anônimo de leitura e definir um nome para o container.
- Carregar (utilizando o botão upload) todos os arquivos docx da documentação com os exemplos de revisões.
- Agora no mecanismo de busca, AI Search, ir para a opção de importação de dados e selecionar uma fonte de dados, que no caso, é o container criado anteriormente.
- No Search Explorer, selecionar o index e inserir as expressões de consulta para efetuar as buscas para filtrar as revisões, como localização, sentimento, nomes, palavras-chaves, etc.
    