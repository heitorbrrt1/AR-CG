# Sistema de Auxílio à Cubagem e Picking via WebXR

Projeto desenvolvido para a disciplina de [Nome da Matéria] utilizando **Three.js** e **WebXR API**. O sistema projeta caixas virtuais em superfícies reais e valida regras logísticas de empilhamento.

## 🚀 Funcionalidades

- **Detecção de Superfície:** Uso de *Hit Testing* para identificar o chão.
- **Geração Dinâmica:** Caixas com dimensões (0.2m - 0.5m) e cores baseadas no volume calculado.
- **Lógica de Cubagem:**
  - 🔴 **Vermelho:** V > X (Pesado)
  - 🟢 **Verde:** Y < V < X (Médio)
  - 🔵 **Azul:** V < Y (Leve)
- **Picking Guiado:** Validação de empilhamento (ex: Caixas vermelhas não podem ficar sobre azuis). Feedback visual imediato em caso de erro.

## 🛠️ Tecnologias

- HTML5 / CSS3 (Design Responsivo)
- Three.js (Renderização 3D)
- WebXR Device API (Realidade Aumentada)

## 📱 Como Testar

1. Acesse o projeto (necessário Android com Chrome atualizado):
   👉 **[Link da sua Vercel ou GitHub Pages aqui]**
2. Aponte para o chão até surgir a retícula.
3. Toque para adicionar caixas e testar o empilhamento.

## 📋 Autor
[Seu Nome] - [Sua Matrícula]