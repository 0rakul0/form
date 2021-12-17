# < Formulario >
usando o formsubmit.co


# < Para experimentar >

- https://0rakul0.github.io/form/

Nesse repositório você irá encontrar um exemplo de como usar o formsubmit.co

# < Objetivo >

demostrar como enviar um formulário para um e-mail sem o uso do back-end.

```html
<section>
    <form action="https://formsubmit.co/0rakul0render@gmail.com" method="post">
      <fieldset class="formulario">
        <legend> envio de formulario </legend>
        <input type="hidden" name="_next" value="https://0rakul0.github.io/form/sucesso.html" />
        <input type="hidden" name="_template" value="table">
        <input type="text" name="name" placeholder="Nome" required />
        <input type="email" name="email" placeholder="E-mail" required />
        <input type="text" name="subject" placeholder="Assunto" required />
        <label for="mensagem">Mensagem</label>
        <textarea name="message" cols="30" rows="10" maxlength="200" required></textarea>
        <input type="submit" value="envio" />
      </fieldset>
    </form>
  </section>
```

# < tecnologias adotadas >

- HTML5
- CSS


