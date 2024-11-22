# modelagem_mecanica
Desafio proposto como uma das etapas do bootcamp Coding the Future Suzano - Análise de Dados com Power Bi

A narrativa propõe a criação de um sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.

O esquema conceitual consiste em 5 entidades principais:

**Cliente, Veículo, Ordem de Serviço, Equipe e Mecânico**

- Cada cliente pode ter um ou mais veículos, mas um veículo so pode ter um único dono. Portanto, a relação é de 1:N.

- Cada veículo é contemplado por uma ordem de serviço e uma ordem de serviço contempla um só veículo. Portanto, o relacionamento é de 1:1.

- Cada ordem de serviço é designada a uma equipe de mecânicos, além de realiza-la, a equipe também fornece informações como o valor do serviço completo. Além disso, uma equipe pode ter mais de uma ordem de serviço, sendo o relacionamento entre essas duas entidades de 1:N.

- Cada equipe possui mais de um mecânico, mas um mecânico não pode ter mais de uma equipe. Portanto, relacionamento de 1:N.
