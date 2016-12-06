# TouchBerry Thumper Ruby Commander

This script is able to detect the changes of the `/tmp/touch` file and
send a REST request to the Thumper.

The script should be run on the Raspberry Pi that has the C++ i2c master application
for the QT1070 running and a TouchBerry shield connected to it.

## Requirements

You may need to install some packages

```shell
sudo apt-get install ruby ruby-dev libssl-dev bundler
```

Next do a `bundle install` to install all the required gems.

## Launching the script

Run the script by issuing

```shell
./thumper_touch.rb
```
