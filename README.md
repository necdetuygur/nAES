# nAES
C# AES Encrypt and Decrypt Class

```
string print = "";
print += "Encoded: " + nAES.Encrypt("test", "1234") + "\r\n";
print += "Decoded: " + nAES.Decrypt(nAES.Encrypt("test", "1234"), "1234");
Console.WriteLine(print);
```
