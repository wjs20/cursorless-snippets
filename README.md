Set the cursorless `Snippet Dir` setting to be:
C:\\Users\\WilliamSteele\\AppData\\Roaming\\Code\\User\\snippets

Clone this repository to that location.

Create snippets like:
"jsonDump.cursorless-snippets"
```
{
  "jsonDump": {
    "definitions": [
      {
        "scope": {
          "langIds": [
            "python"
          ]
        },
        "body": [
          "with open('$file_name', 'w') as f:",
          "\tjson.dump($variable, f)"
        ]
      }
    ],
    "description": "",
    "variables": {
      "file_name": {},
      "variable": {}
    }
  }
}
```
Map the snippet name to the spoken form in:
"C:\Users\WilliamSteele\AppData\Roaming\talon\user\cursorless-settings\experimental\insertion_snippets.csv"
