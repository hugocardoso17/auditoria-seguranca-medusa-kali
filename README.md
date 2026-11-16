# Auditoria de Segurança com Kali Linux e Medusa

## Sobre o projeto

Este projeto foi desenvolvido como parte do desafio da DIO, com o objetivo de estudar vulnerabilidades relacionadas à autenticação e compreender o funcionamento de ataques de força bruta e password spraying.

Os experimentos foram realizados em um laboratório virtual isolado, utilizando Kali Linux, Medusa, Metasploitable 2 e DVWA.

## Objetivos

- Compreender ataques de força bruta.
- Realizar reconhecimento de serviços com Nmap.
- Testar autenticação FTP utilizando Medusa.
- Estudar vulnerabilidades em formulários web utilizando DVWA.
- Realizar enumeração de usuários e testes controlados em SMB.
- Identificar riscos e apresentar medidas de mitigação.

## Ambiente utilizado

| Componente | Ferramenta |
|---|---|
| Virtualização | VirtualBox |
| Sistema atacante | Kali Linux |
| Máquina vulnerável | Metasploitable 2 |
| Aplicação web | DVWA |
| Reconhecimento | Nmap |
| Auditoria de autenticação | Medusa |
| Enumeração SMB | Enum4linux |

Rede utilizada: Host-only.

## 1. Reconhecimento com Nmap

Descrever a descoberta dos serviços disponíveis no alvo, as portas encontradas e suas respectivas versões.

Comando utilizado:

`nmap -sV IP_DO_ALVO`

## 2. Teste de autenticação FTP

Descrever a utilização do Medusa, as wordlists utilizadas e os resultados encontrados.

Incluir evidências da execução.

## 3. Teste de autenticação Web - DVWA

Descrever o funcionamento do módulo Brute Force, as tentativas controladas e a análise das respostas HTTP.

Ferramentas utilizadas: DVWA e Burp Suite/Hydra.

## 4. Enumeração e Password Spraying - SMB

Documentar a enumeração de usuários, a identificação dos compartilhamentos e o teste controlado de autenticação.

## 5. Resultados

Apresentar os resultados efetivamente obtidos em cada cenário, incluindo limitações e evidências.

## 6. Medidas de mitigação

- Utilização de senhas fortes e exclusivas.
- Autenticação multifator.
- Limitação de tentativas de autenticação.
- Monitoramento de logs.
- Desativação de serviços desnecessários.
- Restrição de acesso aos compartilhamentos SMB.
- Implementação de mecanismos de detecção de password spraying.

## 7. Conclusão

O desenvolvimento deste laboratório permitiu compreender como vulnerabilidades de autenticação podem ser exploradas em ambientes desprotegidos.

Também foi possível estudar a importância de mecanismos de proteção, monitoramento e políticas de segurança para reduzir os riscos de acesso não autorizado.

## Aviso ético

Todos os testes foram realizados em ambiente virtual controlado, exclusivamente para fins educacionais.

Nenhum sistema de terceiros foi utilizado como alvo.