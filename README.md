# Atividade Vivencial 2 – Processamento Gráfico  
## Parallax Scrolling

### 📅 Entrega
- **Data limite**: 31/05/2025, até 23h59, via Moodle  
- **Envio**: Link para este repositório com o código-fonte e este arquivo `README.md`  
- **Ajustes permitidos até**: 07/06/2025 (novos commits serão considerados)

---

### 🧾 Descrição da Tarefa

Esta atividade tem como objetivo reforçar os conceitos de **mapeamento de texturas** e **transformações em objetos** utilizando camadas com deslocamento diferenciado (efeito de Parallax Scrolling).

---

### ✅ Requisitos implementados

1. **Personagem controlável**:
   - Um sprite foi definido como personagem principal.
   - Movimentação com as teclas direcionais:
     - `←` e `→` para esquerda e direita
     - `↑` e `↓` para cima e baixo

2. **Cenário em camadas (parallax)**:
   - O fundo da cena é composto por múltiplas camadas.
   - As camadas foram posicionadas inicialmente alinhadas.

3. **Deslocamento com efeito Parallax**:
   - Ao mover o personagem, todas as camadas se deslocam.
   - Camadas **próximas** ao personagem (ex: chão, árvores) deslocam-se **mais rápido**.
   - Camadas **distantes** (ex: montanhas, nuvens) deslocam-se **mais lentamente**.

---

