rakuten-client-go
==================

## Installation

```go
go get -u github.com/ken-aio/rakuten-client-go
```

## Usage

```go
import rakuten "github.com/ken-aio/rakuten-client-go"
```

```go
c := rakuten.NewIchiba("<put your appid>")

param := &rakuten.IchibaItemSearchParam{
        Keyword: "pokemon",
        Sort:    "+itemPrice",
}
resp, _ := c.IchibaItemSearch(param)
fmt.Printf("resp = %+v\n", resp)
```
