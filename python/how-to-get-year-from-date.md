# How to get year from date

```python
import datetime
date = '2022-10-20 10:11:12'
year = datetime.datetime.strptime(date, "%Y-%m-%d %H:%M:%S").year
```

- `datetime` - module to manipulate dates/times
- `date = ` - example date to extract part from
- `datetime.datetime.strptime` - parses given string  with the given format
- `"%Y-%m-%d %H:%M:%S"` - format of the datetime string to parse
- `.year` - returns year part of the date

group: date_extract

## Example: 
```python
import datetime
date = '2022-10-20 10:11:12'
year = datetime.datetime.strptime(date, "%Y-%m-%d %H:%M:%S").year
print(year)
```
```
2022

```

## Additional keywords
- parse
- datetime
- extract
