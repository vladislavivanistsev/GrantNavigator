# GrantNavigator

GrantNavigator is a self-contained demonstration application for exploring potential European Research Council (ERC) grant matches. It provides separate views for researchers and research administrators. [https://vladislavivanistsev.github.io/GrantNavigator/](vladislavivanistsev.github.io/GrantNavigator)

## Features

- Suggests an ERC career stage from the PhD defence year and eligible extension years.
- Compares five-year publications and h-index values with grant- and subpanel-specific benchmarks.
- Supports PE, LS, and SH research areas across Starting, Consolidator, and Advanced Grants.
- Provides an administration view for filtering, sorting, and screening synthetic researcher records.
- Runs entirely in the browser without external runtime dependencies or persistent browser storage.

## Demo notice

This repository is a demonstration. All researcher names and records are synthetic. The results are indicative and are not formal ERC eligibility decisions or predictions of funding success.

## Running locally

No installation or build process is required.

1. Clone or download the repository.
2. Open `index.html` in a modern browser.
3. Select either **Researchers view** or **Administration view**.

## Benchmark data

The application contains self-contained publication, h-index, and success-rate benchmarks in `index.html`. Values used by the interface are rounded upward to integers.

Researcher comparisons use the selected grant type and exact ERC subpanel. Administration records contain only broad panels, so their highlighting uses rounded panel-and-grant averages and requires both the h5-index and output thresholds to be met.

## Main files

- `index.html` — complete browser application and embedded demonstration dataset.
- `researchers.html` — standalone administration-table version retained for reference.
- `LICENSE` — MIT License.

## Privacy

GrantNavigator does not use Web Storage, IndexedDB, cookies, the Cache API, or service workers. Form information remains in the current page session and is not transmitted by the application.

## Development

The application uses standard HTML, CSS, and JavaScript. Its HTML metadata records that the code was produced with OpenAI Codex using GPT-5.6-sol.

## License

GrantNavigator is available under the [MIT License](LICENSE).
