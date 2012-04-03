# Cli

Cli is a port of [http://docs.fuelphp.com/classes/cli.html](Fuel's Cli class).
Please refer to Fuel's docs for usage instructions. The only API difference from Fuel's
implementation is the use of \Exception instead of FuelException. You will need to call
`Cli::_init();` before using Cli's static methods.

## Installation

You may use a require for Cli.php or use composer to install.
