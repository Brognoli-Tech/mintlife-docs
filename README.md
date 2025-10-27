# Kit de Início do Mintlify

Use o kit de início para colocar seus documentos em produção e pronto para personalizar.

Clique no botão verde **Use this template** no topo deste repositório para copiar o kit de início do Mintlify. O kit de início contém exemplos com

- Páginas de guias
- Navegação
- Personalizações
- Páginas de referência de API
- Uso de componentes populares

**[Siga o guia completo de início rápido](https://starter.mintlify.com/quickstart)**

## Desenvolvimento

Instale o [CLI do Mintlify](https://www.npmjs.com/package/mint) para visualizar suas alterações de documentação localmente. Para instalar, use o seguinte comando:

```
npm i -g mint
```

Execute o seguinte comando na raiz da sua documentação, onde seu `docs.json` está localizado:

```
mint dev
```

Visualize sua prévia local em `http://localhost:3000`.

## Publicando alterações

Instale nosso aplicativo GitHub do seu [painel](https://dashboard.mintlify.com/settings/organization/github-app) para propagar alterações do seu repositório para sua implantação. As alterações são implantadas em produção automaticamente após fazer push para o branch padrão.

## Precisa de ajuda?

### Solução de problemas

- Se seu ambiente de desenvolvimento não estiver funcionando: Execute `mint update` para garantir que você tem a versão mais recente do CLI.
- Se uma página carregar como 404: Certifique-se de que você está executando em uma pasta com um `docs.json` válido.

### Recursos
- [Documentação do Mintlify](https://mintlify.com/docs)
