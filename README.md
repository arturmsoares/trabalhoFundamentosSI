# trabalhoFundamentosSI
trabalho em dupla sobre pull requests

## Estrutura de Diretórios

- `readME.md` - Contém as informações sobre o repositório e instalação.
- `teste.java` - Contém um programa em java que lê um texto e executa.

## Instalação

- **Java Development Kit (JDK):** Certifique-se de ter o JDK 11 ou superior instalado. [Download do JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) ou use uma distribuição alternativa como [AdoptOpenJDK](https://adoptium.net/).

 Se o Git não estiver instalado, você pode baixá-lo e instalá-lo a partir do [site oficial](https://git-scm.com/downloads). Após a instalação, você pode verificar se o Git está instalado corretamente com o seguinte comando:

   ```bash
   git --version

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
2. **Navegue até o diretório do projeto:**
    ```bash
    cd nome-do-repositorio
    ```
3. **Instale as dependências:**
    Se o projeto usa `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```
    Ou se usa `package.json`:
    ```bash
    npm install
    ```

## Passos para Contribuir

1. **Faça um Fork do Repositório**

   - Vá para o repositório [original](https://github.com/usuario/nome-do-repositorio) no GitHub.
   - Clique no botão "Fork" no canto superior direito da página. Isso criará uma cópia do repositório em sua própria conta do GitHub.

2. **Clone o Repositório Forkado**

   - Abra o terminal ou prompt de comando.
   - Clone o repositório forkado para o seu computador usando o comando:

     ```bash
     git clone https://github.com/seu-usuario/nome-do-repositorio.git
     ```

   - Navegue até o diretório do repositório:

     ```bash
     cd nome-do-repositorio
     ```

3. **Crie uma Nova Branch**

   - Crie e mude para uma nova branch para suas alterações:

     ```bash
     git checkout -b nome-da-sua-branch
     ```

   - Substitua `nome-da-sua-branch` por um nome descritivo relacionado às suas alterações.

4. **Faça Suas Alterações**

   - Edite os arquivos conforme necessário para suas alterações.

5. **Adicione e Faça Commit das Alterações**

   - Adicione os arquivos modificados ao índice do Git:

     ```bash
     git add .
     ```

   - Faça um commit das suas alterações:

     ```bash
     git commit -m "Descrição das suas alterações"
     ```

6. **Envie as Alterações para o GitHub**

   - Envie a branch para o seu repositório forkado no GitHub:

     ```bash
     git push origin nome-da-sua-branch
     ```

7. **Crie um Pull Request**

   - Vá para o seu repositório forkado no GitHub.
   - Você verá uma notificação para criar um pull request para a branch que você acabou de enviar. Clique em "Compare & pull request".
   - Adicione um título e uma descrição para o pull request explicando as alterações feitas.
   - Certifique-se de que o pull request está sendo enviado para a branch principal do repositório original.
   - Clique em "Create pull request" para enviar seu pull request.