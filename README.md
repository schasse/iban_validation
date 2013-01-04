# IbanValidation

a ActiveModel::Validations IBAN validator based on IBANTools

## Installation

Add this line to your application's Gemfile:

    gem 'iban_validation'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install iban_validation

## Usage

In your rails model

    validates :iban_attribute, iban: true

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
