# Projeto Relógio Simples ⏰

Bem-vindo(a) ao projeto do Relógio Simples! Este é um projeto que demonstra a criação de um relógio digital simples utilizando HTML, CSS e JavaScript. 🕒

![Emoji Relógio](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/285/watch_231a.png)

## Descrição do Projeto

O Relógio Simples é uma aplicação web que exibe a hora atual em formato analogico. Ele é uma ótima maneira de praticar suas habilidades em HTML, CSS e JavaScript, além de proporcionar uma experiência prática de desenvolvimento.

## Funcionalidades

- Exibição da hora atual em formato analógico.
- Atualização automática a cada segundo, mantendo a hora precisa.
- Design simples, fique a vontade para estilizar do jeito que preferir.

## Tecnologias Utilizadas

- HTML: Utilizado para estruturar o esqueleto da página.
- CSS: Responsável pelo estilo visual e layout do relógio.
- JavaScript: Realiza a lógica de atualização da hora e manipulação do DOM.

## Como Usar

1. Clone ou baixe este repositório para o seu computador.
2. Abra o arquivo `index.html` no seu navegador web.
3. O relógio analógico será exibido na página, mostrando a hora atual.

## Exemplo de Código

Aqui está um trecho do código JavaScript responsável por atualizar a hora:

```javascript
const getTime = () => {
    const date = new Date();
    
    return  {
        hours: date.getHours(),
        minutes: date.getMinutes(),
        seconds: date.getSeconds(),
    };

    
}

// Atualiza a hora a cada segundo
setInterval(atualizarHora, 1000);
```

## Licença

Este projeto está sob a licença [MIT](LICENSE), o que significa que você pode usar, modificar e distribuir o código como quiser.

---

Espero que você se divirta explorando e desenvolvendo este projeto de Relógio Simples! Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato. ⏱️🚀