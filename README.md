# BancoDeDados-Projeto-ModeloEntidadeRelacionamento
Aluno: Iago Carvalho Guimarães
Requisitos mínimos:
1. Identificação das principais entidades:Estas são, Aluno, Professor, Cadeira e Terceirizado
2. Atributos essenciais:
    2.1 RG e CPF para dulto;
    2.2 Matrícula para aluno;
    2.3 Código da cadeira para cadeira;
    2.4 Código do projeto para atividades extra curriculares;
4. Relacionamento entre as entidades:
    3.1 Pessoa, Aluno e adulto: Pessoa tem um relacionamento total e exclusivo com relação a aluno e adulto;
    3.2 Adulto, responsável e contratado: Adulto tem um relacionamento total e não exclusivo entre responsável e contratado;
    3.3 Contratado, professor e terceirizado: Contratado tem um relacionamento total e exclusivo entre professor e terceirizado;
5. Cardinalidade:
    4.1 Responsável legal e aluno: Um mesmo responsável pode ser o responsável legal de do mínimo 1 e no máximo n alunos, e 1  aluno so pode ter 1 responsável legal;
    4.2 Aluno e cadeira: Aluno pode estar matriculado em no mínimo 1 cadeira e no máximo n, e matriculados em uma mesma      cadeira pode ter no mínimo 0 alunos e no máximo n;
    4.3 Professor e cadeira: Professor ensina no mínimo 1 e no máximo n cadeiras, e cada cadeira tem no mínimo 1 professor e no máximo 1 professor;
    4.4 Professor e atividades extra curriculares: Professor supervisiona no mínimo 0 projetos extra curriculares e no máximo n, enquanto a atividade extra curricular tem no mínimo 1 professor e no máximo n;
    4.5 Aluno e atividades extra curriculares: O aluno participa de 0 ou 1 atividade extra curricular, e cada atividade extra curricular tem no mínimo 1 aluno e no máximo n;
7. Especialização-generalização: Casos de especialização e generalização para simplificar e repetir ao mínimo os atributos se encontram entre:
    6.1 Pessoa, adulto e aluno;
    6.2 Adulto, Responsável e contratado;
    6.3 Contratado, professor e terceirizado;

Requisitos adicionais:
  1. Atributo composto: Encontrado no nome e sobrenome da entidade pessoa, o motivo é que como nome próprio varia de tamanho é necessário impor um limite para apenas nome e sobrenome
  2. Atributo opcional: Para casos que pode haver uma resposta ou não como por exemplo, deficiência para pessoa, desconto na mensalidade para aluno, dias ausentesa e licensa para contratado, auxílio para terceirizado.
