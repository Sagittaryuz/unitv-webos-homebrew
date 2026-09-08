# Experimento 1.0.5

Objetivo: testar se o CAPTCHA do UniTV Net deixa de falhar quando o WebAppMgr do LG webOS usa modo `netcast` e um User-Agent de Chrome moderno.

Destino: `https://www.uvnetweb.pro/`

Alterações de runtime:
- `trustLevel: netcast`
- `vendorExtension.userAgent` definido como Chrome moderno em Windows
- `vendorExtension.allowCrossDomain: true`

Isto não ignora nem resolve o CAPTCHA automaticamente. Apenas altera a identificação do navegador para testar se o serviço estava recusando/ocultando o desafio por detectar o navegador da LG como antigo.
