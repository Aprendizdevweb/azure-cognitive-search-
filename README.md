# azure-cognitive-search-

# Configurando uma Pesquisa Cognitiva no Azure

Este guia descreve o processo para configurar uma solução de pesquisa cognitiva no Azure. Ele inclui insights, ferramentas que podem se beneficiar da pesquisa cognitiva e os aprendizados adquiridos durante o processo.

## Passo a Passo para Configurar uma Pesquisa Cognitiva

1. **Criação do Serviço de Pesquisa no Azure**

   - **Acesse o portal do Azure**: [Azure Portal](https://portal.azure.com)
   - **Crie um novo serviço de pesquisa**:
     - No menu esquerdo, selecione "Criar um recurso".
     - Escolha "AI + Machine Learning" e clique em "Azure Cognitive Search".
     - Configure os detalhes, como nome do serviço, assinatura, grupo de recursos e local.
     - Selecione a camada de preços ao configurar o serviço.

2. **Configuração do Índice**

   - Após o serviço de pesquisa ser criado, acesse a página do serviço.
   - Clique em "Índices" no menu do lado esquerdo.
   - Crie um novo índice definindo o esquema do documento. Isso inclui campos como `id`, `conteúdo`, `categoria`, etc.
   - Configure as opções de indexação, como campos pesquisáveis e filtráveis.

3. **Criação e Configuração do Indexador**

   - Vá para a seção "Indexadores" e clique em "Adicionar".
   - Escolha a origem de dados (por exemplo, Azure Blob Storage, SQL Database).
   - Configure o indexador para mapear os dados para o índice criado.
   - Defina a frequência de execução do indexador.

4. **Configuração das Habilidades Cognitivas (opcional)**

   - Use habilidades cognitivas para enriquecer os dados durante a indexação.
   - No menu "Habilidades cognitivas", adicione habilidades como reconhecimento de imagem, tradução de texto, ou extração de entidades.
   - Crie uma skillset que integra essas habilidades ao processo de indexação.

5. **Execução de Consultas e Testes**

   - Utilize a ferramenta de pesquisa dentro do portal para executar consultas de teste.
   - Refine os pedidos de pesquisa ajustando os critérios e utilizando filtros.
   - Verifique os resultados e ajuste o índice conforme necessário.

## Insights e Aprendizados

- **Capacidades de Integração**: Ferramentas de análise de dados, BI e apps podem se beneficiar com esta solução.
- **Escalabilidade**: Ajuste a camada de preços de acordo com suas necessidades de escalabilidade.
- **Versatilidade**: Suporte a dados não estruturados e enriquecimento em várias línguas.
- **Aprendizado**: O processo oferece um aprendizado profundo sobre a manipulação de dados e suas transformações com a IA.

## Ferramentas Beneficiadas

- **Power BI**: Integração fácil para visualizações avançadas.
- **Aplicativos personalizados**: Melhoram a busca interna, como em catálogos de produtos.
- **Sistema de gestão de documentos**: Automatiza a indexação e recuperação de documentos.
