SublimeText-JavaScriptCustom
============================

Custom JavaScript snippets for Sublime Text because the defaults suck

## Instructions
1. Clone this repo into your packages folder. On Mac `~/Library/Application Support/Sublime Text 2/Packages/`
1. Ignore the default package in your settings, like such:
```
{
  "ignored_packages": ["JavaScript"]
}
```

## What's different?

### Space after annoymous function 
New:
```
function () {

}
```

Old: `function() {}`

### Single quotes instead of double quotes
New: ```key: 'value'```

Old ```key: "value"```

### No semicolon after if-statement (who thought this was a good idea?!)
New: 
```Javascript
if () {

}
```

Old:
```Javascript
if () { };
```
