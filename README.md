# dbmarket

My solution to the Project for DB

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

Requires JavaSE 17  and JUnit 5.

## Usage

Starting on MarketMain class we load Data from the Csv file using the CsvReader class. Then using the DataController  and IdexController classes 
we create Lists the hold the values to be displayed.
The csvreader directory holds the CsvReader class Handles the whole reading process for a csv file.
While instantiating this class you need to pass a String representing the file path.
This class uses the ; as delimiter to separate the values. 
The model folder contains the Objects that are created and later stored in the Lists.
Finally the utils folder holds 2 classes DataController and IndexController that handle the Daily traded values and daily Index respectively.
The TradedValuesDataUtils class contains the Functions that are used to filter out the expected data.


## Contributing

Anyone can contribute. Some additional improvement could be caching the backup values. Also for the visualization.

## License
