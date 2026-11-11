<div align="center">

# Yunxi
### Uma conversa pode aproximar mundos.

**Comunicação independente · Android nativo · Web e PWA**

[Site oficial](https://yunxi.3fa.site/yunxi-oficial/) · [Experimentar](https://yunxi.3fa.site/) · [Baixar aplicativo](https://yunxi.3fa.site/loja/)

</div>

---

## Sobre o produto

O Yunxi é uma plataforma de comunicação criada por **Rafael Lourenço, conhecido como Inforcusto**. Permite conversar pela internet usando um identificador de seis dígitos, sem exigir uma linha telefônica no cadastro.

Este repositório apresenta o produto e sua proposta técnica. O código-fonte da aplicação permanece privado.

## Recursos

- Mensagens individuais e grupos.
- Envio de áudios, fotos, vídeos e documentos.
- Chamadas de voz e vídeo com WebRTC e suporte a TURN.
- Aplicativo Android nativo e interface responsiva no navegador/PWA.
- Armazenamento local no Android e gestão do armazenamento na nuvem.
- Administração de usuários, planos e atualizações.
- Personalização visual e notificações, conforme a plataforma e as permissões do dispositivo.

## Engenharia do produto

| Camada | Tecnologias e responsabilidades |
| --- | --- |
| Aplicativo Android | Kotlin, recursos nativos e armazenamento local |
| Interface web | HTML, CSS e JavaScript; experiência responsiva e PWA |
| Servidor | PHP e SQLite para dados e serviços da plataforma |
| Chamadas | WebRTC para comunicação e Coturn/TURN quando necessário |
| Implantação | Linux, Nginx e VPS |

O desenvolvimento prioriza melhorias incrementais, retorno de usuários e economia de recursos em infraestrutura própria.

## Segurança e transparência

Texto e áudio nas conversas individuais compatíveis contam com criptografia de ponta a ponta, com estado e código de verificação consultáveis no chat. A disponibilidade depende das versões e chaves dos participantes.

Confira o escopo e as limitações na [página de segurança](https://yunxi.3fa.site/yunxi-oficial/seguranca.html). A comparação de códigos não substitui uma auditoria independente.

## Conheça na prática

1. Acesse o [site oficial](https://yunxi.3fa.site/yunxi-oficial/) para entender a proposta.
2. Experimente a [versão no navegador](https://yunxi.3fa.site/).
3. Consulte a [loja oficial](https://yunxi.3fa.site/loja/) para baixar o aplicativo.

## Autoria e contato

**Rafael Lourenço · Inforcusto**

[E-mail](mailto:dmrafael592@gmail.com) · [Telegram](https://t.me/xiazuc) · [GitHub](https://github.com/zumgabutm)

---

Este repositório é uma apresentação pública do Yunxi; não contém credenciais, dados de usuários ou o código-fonte privado do produto.
