# Laboratório Cisco Packet Tracer - Configuração de DHCP em Roteador Wireless
## Objetivo
Configurando um roteador wireless como servidor DHCP para distribuir endereços IP automaticamente para três computadores da rede.
## Concepts Praticados
- DHCP (Dynamic Host Configuration Protocol)
- Default gateway
- Endereçamento IPv4
- Renovação de endereço IP
- Testes de connectivity
- Administração básica de roteadores
---
## Topologia
A rede foi composta por:
- 1 Roteador Wirelees com DHCP habilitado
- 3 PCs clientes
- Conexões Ethernet entre os dispositivos
<img width="1031" height="494" alt="Captura de tela 2026-06-07 085410" src="https://github.com/user-attachments/assets/31b2f260-b219-4741-baae-2f9808e7cc5c" />


## Configuração Realizada
### 1. Verificação do DHCP padrão
Foi verificado o funcionamento do DHCP padrão do roteador, observando:
- Default gateway
- Faixa de endereços distribuídos
- Configuração inicial do servidor DHCP
### 2. Alteração do endereço IP do roteador
O endereço do roteador foi alterado para:
'''text
192.168.5.1
'''
Após a alteração foi necessário renovar os endereços IP dos clientes.
### 3. Alteração da faixa DHCP
Configuração aplicadas:
'''text
IP Inicial: 192.168.5.126
Máximo de usuários: 75
'''
### 4. Renovação dos clientes
Os computadores foram configurados para obter automaticamente novos endereços via DHCP.
### 5. Testes de conectividade
Foram realizados testes de comunicação utilizando:
'''bash
ipconfig
ping 192.168.5.1
ping 192.168.5.126
ping 192.168.5.127
'''
Todos os testes retornaram com sucesso.
---
## Resultado
O servidor DHCP distribuiu corretamente os endereços IP para todos o clientes da rede.
Os dispositivos conseguiram se comunicar entre si e com o roteador sem falhas.
---

## Evidências 1

<img width="1341" height="937" alt="Captura de tela 2026-06-07 085329" src="https://github.com/user-attachments/assets/6573a5b1-84b4-4f60-848b-57b2041db472" />

---

## Evidência 2

<img width="783" height="580" alt="Captura de tela 2026-06-07 085549" src="https://github.com/user-attachments/assets/b0498fe5-a584-48db-8e42-5c8b34b13213" />
