# Really Relaxed JSON (RJSON)

RJSON is JSON with optional commas and quotes, and with comments allowed. The parser reads RJSON,
JSON and JavaScript object notation, and converts between them.

This repository is a signpost: the source is not published here. Use it to
[report issues](https://github.com/code-evolve/really-relaxed-json/issues).

## Specification

[https://www.relaxedjson.org](https://www.relaxedjson.org), with an online converter.

## JavaScript (npm)

```sh
npm install really-relaxed-json
```

[https://www.npmjs.com/package/really-relaxed-json](https://www.npmjs.com/package/really-relaxed-json)

## Java (Maven Central)

```xml
<dependency>
    <groupId>tv.twelvetone.rjson</groupId>
    <artifactId>rjson</artifactId>
    <version>1.3.1</version>
</dependency>
<!-- The library needs the Kotlin runtime, which versions before 1.4.1 do not declare -->
<dependency>
    <groupId>org.jetbrains.kotlin</groupId>
    <artifactId>kotlin-stdlib</artifactId>
    <version>1.7.21</version>
</dependency>
```

No `<repositories>` entry is needed: it resolves from Maven Central.

## License

MIT
