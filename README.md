
## Instalação

VittaWhatsapp está disponível no PyPi:

```bash
python3 -m pip install vittawhatsapp
```

```bash
pip3 install vittawhatsapp
```

```bash
pip install vittawhatsapp
```


## Clonar Repositório

gh repo clone fabriciomrm/vittawhatsapp

## Features

- Envia messagem para grupos e contatos do Whatsapp
- Envia imagens para grupos e contatos do Whatsapp

## Uso

```py
import vittawhatsapp

# Envia mensagem para um contato as 13:30
vittawhatsapp.sendwhatmsg("+910123456789", "Olá", 13, 30)

# Envia a mesma mensagem e fecha a Aba depois de 2 segundos
vittawhatsapp.sendwhatmsg("+910123456789", "Olá", 13, 30, 15, True, 2)

# Envia uma mensagem a um grupo a meia noite
vittawhatsapp.sendwhatmsg_to_group("AB123CDEFGHijklmn", "Hey All!", 0, 0)

# Envia uma imagem a um grupo com a mensagem Olá
vittawhatsapp.sendwhats_image("AB123CDEFGHijklmn", "Images/Hello.png", "Olá")

# Envia uma imagem a um contato
vittawhatsapp.sendwhats_image("+910123456789", "Images/Hello.png")

```


## Licença

MIT.
