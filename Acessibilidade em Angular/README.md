![Buscante](thumbnail.png)

# Aprendizados
1. Acessibilidade no roteamento
Adicionar títulos descritivos a cada página da aplicação para melhorar a experiência de navegação;
Utilizar a diretiva RouterLinkActive para destacar visualmente os links ativos, proporcionando uma navegação mais clara e compreensível;
Aprimorar a acessibilidade com o uso de ariaCurrentWhenActive, para uma identificação eficaz de elementos ativos;
Implementar foco automático em elementos, utilizando as ferramentas do Angular, como @ViewChild e ElementRef, para aprimorar a usabilidade da aplicação.
2. Exploração dos Atributos Aria:  
Utilizar o atributo aria-label para fornecer descrições acessíveis a elementos, melhorando a experiência para pessoas usuárias de tecnologias assistivas;
Empregar a sintaxe [attr.aria-label] no Angular para vincular dinamicamente descrições acessíveis aos elementos, personalizando informações específicas da aplicação;
Entender o papel do atributo role na identificação semântica de elementos, utilizando valores comuns como "radiogroup", "alert" e "region".

# Buscante

Aplicação que permite pesquisar e descobrir livros utilizando a API do Google Books. 

## 🔨 Funcionalidades do projeto

### Pesquisa de Livros:

As pessoas podem inserir palavras-chave na barra de pesquisa para buscar livros de forma dinâmica.

### Detalhes do Livro:

Ao clicar em um livro específico pode-se obter mais detalhes, como título, sinopse, autoria e outras informações fornecidas pela API do Google Books.

### Link para ler prévia do livro:

Link com opção de ler uma prévia do livro.

## ✔️ Técnicas e tecnologias utilizadas

As técnicas e tecnologias utilizadas foram:

- `Angular`
- `Google Books API`
- `RxJs`


## 🛠️ Abrir e rodar o projeto

Para abrir e rodar o projeto, execute *npm i* para instalar as dependências e *ng serve* para iniciar o projeto.

Depois, acesse [http://localhost:4200/](url) no seu navegador. 

## 📚 Mais informações do curso

O curso visa implementar estratégias de acessibilidade para tornar o Buscante uma aplicação mais inclusiva e acessível.
