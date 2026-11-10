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
4. O diretorio publicado precisa responder sob o caminho `/orbis/`.

Exemplo de estrutura publica:

```text
https://SEU_DOMINIO/orbis/icons/
https://SEU_DOMINIO/orbis/cars/
https://SEU_DOMINIO/orbis/creator/
```

As configuracoes publicas da framework usam caminhos relativos como
`/orbis/cars/`. Ajuste o dominio ou proxy conforme sua hospedagem.

## Repositorios da framework

- [OB-Framework](https://github.com/obframework/OB-Framework): GTA V Enhanced.
- [OB-Framework-Legacy](https://github.com/obframework/OB-Framework-Legacy): GTA V Legacy.

## Creditos

Arquivos com creditos proprios foram preservados dentro de suas respectivas
pastas. Os assets de terceiros continuam sujeitos as licencas e termos de seus
autores.
