# README

```
chmod +x client
chmod +x server
./client
```

OTP 25:

```
./client
<<131,104,4,100,0,2,105,115,100,0,4,116,104,105,115,100,0,1,97,100,0,3,98,117,103>>
{is,this,a,bug}%
```

OTP 26:

```
./client
<<194,131,104,4,119,2,105,115,119,4,116,104,105,115,119,1,97,119,3,98,117,103>>
escript: exception error: bad argument
  in function  binary_to_term/1
     called as binary_to_term(<<194,131,104,4,119,2,105,115,119,4,116,104,105,
                                115,119,1,97,119,3,98,117,103>>)
     *** argument 1: invalid external representation of a term
```
