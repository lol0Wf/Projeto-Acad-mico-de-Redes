# Projeto de Redes – Infraestrutura com Serviço Web e Monitoramento

## Visão Geral
Este projeto consiste na implementação de uma **infraestrutura de rede completa**, conectada à Internet, utilizando sistemas Linux e serviços reais de rede. O objetivo foi integrar **infraestrutura, segurança, serviços de rede e aplicação web**, simulando um ambiente próximo ao utilizado em cenários reais.

A rede foi projetada para oferecer conectividade segura, monitoramento em tempo real e acesso a serviços para usuários finais, com separação lógica por sub-redes e controle de tráfego.

---

## Arquitetura da Rede
- Dispositivo de borda atuando como **roteador** (LAN ↔ WAN)
- Múltiplas **sub-redes internas**
- Roteamento interno entre sub-redes
- Acesso à Internet via **NAT**
- Políticas de segurança baseadas em firewall

---

## Serviços Implementados
- **DHCP** – distribuição automática de endereços IP  
- **DNS** – resolução de nomes para hosts internos  
- **Firewall** – regras avançadas com política padrão restritiva  
- **NAT** – acesso das redes internas à Internet  
- **NTP** – sincronização de relógio dos dispositivos  
- **Wi-Fi (Access Point)** – conexão de clientes sem fio  
- **Servidor Web (Apache)** – aplicação web para usuários finais  
- **Monitoramento de Rede e Sistema** – coleta e visualização de métricas em tempo real  

---

## Monitoramento
Foi implementado um sistema de monitoramento que coleta informações sobre:
- Uso de CPU e memória
- Tráfego de rede
- Estado dos serviços
- Dispositivos conectados

O painel de monitoramento foi **integrado diretamente à aplicação web**, permitindo visualização via navegador.

---

## Segurança
- Firewall configurado com **iptables**
- Controle seletivo de tráfego por IP
- Bloqueio/liberação de serviços específicos
- Separação de acessos entre sub-redes
- Diagnóstico e varredura da rede utilizando **Nmap**

---

## Ambiente de Implementação
- Sistema operacional: **Linux (Ubuntu)**
- Infraestrutura implementada em ambiente real/virtualizado
- Serviços configurados manualmente, sem uso de simuladores simplificados

---

## Documentação
O projeto conta com documentação detalhada descrevendo:
- Topologia da rede
- Configuração dos serviços
- Regras de firewall
- Testes realizados
- Resultados obtidos

---

## Objetivo Acadêmico
Projeto desenvolvido como trabalho acadêmico com foco em:
- Redes de computadores
- Infraestrutura de sistemas
- Integração entre serviços de rede e aplicações
- Monitoramento e segurança


