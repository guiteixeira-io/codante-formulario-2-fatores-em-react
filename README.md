# Formulário de Autenticação em 2 fatores - React

![image](https://github.com/user-attachments/assets/ba5b6445-0d22-4d62-9552-77826b14f798)

É crescente o uso de aplicações que implementam algum tipo de segurança adicional na autenticação. Uma das formas mais comuns para isso é utilizando uma estratégia de 2 fatores. Além da senha tradicional, o usuário recebe em seu e-mail ou por SMS uma senha de uso único (também conhecida como OTP - One-Time Password).

## Tecnologías

- Refs no React
- Formulários controlados no React
- Eventos

## 🔨 Requisitos

- Um formulário com 5 campos de entrada, cada um representando um dígito da senha OTP.
- A submissão desse formulário ocorre quando o usuário pressionar a tecla Enter ou clicar no botão de submissão.
- Os campos de entrada só aceitam números, permitindo apenas um único dígito em cada.
- Ao carregar a página, a aplicação foca no primeiro campo de dígito.
- Ao digitar no primeiro campo, o foco é transferido automaticamente para o segundo campo, e assim sucessivamente.
- Se algum dígito for apagado, o foco retorna para o dígito anterior.
- Deve ser possível colar um código de 5 dígitos e ele deve aparecer corretamente nos campos de entrada.
  - Um erro deve ser exibido quando o texto colado não possuir 5 dígitos numéricos.
- A navegação entre os campos é possível utilizando as setas do teclado (ArrowLeft e ArrowRight).
- Em dispositivos móveis, o teclado numérico deve ser ativado (ao invés do teclado tradicional).
