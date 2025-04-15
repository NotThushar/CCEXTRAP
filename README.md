# Fixed the line 133 & ssl error
# CCEXTRAP (PHP)

CCEXTRAP is a PHP script that allows you to generate multiple credit card numbers automatically according to the amount you want. In addition, this script is also equipped with a feature to check the status of the credit card, whether Live, Die, or Unknow.

## Main Features

- **Generate Credit Card**: Generates credit card numbers based on the BIN (Bank Identification Number) you enter.
- **Automatic Status Check**: Checks the status of the generated credit card (Live, Die, or Unknow) automatically.
- **Manual Status Check**: Allows you to check the credit card status manually via the website.

## Installation

Here are the steps to install and run the CCEXTRAP script:

1. **Clone Repository**:

```bash
git clone https://github.com/hndko/CCEXTRAP
```

2. **Enter the CCEXTRAP Directory**:

```bash
cd CCEXTRAP
```

3. **Run the Script**:
```bash
php run.php
```

## Instructions

After the script is run, you will be asked to enter some information:

1. **Bin**: Enter the BIN (Bank Identification Number) you want.
2. **Check Status Valid**: Select one of the following options:
- **1**: Auto Check Status (Live, Die, or Unknow) for each credit card generated.
- **2**: Manual Check Status (You will check the status manually through the website).
3. **Amount**: Enter the number of credit cards you want to generate.

## Screenshot

Here is an example of what the CCEXTRAP script looks like:

![Screenshot 2025-02-24 094259](https://github.com/user-attachments/assets/c47552b5-9ebc-41ae-af7f-4bf5062a8ee2)

## Contributions

If you would like to contribute to the development of this script, please fork this repository and create a pull request with your proposed changes.

## License

This script is licensed under the [MIT License](https://opensource.org/licenses/MIT). Please refer to the `LICENSE` file for more information.

---

With this guide, you can easily install and use the CCEXTRAP script to generate and check credit card status. Good luck!
