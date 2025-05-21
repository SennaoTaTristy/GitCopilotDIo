DioGitCopilot
Atividade de versionamento de código e integração com o github copilot.

# Identificador de Bandeira do Cartão de Crédito

## Descrição do Projeto

Este projeto consiste em uma aplicação web simples que identifica a bandeira (bandeira do cartão de crédito) a partir do número do cartão informado pelo usuário. A aplicação analisa os prefixos e o comprimento do número do cartão para determinar se ele é Visa, MasterCard, American Express, Discover, ou se a bandeira não é reconhecida.

O projeto também demonstra o uso do GitHub Copilot para acelerar o desenvolvimento e a capacidade de documentar e apresentar um projeto completo em uma plataforma de versionamento como o GitHub.

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- GitHub para versionamento

---

## Como Executar

1. Clone ou baixe o repositório.
2. Abra o arquivo `index.html` em um navegador web moderno (Chrome, Firefox, Edge, etc.).
3. No campo indicado, digite o número do cartão de crédito.
4. Clique no botão **Identificar**.
5. O nome da bandeira do cartão será exibido junto com o ícone correspondente.

---

## Funcionamento

- O sistema remove todos os caracteres que não são números do input.
- Verifica o comprimento do número e o prefixo (BIN).
- Compara com os padrões conhecidos das bandeiras Visa, MasterCard, American Express e Discover.
- Exibe o resultado na tela, com nome e imagem da bandeira.

---

## Estrutura do Repositório

├── index.html # Arquivo principal da aplicação (HTML, CSS, JS)
└── README.md # Documentação do projeto


---

## Possíveis Melhorias Futuras

- Implementar a validação do número do cartão usando o algoritmo de Luhn.
- Suportar mais bandeiras de cartão de crédito.
- Criar testes automatizados para as funções JavaScript.
- Melhorar a interface gráfica e a responsividade da página.
- Adicionar suporte para diferentes idiomas.

---

## Licença

Este projeto está sob a licença MIT.

---

## Contato

Qualquer dúvida ou sugestão, sinta-se à vontade para abrir uma issue no GitHub ou me contatar diretamente.

---

Obrigado por acompanhar este projeto! 🚀

