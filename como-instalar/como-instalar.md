---
title: "Como instalar o nosso sistema?"
excerpt: "Blog do sistema de gerenciamento de conteúdo mais popular da internet!"
date: "2025-05-12"
coverImage: "https://github.com/Cyma-Digital/cymadisplay-blog/como-instalar/cover.png"
author:
  name: "Autor"
tags:
  - introdução
  - primeiros passos
---

## Introdução

Neste tutorial, você aprenderá como instalar o nosso sistema de **Digital Signage** em um **Raspberry Pi**.

---

## O que você vai precisar

- Um cartão microSD de **pelo menos 8GB** (recomendado: 16GB ou mais, classe 10)
- Leitor de cartão microSD
- [Balena Etcher](https://www.balena.io/etcher/) (disponível para Windows, macOS e Linux)
- Um computador com acesso à internet
- Imagem do sistema que pode ser baixada através deste [link](https://example.com/download/sistema-digital-signage.img.gz).

---

## Etapa 1: Instale o Balena Etcher

1. Acesse o site oficial: [https://www.balena.io/etcher/](https://www.balena.io/etcher/)
2. Baixe a versão compatível com o seu sistema operacional.
3. Instale e abra o **Balena Etcher**.

---

## Etapa 2: Descompacte a imagem (se necessário)

O **Balena Etcher** consegue descompactar automaticamente, mas se preferir, você pode descompactar manualmente com um utilitário como:

- **Windows**: [7-Zip](https://www.7-zip.org/)
- **macOS/Linux**: `gunzip` ou `xz -d`

---

## Etapa 3: Grave a imagem no cartão microSD

1. Insira o cartão microSD no computador.
2. No **Balena Etcher**, clique em **"Flash from file"** e selecione o arquivo `.img` (ou `.img.gz`, `.img.xz`).
3. Clique em **"Select target"** e escolha o cartão SD.
4. Clique em **"Flash!"** para iniciar a gravação.
5. Aguarde até que a gravação e verificação sejam concluídas.

> ⚠️ Atenção: Todos os dados do cartão microSD serão apagados.

![Balena Etcher - Gravação](https://global.discourse-cdn.com/balena/optimized/2X/e/e15f6e8f774132f9da2833b4bb1ebae4e7c87546_2_690x456.png)

---

## Etapa 4: Inicialize o Raspberry Pi

1. Remova o cartão microSD com segurança.
2. Insira-o no seu **Raspberry Pi**.
3. Conecte o cabo de alimentação e aguarde a inicialização.
4. O sistema de Digital Signage será iniciado automaticamente.

---

## Pronto!

Seu Raspberry Pi agora está com o nosso sistema de **Digital Signage** instalado e pronto para uso.

Se tiver dúvidas ou precisar de suporte, entre em contato com nossa equipe técnica.
