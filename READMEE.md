# Lab de Cibersegurança: Ataques de Força Bruta com Medusa

Este repositório documenta um desafio prático de **Pentest** focado na simulação de ataques de força bruta e na análise de medidas defensivas. O projeto utiliza um ambiente controlado com máquinas virtuais para exercitar a exploração ética de protocolos de rede e aplicações web.

## 🚀 Objetivo do Desafio
Implementar e documentar um cenário de ataque e defesa utilizando o **Kali Linux** como máquina atacante e o **Metasploitable 2** como alvo vulnerável.

## 🛠️ Tecnologias e Ferramentas
*   **Virtualização:** Oracle VM VirtualBox.
*   **SO Atacante:** Kali Linux.
*   **SO Alvo:** Metasploitable 2 (Ambiente propositalmente vulnerável).
*   **Ferramenta de Ataque:** `Medusa` (Brute-force paralelo).
**Aplicações Alvo:** FTP, SMB e DVWA (Damn Vulnerable Web App).

## 💻 Cenários Testados
1.  **Força Bruta em FTP:** Teste de credenciais no serviço de transferência de arquivos.
2.  **Password Spraying em SMB:** Tentativa de acesso em massa utilizando uma única senha contra múltiplos usuários.
3.  **Brute Force Web (DVWA):** Automação de tentativas de login em formulários HTTP.

## 🛡️ Medidas de Prevenção (Mitigação)
A parte fundamental deste laboratório é a recomendação de boas práticas para evitar esses ataques:
*   Implementação de **Políticas de Bloqueio** (Account Lockout).
*   Uso de **Autenticação Multifator (MFA/2FA)**.
*   Monitoramento ativo de logs de falha de login.
*   Fortalecimento da complexidade de senhas.

---
*Este projeto tem fins estritamente educacionais e foi realizado em ambiente isolado.*
Use o código com cuidado.





