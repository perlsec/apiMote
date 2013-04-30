apiMote
=======

Example Profile Structure
=================
```json
{
    "name": "Test",
    "timeout": 20
    "controls": [
        {
            "label": "Button One",
            "url": "http://test.com/test1.php",
            "action": "GET"
        },
        {
            "label": "Button Two",
            "url": "http://test.com/test2.php",
            "action": "POST",
            "extras": [
                "name",
                "age",
                "sex"
            ]
        }
    ]
}
```
