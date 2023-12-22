# MC-EDUCATION
Commands for Minecraft Education 

The structure for a single tests parameters is
```json
{
    "account": "${user}",
    "operation_type": "${operation_type}",
    "query": "${query}",
    "commit": false,
    "should_query_fail": false,
    "expected_error": "${error_type}",
    "expected_row_count": 1
}
``` 
