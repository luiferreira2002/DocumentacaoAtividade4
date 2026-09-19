# DocumentacaoAtividade4
### Dispositivos

| ID | Nome | Modelo | Camada / função |
|----|------|--------|-----------------|
| D01 | Router0 | Cisco 2811 | Núcleo / roteamento |
| D02 | Switch0 | Switch-PT-Empty | Distribuição |
| D03 | Switch0(2) | Switch-PT-Empty | Distribuição |
| D04 | Switch0(1) | Switch-PT-Empty | Agregação (esquerda) |
| D05 | Switch0(3) | Switch-PT-Empty | Agregação (direita) |
| D06 | Switch4 | Cisco 2950-24 | Acesso |
| D07 | Switch5 | Cisco 2950-24 | Acesso |
| D08 | Switch6 | Cisco 2950-24 | Acesso |
| D09 | Switch7 | Cisco 2950-24 | Acesso |
| D10–D13 | PC0 … PC3 | PC-PT | Hosts finais |
| D14–D17 | Laptop0 … Laptop3 | Laptop-PT | Hosts finais |
| D18 | Server0 | Server-PT | Servidor |

### Conexões

| ID | Dispositivo A | Dispositivo B | Cabo | Estado |
|----|---------------|---------------|------|--------|
| L01 | Router0 | Switch0 | Direto | Ativo |
| L02 | Router0 | Switch0(2) | Direto | Ativo |
| L03 | Switch0 | Switch0(2) | Feixe de enlaces paralelos | Parcial (bloqueio) |
| L04 | Switch0 | Switch0(1) | Crossover | Bloqueado |
| L05 | Switch0 | Switch0(3) | Crossover | Ativo |
| L06 | Switch0(2) | Switch0(1) | Crossover | Ativo |
| L07 | Switch0(2) | Switch0(3) | Crossover | Ativo |
| L08 | Switch0(1) | Switch4 | Crossover | Ativo |
| L09 | Switch0(1) | Switch5 | Crossover | Ativo |
| L10 | Switch0(3) | Switch6 | Crossover | Ativo |
| L11 | Switch0(3) | Switch7 | Crossover | Ativo |
| L12 | Switch4 | PC0 | Direto | Ativo |
| L13 | Switch4 | PC1 | Direto | Ativo |
| L14 | Switch5 | PC2 | Direto | Ativo |
| L15 | Switch5 | PC3 | Direto | Ativo |
| L16 | Switch6 | Laptop0 | Direto | Ativo |
| L17 | Switch6 | Laptop1 | Direto | Ativo |
| L18 | Switch7 | Laptop2 | Direto | Ativo |
| L19 | Switch7 | Laptop3 | Direto | Ativo |
| L20 | Switch7 | Server0 | Direto | Ativo |
