## SHA1 :key:

SHA1 - Secure Hash Algoritm - é um conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA).

A encriptação gera conjunto de characteres identificador de 40 dígitos.

É uma forma curta de representar um arquivo.



### Exemplo realizado no Git Bash

openssl sha1 texto.txt
SHA1 (texto.txt) = 21c399a68bb2b63bc22cf5f0691618062ec7fe9



### Objetos

- BLOBS - bloco básico de composição 

- TREES - armazena e aponta tipos de blocos diferentes / contém metadados

- COMMITS - junta tudo: aponta para uma árvore

  ​										aponta para um parente

  ​										aponta para um autor

  ​										aponta para uma mensagem

  timestamp (linha do tempo) data + hora que foi criado (possui SHA1)