# Ramanujan Birthday Square

This project generates a special 4x4 magic square based on any given date, inspired by the birthday square created by Indian mathematician Srinivasa Ramanujan. The program takes a date input in the format `dd mm yyyy`, and creates a 4x4 matrix with specific transformations applied to each component of the date. The resulting matrix has unique numerical patterns and properties.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This program takes a date (day, month, and year) as input, and transforms it into a 4x4 matrix using a specific set of operations. It is inspired by a famous magic square created by Ramanujan on his birthday, where each row, column, and diagonal sum up to the same value. While the generated matrix from this program may not have the exact properties of a magic square, it represents a playful approach to numerical transformations based on dates.

## Installation

To run this program, you need Python installed on your system. You can download Python from the official website: [python.org](https://www.python.org/).

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/ramanujan-birthday-square.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ramanujan-birthday-square
   ```

3. Install any required dependencies (though this script doesn't have external dependencies).

## Usage

1. Open a terminal or command prompt.
2. Run the Python script:

   ```bash
   python ramanujan_bday_square.py
   ```

3. When prompted, enter the date in the format `dd mm yyyy` (e.g., `22 12 1887`).
4. The program will output a 4x4 matrix generated based on the input date.

### Functions

- **date_to_numbers()**:
  - This function takes a date input from the user and converts it into numeric components such as the day, month, and parts of the year (century and year digits).
  
- **ramanujan_bday_square()**:
  - This function generates a 4x4 matrix by applying certain transformations to the day, month, and year digits. The matrix is displayed based on these transformations, resulting in a unique grid of numbers.

## Example

### Input

```plaintext
Enter the date in the format dd mm yyyy: 22 12 1887
```

### Output (4x4 matrix)

```plaintext
[
    [22, 12, 18, 87],
    [88, 17, 9, 25],
    [10, 24, 89, 16],
    [19, 86, 23, 11]
]
```

This output matrix is derived from the transformations applied to the date `22 12 1887`.

## Contributing

Feel free to contribute to this project by opening a pull request. Whether it's bug fixes, feature additions, or improving the documentation, your help is welcome!

1. Fork the repository.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Open a pull request.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
