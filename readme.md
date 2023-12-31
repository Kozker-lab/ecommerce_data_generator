# Ecommerce Synthetic Data Generation

This project is designed to generate synthetic, but realistic, data for an electronics e-commerce retail store. The data is generated using a Jupyter notebook (`e_commerce_synthetic.ipynb`), which allows for easy modification and execution of the data generation process.

## Features

- **Realistic Customer Information**: The Faker library is used to generate realistic customer information, such as names, addresses, and phone numbers.
- **Electronics Products**: The script simulates a variety of electronics products, including TVs, smartphones, laptops, and more.
- **Order details and Other Information**: The script generates realistic orders data, including quantities, prices, and dates. Inventorylog data, and customer service data has also been generated. Reviews have been generated with the help of OpenAI's `GPT-4` Model.

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

You need to have Python installed on your machine. You can download Python [here](https://www.python.org/downloads/).

## How to Use

1. Clone this repository to your local machine.
```bash
git clone https://github.com/yourusername/ecommerce-datagen.git
```

2. Navigate to the project directory.
```bash
cd ecommerce-datagen
```
3. Install the required dependencies by running 
```bash
pip install -r requirements.txt
```

4. **Run the Notebook**: Open the `e_commerce_synthetic.ipynb` notebook in Jupyter and run the cells to generate the data.

## Customization

You can customize the types of data generated by modifying the `e_commerce_synthetic.ipynb` notebook. The notebook contains comments explaining what each part of the code does, making it easy to adjust to your needs.

## Contributing

Contributions are welcome! Please read the contributing guidelines before making any changes.
GitHub Copilot: Sure, here's a basic README for your project. You can expand it with more details as needed.

```markdown
# E-Commerce Data Generation Project

This project is about generating synthetic data for an e-commerce application. The data includes information about orders, shipments, and products.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Python installed on your machine. You can download Python [here](https://www.python.org/downloads/).

### Installing

Clone the repository to your local machine.

```bash
git clone https://github.com/yourusername/your-repo-name.git
```

Navigate to the project directory.

```bash
cd your-repo-name
```

Install the required packages.

```bash
pip install -r requirements.txt
```

## Built With

* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Faker](https://pypi.org/project/Faker/)
* [OpenAI API](https://platform.openai.com)

## Authors

* **Govind Bhat** - *E-commerce Store Realistic Data Generation* - [YourUsername](https://github.com/git-GB)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details