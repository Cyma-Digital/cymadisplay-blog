---
title: "Como instalar o nosso sistema?"
excerpt: "Blog do sistema de gerenciamento de conteúdo mais popular da internet!"
date: "2025-05-12"
coverImage: "https://raw.githubusercontent.com/Cyma-Digital/cymadisplay-blog/refs/heads/main/como-instalar/cover.png"
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

- Um cartão microSD de **pelo menos 8GB** (recomendado: 16GB ou mais)
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

## Etapa 2: Grave a imagem no cartão microSD

1. Insira o cartão microSD no computador.
2. No **Balena Etcher**, clique em **"Flash from file"** e selecione o arquivo `.zip` (ou `.img`).
3. Clique em **"Select target"** e escolha o cartão SD.
4. Clique em **"Flash!"** para iniciar a gravação.
5. Aguarde até que a gravação e verificação sejam concluídas.

> ⚠️ Atenção: Todos os dados do cartão microSD serão apagados.

![Balena Etcher - Gravação]("https://github.com/Cyma-Digital/cymadisplay-blog/como-instalar/balena-etcher.png")

Observação: Neste tutorial utilizamos a versão 1.7.9 do Balena para realizar a gravação da imagem.

---

## Etapa 3: Inicialize o Raspberry Pi

1. Remova o cartão microSD com segurança.
2. Insira-o no seu **Raspberry Pi**.
3. Conecte o cabo de alimentação e aguarde a inicialização.
4. O sistema de Digital Signage será iniciado automaticamente.

---

## Observações

O **Balena Etcher** consegue descompactar automaticamente, mas se preferir, você pode descompactar manualmente com um utilitário como:

- **Windows**: [7-Zip](https://www.7-zip.org/) ou aplicativo nativo do sistema.
- **macOS/Linux**: `gunzip` ou `xz -d`

---

## Pronto!

Seu Raspberry Pi agora está com o nosso sistema de **Digital Signage** instalado e pronto para uso. Agora bastar realizar o pareamento do seu dispositivo na plataforma do Cyma Display para poder realizar os agendamentos.

&nbsp;

Se tiver dúvidas ou precisar de suporte, entre em contato com nossa equipe técnica.
