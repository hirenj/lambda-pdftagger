# Pdf annotation lambda


Forked from `0xabu/pdfannots`

```
pip3 install pdfminer.six -t lib
find lib -name 'pdfminer' -type d -exec mv ./{} "$PWD/lib" \;
rm -rf lib/Crypto
```