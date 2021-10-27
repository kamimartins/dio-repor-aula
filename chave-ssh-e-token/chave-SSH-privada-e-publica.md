### **Para chave SSH privada e pública**

1. criando a chave ssh pub and private ssh-keygen -t ed25519 -C [seuemail@mail.com](mailto:seuemail@mail.com) na sua máquina

2. para visualizar o conteúdo da chave pública cat <id_da_sua_chave_pub>

   

- Copiando a chave pub para o gihub

  settings > keys > SSH and GPC keys > new SSH key

1. iniciando o processo do **key-agent** em background na sua máquina

   comando: eval $(ssh-agent -s)

2. adicionado a chave privada ao key-agent ssh-add <id_da_sua_chave_private>

3. depois é só clonar um repositório com o link SSH



### Criando Token

settings > developer settings > personal acess tokens > generate new token

obs: copie esse token o quanto antes pois a visualização no github é temporária 