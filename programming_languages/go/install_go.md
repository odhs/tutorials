### Install Golang

## Ubuntu / Debian based

The server-side project was developed using GO language. 

Download Golang for Ubuntu

```sh
curl -OL <https://go.dev/dl/go1.23.0.linux-amd64.tar.gz>
sudo tar -C /usr/local -xvf go1.23.0.linux-amd64.tar.gz
```

#### Define Environment Variables

Put on the end of the file `~/.profile`

```sh
export PATH=$PATH:~/go/bin
export PATH=$PATH:/usr/local/go/bin
```

Run for the terminal to recognize the changes:

```sh
source ~/.profile
```

Check if it is working

```sh
go version
```

## Windows

Download the compacted file at `https://go.dev/dl/` and then 
unzip at `c:/go/`. Include in the environment variable PATH the path `C:/go/bin`