# ahrefs-api-python

ahrefs の API を使った Python ライブラリーです。

ドキュメントは以下を参照してください

ahrefs API v3
https://docs.ahrefs.com/docs/api/reference/introduction

## Install:

```
pip install ahrefs_python
```

## Usage example:

```
api = AhrefsApi('http://apiv2.ahrefs.com', 'xxxx')
ahrefs_rank_result = api.ahrefs_rank('example.net').order_by('url:asc').where('url="http://example.net/"').get()
```

'xxxxx'にはトークンをいれてください
