# MineCube Wiki

Ta strona została zbudowana przy użyciu [Docusaurus](https://docusaurus.io/).

## 📦 Wymagania

- **Node.js `>=18.0`**
- **pnpm** jako menedżer pakietów

Jeśli nie masz pnpm, zainstaluj go globalnie:

```bash
npm install -g pnpm
```

---

## 🔧 Instalacja

```bash
pnpm install
```

---

## 🚀 Lokalny serwer deweloperski

```bash
pnpm start
```

Po uruchomieniu strona otworzy się w przeglądarce. Zmiany w plikach będą widoczne natychmiast.

---

## 🏗️ Budowanie strony

```bash
pnpm build
```

Wygeneruje statyczne pliki w katalogu `build/`.

---

## 🧹 Czyszczenie cache

```bash
pnpm docusaurus clear
```

Usuwa cache oraz pliki builda, przydatne gdy coś się „psuje”.

---

## 💡 Wskazówki

- W razie problemów z Webpackem spróbuj użyć `pnpm docusaurus clear`
- Pliki wiki znajdują się w `docs/`
- Najbardziej będzie ciebie interesować polecenie `start`

---

Miłego tworzenia wiki! 😊
