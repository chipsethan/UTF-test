# UTF-test
https://github.com/ww898/utf-cpp

https://github.com/nemtrif/utfcpp

performance benchmark, tested with a 126MB UTF8 text file

Visual Studio 2019 - 16.10.0 (Win10 Pro 20H2, x64, Intel i7-8700)

Mikhail Pilin (2.3)

UTF8-->UTF32:584.876ms

UTF8-->UTF16:417.439ms

UTF32-->UTF8:311.549ms

UTF16-->UTF8:276.505ms

Nemanja Trifunovic (3.2.1)

UTF8-->UTF32:1081.22ms

UTF8-->UTF16:950.651ms

UTF32-->UTF8:309.367ms

UTF16-->UTF8:476.447ms

identical results, ok


g++ 10.3.0 - msys2 (Win10 Pro 20H2, x64, Intel i7-8700)

Mikhail Pilin (2.3)

UTF8-->UTF32:334.683ms

UTF8-->UTF16:256.315ms

UTF32-->UTF8:240.74ms

UTF16-->UTF8:323.077ms

Nemanja Trifunovic (3.2.1)

UTF8-->UTF32:371.187ms

UTF8-->UTF16:253.828ms

UTF32-->UTF8:429.623ms

UTF16-->UTF8:467.776ms

identical results, ok
