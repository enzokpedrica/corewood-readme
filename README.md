# CoreWood

**Da modelagem à máquina, sem trabalho manual no meio.**

Plataforma de automação da engenharia de produto para a indústria moveleira.
Recebe a modelagem 3D e devolve documentação técnica, programação de máquina
e dados de ERP — automaticamente.

---

## O problema

Entre a modelagem 3D e o produto pronto para a fábrica existe um bloco de
trabalho manual: documentos de furação e usinagem, roteiro de produção,
paletização, programação CNC, preenchimento de ERP. É lento, depende da
memória e da experiência de pessoas específicas, e está sujeito a erro —
peça errada, código trocado, operação esquecida.

## O que o CoreWood faz
CAD (.step)  →  CoreWood  →  Documentação técnica  →  ERP + chão de fábrica

A partir da geometria 3D, gera automaticamente:

- Documentos de furação, usinagem e grampeação
- Roteiro de produção integrado ao ERP
- Documento de paletização com validação automática de peso e altura
- Programação CNC (conversão STEP → MPR, HOMAG/Weeke)
- Exportação de PDFs em lote
- Gestão documental e impressão rastreável

## Resultados

Medidos em testes cronometrados com usuários reais, em produtos reais da linha —
não estimados.

| Processo              | Antes    | Depois | Redução |
|-----------------------|----------|--------|---------|
| Roteiro de produção   | 3h50     | 6 min  | **97%** |
| Paletização           | 27 min   | 4 min  | **85%** |
| Documento de furação  | 45 min   | 11 min | **76%** |
| Exportação de PDFs    | 25 min   | 6 min  | **76%** |
| Exportação BHX        | 20 min   | 5 min  | **75%** |

No teste de roteiro, os erros de preenchimento caíram de **8 para 0**.

Além do tempo: processos que dependiam de uma única pessoa ou de um
computador específico passaram a estar disponíveis para toda a equipe, e
regras que viviam na memória (ou em cadernos de anotações) passaram a ser
validadas pelo sistema.

## Stack

Python · FastAPI · React · PostgreSQL · Docker · pythonOCC

## Status

Em produção. Desenvolvimento e manutenção próprios.

---

© Todos os direitos reservados.
