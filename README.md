# bfm1 Реализация задания

1. открыть в браузере index.html

2. заполнить пол



в директории **encripter** 3 скрипта:
 * genkeys.js
 * gensig.js
 * verifysig.js


**node genkeys.js**

`создает на диске ключевую пару private.key и public.key`


**node gensig.js \<file\> \<private key\>**

`для указанного файла <file> вычисляется хешь и шифруется секретным ключом <private key>, полученная подпись сохраняется в файле с расширением dig`


**node verifysig.js \<file\> \<signature\> \<public key\>**

`проверяет валидность подписи <signature> для указанного файла <file> с использованием открытого ключа <public key>`
