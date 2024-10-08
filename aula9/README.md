# Diagrama de Casos de Uso
### Atores podem ser:
- Humanos;
- Máquinas;
- Sistemas externos;
- Sensores;
- Unidades organizacionais.

### Casos de Uso
- São representados por uma elipse.

### Sistema
- É representado por um retângulo que engloba os casos de uso referentes ao sistema.

### Exemplo de Diagrama de Caso de Uso:
#### Sistema caixa eletrônico
- Imagine um sistema de caixa eletrônico, que tem vários casos de uso;
- **Atores**: Titular do Cartão, Banco;
- **Casos de Uso**: Scar dinheiro, verificar saldo, transferir fundos, depositar dinheiro.

### Relacionamento em Diagramas de Casos de Uso
- Os relacionamentos ilustram como diferentes atores e casos de uso interagem dentro de um sistema.
- **Associação**: Representa a interação entre um ator e um caso de uso. Um 'Titular do Cartão' pode se associar ao caso de uso 'Scara Dinheiro' em um sistema de caixa de banco.
- **Incluir <\<include>>**: Um relacionamento include significa que o caso de uso A **sempre** irá incluir (utilizar) o caso de uso B.
  - Representado por uma seta tracejada que deve conter o nome <\<include>>.
- **Extensão <\<extend>>**: Um relacionamento extend significa que o caso de uso A **pode ou não estender (utilizar) o caso de uso** B.

### Diretrizes para Diagrams de Caso de Uso
- **Padrões de Nomenclatura**: Utilize nomes claros e concisos para atores e casos de uso, geralmente na forma de substantivos e verbos, respectivamente;
- **Direções de Seta**: As setas devem indicar a direção da comunicação ou interação;
- **Posicionamento de Casos de Uso**: Organizee os casos de uso lógicamente dentro do diagrama para melhorar legibilidade;
- **Uso de Caixas do Sistema**: As caixas do sistema representam claramente os limites do sistema que está sendo modelado;
- **Uso adequado de Relacionamentos**: Utilize os relacionamentos apropriados entre osw elementos para representar com precisão as interações e relacionamentos.

### Tipos de Casos de Uso
- **Diagrama de Caso de Uso**: Fornece uma visão geral de alto nível dos casos de uso do sistema;
- **Caso de uso Informal**: Oferece uma descrição breve e informa do cenário de interação.
