# Tipo de gramática

O programa informa o tipo de gramática da linguaguem baseado nas regras inseridas pelo usuário.
Os tipos de gramática possíveis são:
Tipo 0: Sem restrição
aceita regras do tipo α->β

Tipo 1:Sensível ao contexto

Aceita regras do tipo α->β

Para α,β quaiser. Onde, |α|<= |β|

exceção: será aceito S->ε se o não terminal S não aparecer no lado direito de uma regra.

Tipo 2:livre de contexto

A->β

Para A,β quaisquer. Onde A é não-terminal.

Tipo 3: gramática regular

Seguindo esses tipos a seguir:
A->aB

A->a

A->ε

Confira o arquivo exemplo.txt para saber como funciona a entrada das regras.
