# PHP Swap

The purpose of this script is to swap between two versions of PHP installed using [Homebrew](https://brew.sh) on macOS.

The script simply checks to see which version is running and swaps to the other version installed.

## Installation

Install the script file `phpswap` in `/usr/local/bin` or wherever your binaries are stored. Once there, navigate to that directory and make it executable by entering the following command.

```
chmod +x phpswap
```

## Output

With `php` and `php@8.0` installed, output should look something like this.

```
You are running PHP 8.2. Switching to 8.0.

You are now running PHP 8.0.
```

That's it! That's all it does (for now). May its existence be a blessing!