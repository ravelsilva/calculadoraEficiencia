# 📈 Calculadora de Eficiência de Chamados

Este projeto é uma calculadora web feita em HTML, CSS e JavaScript puro, criada para medir a eficiência de atendimento de chamados no ambiente de trabalho.
Ela ajuda a prever prazos de fechamento com base no tempo de resposta inicial e em diferentes níveis de eficiência.

---

<img width="335" height="560" alt="image" src="https://github.com/user-attachments/assets/9f746950-9eaa-4ec6-bdbd-2752f3dba2ad" />
<img width="395" height="552" alt="image" src="https://github.com/user-attachments/assets/64f08f60-e1c9-43d7-ab79-8432700396a9" />

---

## 🚀 Como Funciona

1. **Informe os dados:**
   - ⏰ **Hora de abertura do chamado**
   - ⏰ **Hora em que o chamado foi pego**

2. O sistema:
   - 🔒 Valida se os horários estão **dentro do expediente permitido** (08:00 às 18:00) e **fora do horário de almoço** (12:00 às 13:00).
   - 🧮 Calcula o **tempo necessário** para fechar o chamado em diferentes cenários de eficiência (70%, 75%, 80%, 85% e 90%).
   - 📅 Exibe até **duas possibilidades** de fechamento (mesmo dia ou dias seguintes, se ultrapassar o expediente).
   - 📊 Mostra o **TMA (Tempo Médio de Atendimento)** **acumulado** — por exemplo, `40:00:00` significa **40 horas úteis corridas**, não um horário de relógio.
   - 🚨 Alerta se o TMA ultrapassar o limite aceitável (ex.: 10 horas).

---

## ⏰ Regras de Horário

- ✅ Chamados só podem ser **abertos ou pegos** entre **08:00 e 18:00**.
- 🚫 Não é permitido abrir ou pegar chamados **durante o intervalo de almoço** (12:00–13:00).
- 🕒 O cálculo desconta automaticamente **1 hora de almoço** em cada dia útil que o atendimento ultrapassar.

---

## ⚙️ Tecnologias

- **HTML5**
- **CSS3** (estilos embutidos)
- **JavaScript** (vanilla JS)

---

## 💻 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/ravelsilva/calculadoraEficiencia.git
Abra o arquivo index.html em qualquer navegador moderno.

Preencha:

Hora de abertura

Hora que pegou

Clique em Calcular.

Veja:

⏳ As possibilidades de fechamento

⏳ O TMA acumulado

✅ Se está dentro ou fora da meta

🧑‍💼 Motivação
Desenvolvi esta calculadora para medir a eficiência dos atendimentos de chamados no meu trabalho atual, de forma prática, rápida e visual.
Ela ajuda a controlar prazos, planejar esforços e manter a equipe alinhada às metas de SLA.

📜 Licença
Uso interno. Sinta-se à vontade para adaptar e evoluir!
🚫 Proibido uso comercial sem autorização.
