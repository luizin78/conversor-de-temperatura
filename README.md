# conversor-de-temperatura
Conversor de Temperatura

Um conversor de temperatura simples e intuitivo que permite converter valores entre Celsius (°C), Fahrenheit (°F) e Kelvin (K).

O projeto foi desenvolvido com o objetivo de praticar lógica de programação, manipulação de dados e implementação de fórmulas matemáticas em uma aplicação prática.

Índice
Sobre o projeto
Funcionalidades
Conversões disponíveis
Tecnologias
Pré-requisitos
Instalação
Como usar
Exemplos
Estrutura do projeto
Fórmulas
Melhorias futuras
Contribuição
Licença
Autor
 Sobre o projeto

O Conversor de Temperatura é uma aplicação criada para facilitar a conversão entre diferentes escalas de temperatura.

A aplicação recebe uma temperatura, identifica a unidade de origem e permite convertê-la para outra unidade.

Escalas suportadas
 Celsius (°C)
 Fahrenheit (°F)
 Kelvin (K)

O projeto pode ser utilizado tanto para fins educacionais quanto como base para aplicações maiores que necessitem trabalhar com diferentes unidades de temperatura.

 Funcionalidades
 Converter Celsius para Fahrenheit
 Converter Celsius para Kelvin
 Converter Fahrenheit para Celsius
 Converter Fahrenheit para Kelvin
 Converter Kelvin para Celsius
 Converter Kelvin para Fahrenheit
 Aceitar valores decimais
 Exibir o resultado da conversão
 Interface gráfica
 Histórico de conversões
 Testes automatizados
 Suporte para outras unidades de temperatura
 Conversões disponíveis
De	Para	Disponível
Celsius	Fahrenheit	
Celsius	Kelvin	
Fahrenheit	Celsius	
Fahrenheit	Kelvin	
Kelvin	Celsius	
Kelvin	Fahrenheit	
 Tecnologias

As tecnologias utilizadas no projeto são:

Linguagem: Python
Versionamento: Git
Repositório: GitHub

Caso o projeto utilize outra linguagem ou tecnologia, substitua esta seção de acordo com sua implementação.

 Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

Python 3.10 ou superior
Git

Para verificar a versão do Python:

python --version


Ou:

python3 --version

 Instalação
1. Clone o repositório
git clone https://github.com/seu-usuario/conversor-temperatura.git

2. Entre na pasta do projeto
cd conversor-temperatura

3. Execute a aplicação
python main.py


Em alguns sistemas, pode ser necessário utilizar:

python3 main.py
 Como usar

Após executar o programa, informe a temperatura que deseja converter e escolha as unidades de origem e destino.

Exemplo:

=== CONVERSOR DE TEMPERATURA ===

Digite a temperatura: 25

Unidade de origem:
1 - Celsius
2 - Fahrenheit
3 - Kelvin

Escolha: 1

Unidade de destino:
1 - Celsius
2 - Fahrenheit
3 - Kelvin

Escolha: 2

Resultado: 25°C = 77°F

Exemplos
Celsius → Fahrenheit

Entrada:

25°C


Resultado:

77°F

Celsius → Kelvin

Entrada:

25°C


Resultado:

298.15K

Fahrenheit → Celsius

Entrada:

77°F


Resultado:

25°C

Kelvin → Celsius

Entrada:

300K


Resultado:

26.85°C
 Fórmulas
Celsius para Fahrenheit
°F = (°C × 9/5) + 32

Fahrenheit para Celsius
°C = (°F - 32) × 5/9

Celsius para Kelvin
K = °C + 273.15

Kelvin para Celsius
°C = K - 273.15

Fahrenheit para Kelvin
K = (°F - 32) × 5/9 + 273.15

Kelvin para Fahrenheit
°F = (K - 273.15) × 9/5 + 32

Estrutura do projeto

Uma possível estrutura para o projeto:

conversor-temperatura/
│
├── main.py
├── README.md
├── requirements.txt
└── .gitignore

Descrição dos arquivos
Arquivo	Descrição
main.py	Arquivo principal da aplicação
README.md	Documentação do projeto
requirements.txt	Dependências do projeto
.gitignore	Arquivos ignorados pelo Git
Objetivos do projeto

Este projeto pode ser utilizado para praticar:

Lógica de programação
Operações matemáticas
Funções
Condicionais
Entrada e saída de dados
Validação de informações
Organização de código
Versionamento com Git
🔮 Melhorias futuras

Algumas funcionalidades que podem ser adicionadas futuramente:

Criar uma interface gráfica.
Criar uma versão web.
Adicionar suporte para Rankine.
Adicionar histórico de conversões.
Permitir conversões em lote.
Adicionar validação mais completa dos valores informados.
Criar testes automatizados.
Adicionar arredondamento configurável.
Criar uma API para realizar conversões.
Adicionar suporte a diferentes idiomas.
 Contribuição

Contribuições são bem-vindas!

Para contribuir:

Faça um fork do projeto.
Crie uma nova branch:
git checkout -b feature/nova-funcionalidade

Faça suas alterações.
Faça o commit:
git commit -m "feat: adiciona nova funcionalidade"

Envie suas alterações:
git push origin feature/nova-funcionalidade

Abra um Pull Request.
 Encontrou um problema?

Caso encontre algum bug ou tenha uma sugestão de melhoria, abra uma Issue descrevendo o problema ou a funcionalidade desejada.

Ao reportar um problema, procure incluir:

O que aconteceu;
O que você esperava que acontecesse;
Passos para reproduzir o problema;
Mensagens de erro, caso existam;
Sistema operacional utilizado.
 Licença

Este projeto está disponível sob a licença MIT.

Você pode utilizar, modificar e distribuir o projeto de acordo com os termos da licença.

Autor

Desenvolvido por Seu Nome.

GitHub: @seu-usuario
LinkedIn: Seu Nome

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!

Feito com 💻 e 🌡️
