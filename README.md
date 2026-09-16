# Painel de Gestão — Isabel Cortinas

Case study. Código e dados são de propriedade do cliente e não estão neste repositório.

Sistema de gestão para uma loja de persianas, cortinas e toldos (Teresina/PI). Desenvolvido sob demanda, em produção.

## Escopo

Fluxo de pedido completo: Atendimento → Conferência de Medidas → Produção → Montagem/Retirada → Concluído.

Módulos: estoque, fluxo de caixa, agenda, usuários (com permissões por papel) e clientes.

## Funcionalidades

- Cadastro de itens com medidas, lado de comando (motorizado), quantidade e acessórios.
- Colunas de produção separadas por tipo de produto, com permissão por papel.
- Agrupamento de itens por pedido nas etapas de montagem/retirada.
- Agendamento de montagem.
- Envio de avaliação via WhatsApp.
- Lançamento automático no fluxo de caixa a partir do formulário de pedido.
- Agenda com visualização por mês/dia.
- Geração de documentos para impressão (orçamento/pedido).

## Stack

Frontend single-file (HTML/JS/CSS, sem framework). Banco de dados Postgres (Supabase) com Row Level Security. Deploy contínuo via Vercel.
