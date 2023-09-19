---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---

# Ein enkel intro til Rust

"C++, men bedre"

---

# Litt om Rust

- Blei påbegynt av Graydon Hoare, ein Mozilla-tilsett, i 2006
- Siktar seg inn på same "marknad" som C og C++
- Dømer: Operativsystem, drivarar, biblioteksmodular, spel, nettlesarar, o.l.
- Stort fokus på yting, typetryggleik, minnetryggleik og samtidigheit

---

# Korleis kome i gang

Vi brukar Rustup til å halde Rust oppdatert

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Seinare, for å oppdatere Rust og Cargo:

```sh
rustup update
```

---

# Om Cargo

Cargo er Rust sitt pakkesystem, og er også ein byggjeautomatiserar.

```sh
# Lage nytt prosjekt
cargo new hello_world

# Bygge køyrbart program
cargo build

# Bygge og køyre i ein kommando
cargo run

# Installere pakke, som npm install
cargo install
```

---

# Editorstøtte

Det enklaste er å bruke VSCode med rust-analyzer.

Kan også bruke Vim, Emacs, eller IntelliJ med plugin.

---

# Opplegg for i dag

Den beste måten å lære eit språk på er å bygge noko med det!

Vi skal gå saman to og lage enkle program.

Vi prøver å løyse dei på ein så idiomatisk Rust-måte som vi klarer.

Det er lov å bruke eksterne pakkar (crates), men prøv først utan for å sjå om du treng det.

Når det er 20 minutt igjen så tek vi ein show & tell og diskuterer korleis det gjekk.

---

<style scoped>
li {
  font-size: 24px;
}
</style>

# Programma vi skal lage

1. Eit program som printar noko frå minst to ulike trådar, slik at ein kan sjå at meldingane kjem frå begge trådane samtidig
    1. Ekstra: Eit program som jobbar med eit delt tal, og der begge trådane endrar på talet samtidig
2. Ein kalkulator (i kommandolinja) som tek inn to tal og ein operator (`+,-,*,/`) og gir ut resultatet
    1. Ekstra: Kan gi inn arbitrært mange tal
3. Eit program som les ut hunderasar frå https://dogapi.dog/docs/api-v2 og viser rasenamn og maks vekt (for både tisper og hannhundar) i kg
4. Ein veldig basic implementasjon av `ls`, som printar ut alle filer og mapper i ei mappe. Begynn med at den berre ser på "current working directory".
5. Eit program som viser grafikk på skjermen (ein blå sirkel og ein grøn firkant)
    1. Ekstra: Kan styre sirkelen med piltastane

---

# Fleire forslag

- Eit program som finn løysinga på følgande: Finn summen til alle partal i fibonacci-rekka som er mindre i storleik enn 4 millionar. Vis også kor mange tal det var, og vis dei 10 første av dei.
- Eit loggebibliotek som kan skrive til fil
- Eit program som les antal teikn, ord og linjer i ei tekstfil
- Ein minimal webserver som tek inn eit argument som query string og returnerer det som respons

---

# Gode ressursar undervegs

Blir posta på Slack.

[The Rust Programming Language](https://doc.rust-lang.org/book/ch01-00-getting-started.html)
[A half-hour to learn Rust](https://fasterthanli.me/articles/a-half-hour-to-learn-rust)
[Rust 101](https://www.ralfj.de/projects/rust-101/main.html)
Google

