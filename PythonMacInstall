# Install Python on Mac (Apple Silicon) Using Homebrew

## Step 1: Install Homebrew
If you haven't installed Homebrew, open **Terminal** and run:
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
After installation, add Homebrew to your shell profile:
```sh
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zshrc
source ~/.zshrc
```

## Step 2: Install Python
Run the following command to install Python:
```sh
brew install python
```

## Step 3: Verify Installation
Check if Python is installed correctly:
```sh
python3 --version
```
It should return output similar to:
```
Python 3.x.x
```

## Step 4: Set Homebrew Python as Default (Optional)
To ensure you're using the Homebrew-installed Python instead of macOS's built-in version, add this to your `~/.zshrc` file:
```sh
export PATH="/opt/homebrew/bin:$PATH"
```
Then apply the changes:
```sh
source ~/.zshrc
```

Now, whenever you run `python3`, it will use the Homebrew-installed version.
