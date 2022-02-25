# edgium.me

DNS wildcard tão simples, que você ficará mal acostumado!

Pare de editar manualmente seu arquivo **hosts**, use o [edgium.me](https://edgium.me) para gerenciar seu DNS.

### Exemplos de uso

#### Diretamente com o IP

- **10.0.0.1.edgium.me** traduz para **10.0.0.1**
- **192-168-1-250.edgium.me** traduz para **192.168.1.250**
- **0a000803.edgium.me** traduz para **10.0.8.3**

#### With a name

- **app.10.8.0.1.edgium.me** traduz para **10.8.0.1**
- **app-116-203-255-68.edgium.me** traduz para **116.203.255.68**
- **app-c0a801fc.edgium.me** traduz para **192.168.1.252**
- **customer1.app.10.0.0.1.edgium.me** traduz para **10.0.0.1**
- **customer2-app-127-0-0-1.edgium.me** traduz para **127.0.0.1**
- **customer3-app-7f000101.edgium.me** traduz para **127.0.1.1**

#### O [edgium.me](https://edgium.me) também traduz **\<anything\>[.-]\<Endereço IP\>.edgium.me** em notações de **"ponto"**, **"traço"** ou **"hexadecimal"** para o **\<Endereço IP\>** correspondente

- notação de ponto: **magic.127.0.0.1.edgium.me**
- notação de traço: **magic-127-0-0-1.edgium.me**
- notação de hexadecimal: **magic-7f000001.edgium.me**

### Algo mais?

Dúvidas, sugestões ou problemas? Manda um issue ou pull request aqui em nosso repositório: https://github.com/edgium/edgium.me

### Licença

Projeto concebido com base em [nip.io](https://nip.io/)
