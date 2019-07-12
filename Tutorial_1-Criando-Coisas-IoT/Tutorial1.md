# Criando uma coisa IoT no AWS IoT Core

## Criando sua primeira Coisa (Thing)

1. Abra a página inicial da AWSe faça login no Console de Gerenciamento da AWS
2. No canto superior direito, clique em serviços e em seguidas na seção **IoT**, clique em Iot Core.
3. Em seguida, no menu lateral do lado direito clique em Gerenciar e aparecerá uma tela parecida com a imagem abaixo. Então clique em **Registrar uma coisa**.

4. Em seguida clique no botão **criar uma coisa**, que irá abrir um menu de configurações para sua nova coisa.
Por enquanto, apenas preencha o campo **nome** e o restante deixe como está e clique no botão **próximo** no canto inferior direito da tela.

5. Na nova tela exibida após o passo anterior, clique na opção **Cria certificado**. **ATENÇÃO:** Esses certificados devem ser salvos em um local seguro, pois são uma da segurança para o acesso da sua Coisa ao servidor da Amazon, faça cópias de Backup por segurança, ou poderá perder toda a configuração e dados dessa coisa criada, e será necessário refazer tudo.

6. Clique nos botões **Fazer download** para salvar os certificados, serão salvos 3 arquivos diferente:
   - a. Escolha Download (Fazer download) para seu certificado.
   - b. Escolha Download (Fazer download) para sua chave privada.
   - c. Escolha Download (Fazer download) para o CA raiz da Amazon. Isso exibirá uma nova página da Web. Escolha RSA 2048 bit key: Amazon Root CA 1 (Chave de bits RSA 2048: CA raiz 1 da Amazon). Isso abre uma página da web com o texto do certificado CA raiz. Copie esse texto e cole-o em um arquivo denominado Amazon_Root_CA_1.pem.

Ao terminar de salvar os certificados, clique no botão **Activate (Ativar)** para ativar o certificado X.509 e, em seguida, escolha **Attach a policy (Anexar uma política)**

7. Na página **Add a policy for your thing (Adicionar uma política à sua coisa)** deixe os campos em branco e clique em **Register Thing (Registrar a coisa)**.

Se os passos forem seguidos corretamente, nossa coisa estará criada, porém antes de usar, precismos criar as poíticas de segurança para evitarmos falhas na segurança e assim evitar invasões e inserções de dados indesejados na comunicação das coisas (_things_).

8.

