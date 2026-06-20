# 📊 Projeto: Dashboard de Análise Comercial e Performance de Vendas

## 🎯 1. Contexto de Negócio
A diretoria da empresa fictícia "TechStore" identificou uma queda nas margens de lucro no último trimestre, mas não conseguia mapear visualmente quais categorias de produtos ou regiões estavam gerando mais custos de frete e devoluções. O objetivo deste projeto foi centralizar os dados dispersos para facilitar a tomada de decisão.

## 🛠️ 2. Ferramentas Utilizadas
* **Coleta e Tratamento:** Google Planilhas (funções PROCV, QUERY e tabelas dinâmicas)
* **Visualização de Dados (BI):** Looker Studio
* **Metodologia:** Criação de KPIs de Faturamento, Ticket Médio e Margem Líquida.

## 🔀 3. Processo de ETL (Extração, Transformação e Limpeza)
Os dados brutos apresentavam inconsistências que foram tratadas diretamente na fonte antes da integração com o Looker Studio:
* Remoção de registros duplicados e valores nulos na coluna de ID do cliente.
* Padronização do formato de datas (DD/MM/AAAA).
* Criação de uma coluna calculada para determinar a margem de lucro por produto.

## 💡 4. Principais Insights Gerados
* **Gargalo Logístico:** A região Nordeste apresentou o maior faturamento, porém a margem líquida foi espremida pelo custo do frete, indicando a necessidade de buscar novos parceiros de logística na região.
* **Sazonalidade:** Identificou-se um pico de vendas recorrente nas duas primeiras semanas de cada mês, permitindo ao setor de compras planejar melhor o estoque.

## 📈 5. Visualização do Dashboard
* 🔗 **[Clique aqui para acessar o Dashboard Interativo em Tela Cheia](COLE_AQUI_O_LINK_DE_COMPARTILHAMENTO_DO_SEU_DASHBOARD)**

### 🧠 Como esse novo código funciona e o que mudou?

1. **Os Botões de Filtro (`<button>`)**: Adicionei uma barra com os temas que você sugeriu. Cada botão chama uma função rápida em JavaScript chamada `filtrarProjetos('nome-do-tema')`.
2. **Atributo de Identificação (`data-categoria`)**: Dentro de cada Card de projeto, se você reparar nas linhas dos códigos, há uma marcação como `data-categoria="administracao"` ou `data-categoria="financas economia"`. O script lê essa marcação para saber o que esconder e o que mostrar quando o botão correspondente for clicado.
3. **Organização das Visualizações**: 
   * No **Projeto 1**, o espaço está limpo e preparado para carregar o Looker Studio dentro da janela (`<iframe>`).
   * No **Projeto 2**, o código foi corrigido: ele carrega de forma limpa a imagem do painel financeiro enviado por você no seu layout e oferece dois botões organizados — um para ler a documentação técnica no seu GitHub e outro para abrir o Power BI em tela cheia (solução perfeita para quem acessa via celular).

### 🚀 O que fazer agora?

1. Vá no seu repositório principal do GitHub, edite seu arquivo `index.html` e cole o código acima.
2. Salve clicando em **Commit changes**.
3. Aguarde um minuto, abra o link do seu site e teste clicar nos botões de filtros ("Administração", "Finanças", etc.) para ver a interatividade funcionando perfeitamente.

Quer que eu te mostre como adicionar um **terceiro projeto fictício focado em Economia** na estrutura do código para você ver como a grade de projetos se comporta em telas maiores?




---
💼 **Contato:**
* LinkedIn: [Seu Nome](COLE_LINK_DO_SEU_LINKEDIN_AQUI)
* E-mail: seu-email@exemplo.com
