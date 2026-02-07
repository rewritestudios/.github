<div align="center">

# Remessage Open Source

**SMS do jeito que deveria ser** — simples, previsível e absurdamente barato.
Envie SMS transacionais e OTPs com **taxa fixa de US$ 0.01 por mensagem**, sem contratos, sem surpresas e sem burocracia.

Feito para devs que querem **confiabilidade, DX excelente e controle total** sobre envios de SMS.

## Integre em poucas linhas

</div>

```ts
import { Remessage } from 'remessage'

const client = new Remessage(process.env.REMESSAGE_API_KEY)

await client.messages.send({
    from: 'Remessage',
    to: '+5511999999999',
    content: 'Seu código de verificação é 482931',
});
```
<div align="center">

Simples assim, o jeito **Remessage** de ser.

## Não fique preso a um único provedor

O **Remessage** não é apenas um gateway — é uma **camada de abstração**.

Você pode usar o Remessage com **múltiplos provedores de SMS**, alternando ou combinando conforme preço, entrega ou região:

</div>

- Twilio
- Zenvia
- SMPP direto
- Outros provedores compatíveis

<div align="center">

Tudo usando **a mesma API**, os mesmos webhooks e a mesma DX.

Troque de provedor sem reescrever seu código.

## Junte-se à revolução do SMS

O **Remessage** nasce open source porque acreditamos que infraestrutura crítica **não deveria ser uma caixa-preta.**

Contribua, discuta ideias e ajude a construir o futuro do envio de SMS simples e acessível.

**Remessage** — SMS do jeito que deveria ser.

</div>
