
# Ordinal Century Number Replacer

Util class to replace ordinal numbers under 30




## API Reference

#### .isOrdinal
Check if string is an ordinal word

```
  .isOrdinal("1s") //false
  .isOrdinal("21st") //true
  .isOrdinal("28rd") //false
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `word` | `string` | **Required**. word to check |

#### .getComplete

```
  .getComplete("21st") //twenty-first
  .getComplete("13th") //thirteenth
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `word`      | `string` | **Required**. word to replace |


