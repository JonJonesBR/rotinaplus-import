# rotinaplus-import

Página estática de redirecionamento pro app [Rotina+](https://github.com/JonJonesBR/RotinaPlus-App-para-Academia) (código-fonte do app em repositório privado, separado deste).

O WhatsApp só deixa links `http(s)://` clicáveis — não o esquema customizado `rotinaplus://` que o app usa pra importar um vínculo direto. Esta página só lê o parâmetro `?data=` da própria URL e redireciona na hora pra `rotinaplus://import?data=...`, sem guardar nem processar nada no servidor.

Publicada via GitHub Pages. Sem lógica de negócio, sem dado de ninguém armazenado aqui — o conteúdo do `?data=` passa só pela URL de cada acesso individual, no navegador de quem abriu o link, e expira sozinho (verificado pelo app) pouco tempo depois de gerado.
