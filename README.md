# Reason Proto

## add 
```shell
# normal add
git submodule add -b master --name api/reason-proto https://github.com/go-cinch/reason-proto.git ./api/reason-proto

# or force add
git submodule add -f -b master --name api/reason-proto https://github.com/go-cinch/reason-proto.git ./api/reason-proto
```

## update
```shell
git submodule update --force --recursive --init --remote
```
