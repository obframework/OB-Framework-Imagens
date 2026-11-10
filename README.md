# OB Framework Imagens

Repositorio de assets web utilizados pelo **OB Framework** e pelo
**OB Framework Legacy**.

Ele foi separado dos repositorios de codigo porque possui aproximadamente
2,1 GB de imagens. Os arquivos sao armazenados com Git LFS.

## Conteudo

- `barbershop/`: imagens do sistema de barbearia;
- `cars/`: imagens de veiculos;
- `creator/`: assets do criador de personagem;
- `icons/`: icones de inventario e interfaces;
- `skinshop/`: imagens da loja de roupas;
- `tattoos/`: imagens de tatuagens.

## Como instalar

1. Instale o Git LFS: `git lfs install`.
2. Clone este repositorio.
3. Publique o conteudo em um servidor HTTP/HTTPS.
4. Mantenha a estrutura das subpastas e configure a framework com a URL base
   escolhida.

Exemplo de estrutura publica:

```text
https://SEU_DOMINIO/QUALQUER_PASTA/icons/
https://SEU_DOMINIO/QUALQUER_PASTA/cars/
https://SEU_DOMINIO/QUALQUER_PASTA/creator/
```

A pasta base pode ter qualquer nome ou ser a raiz do dominio. O importante e
preservar `barbershop/`, `cars/`, `creator/`, `icons/`, `skinshop/` e
`tattoos/` dentro dela. Depois, ajuste `ImageBaseUrl` ou `BaseUrl` nos recursos
da framework para apontar para os caminhos escolhidos, por exemplo
`https://SEU_DOMINIO/QUALQUER_PASTA/cars/`.

## Repositorios da framework

- [OB-Framework](https://github.com/obframework/OB-Framework): GTA V Enhanced.
- [OB-Framework-Legacy](https://github.com/obframework/OB-Framework-Legacy): GTA V Legacy.

## Creditos

Arquivos com creditos proprios foram preservados dentro de suas respectivas
pastas. Os assets de terceiros continuam sujeitos as licencas e termos de seus
autores.
