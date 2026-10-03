# Guia de Negócios da Cidade

Diretório local de negócios, serviços e profissionais.

## Páginas
- index.html — guia público e busca.
- negocio.html?n=slug — página individual.
- admin.html — painel administrativo.
- supabase/schema.sql — estrutura do banco.

## Banco
Supabase: projeto mvxotnzttuxnzfkrdlqe.

A chave usada no navegador é a chave publicável do projeto. Nenhuma service_role/secret deve ser colocada neste repositório.

## Administração
O painel usa Supabase Auth + a tabela public.admins. O usuário administrador precisa existir no Auth e também ter sua linha em public.admins, com is_admin=true em raw_app_meta_data.

## Imagens
Nesta versão as imagens são reduzidas no navegador e salvas no registro do negócio como dados de imagem.

## GitHub Pages
O workflow em .github/workflows/pages.yml publica o conteúdo do repositório usando GitHub Pages.