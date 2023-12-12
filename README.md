# FunGenKit

`FunGenKit` is a Python package developed by Gao Wang's Lab, providing a suite of in-house computational tools tailored for functional genomics research. This package focuses on efficient and parallelizable computation methods, including 

- correlation matrix calculations


## Installation

Before installing `FunGenKit`, ensure you have Python and `nbdev` installed on your system. `FunGenKit` is developed using `nbdev`, which allows for an integrated development process using Jupyter Notebooks.

### Install nbdev

If you haven't installed `nbdev` yet, you can do so using pip:

```bash
pip install nbdev
```

### Clone the Repository

Clone the `FunGenKit` repository to your local machine:
```bash
git clone https://github.com/yourusername/FunGenKit.git
cd FunGenKit
```

### Install Dependencies

Make sure all required dependencies are installed:

```bash
pip install -r requirements.txt
```

## Usage

`FunGenKit` is developed in Jupyter Notebooks, where each notebook corresponds to a specific module in the package. 

To use the package, simply import it into your Python environment:

```python
from fungenkit import correlation_matrix_in_chunks
```
## Development

To contribute to `FunGenKit`, follow these steps:

1. **Create a New Notebook**: Add a new notebook to the `nbs/` folder for additional functionality.
2. **Build the Library**: Convert notebooks into Python modules using `nbdev_build_lib`.
3. **Run Tests**: Write and run tests using standard `assert` statements in your notebooks. Test the entire library with `nbdev_test_nbs`.
4. **Generate Documentation**: Use `nbdev_build_docs` to create documentation from your notebooks.
5. **Push Changes**: Use `git` to commit and push your changes.

## Continuous Integration

`FunGenKit` uses GitHub Actions for continuous integration. This ensures that all tests pass and the library is correctly built with each push.

## Documentation

You can find the complete documentation for `FunGenKit` at [GitHub Pages URL]. This documentation is automatically generated from the Jupyter Notebooks used to build the library.

## Support

If you encounter any problems or have questions, please file an issue on the GitHub repository.

## License

`FunGenKit` is released under the [MIT License](LICENSE).
