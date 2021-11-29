# AtomicAssets helpers

## Examples

Get immutable attributes from NFT asset

```c++
const ATTRIBUTE_MAP immutable = atomic::get_template_immutable( asset );
```

Get `name` attribute from attributes

```c++
const name example = atomic::attribute_to_name( immutable, "example" );
```
