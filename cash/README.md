# Cash

This program calculates the conversion between one currency to anothers currencies 

## Prerequisites

* Open a terminal
* Install the dependencies

```sh
❯ cd /cash/bin
❯ npm install
```

## Usage

* Execute index.js

You can :

- Calculate the conversion between currencies

```sh
> node index.js <amount> <currency>
```

Example : 

```sh
$ node bin/index.js 1 usd
```

- Save currencies as defaults currencies
```sh
> node bin/index.js --save <amount> <currency>
```

    Example : 
    ```sh
    $ node bin/index.js --save usd eur pln aud
    ```

- Display help message
```sh
$ node index.js --help
```

- Display version number
```sh
$ node index.js --version
```

## Currencies

You can use all this currencies : 

  "AUD": "Australian Dollar",
  "RUB": "Russian Rouble",
  "EUR": "Euro",
  "BGN": "Bulgarian Lev",
  "BRL": "Real Brazilian",
  "CAD": "Canadian Dollar",
  "CHF": "Swiss Franc",
  "CNY": "Chinese Yuan",
  "CZK": "Czech Koruna",
  "DKK": "Danish Krone",
  "GBP": "Pound Sterling",
  "HKD": "Hong Kong Dollar",
  "HRK": "Croatian Kuna",
  "HUF": "Hungarian Forint",
  "IDR": "Indonesian Rupiah",
  "ILS": "Israeli Shekel",
  "INR": "Indian Rupee",
  "JPY": "Japanes Yen",
  "KRW": "South Korean Won",
  "MXN": "Mexican Peso",
  "MYR": "Malaysian Ringgit",
  "NOK": "Norwegian Krone",
  "PHP": "Philippine Peso",
  "PLN": "Polish Zloty",
  "RON": "Romanian New Leu",
  "SEK": "Swedish Krona",
  "SGD": "Singapore Dollar",
  "THB": "Thai Baht",
  "TRY": "Turkish Lira",
  "USD": "US Dollar",
  "ZAR": "South African Rand",
  "NZD": "New Zealand Dollar"

