# 🌍 Language Files

You can help translating or improving the bot language files by creating a Pull Request.

## Important Rules ⚠️

- Keep all placeholders inside `{}` exactly the same
- Do NOT translate or modify placeholders
- Keep JSON formatting valid
- Keep the same structure and keys
- Do not remove escape characters
- Backticks `` ` `` inside bot messages may automatically become `"` at the end because of platform formatting

## Examples

### Original
```json
{
  "success": "{FeelsOkayMan 👍|wydiosOk} Emote ` {emoteName} ` was added successfully"
}
```

✅ Correct Translation (Russian)
```json
{
  "success": "{FeelsOkayMan 👍|wydiosOk} Эмоут ` {emoteName} ` был успешно добавлен"
}
```

❌ Wrong Translation (Russian)
```json
{
  "success": "{FeelsOkayMan 👍|wydiosOk} Эмоут ` {emotename} ` был успешно добавлен"
}
```
