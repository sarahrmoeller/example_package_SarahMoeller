# example_package_sarahmoeller

A small Python package for rescaling numeric arrays to the range `[0, 1]`.

#
## Installation

Download the source code and use the package manager [pip](https://pip.pypa.io/en/stable/) to install `package`:

```bash
pip install .
```

## Usage

```python
import numpy as np
from example_package_sarahmoeller.rescale import rescale


# rescales over 0 to 1
rescale(np.linspace(0, 100, 5))
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

This project is licensed under the BSD 2-Clause License. See the `LICENSE` file for details.

## Notes

- The function uses NumPy to compute the minimum and maximum values.
- Input arrays are normalized linearly to the `[0, 1]` interval.
