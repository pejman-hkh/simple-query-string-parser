# simple-query-string-parser
Simple query string parser

# Building
```
g++ -std=c++11 qsi.cpp -o qsi
```

# Test
```
./qsi "&test=123&test2=asasd"
./qsi "&test[]=123&test[]=dddd&test2[]=asasd"
./qsi "&test[][]=123&test[][]=dddd&test2[]=asasd"
```
