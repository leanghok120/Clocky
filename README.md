# clocky

clocky is a **simple** CLI clock written in Go. clocky is a project inspired by [tty-clock](https://github.com/xorg62/tty-clock).

## Installation

### Binary

There are a couple of binaries for mac (arm64) and linux. Head over to [Releases](https://github.com/leanghok120/clocky/releases/tag/v1.3.0) to download them.

#### Macos

After you install the binary (clockym) for macos, make sure to rename it to "clocky" and put it into your $GOPATH/bin directory

### Go

```sh
go install github.com/leanghok120/clocky/cmd/clocky@latest
```

From source:

```sh
git clone https://github.com/leanghok120/clocky.git
cd clocky/cmd/clocky/
go build
go install
```

## Usage

### Help

```sh
clocky -h
```

### 24 hour format

By default clocky uses 24 hour format

```sh
clocky
```

### 12 hour format

You can also use 12 hour format

```sh
clocky -f 12
```

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request.

## Acknowledgements

- Thanks to [figlet4go](https://github.com/mbndr/figlet4go) for providing ASCII art rendering functionality.
