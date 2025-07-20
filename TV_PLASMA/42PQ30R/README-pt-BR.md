# Engenharia Reversa – LG 42PQ30R (TV de Plasma)

Este projeto documenta o processo completo de engenharia da placa Z e Y da TV de plasma LG 42PQ30R, incluindo análises de circuito, medições e diagnósticos de falhas comuns.

# _Detalhes:_

## Z-Board:

**Modelo:**

LGE PDP 081223

BOARD: 42G2_Z

PART NO: EAX57633801

REV.: M

LOC NO: 3XXX

<p align="center">
 <img src="images/Z-board-top.jpg" alt="ZBOARD" width="80%"/>
</p>

### Z-Board Topo detalhe básico

<p align="center">
 <img src="images/Z-top-detail.jpg" alt="ZBOARD-detail" width="80%"/>
</p>

### Z-Board Por baixo detalhe básico

<p align="center">
 <img src="images/Z-bottom-detail.jpg" alt="ZBOARD-detail-bottom" width="80%"/>
</p>

## Y-Board:

**Modelo:**

LGE PDP 090209

BOARD: 42G2_YSUS

PART NO: EAX57633701

REV.: N

LOC NO: 2XXX

<p align="center">
 <img src="images/Y-board-top.jpg" alt="YBOARD" width="80%"/>
</p>

### Y-Board Topo detalhe básico

<p align="center">
 <img src="images/Y-board-top-detailed.jpg" alt="YBOARD-TOP-DETAILED" width="80%"/>
</p>

### Y-Board Por baixo detalhe básico

<p align="center">
 <img src="images/Y-board-bottom-detailed.jpg" alt="YBOARD-detail-bottom" width="80%"/>
</p>

---

## 📷 Fotos e Esquemas

- Fotos gerais da placa Y-SUS [top](images/Y-board-top.jpg) [bottom](images/Y-board-bottom.jpg)
- Fotos gerais da placa Z-SUS [top](images/Z-board-top.jpg) [bottom](images/Z-board-bottom.jpg)
- [ ] Detalhes de componentes críticos (IGBTs, transformadores, optoacopladores)
- [ ] Marcação dos pinos e trilhas relevantes
- [ ] Anotações sobre modificação/limpeza de resinas

---

## 🧩 Mapeamento das Placas

### Y-SUS
- Alimentações (VSC, VY, GND)
- Etapas de chaveamento
- IGBTs utilizados
- Controle lógico (drives e osciladores)
- Observações sobre desgaste ou aquecimento

### Z-SUS
- Alimentações (VS, GND)
- Etapas de chaveamento
- Controle de sustain e apagamento
- Proteções observadas
- Análise do SCR de proteção (VY/VSC)

---

## 🛠 Modificações e Testes

- [ ] Remoção de resinas
- [ ] Substituição de transistores alterados
- [ ] Testes com os circuitos isolados
- [ ] Condução reversa para análise de chaveamento
- [ ] Observações com e sem carga

---

## 📊 Análises e Oscilogramas

- Overshoots medidos (ex: 19 MHz sem carga)
- Análise do controle de gate
- Ruídos propagados pela placa
- Comparações antes/depois de substituições

---

## 🧪 Próximos Passos

- [ ] Montagem final na TV
- [ ] Testes de estabilidade e imagem
- [ ] Captura de sinais com osciloscópio após instalação
- [ ] Registro de anomalias (caso ocorram)

---

## 📝 Conclusão

(Reservado para quando o projeto estiver próximo da finalização)

---

## 📁 Estrutura do Repositório

```bash
TV_PLASMA/
├── Y-SUS/
│   ├── fotos/
│   └── esquemas/
├── Z-SUS/
│   ├── fotos/
│   └── esquemas/
├── README.md
└── oscilogramas/

