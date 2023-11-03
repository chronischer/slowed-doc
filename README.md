
# Slowed Documentation

Ensinarei a usar os métodos do slowed, para os padrões cheque a documentação oficial.

### Mensagens de texto

# enviar

Envia uma mensagem respondendo o comando que invocou a função

```javascript
await enviar("Sua Mensagem Aqui")
```

# sendPoll

envia uma enquete

```javascript
await slowed.sendPoll(from, "titulo", ["Lorem", "Ipsum"]
```

# sendjson

Envia uma mensagem com o json da mensagem

```javascript
await slowed.sendjson(from, {text: "texto aqui"})
```

# sendFor

Envia uma mensagem apenas para alguns usuários 

```javascript
await slowed.sendFor(from, array, {text: "hello world!"})
```
no local que está localizado "array" Substitua por uma array com o jid do usuário que vai receber, exemplo de array:

```json
[owner, "5511XXXXXXXXXX@s.whatsapp.net"]
```

# sendForContent

Funciona como o sendjson soq com o sendFor

```javascript
await slowed.sendForContent(from, [owner], {text: "ola"})
```
.