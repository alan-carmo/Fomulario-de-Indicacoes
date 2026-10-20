# Formulário Digital: Tabela de Indicações para o Comitê

## 💻 Tecnologias Utilizadas
Este formulário digital foi desenvolvido de forma nativa utilizando as seguintes tecnologias web:
- **HTML5**: Para a estruturação semântica de todo o conteúdo, formulários e tabelas.
- **CSS3**: Para a estilização visual, utilizando recursos modernos como variáveis (`:root`), layouts responsivos, e um design limpo e intuitivo.
- **JavaScript (Vanilla JS)**: Para toda a lógica de funcionamento, interatividade, validação de campos, ordenação, atalhos de teclado e persistência de dados.
- **Bibliotecas de Exportação**: Utiliza `jsPDF` e `jsPDF-AutoTable` para a funcionalidade de geração de relatórios em PDF.

## 🎯 O que ele faz?
Este sistema é uma ferramenta interativa e dinâmica projetada para gerenciar as indicações de funcionários. Suas principais funcionalidades incluem:
- **Preenchimento Estruturado**: Permite a inserção de dados de colaboradores (matrícula, nome, cargo, setor, avaliações, etc.) de forma organizada em uma tabela.
- **Validação de Dados**: Garante que campos críticos sejam preenchidos antes de qualquer exportação, evitando envios incompletos.
- **Gestão e Ordenação**: Possui um sistema de ordenação avançada (multi-nível) para organizar as indicações conforme a necessidade.
- **Exportação Multiformato**: Permite exportar os dados consolidados para PDF (pronto para impressão ou envio) e para CSV (editável no Excel).
- **Recursos Avançados**: Conta com salvamento automático, envio direto para e-mail integrado e atalhos de teclado para produtividade.

## 🚀 Por que foi criado?
O principal motivo para a criação deste formulário digital foi a **padronização das informações**.

O formulário foi desenvolvido para estruturar os dados que são necessários para imputar ao **comitê diretivo**. Anteriormente, sempre que eram enviadas solicitações de promoções ou transferências de colaboradores, elas chegavam frequentemente com **informações faltantes e/ou divergentes**. Isso causava atrasos, retrabalho e ruídos na comunicação. 

Com a implementação desta ferramenta, o processo passa a ser guiado, garantindo que todas as solicitações cheguem ao comitê de forma íntegra, padronizada e com todos os dados essenciais para a tomada de decisão.

## 🔌 Por que em um único arquivo?
O motivo de toda a aplicação (estrutura, estilos e lógica) ter sido compilada em **um único arquivo** foi justamente para **não depender do uso de internet**.

Ao ter tudo contido em apenas um arquivo local, os gestores e responsáveis podem abrir o formulário em qualquer computador da rede interna usando apenas o navegador padrão, sem precisar de instalações adicionais, hospedagem em servidores web ou de uma conexão ativa com a internet para preencher e validar as indicações do dia a dia.
