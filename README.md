# Benchmark Scores Documentation

Welcome to the Benchmark Scores Documentation project! This project is designed to record and organize scores of various models across different benchmarks. All files are in Markdown format to ensure easy readability and maintainability.

## Table of Contents

- [Benchmark Scores Documentation](#benchmark-scores-documentation)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Directory Structure](#directory-structure)
    - [Directory Details](#directory-details)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)

## Project Overview

This project aims to consolidate scores of different models across various benchmarks into a single, well-organized repository. Each benchmark and model has its own dedicated file to provide detailed information and scores.

## Directory Structure

```plaintext
benchmark-scores/
├── README.md
├── benchmarks/
│   ├── benchmark1/
│   │   ├── overview.md
│   │   ├── model1.md
│   │   ├── model2.md
│   │   └── ...
│   ├── benchmark2/
│   │   ├── overview.md
│   │   ├── model1.md
│   │   ├── model2.md
│   │   └── ...
│   └── ...
├── models/
│   ├── model1.md
│   ├── model2.md
│   └── ...
└── summary/
    ├── all_benchmarks.md
    ├── benchmark1_summary.md
    ├── benchmark2_summary.md
    └── ...
```

### Directory Details

- **benchmarks/**: Contains directories for each benchmark. Each directory includes:
  - `overview.md`: General description and methodology of the benchmark.
  - Individual model score files (e.g., `model1.md`, `model2.md`).

- **models/**: Contains files for each model with detailed information such as author, version, application area, and description.

- **summary/**: Contains summary files:
  - `all_benchmarks.md`: Overview of all benchmarks and model scores.
  - Individual benchmark summary files (e.g., `benchmark1_summary.md`, `benchmark2_summary.md`).

## Usage

To use this documentation:

1. Navigate through the `benchmarks/` directory to find specific benchmark details and scores for various models.
2. Check the `models/` directory for detailed information about each model.
3. Refer to the `summary/` directory for overviews and comparative analyses of the benchmarks and models.

## Contributing

We welcome contributions! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

Please ensure that your contributions align with the existing file structure and naming conventions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.