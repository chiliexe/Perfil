# Perfil Interativo

Página HTML interativa para compartilhar meu currículo, pode servir como modelo para apresentação do seu perfil como programador.

### Tecnologias Utilizadas

* HTML
* CSS / Tailwind CSS
* JavaScript (com Chart.js)

---

## Como Usar Este Modelo para Criar Seu Próprio Perfil

Bem-vindo ao repositório do seu perfil/currículo interativo! Este projeto oferece um modelo moderno e dinâmico para apresentar suas habilidades, experiência e projetos de forma engajadora, utilizando HTML, Tailwind CSS e JavaScript (Chart.js para visualizações).

Este `README` irá guiá-lo em como **forkar este repositório**, personalizá-lo com suas informações e publicá-lo gratuitamente no GitHub Pages.

Siga estes passos simples para ter seu perfil interativo online:

### Pré-requisitos

Antes de começar, certifique-se de ter:

* Uma conta no GitHub.
* Conhecimento básico de Git (clonar, adicionar, commit, push).
* Um editor de texto (como VS Code, Sublime Text, Atom, etc.).

### Etapa 1: Forkar Este Repositório

O primeiro passo é criar uma cópia deste repositório na sua própria conta do GitHub.

1.  **Vá para a página deste repositório no GitHub:**
    * `https://github.com/chiliexe/Perfil` (Este é o link do repositório original. Se você já for o `chiliexe`, pode pular esta etapa e ir direto para o "Clonar o Repositório" na Etapa 2, mas o fork é a forma padrão para outros usuários).
2.  No canto superior direito da página, clique no botão **"Fork"**.
    
3.  Você será redirecionado para uma página onde pode confirmar o fork. Clique em **"Create fork"**.
    * Isso criará uma cópia deste repositório (ex: `seu-usuario/Perfil`) na sua conta do GitHub.

### Etapa 2: Clonar Seu Novo Repositório e Personalizar o Conteúdo

Agora que você tem uma cópia do repositório, é hora de baixá-lo para o seu computador e preenchê-lo com suas informações.

1.  **Clone o repositório forkeado para o seu computador:**
    * Vá para o **seu novo repositório forkeado** no GitHub (ex: `https://github.com/seu-usuario/Perfil`).
    * Clique no botão verde **"Code"** e copie o URL HTTPS.
    * Abra seu terminal (ou Git Bash) e execute:
        ```bash
        git clone [URL_DO_SEU_REPOSITORIO_FORKEADO]
        ```
        *Exemplo:* `git clone https://github.com/seu-usuario/Perfil.git`
    * Navegue para dentro da pasta clonada:
        ```bash
        cd Perfil
        ```

2.  **Abra o arquivo `index.html` no seu editor de texto.**

3.  **Localize a Seção de Dados JavaScript:**
    * Role para baixo no arquivo `index.html` até encontrar o bloco de código JavaScript que começa com:
        ```javascript
        // --- DADOS DO CURRÍCULO (PREENCHA AQUI) ---
        const cvData = {
            header: {
                name: "[Seu Nome Completo]",
                title: "[Seu Cargo ou Área de Atuação]",
                // ... e assim por diante
            },
            // ... restante do objeto cvData
        };
        ```

4.  **Edite o Objeto `cvData` com suas informações:**
    * **Substitua todos os valores entre colchetes `[]`** e os textos de exemplo pelos seus próprios dados.
    * Preencha o `header` (nome, cargo, contatos, links).
    * Escreva seu `summary` (resumo profissional).
    * Adicione suas `skills` (habilidades) em categorias, com um nível de proficiência (0-100). Você pode adicionar ou remover categorias conforme necessário.
    * Detalhe sua `experience` (experiência profissional), usando verbos de ação e, se possível, quantificando resultados.
    * Liste seus `projects` (projetos pessoais), incluindo links para GitHub e demos ao vivo.
    * Preencha sua `education` (formação acadêmica) e `courses` (cursos e certificações).

5.  **Salve o arquivo `index.html`** após todas as suas modificações.

### Etapa 3: Enviar Suas Alterações para o GitHub

Com suas informações no lugar, é hora de enviar o código atualizado para o seu repositório no GitHub.

1.  **No seu terminal (dentro da pasta `Perfil`):**
    * Adicione as alterações:
        ```bash
        git add .
        ```
    * Faça o commit das alterações:
        ```bash
        git commit -m "Atualiza perfil com minhas informações"
        ```
    * Envie para o GitHub:
        ```bash
        git push origin main # Ou 'git push origin master' se sua branch principal for master
        ```

### Etapa 4: Publicar Seu Perfil com GitHub Pages

Esta é a etapa final para tornar seu perfil acessível online.

1.  **Vá para o seu repositório forkeado no GitHub** (no navegador).
2.  Clique na aba **"Settings"** (Configurações).
    
3.  No menu lateral esquerdo, clique em **"Pages"**.
    
4.  Na seção "Build and deployment" (Construção e implantação):
    * Em "Source" (Origem), selecione **"Deploy from a branch"** (Implantar a partir de uma branch).
    * Em "Branch", no dropdown, selecione a branch onde seu código está (geralmente **`main`** ou `master`).
    * No dropdown ao lado, selecione a pasta onde seus arquivos estão. Para este modelo, será **`/ (root)`** (raiz), pois o `index.html` está na raiz do repositório.
    
5.  Clique em **"Save"** (Salvar).

### Etapa 5: Acesse Seu Perfil Online!

* Após alguns minutos (o GitHub leva um tempo para construir e publicar a página, geralmente de 1 a 10 minutos), você verá uma mensagem verde na seção "Pages" indicando que seu site está publicado.
* O URL do seu perfil será exibido ali. Ele geralmente será no formato:
    * `https://seu-usuario.github.io/Perfil` (para sites de projeto, que é o caso se você forcou este repositório).
    * Se você quiser um URL mais limpo como `https://seu-usuario.github.io`, você precisaria renomear o seu repositório forkeado para `seu-usuario.github.io` (e o `index.html` deve estar na raiz desse repositório).

---

Parabéns! Você agora tem um perfil interativo e profissional online, hospedado gratuitamente no GitHub Pages. Sinta-se à vontade para explorar e modificar o código HTML/CSS/JS para personalizar ainda mais o design e as funcionalidades.
