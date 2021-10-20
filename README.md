# OracleDBScripts

Este repositório contém scripts para operações de DBA no banco de dados Oracle. O código a seguir é meu e não da Oracle Corporation. Isso é apenas para fins de teste e aprendizado, use-o na produção por sua própria conta e risco.

O script seguinte foi testado em 18c na arquitetura CDB (funciona em um PDB):

<B>Limit Parallel Queries with Resource Manager</B>: é um código de amostra para limitar a quantidade de sessões paralelas por instrução SQL. O script cria 3 grupos (alto, médio, baixo) e atribui um limite para cada um. Em seguida, ele é mapeado para um usuário no banco de dados.

O seguinte foi testado em 12.1 (captura) e 19c (reprodução):

<B>Usando_SPA_com_APIs</B>: Usando SQL Performance Analyzer para comparar a performance dos SQLs na origem e destino.

<B>Usando_DBReplay_com_APIs</B>: Usando Database Replay para comparar a performance dos SQLs na origem e destino com concorrência.
