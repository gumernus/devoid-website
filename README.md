test
<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://cdn.discordapp.com/attachments/924652321793769542/924785573862981682/c7525dbaf38efd42f323f112c8677238.png" alt="Project logo"></a>
</p>

<h1 align="center">Devoid Web</h1>

<div align="center">

</div>

## 💾 Instalace  & Run
Před jakýmkoliv prvním spuštěím webu je potřeba stáhnout a nainstalovat veškteré potřebné věci.

### Development
Pro development je potřeba stáhnou i typescript a nějaké další věci oproti tomu když chceme pouze stáhnou věci pro deploy.

```
npm install --save-dev
```

Pokud budeme chtít web rozjet stačí tento command.
```
npm run serve
```
### Deploy
Pro deploy budeme potřebovat také nainstalovat nějaké věci.

```
npm install
```

---

## 🚀 Deploy</a>
Nejdříve musíme udělat dist složku.
```
npm run build
```

Následně je vše připraveno ke spuštění na hostingu. Pokud by jsme chtěli můžeme web rozjet přes pm2. Které se dá jednoduše nainstalovat zkrze `npm i pm2` a serve `npm i serve`. A teď to jen rozjet. S tímto commandem se web rozjede na portu 8080.

```
pm2 serve -s -l 8080 dist
```

---

## ⛏️ Vytvořeno díky </a>
- [Typescript](https://www.typescriptlang.org/) - Hlavní jazyk
- [MongoDB](https://www.mongodb.com/) - Databáze
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server
- [Bootstrap](https://getbootstrap.com/) - Základ designu

---

## ✍️ Autoři</a>

- [@gumernus](https://github.com/gumernus) 
- [@jan-holecek](https://github.com/jan-holecek)



