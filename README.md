## 🌐 [English Version of README](README_EN.md)

# AluraBooks Cadastro

Este projeto consiste em uma aplicação web para cadastro de usuários, utilizando HTML, CSS e JavaScript. Ele apresenta funcionalidades como validação de CEP e busca automática de endereço, além de um design responsivo e integrado com bibliotecas externas como Swiper e Google Fonts.

## 🔨 Funcionalidades do Projeto

- Formulário de cadastro de usuários.
- Validação e preenchimento automático do endereço utilizando a API de CEP.
- Design responsivo adaptado para diferentes tamanhos de tela.
- Estrutura modular de estilos CSS, facilitando a manutenção.
- Navegação e interação intuitivas para o usuário.

### Exemplo Visual do Projeto

![chrome-capture-2024-11-20](https://github.com/user-attachments/assets/fbaaaf46-16da-40f4-814e-5b8760e61b93)

## ✔️ Técnicas e Tecnologias Utilizadas

- **HTML5**: Estrutura semântica.
- **CSS3**: Estilização com uso de variáveis e design responsivo.
- **JavaScript (ES6+)**: Interatividade e integração com APIs externas.
- **API ViaCEP**: Busca de endereços com base no CEP informado.
- **Google Fonts**: Importação de fontes personalizadas.
- **Swiper.js**: Biblioteca externa para aprimoramento da interface.
- **Responsividade**: Suporte para diversos dispositivos.

## 📁 Estrutura do Projeto

- **img/**: Contém todas as imagens utilizadas no projeto, incluindo ícones e logotipos.
- **styles/**: Arquivos CSS para estilização do projeto.
    - `reset.css`: Reset de estilos para consistência entre navegadores.
    - `header.css`: Estilos aplicados ao cabeçalho.
    - `formulario.css`: Estilização do formulário de cadastro.
    - `rodape.css`: Estilos para o rodapé.
    - `banner.css`: Estilos para o banner principal.
    - `styles.css`: Importação e configuração de estilos principais.
- **index.html**: Página principal com o formulário de cadastro.
- **cadastro-finalizado.html**: Página de confirmação após o cadastro.
- **script.js**: Script para validação de formulário e integração com a API de CEP.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:
      ```bash
      git clone <URL_DO_REPOSITORIO>
      ```

2. **Abra os arquivos no navegador**:
    - Navegue até a pasta do projeto.
    - Abra o arquivo `index.html` diretamente em um navegador para visualizar o projeto.

## 🌐 Deploy

Para hospedar o projeto e torná-lo acessível online, siga os passos abaixo:

1. **Utilize uma plataforma de hospedagem gratuita**:
    - Algumas opções populares incluem:
        - [GitHub Pages](https://pages.github.com/): Ideal para projetos estáticos.
        - [Netlify](https://www.netlify.com/): Permite deploy rápido e fácil.
        - [Vercel](https://vercel.com/): Oferece integração contínua e preview para projetos front-end.

2. **Passos para deploy com GitHub Pages**:
    - No repositório do projeto no GitHub, vá para a aba **Settings**.
    - Na seção **Pages**, selecione a branch desejada (geralmente `main` ou `gh-pages`) e salve.
    - Após alguns minutos, o projeto estará disponível em um link no formato: `https://<seu-usuario>.github.io/<nome-do-repositorio>`.

3. **Passos para deploy com Netlify ou Vercel**:
    - Crie uma conta na plataforma escolhida.
    - Vincule o repositório do GitHub ao serviço.
    - Configure as opções de build (geralmente não é necessário alterar nada para projetos estáticos).
    - Publique o projeto com um clique, e um link será gerado automaticamente.

