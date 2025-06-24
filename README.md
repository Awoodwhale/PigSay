# PigSay(猪曰)

## Install

```bash
uv tool install pigsay
```

## Use

```bash
uvx pigsay encrypt <need encrypt text>
uvx pigsay decrypt <need decrypt text>
uvx pigsay encrypt-file input.txt output.pig
uvx pigsay decrypt-file input.pig output.txt
```

## Args

| Cmd | Arg | Desc |
|------|------|------|
| `encrypt` | `<text>` | Encrypt some text |
| `decrypt` | `<cipher>` | Decrypt some text |
| `encrypt-file` | `<input> <output>` | Encrypt a file |
| `decrypt-file` | `<input> <output>` | Decrypt a file |
