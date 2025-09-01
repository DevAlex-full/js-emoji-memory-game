# 🧠 Jogo da Memória

Um jogo da memória interativo desenvolvido com HTML, CSS e JavaScript vanilla. O objetivo é encontrar todos os pares de emojis idênticos virando as cartas.

## 🎮 Como Jogar

1. Clique em uma carta para revelá-la
2. Clique em uma segunda carta para tentar formar um par
3. Se as cartas forem iguais, elas permanecerão viradas
4. Se forem diferentes, elas voltarão a ficar viradas para baixo
5. Continue até encontrar todos os pares
6. Vença o jogo quando todos os pares forem encontrados!

## 🚀 Funcionalidades

- **Interface Responsiva**: Design adaptável para diferentes tamanhos de tela
- **Animações 3D**: Efeito de flip nas cartas com transições suaves
- **Sistema de Pareamento**: Lógica que verifica automaticamente se as cartas formam um par
- **Reset do Jogo**: Botão para reiniciar a partida a qualquer momento
- **Feedback Visual**: Indicações visuais claras para cartas abertas e pareadas
- **Emojis Temáticos**: Conjunto diversificado de emojis como símbolos do jogo

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica do jogo
- **CSS3**: 
  - Flexbox para layout responsivo
  - Transforms 3D para animações das cartas
  - Gradientes e efeitos visuais modernos
- **JavaScript ES6+**:
  - Manipulação do DOM
  - Event handling
  - Algoritmo de embaralhamento
  - Lógica de verificação de pares

## 📁 Estrutura do Projeto

```
jogo-da-memoria/
├── index.html
├── src/
│   ├── styles/
│   │   ├── reset.css
│   │   └── main.css
│   └── scripts/
│       └── engine.js
└── README.md
```

## 🎨 Características Técnicas

### CSS
- **Layout Grid**: Utiliza flexbox para organizar as 16 cartas em um grid 4x4
- **Animações 3D**: Implementa `transform-style: preserve-3d` e `perspective` para efeitos de rotação
- **Design Moderno**: Gradiente de fundo com cores vibrantes e tipografia elegante
- **Estados Visuais**: Classes CSS para diferentes estados das cartas (fechada, aberta, pareada)

### JavaScript
- **Embaralhamento**: Algoritmo simples de randomização dos emojis
- **Controle de Estado**: Gerenciamento de cartas abertas e verificação de pares
- **Prevenção de Bugs**: Limitação de 2 cartas abertas simultaneamente
- **Detecção de Vitória**: Verificação automática quando todos os pares são encontrados

## 🔧 Como Executar

1. Clone ou baixe o projeto
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Comece a jogar!

```bash
# Ou serve localmente (opcional)
# Usando Python
python -m http.server 8000

# Usando Node.js
npx serve .
```

## 🎯 Próximas Melhorias

- [ ] Sistema de pontuação baseado no número de tentativas
- [ ] Cronômetro para medir o tempo de conclusão
- [ ] Diferentes níveis de dificuldade (3x3, 5x5, 6x6)
- [ ] Temas customizáveis de emojis
- [ ] Ranking local de melhores tempos
- [ ] Efeitos sonoros
- [ ] Modo multijogador

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir novas funcionalidades
- Enviar pull requests
- Melhorar a documentação

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

**Desenvolvido com ❤️ usando JavaScript vanilla**
