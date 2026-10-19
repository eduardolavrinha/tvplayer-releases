# TV Player

Player de IPTV para Android TV e Google TV: canais ao vivo com guia de programação, filmes e
séries com sinopse e elenco, e "continuar assistindo".

**O app não traz nenhum canal, filme ou lista.** Ele só reproduz o que vem da sua própria
assinatura de IPTV: você entra com os dados do seu provedor (Xtream Codes ou lista M3U).

## Instalar

### Pelo app Downloader (mais fácil)

1. Na TV, instale o **Downloader** (by AFTVnews) pela loja de apps.
2. Permita que o Downloader instale apps: *Configurações → Apps → Acesso especial →
   Instalar apps desconhecidos → Downloader* (o caminho muda um pouco entre aparelhos).
3. Abra o Downloader e digite o código **`CÓDIGO`** no campo de endereço.
4. Confirme a instalação. Depois do TV Player instalado, pode apagar o arquivo baixado.

### Pelo link direto

<https://github.com/eduardolavrinha/tvplayer-releases/releases/latest/download/tvplayer.apk>

Esse link sempre aponta para a versão mais recente.

## Requisitos

- Android TV / Google TV com Android 8.0 ou mais novo.
- Aparelhos Fire TV com Fire OS (Android) também funcionam. Os Fire TV com Vega OS não
  rodam apps Android.

## Atualizar

Baixe de novo pelo mesmo código ou link e instale por cima: login, catálogo e preferências
continuam.

## Privacidade

- Seus dados de acesso ao provedor ficam só no aparelho, cifrados.
- O app conversa apenas com: o servidor do seu provedor; o TMDB (sinopses, elenco e
  imagens); o OpenSubtitles, só se você cadastrar sua conta; o TheIntroDB e o IntroDB
  (marcas de abertura e créditos); e fontes públicas de guia de programação (open-epg.com,
  iptv-epg.org).
- O app guarda um registro técnico (desempenho e erros) num arquivo no próprio aparelho, para
  diagnóstico. Ele não é enviado para lugar nenhum.

## Créditos

Este produto usa a API do TMDB, mas não é endossado nem certificado pelo TMDB.
