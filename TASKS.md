# Tarefas sugeridas após revisão

1. **Corrigir erro de digitação no README**
   - Contexto: na seção "Aprendizado Atual" o item sobre Tailwind CSS termina com a palavra truncada "cust" em vez de "customizável" (linha 16 do README.md).
   - Tarefa: ajustar o texto para completar a palavra e manter a frase coerente.

2. **Corrigir bug de responsividade no HTML**
   - Contexto: `index.html` não declara a meta tag `viewport`, o que causa zoom e escala incorretos em dispositivos móveis e tablets.
   - Tarefa: adicionar `<meta name="viewport" content="width=device-width, initial-scale=1.0">` no `<head>` para habilitar layout responsivo.

3. **Alinhar documentação com o estado do código**
   - Contexto: o README lista ferramentas como React, Sass e Netlify, mas o projeto atual é uma página estática apenas com HTML e CSS.
   - Tarefa: atualizar a descrição para refletir o escopo real do projeto ou criar uma seção separada que diferencie habilidades pessoais do conteúdo do repositório.

4. **Melhorar cobertura de testes**
   - Contexto: não há testes automatizados para validar o formulário de login ou os estilos base.
   - Tarefa: adicionar um teste automatizado (por exemplo, com Playwright ou Cypress) que confira a renderização do formulário, a presença do logo e o comportamento do botão de envio sem recarregar a página.
