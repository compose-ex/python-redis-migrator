# python-redis-migrator
this project assists with migrating redis servers based on a a gist from [migrate-redis.py](https://gist.github.com/kitwalker12/517d99c3835975ad4d1718d28a63553e)

This version has been ported to Python 3.

##

`pip3 install -r requirements.txt`

## Usage

```
python3 migrate-redis.py <srchost> <srcpassword> <srcport> <desthost> <destpassword> <destport> [-sslsrc] [-ssldst] [--flush] [--db=0]
```

