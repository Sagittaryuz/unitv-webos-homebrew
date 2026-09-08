# UniTV Net para LG webOS

Wrapper webOS para abrir a versão Web do UniTV Net em tela cheia.

Versão: **1.0.5 experimental**

Destino Web: `https://www.uvnetweb.pro/`

A versão 1.0.5 usa `trustLevel: netcast` e substitui o User-Agent do WebAppMgr por um Chrome moderno, mantendo o CAPTCHA original do serviço. O objetivo é testar se o desafio volta a aparecer quando o site deixa de identificar o navegador LG como antigo. Também habilita `allowCrossDomain` no modo netcast.

O pacote é gerado e validado pelo `ares-package` oficial do webOS CLI antes de ser publicado no repositório Homebrew.
