# Jogo do Número Secreto

Um jogo interativo e responsivo desenvolvido com HTML, CSS e JavaScript, onde o usuário deve adivinhar um número secreto gerado aleatoriamente pelo sistema.

O projeto conta com recursos visuais e narração por voz (Text-to-Speech) para tornar a experiência mais dinâmica e acessível.

---

## Funcionalidades

- **Geração Aleatória Inteligente**: O jogo sorteia um número entre 1 e 10 e armazena os números já sorteados para evitar repetições imediatas.
- **Dicas Dinâmicas**: Informa se o número secreto é maior ou menor a cada chute incorreto.
- **Contador de Tentativas**: Exibe o total de chutes necessários para acertar, tratando a concordância singular/plural.
- **Feedback por Voz**: Narração em Português do Brasil com a biblioteca *ResponsiveVoice*.
- **Reinício Fácil**: Permite iniciar uma nova rodada diretamente pelo botão "Novo jogo", sem precisar recarregar a página.

---

## Tecnologias Utilizadas

- **HTML5**: Estruturação semântica da página.
- **CSS3**: Estilização moderna e layout responsivo.
- **JavaScript (ES6+)**: Lógica do jogo, manipulação do DOM e controle de estado.
- **[ResponsiveVoice API](https://responsivevoice.org/)**: Recurso de acessibilidade para sintetização de voz.

---

## Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Carlosvms/Jogo-numero-secreto.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd Jogo-numero-secreto
   ```

3. **Abra o arquivo `index.html`:**
   - Dê dois cliques no arquivo `index.html`, ou
   - Use uma extensão como o **Live Server** no VS Code.

> **Nota:** Para que a narração de voz funcione corretamente, certifique-se de estar conectado à internet (já que a biblioteca *ResponsiveVoice* é carregada via CDN).

---

## Contexto

Projeto desenvolvido durante o curso de **Lógica de Programação com JavaScript** do programa ONE[Alura](https://www.alura.com.br/).

---

Desenvolvido por [Carlos](https://github.com/Carlosvms).