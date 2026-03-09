# POO---2026-2
Resumo

Este projeto consiste no desenvolvimento de um sistema capaz de simular uma rede elétrica residencial, permitindo o cadastro de cômodos e equipamentos elétricos, bem como a análise do consumo de energia e da carga elétrica presente em cada circuito da residência.
O sistema tem como objetivo representar de forma simplificada o funcionamento de uma instalação elétrica doméstica, possibilitando realizar cálculos relacionados à potência, corrente elétrica e consumo energético dos aparelhos conectados.
O projeto será desenvolvido na linguagem C, aplicando conceitos da Programação Orientada a Objetos por meio da utilização de estruturas (structs), modularização do código e separação entre interface e lógica do sistema.

Objetivos

-> Modelar os principais elementos de uma instalação elétrica residencial;
-> Permitir o cadastro de cômodos e aparelhos elétricos;
-> Calcular potência total e consumo energético dos equipamentos;
-> Determinar a corrente elétrica dos circuitos utilizando a Lei de Ohm;
-> Identificar possíveis situações de sobrecarga elétrica;
-> Organizar o sistema utilizando separação entre front-end e back-end.

Estruturas do Sistema 

Front-end

-> Cadastrar cômodos da residência;
-> Adicionar aparelhos elétricos;
-> Visualizar os equipamentos cadastrados;
-> Calcular consumo energético;
-> Verificar possíveis sobrecargas no circuito.

Back-end

-> Armazenamento das estruturas de dados;
-> Cálculos elétricos;
-> Gerenciamento das informações cadastradas;
-> Geração de relatórios de consumo.

Modelagem do Sistema

Casa - Representa a residência como um todo, contendo informações gerais da instalação elétrica, como tensão da rede e lista de cômodos cadastrados.

Cômodo - Representa cada ambiente da casa (sala, cozinha, quarto, etc.), armazenando os aparelhos elétricos presentes naquele local.

Aparelho - Representa um equipamento elétrico da residência, contendo informações como nome, potência elétrica e tempo médio de utilização diária.

Circuito - Responsável por representar o circuito elétrico associado ao cômodo, permitindo calcular a corrente elétrica e verificar possíveis sobrecargas.

Funcionamento do Sistema

-> Cadastrar novos cômodos;
-> Adicionar aparelhos elétricos aos cômodos;
-> Listar os equipamentos cadastrados;
-> Calcular potência total de cada ambiente;
-> Calcular o consumo diário e mensal de energia;
-> Verificar se a corrente elétrica ultrapassa o limite seguro do circuito.
