# Semáforo da Comunicação

Uma aplicação web simples projetada para conscientizar desenvolvedores e designers sobre boas e más práticas de comunicação textual e visual em interfaces digitais.

## 🚦 Estrutura do Projeto
O conteúdo está dividido didaticamente através da metáfora visual de um semáforo (contendo 15 cards explicativos no total):
- 🟢 **VERDE**: Práticas recomendadas que impulsionam a clareza.
- 🟡 **AMARELO**: Elementos que pedem cautela e contexto para serem usados.
- 🔴 **VERMELHO**: Barreiras de comunicação que devem ser totalmente evitadas.

## ♿ Práticas de Acessibilidade Implementadas
1. **Semântica HTML5**: Uso exato de estruturas como `<main>`, `<section>`, e `<article>` para delimitar as áreas e os cards.
2. **Alto Contraste Controlado**: Cores escuras escolhidas especificamente sobre os fundos claros para passar nos testes de taxa de contraste (WCAG AA).
3. **Leitura não-dependente de Cor**: Ícones visuais (emojis) e títulos textuais acompanham os blocos coloridos para que usuários daltônicos compreendam as categorias sem depender das cores.
4. **Hierarquia Lógica**: Progressão linear correta de cabeçalhos (`<h1>`, `<h2>`, `<h3>`).
5. **Acessibilidade de Leitores de Tela**: Atributos `aria-hidden="true"` aplicados nos emojis repetitivos para evitar poluição auditiva em softwares de leitura.
6. **Responsividade Flexível**: Layout totalmente adaptável para qualquer tamanho de tela sem perda de legibilidade de texto.
