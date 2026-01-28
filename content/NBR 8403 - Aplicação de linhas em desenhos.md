---
disciplina: Desenho Técnico
data_criacao: 2026-01-28
status: ✅ Pronta
---

# 🔙 [Voltar para a Ementa](index.md.md)

# 📜 Norma: NBR 8403

## 🎯 Objetivos desta Nota
- [ ] Padronizar a largura e o tipo das linhas conforme a função no desenho.
- [ ] Estabelecer a hierarquia visual (linhas largas vs. estreitas).
- [ ] Servir de guia para a configuração de penas (layers) em softwares CAD.

---

## 📝 Conteúdo Técnico da Norma

A NBR 8403 determina que a largura das linhas deve ser escolhida conforme o escalonamento baseado em $\sqrt{2}$. As larguras padrão são: **0,13; 0,18; 0,25; 0,35; 0,50; 0,70; 1,00; 1,40 e 2,00 mm**.

### 1. Tipos de Linhas e Suas Funções



| Código | Tipo de Linha | Aplicação Principal |
| :--- | :--- | :--- |
| **A** | Contínua Larga | Contornos e arestas **visíveis**. |
| **B** | Contínua Estreita | Linhas de cota, auxiliares, hachuras e eixos curtos. |
| **C** | Contínua Estreita a mão livre | Limites de vistas parciais ou cortes rompidos. |
| **E** | Tracejada Larga | Contornos e arestas **não visíveis** (ocultas). |
| **G** | Traço e Ponto Estreita | Linhas de centro, simetria e trajetórias. |
| **H** | Traço e Ponto Larga nas extremidades | Indicação de **planos de corte**. |
| **K** | Traço e Dois Pontos Estreita | Peças móveis, contornos de peças adjacentes. |

### 2. Espaçamento e Proporção
Para que o desenho seja limpo, a norma exige consistência:
* O espaçamento entre linhas paralelas não deve ser menor que **0,7 mm**.
* Em uma mesma escala, a largura das linhas deve ser rigorosamente a mesma em todas as vistas.
* As linhas tracejadas devem se tocar nos cantos, formando ângulos definidos, nunca deixando buracos nas quinas.

==[Image showing correct vs incorrect line intersections in technical drawing]==

### 3. Hierarquia de Coincidência
Se duas linhas de tipos diferentes coincidirem no mesmo lugar, a norma estabelece uma ordem de prioridade:
1. **Contorno Visível** (Linha A) - Tem prioridade máxima.
2. **Contorno Oculto** (Linha E).
3. **Plano de Corte** (Linha H).
4. **Linhas de Centro / Simetria** (Linha G).
5. **Linhas Auxiliares** (Linha B).

---

## 🛠️ Prática e Exercícios
- **Configuração de Penas:** Se você estiver desenhando um contorno visível com 0,50 mm, qual deve ser a largura da linha de cota? (Dica: Use a proporção de metade da largura, ou seja, 0,25 mm).
- **Identificação:** Em um desenho de conjunto, identifique a linha tipo **K** e explique por que ela está representando uma peça vizinha.

---

## 🔗 Conexões Relacionadas
- **Base Prática:** [[Simbologia e Convenções]]
- **Aplicação:** [[Cortes]] (Uso da Linha H).
- **Detalhamento:** [[Cotagem]] (Uso da Linha B).

---
## 💬 Dúvidas Frequentes (FAQ)
> [!faq] Por que a linha de centro (Traço e Ponto) deve ultrapassar o contorno da peça?
> Segundo a norma, as linhas de centro devem ultrapassar levemente o contorno (cerca de 2 a 3 mm) para deixar claro que se trata de um eixo de simetria e não de uma aresta da própria peça.