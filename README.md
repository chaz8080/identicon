# Identicon

Sample code for [Udemy course - The Complete Elixir and Phoenix Bootcamp](https://www.udemy.com/the-complete-elixir-and-phoenix-bootcamp-and-tutorial/learn/v4/content)

## Installation

### Windows

1. Install [Chocolatey](https://chocolatey.org/install)

```
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

2. Install elixir 

```
choco install -y elixir
```

## Running the app

```
cd <project>
mix deps.get
iex -S mix

iex> Identicon.main "Your String"
```

Generate identicons in the images folder.