# Atividade-identidade-visual-Itau-
# 🎨 Itaú Design System & Component Library

Este repositório contém a documentação e especificação visual do **Design System / Protótipo de Interface do Banco Itaú**, desenvolvido como parte da atividade acadêmica/prática de UX/UI e Design Systems.

---

## 📌 Visão Geral

O objetivo deste projeto é estruturar os fundamentos visuais, tokens de design, acessibilidade e tipografia alinhados à identidade do **Itaú**, garantindo consistência, acessibilidade (contraste) e escalabilidade no desenvolvimento de interfaces de produtos digitais.

---

## 🎨 Design Tokens & Paleta de Cores

A paleta de cores foi estruturada com variações para temas light/dark, estados de suporte (sucesso, alerta/perigo) e hierarquia primária/secundária.

### 🔴 Primárias (Brand Colors)
| Amostra | Token | Hex | Aplicação |
| :---: | :--- | :--- | :--- |
| 🟠 | `color-primary-dark` | `#CC4600` | Estados hover/active de botões primários |
| 🟧 | `color-primary` | `#FF6200` | Cor institucional / Ações primárias |
| 📙 | `color-primary-light` | `#FF8133` | Destaques sutis e elementos secundários |

### 🔵 Secundárias
| Amostra | Token | Hex | Aplicação |
| :---: | :--- | :--- | :--- |
| 🩵 | `color-secondary-light` | `#539AE9` | Destaques de apoio / Hover leve |
| 💙 | `color-secondary` | `#267FE3` | Ações secundárias / Links / Interações |
| 🟦 | `color-secondary-dark` | `#1866BE` | Estados de foco / Leitura contrastante |

### 🌑 Dark (Escuros & Neutros)
| Amostra | Token | Hex | Aplicação |
| :---: | :--- | :--- | :--- |
| ⬛ | `color-dark-light` | `#403B3B` | Textos secundários em backgrounds claros |
| 🖤 | `color-dark` | `#262323` | Cor padrão de texto principal |
| 🏿 | `color-dark-deep` | `#0B0A0A` | Headings / Backgrounds escuros |

### ⚪ Light (Claros & Neutros)
| Amostra | Token | Hex | Aplicação |
| :---: | :--- | :--- | :--- |
| ⬜ | `color-light-pure` | `#FFFFFF` | Background de cards / Modais / Texto em fundos escuros |
| 🌫️ | `color-light` | `#F2F5F7` | Background padrão da aplicação / Seções |
| 🩶 | `color-light-dark` | `#D3DDE4` | Bordas / Divisores / Desabilitados |

### 🟢 Sucesso (Success)
| Amostra | Token | Hex |
| :---: | :--- | :--- |
| 🟢 | `color-success-light` | `#76E085` |
| 🟩 | `color-success` | `#52D65F` |
| 🌲 | `color-success-dark` | `#2FC63E` |

### 🔴 Alerta / Perigo (Danger)
| Amostra | Token | Hex |
| :---: | :--- | :--- |
| 🍷 | `color-danger-dark` | `#9E1500` |
| 🟥 | `color-danger` | `#D11C00` |
| 🔴 | `color-danger-light` | `#FF2705` |

---

## 🔤 Tipografia & Escala Tipográfica (Font Scale)

A família tipográfica oficial adotada para os protótipos é a **Poppins**, devido à sua alta legibilidade em telas digitais, proporções geométricas e excelente adaptabilidade para Web e Mobile.

### Escala de Tamanhos (Font Scale)

```css
--font-family-base: 'Poppins', sans-serif;

--font-size-small:    14px; /* Textos de apoio, legendas, badges */
--font-size-paragraph:16px; /* Corpo de texto padrão (Body) */
--font-size-h5:       18px; /* Títulos de seções pequenas / Subtítulos */
--font-size-h4:       24px; /* Títulos de cards e modais */
--font-size-h3:       28px; /* Títulos de páginas secundárias */
--font-size-h2:       34px; /* Títulos de seções principais */
--font-size-h1:       40px; /* Títulos de destaque / Highlights */
