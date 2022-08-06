# Card Tracer

![Card tracer](https://i.imgur.com/fRoVyTA.png)

## What is card trace?
In card trace feature bot will trace all the cards according to filters such as character name, series names, print number, edition.
This works same as `k!collection` command of karuta.

## Commands
:::info
**Command** : `m.trace c: s: e: p:` <br/>
`c:`- character name<br/>
`s:`- series name<br/>
`e:`- edition<br/>
`p:`- print number<br/>

**Example** : <br/>
`m.trace c:yumeko`<br/>
`m.trace c:yumeko s:kakegurui e:4`<br/>
`m.trace c:yumeko s:kakegurui e:4 p:1`
:::

## How to hide a card from this feature?

![Trace Hide](https://i.imgur.com/EuENLLO.gif)

- Process `kci <code>` of the card you want to hide.
- Simply reply to kci embed of karuta bot.
- After that process `m.tracehide`.
- If bot replies with `<code> is hidden now` means your card code is hidden from public.

```
To unhide card do the 1st and 2nd step same and then process m.traceunhide command.
```

:::info Note
Your card code will be public if you give hidden card to someone else and they flex it, it'll be public even if you take that back so make sure to hide it again afterwards.
:::