# Exercício 7 - Servidor HTTP e erro HTTPS

## Comandos utilizados
python3 -m http.server 8443 --bind 0.0.0.0

## Explicação
O navegador tenta fazer um handshake SSL, mas o servidor não sabe responder isso porque é HTTP puro, então a conexão falha e o navegador mostra um erro.
