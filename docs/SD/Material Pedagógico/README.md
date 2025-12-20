# Material Pedagógico
Conjunto de slides usados na aulas teóricas da UC no ano letivo 2025/2026

---

## [Races](1_Races.pdf)
Teste de Primalidade Paralela <br>
Contador Partilhado <br>
Procedimento para uma dada Thread <br>
Implementação <br>
Desafio

## [Locks](2_Locks.pdf)
Interface de uso de Locks <br>
Como implementar um Lock <br>
Secções Críticas <br>

## [Locks](3_Locks.pdf)
Motivações para Locks <br>
Exemplo <br>
Primeira Tentativa <br>
Multiplas Threads <br>
Deadlock <br>
Ordenação de Locks <br>
Justiça <br>
2PL <br>
Lock de Coleção <br>
Coleções com 2PL <br>

## [Locks](4_Locks.pdf)
Locks vs Variáveis <br>
Variáveis Automáticas <br>
Variáveis Globais/de Classe <br>
Locks Encapsulados <br>
Estado compartilhado vs estado local do thread <br>
Quiz <br>
Corridas de leitura <br>
Coleções e 'getters' <br>
Locks para Leitores e Escritores <br>

## [Mutex](5_Mutex.pdf)
Deadlock <br>
Starvation-Free <br>
Soluções com 2 ou mais Threads <br>
Algoritmo de Peterson <br>
O Algoritmo de Filtro para n Threads <br>
Starvation <br>

## [Mutex](6_Mutex.pdf)
Algoritmo de Bakery <br>

## [Conditions](7_Conditions.pdf)
Motivação <br>
Variavel de Condição <br>
Erros Comuns <br>
Reader-Writer com Conditions <br>
Justiça <br>
Correções <br>

## [Extra](8_Extra.pdf)
Mutex com o Algoritmo de Peterson <br>
Barreiras de Memória <br>
Usos práticos <br>
Condições vs Monitores <br>

## [Introdução a Sistemas Distribuídos](9_Intro.pdf)
Definição de Sistemas Distribuídos <br>
Objetivos <br>
Arquiteturas de Sistemas Distribuídos <br>
Cliente-Servidor <br>
Layered <br>
Event-Based <br>
Peer-to-Peer <br>
Protocolos <br>
Protobuf <br>
Middleware <br>

## [Comunicação](10_Communication.pdf)
Modelo OSI <br>
Camadas <br>
Simplificação do Modelo <br>
TCP/IP <br>
Buffering na Comunicação TCP/IP <br>
Sockets <br>
Interfaces de Sockets em Java <br>
MoM <br>
Comunicação em Grupos <br>
MPI <br>

## [Serialização](11_Serialization.pdf)
Motivação <br>
Texto vs Binário <br>
Formatos Binários <br>
Single Object vs Multiple Objects <br>
Tipos Compostos <br>
Implícito vs Explícito <br>
Tipos Compostos <br>
Program vs Data first <br>
Código de Conversão <br>
Versionamento <br>
Streaming vs Object Model <br>
Sumário <br>

## [Arquiteturas de Clientes e Servidores](12_Architectures.pdf)
Motivação <br>
RPC <br>
Single-Threaded Server <br>
Thread-Per-Connection Server <br>
Thread-Per-Request Server <br>
Thread Pool Server <br>
Notificações e Implicações <br>
Modelo Geral de Comunicação <br>
Limitações do RPC <br>
Migração de Código <br>
Desafios <br>
Virtualização <br>
Computação na Nuvem <br>
Computação na Periferia <br>
Sumário <br>

## [RPC](13_RPC.pdf)
Exemplo <br>
Paradigmas <br>
Problemas principais <br>
RPC/RMI <br>
Cliente/Servidor com Sockets <br>
Stubs <br>
Naming <br>
Geração de Stubs e Namings <br>
Gestão de Excepções <br>
Sumário <br>

## [Sincronização de Relógios](14_Clock_Synchronization.pdf)
Problemas com Relógios <br>
NTP <br>
RBS <br>
Exclusão Mútua com Relógios Físicos <br>
Problemas dos Timeouts <br>
Modelo de Sistema Assíncrono <br>
Causalidade <br>
Relógios Lógicos de Lamport <br>
Conclusão <br>

## [Transações Distribuídas](15_Distributed_Transactions.pdf)
Tolerancia a Falhas <br>
Commit Transacional <br>
2PC <br>
Problemas do 2PC <br>
3PC (ou TRPC) <br>
Replicação <br>
Quorum <br>
Bully Algorithm <br>
Consenso <br>
Paxos <br>
Sumário <br>

## [Procura de Recursos](16_Resource_Location.pdf)
Sistemas Descentralizados <br>
Procura Hierárquica <br>
DHTs <br>
Chord <br>
Multicast <br>
Problemas de Multicast <br>
Abordagens para Multicast <br>
Gossip <br>
Gossip e Epidemias <br>
Fanout vs Confiabilidade <br>
Redundância <br>
Sumário <br>

## [Final](17_Final.pdf)
Resumo <br>
Próximos Passos <br>