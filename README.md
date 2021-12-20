# Abstração
- Abstração é o processo que isola quais são as caracteristacas e comportametos relevantes de um objeto em um dado contexto sem se importa com será sua implementação
- Com a abstração é possível alcaçar as responstas das seguintes pergunstas:
    - O QUE o objeto deve SABER, nesse dado contexto?
    - O QUE o objeto deve FAZER, nesse dado contexto?
        - A abstração não tem comoo objetivo dizer COMO fazer
- A abstração permite expor O QUE o objeto faz sem expor COMO ele FAZ 
    - Não expoe a implementação
    - Alterar O QUE o objeto faz (API), afetará outros objetos

# Encapsulamento
- O encapsulamento permite agrupar dados e código em um único local
- O encapsulamento permite restringir acesso direto a membros do objeto
- O encapsulamento permite esconder os detalhes da implementação do objeto
    - Alterar COMO o objeto FAZ (implementação), não afetá outros objetos

# Herança
- A herança possibilita que classes herdeiras reutilizem ou ocultem dados herdados de outra classe
- A herança possibilita que classes herdeiras reutilizem, extendam ou substituam código herdados de outra classe

# Polimorfismo
- O polimorfismo possibilita definir uma única forma de acesso e ter diversas implementações diferentes

----
----
----

# Interfaces
- Um interface separa O QUE deve ser feito do COMO deve ser feito
- Um interface oculta a implementação
- Um interface exibe a funcionalidade
- Um interface pemite que classes que não se conheçam possam se comunicar

# Classe Abstratas
- Um classe que não pode ser instânciada
- Um classe que representa um conceito
- Um classe que diz O QUE sabe e COMO sabe
- Um classe que diz O QUE FAZER, mas não diz COMO FAZER
- Um classe que pode ter métodos abstrados e não-abstratos
- Um classe que estimula o uso da HERANÇA
- Um classe que implementa uma abstração variável (0-100%)