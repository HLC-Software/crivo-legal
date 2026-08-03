# Central legal do Crivo

Site estático com variáveis do Jekyll, pronto para GitHub Pages. O próprio GitHub processa as páginas; não é necessário instalar Node.js, framework, banco de dados ou servidor.

## Único arquivo que você precisa editar

Abra o arquivo _config.yml e preencha:

- app_name: nome do aplicativo;
- developer_name: nome público exibido como desenvolvedor;
- legal_name: seu nome civil completo ou a razão social, se houver;
- support_email: e-mail público de suporte;
- last_updated: data exibida nos documentos;
- current_year: ano utilizado no rodapé;
- url: endereço final do site.

Esses valores são aplicados automaticamente em todas as páginas durante a publicação.

Não publique enquanto legal_name, support_email e url ainda contiverem valores de exemplo. O conteúdo foi preparado como base informativa para o produto e deve ser revisado pelo responsável pelo aplicativo; ele não substitui orientação jurídica profissional.

## Publicar no GitHub Pages

1. Crie um repositório chamado crivo-legal.
2. Copie o conteúdo desta pasta para a raiz do repositório.
3. No GitHub, abra Settings → Pages.
4. Em Build and deployment, selecione Deploy from a branch.
5. Escolha a branch main e a pasta / (root).
6. No Cloudflare DNS, crie um CNAME chamado crivo apontando para SEU-USUARIO.github.io, inicialmente como DNS only.
7. No GitHub Pages, informe o domínio personalizado. O próprio GitHub criará o arquivo CNAME.
8. Depois da validação, ative Enforce HTTPS.

## Páginas

- / — central de confiança
- /privacidade/ — Política de Privacidade
- /termos/ — Termos de Uso
- /excluir-conta/ — instruções e solicitação de exclusão
- /suporte/ — suporte e denúncias

## Atualizações futuras

Ao mudar funcionalidades, fornecedores ou dados coletados, atualize o conteúdo e a variável last_updated. Mantenha a Política de Privacidade alinhada ao formulário Data Safety do Google Play e ao comportamento real do aplicativo.
