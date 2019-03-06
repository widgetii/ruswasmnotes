## Каноничный пример работы с WASM

```js
<!DOCTYPE HTML>
<script type="module">
async function run() {
    const { instance } = await WebAssembly.
        instantiateStreaming(fetch("/simd.wasm"))
    const view = new Int32Array(instance.exports.memory.buffer)
    Object.assign(view, [1, 2, 3, 4, 5, 6, 7, 8])
    instance.exports.doit()
    console.log(view.slice(8, 12))
}
run()
</script>
```
