# Aplicativo de Receitas por IA

## 📒 Descrição
Este projeto é um aplicativo de iOS desenvolvido em Swift que permite ao usuário definir pelo menos 3 alimentos e receber a descrição de uma receita gerada por uma IA. A aplicação demonstra como integrar serviços de IA generativa com uma aplicação móvel para enriquecer a experiência do usuário.

## 🤖 Tecnologias Utilizadas
- **Swift**: Linguagem de programação usada para desenvolver o aplicativo.
- **GPT-4 da OpenAI**: Modelo de linguagem utilizado para gerar descrições automáticas de imagens.
- **UIKit**: Framework utilizado para construir a interface do usuário.
- **URLSession**: Para fazer requisições HTTP e integrar com o serviço da OpenAI.

## 🧐 Processo de Criação
1. **Configuração do Projeto**: Iniciamos criando um novo projeto no Xcode e configurando a interface várias UIViews com UIImages contendo imagens de alimentos para gerar a receita no UITextView em outra tela.
2. **Integração com a IA**: Utilizamos a API do GPT-3.5 para enviar os alimentos escolhidos e receber a receita. Para isso, configuramos as requisições HTTP usando URLSession.
3. **Interface do Usuário**: Desenvolvemos uma interface simples onde o usuário pode escolher três alimentos e então com esses alimentos escolhidos é requisitado ao serviço de IA para gerar uma receita.
4. **Exibição do Resultado**: A receita gerada pela IA é exibida na interface do usuário.

## 🚀 Resultados
- **Interface Simples e Intuitiva**: Os usuários podem facilmente escolher no mínimo 3 alimentos e receber uma deliciosa receita.
- **Geração de Descrições Precisas**: Utilizando o GPT-3.5, conseguimos gerar receitas detalhadas e precisas dos alimentos escolhidos pelo usuário.
- **Demonstração de Integração com IA**: Este projeto serve como um exemplo prático de como integrar serviços de IA generativa em aplicações móveis, oferecendo um valor adicional aos usuários.

## Link para o Repositório do App
[link para o repositorio do app](https://github.com/glaubergustavo/RecipeByAI)

