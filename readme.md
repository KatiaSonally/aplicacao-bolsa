Este projeto tem como objetivo desenvolver uma aplicação de negociações em bolsa de valores, utilizando TypeScript como linguagem de programação. Ele será dividido em três fases: TypeScript Básico, TypeScript Intermediário e TypeScript Avançado. Nesta primeira fase, focamos no TypeScript Básico e na construção das funcionalidades essenciais da aplicação.

<h3>Funcionalidades Implementadas</h3>
Cadastro de negociação: O usuário pode inserir uma data, uma quantidade e um valor para cadastrar uma negociação na aplicação.

Imutabilidade dos dados: Foram aplicadas soluções para garantir que os dados da negociação não possam ser modificados após o cadastro. As soluções implementadas incluem:

Utilização de getters: Acessores (getters) foram utilizados para permitir apenas a leitura dos dados da negociação, sem a possibilidade de modificação direta.

Declaração no constructor: Os dados da negociação são inicializados no construtor da classe e não podem ser modificados após a criação do objeto.

Atribuição privada (private): Os atributos da negociação foram declarados como privados, impedindo o acesso e modificação direta dos mesmos fora da classe.

Atribuição pública com o modificador readonly: Além de privados, os atributos foram declarados como somente leitura (readonly), garantindo que eles só possam ser definidos no momento da criação do objeto e não possam ser alterados posteriormente.

Programação defensiva: Medidas adicionais de programação defensiva foram implementadas para garantir que os dados da negociação sejam protegidos contra possíveis manipulações indesejadas.

![image](https://github.com/KatiaSonally/aplicacao-bolsa/assets/119110042/caf7c380-b9d8-4c92-8dbe-6afa8d652a8f)

<h3>Próximas Etapas</h3>
Nas próximas fases do projeto, serão abordados conceitos mais avançados de TypeScript, com foco em melhorias de código, boas práticas e recursos mais avançados da linguagem. Algumas das funcionalidades planejadas para as próximas etapas são:

Exibição de negociações cadastradas: Implementação de uma lista que exibirá as informações das negociações cadastradas, permitindo ao usuário visualizar o histórico de negociações.

TypeScript Intermediário: Aplicação de conceitos intermediários de TypeScript, como interfaces, tipos genéricos e decorators.

TypeScript Avançado: Exploração de recursos avançados do TypeScript, incluindo tipos condicionais, mapped types e namespaces.

<h3>Como Executar a Aplicação</h3>
Para executar a aplicação, siga os passos abaixo:

Certifique-se de ter o ambiente Node.js instalado em sua máquina.

Clone este repositório para o seu computador.

Navegue até a pasta do projeto e instale as dependências utilizando o gerenciador de pacotes do Node.js (npm ou yarn).

Execute o comando "npm start" ou "yarn start" para iniciar a aplicação.

Acesse a aplicação através do navegador utilizando o endereço http://localhost:3000 (ou outra porta, caso especificada no terminal).

<h3>Contribuições</h3>
Contribuições são bem-vindas! Se você tem alguma ideia de melhoria ou correção de bugs, sinta-se à vontade para abrir uma issue ou enviar um pull request.
