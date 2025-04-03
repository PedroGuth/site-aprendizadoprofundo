# 🧠 Rede Neural Interativa

Este projeto é uma ferramenta educacional interativa para construção e treinamento de redes neurais diretamente no navegador. Com foco visual e didático, você pode montar redes personalizadas, treinar com dados clássicos e visualizar o comportamento interno da rede em tempo real.

![screenshot](./screenshot.png) <!-- Adicione uma imagem se quiser -->

---

## ✨ Funcionalidades

- Criação visual de redes neurais:
  - Ajuste o número de camadas e neurônios
  - Selecione funções de ativação por camada (`sigmoid`, `relu`, `tanh`, `none`)
- Visualização em tempo real:
  - Pesos, biases, valores de `z` e ativações `a` por neurônio
  - Conexões coloridas e espessura proporcional ao peso
- Treinamento:
  - Treinamento manual (uma época)
  - Treinamento contínuo (épocas automáticas)
  - Treinamento completo com backpropagation
  - Erro médio exibido graficamente por época
- Validação dos dados:
  - Interface para inserir inputs e saídas esperadas
  - Cálculo da saída da rede e diferença com o esperado
- Datasets prontos:
  - `XOR`, `AND`, `OR`, `NAND`, `NOR`, `XNOR`, `Majority`, `Sum`, `Step`
- Tema claro/escuro 🌙
- Exportar e importar redes via JSON

---

## 🧠 Conceito Matemático

Cada neurônio realiza:

z = Σ(wᵢ * xᵢ) + b
a = f(z)


Onde:
- `xᵢ` são as entradas
- `wᵢ` são os pesos
- `b` é o bias
- `f(z)` é a função de ativação

O treinamento utiliza **gradiente descendente** com **backpropagation**, atualizando pesos e biases para minimizar o erro quadrático médio (MSE).

---

## 🚀 Como usar

1. Clone este repositório:
git clone https://github.com/PedroGuth/rede-neural-interativa.git

2. Abra o arquivo index.html no seu navegador.

## 📷 Demo Online
Acesse: https://aprendizadoprofundo.com.br
