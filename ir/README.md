# remote controller encoder and decoder for Raspberry Pi

## `test_file`

setting file for `json2signal.py`

## `aircon.sh`

script for IR signal generation and IR signal transmission by lirc

## `json2signal.py`

script to generate IR signal from setting file  
usage:

```console
$ sudo python json2signal.py <setting file>
```

dependency: `rev_bit.py`  
caution: it will overwrite `/etc/lirc/lircd.conf`

## `decode_ir.py`

script for decoding IR signal from lirc's script `mode2` format file  
dependency: `rev_bit.py`

## References

* [Raspberry Pi 3でリモコン信号を解析する (10/1リモコン信号解析結果更新) - スマートホーム構築記](https://kagemomiji.hateblo.jp/entry/2016/09/03/102809)
* [Raspberry Pi 3でのlirc信号生成スクリプトの作成 - スマートホーム構築記](https://kagemomiji.hateblo.jp/entry/2016/10/02/173010)

