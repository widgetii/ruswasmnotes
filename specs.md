## Спецификации

* [Core specification](http://webassembly.github.io/spec/core/index.html) -
    определяет структуру wasm-модулей, их бинарное и текстовое представления, а
    также семантику валидации, инстанцирования и исполнения

* [JavaScript API](http://webassembly.github.io/spec/js-api/index.html) -
    определяет JavaScript классы и объекты для доступа к WebAssembly из
    JavaScript, включая методы валидации, компиляции, инстанцирования, а также
    импортов и экспортов из/в JavaScript

* [Web API](http://webassembly.github.io/spec/web-api/index.html) - определяет
    расширения JavaScript API для браузеров, в частности потоковые компиляцию и
    инстанциорование

## Интерпретаторы

* [Референсный интерпретатор](https://github.com/WebAssembly/spec/blob/master/interpreter/README.md)

## Компиляторы

### WASM

* [wabt](https://github.com/WebAssembly/wabt) - wat2wasm, wasm2wat

* [Binaryen](https://github.com/WebAssembly/binaryen) - asm2wasm, s2wasm,
    mir2wasm

### C/C++

* [Emscripten](https://kripken.github.io/emscripten-site/) - C/C++ => JS + wasm,
    фактически это форк LLVM

* [LLVM>5](https://llvm.org/) - +LLD с 6-ой версии

### Asm.js

* [asm2wasm](https://github.com/WebAssembly/binaryen/blob/master/src/asm2wasm.h)
    - asm.js to WebAssembly

### TypeScript

* [AssemblyScript](https://github.com/AssemblyScript/assemblyscript) -
    TypeScript to Binaryen IR

### Haskell

* [Asterius](https://github.com/tweag/asterius) - Haskell to WebAssembly

