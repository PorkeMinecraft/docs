---
sidebar_position: 1
---

# 🌍 Państwa

## Wprowadzenie

Na serwerze EarthSMP, gracze mogą tworzyć i zarządzać swoimi własnymi państwami. Każde państwo może mieć swoje własne prawa, członków i regiony. Dzięki temu systemowi możesz zabezpieczyć swój teren przed innymi graczami, prowadzić dyplomację oraz współpracować z przyjaciółmi w ramach jednego państwa.

## Tworzenie państwa

Aby stworzyć swoje własne państwo, użyj komendy:

Koszt: 7,5k

```
/lands create <nazwa>
```

Przykład:

```
/lands create Argentyna
```

Po utworzeniu państwa, automatycznie staniesz się jego liderem.

### Tworzenie obozu

Jeśli jesteś nowy i jeszcze nie masz 7,5k na stworzenie kraju to możesz stworzyć obóz za darmo, obóz jest na 3 dni.

```
/lands createcamp <nazwa>
```

## Zarządzanie państwem

### Dodawanie członków

Aby dodać członka do swojego państwa, użyj komendy:

```
/lands trust <nazwa_gracza>
```

Gracz, którego zaprosisz, musi zaakceptować zaproszenie komendą:

```
/lands accept <nazwa_państwa>
```

### Usuwanie członków

Aby usunąć członka z państwa, użyj komendy:

```
/lands untrust <nazwa_gracza>
```

### Nadawanie rang

Możesz nadawać różne rangi członkom państwa, co pozwoli im na wykonywanie różnych czynności:

```
/lands setrole <gracz> <obszar> <rola>
```

## Podstawowe komendy

- W trakcie przygotowania...

## Inne funkcje

### Sojusze

Możesz tworzyć sojusze z innymi państwami, co pozwoli na współpracę i wzajemną ochronę. Aby zaprosić inne państwo do sojuszu, użyj komendy:

```
/lands relations allies add <nazwa_państwa>
```

### Wojny

Od piątku do soboty w godzinach od 12-18 można wypowiedzieć wojnę bez akceptacji drugiej strony, czas przygotowania do wojny to 24 godziny.
Państwo broniące może w ciagu tych 24 godzin odwołać się poprzez odpowiedni ticket na naszym [Discordzie](https://dc.minecube.pl), takie odwołanie od wojny musi być podstawne i może zostać odrzucone lub zaakceptowane.

Aby wypowiedzieć wojnę użyj komendy:

```
/wojna declare <nazwa_państwa>
```

### Ekonomia

W trakcie przygotowania...

## FAQ

### Jak mogę zmienić lidera państwa?

Aby przekazać liderowanie innej osobie, użyj komendy:

```
/lands setowner <nazwa_gracza>
```

### Jak mogę teleportować się do mojego państwa?

Aby teleportować się do swojego państwa, użyj komendy:

```
/lands spawn
```

### Czy mogę zmienić nazwę państwa?

Tak, aby zmienić nazwę swojego państwa, użyj komendy:

```
/lands rename <nowa_nazwa>
```

### Jak zmienić nazwę państwa na kolorową?

Aby to zrobić wystarczy że wpiszesz komendę do zmiany a za nią nazwe kraju z kodami kolorów:

```
/lands rename <nowa_nazwa>
```

Przykład:

```
/lands rename &f&lPol&c&lska
```

Teraz uzyskamy biało-czerwony napis Polska który będzie pogrubiony. Dostępne kody kolorów możesz sprawdzić pod komendą `/colors`
