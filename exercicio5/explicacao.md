# Exercício 5 - Certificado Autoassinado

## Comandos utilizados
openssl x509 -req -days 365 -in aluno.csr -signkey aluno.key -out aluno.crt

## Explicação
Usando o CSR e a chave privada nós nos damos Autoridade Certificadora com nossa própria chave.
