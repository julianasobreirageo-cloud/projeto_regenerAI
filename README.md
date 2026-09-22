# Projeto RegenerAI — loja (protótipo)

Site de catálogo com **capas reais** extraídas da primeira página dos PDFs fornecidos e fotos reais fornecidas. Nenhum checkout está ativo.

## Testar
`npm start` e abrir `http://localhost:3000`.

## Publicar
Criar um repositório GitHub, enviar o conteúdo desta pasta e conectar o repositório ao Railway como serviço Node. Start command: `npm start`. Railway fornece a variável PORT. Não foi realizado deploy nem alteração em contas.

## Configurar produtos
Editar `products.json`: `price` (número em reais), `checkoutUrl` (URL HTTPS gerada pela plataforma de pagamento) e `status` = `published` **somente após** validar preço, checkout, direitos autorais, dados da loja e entrega. Enquanto não configurado, botão permanece desativado. `status=review` para o livro profissional até revisão de direitos de reprodução dos instrumentos e condições de comercialização. Não hospedar PDFs integrais em pasta pública do site; entrega deve ser feita pela plataforma de checkout.

## Pendências
Confirmar marca/logotipo oficial, preços, plataforma, termos, política de privacidade, contatos comerciais, autorização para uso público de fotografias de pessoas (especialmente crianças) e direitos sobre imagens e testes. Fotos de atividades estão incluídas apenas para avaliação privada: remova/substitua antes de publicar se não houver autorização. Currículo foi resumido a partir do PDF; confirmar texto final com a autora.
