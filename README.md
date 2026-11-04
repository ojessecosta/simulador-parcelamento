# 💳 Simulador de Parcelamento Comercial

Um simulador interativo de parcelamento desenvolvido em **HTML, CSS e JavaScript puro** (Vanilla JS), projetado para calcular taxas dinâmicas de cartão de crédito, valores de entrada, pagamentos à vista (Pix/Dinheiro/Débito) e o parcelamento detalhado em até **18x** com base em faixas de juros progressivas.

---

## 🚀 Funcionalidades

* **Cálculo em Tempo Real:** Atualização automática de todos os valores e taxas conforme o usuário digita o preço do produto ou o valor da entrada.
* **Múltiplas Formas de Pagamento:**
  * Cálculo dinâmico para Pix, Transferências e Dinheiro (valor líquido sem acréscimo).
  * Simulação de pagamento no **Débito** com taxa fixa aplicada.
* **Tabela de Parcelamento Detalhada (1x a 18x):**
  * Apresentação da parcela mensal e do valor total final do produto.
  * Incidência de taxas de juros progressivas específicas por quantidade de parcelas.
* **Validação de Entrada:** Restrição de caracteres nos inputs numéricos para garantir a integridade dos dados inseridos.
* **Formatação Monetária Padrão Brasil (`pt-BR`):** Exibição limpa e formatada com separadores de milhar e casas decimais corretas.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica da interface do usuário.
* **CSS3:** Estilização moderna com design responsivo, gradientes lineares, efeitos de foco em inputs e tabela estilizada com linhas alternadas.
* **JavaScript (Vanilla):** Lógica de cálculo financeiro, manipulação dinâmica do DOM em tempo real via `setInterval` e formatação de moeda com a API `Intl`.

---

## 📂 Estrutura do Código

O projeto foi construído em arquivo único para facilitar o deploy rápido e o uso local ou incorporado:

* `index.html`: Contém a estrutura HTML, as regras de estilo incorporadas (`<style>`) e a lógica de script interativa (`<script>`).

---
