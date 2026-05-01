# PTH Klęski Elementarne Geoparsing Pipeline

**Status:** CLI tool is currently under active development.

---

## About

A command-line tool that processes historical disaster records from the [Polskie Towarzystwo Historyczne (PTH) — Klęski Elementarne](https://pth.net.pl/projekty/bazy-danych/kleski-elementarne) database and converts them into geocoded, uncertainty-aware GIS data.

The pipeline handles records in Latin, Polish, and German from the 10th century to the present day.

## Current State

- Core pipeline (scraping → cleaning → language detection → NLP → geocoding → uncertainty scoring) is implemented.
- CLI interface (`pth_disasters`) is under development and not yet stable.
- Full documentation and installation instructions will be added once the CLI reaches a usable state.

## Next Steps

- Complete and stabilize the CLI
- Add proper testing and error handling
- Release first working version

---

**License:** MIT
