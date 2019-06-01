# nAES
## C# AES Encrypt and Decrypt Class

```
string print = "";
print += "Encoded: " + nAES.Encrypt("test", "1234") + "\r\n";
print += "Decoded: " + nAES.Decrypt(nAES.Encrypt("test", "1234"), "1234");
Console.WriteLine(print);
```

## JS AES Encrypt and Decrypt Functions
```
var message = "test1";
var password = "pass1";
var a = nAES.Encode(message, password);
console.log(a);
var b = nAES.Decode(a, password);
console.log(b);
```
