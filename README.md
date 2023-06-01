# chinese-xinhua-go
📙 中华新华字典数据库。包括歇后语，成语，词语，汉字。

Origin Repo: https://github.com/pwxcoo/chinese-xinhua

## Usage

``` go
import (
	"github.com/golr/chinese-xinhua-go/ci"
	"github.com/golr/chinese-xinhua-go/idiom"
	"github.com/golr/chinese-xinhua-go/word"
	"github.com/golr/chinese-xinhua-go/xiehouyu"
)

idioms, err := idiom.GetIdioms()
words, err := word.GetWords()
cis, err := ci.GetCis()
xiehouyus, err := xiehouyu.GetXieHouYus()
```
