# Packet Tracer - Criando uma LAN
## Objetivo
Criar uma rede local (LAN) utilizando o Cisco Packet Tracer, conectando dispositivos finais, configurando endereçamento IPv4 e verificando a conectividade entre os hosts e a internet.
## Topologia
A rede foi composta pelos seguintes dispositivos:
- Office Router
- 1 Switch
- 2 PCs (Admin PC e Manager PC)
- 1 Impressora
- 1 Servidor Web (www.cisco.pt)
<img width="552" height="395" alt="Captura de tela 2026-06-12 091614" src="https://github.com/user-attachments/assets/a9bcaaa2-46d4-4df2-b20e-42478af45f29" />

## Atividades Realizadas
### 1. Conexão Física
- Conexão do roteador ao provedor (ISP)
- Conexão do roteador ao switch
- Conexão dos PCs ao switch
- Conexão da impressora ao switch
- Verificação do estado dos links
### 2. Configuração de Endereçamento IPv4
#### PCs
Configuração via DHCP:
- Admin PC
- Manager PC
#### Impressora
Static configuration:
- IP: 192.168.1.100
- Máscara: 255.255.255.0
### 3. Testes de Conectividade
Realizados testes de:
- Ping dos PCs para a impressora
- Ping para o servidor web
- Acesso ao servidor utilizando endereço IP
- Acesso ao servidor utilizando URL
## Results
- Todos os dispositivos conectados corretamente
- Enderaçamento IPv4 configurado com sucesso
- Comunicação entre os hosts validada
- Acesso ao servidor web confirmado
- Atividade concluída com 100% de aproveitamento
<img width="835" height="766" alt="Captura de tela 2026-06-12 091649" src="https://github.com/user-attachments/assets/9405de23-e446-4843-93c2-6dd0ae0f5dfa" />

## Conhecimentos Praticados
- Cabeamento Ethernet
- DHCP
- Endereçamento IPv4
- Gateway padrão
- Máscara de sub-rede
- Testes de conectividade com ping
- Navegação por IP E DNS
- Verificação de interfaces de rede
## Reflexão
Em uma instalação real semelhante a esta, o maior desafio geralmente é garantir que todos os dispositivos estejam corretamente conectados e configurados. Pequenos detalhes, como equipamentos desligados, cabos conectados em portas incorretas, erros de enderaçamento IP ou configurações inappropriate de DHCP e gateway, podem impedir totalmente a comunicação da rede.
Por isso, além do conhecimento técnico, a atenção aos detalhes e a capacidade de realizar testes sistemáticos são fundamentais para identificar e corrigir problemas durante a implantação de uma nova rede.
