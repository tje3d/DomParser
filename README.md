# DomParser
This is a simple DomParser which can parse invalid html too. Edited version of http://simplehtmldom.sourceforge.net/.
# Installation
`composer require tje3d/domparser`
# Examples
### ✔️ Parse a string
```
$dom = Tje3d\DomParser\DomParser::parse(file_get_contents('url'))
```
### ✔️ Query element
```
$dom->find('.elementClass') // All element's with this class
$dom->find('#myId', 0) // First element with this id
$dom->find('[name=user]')
```
### ✔️ Available Functions
```
innerText, innerHTML, html, getAllAttributes, getAttribute, attr, hasAttribute, parentNode, nextSibling, previousSibling, nodeName
```

# Contact me
You can contact me via [Telegram](https://telegram.me/tje3d) or [Email](mailto:tje3d@yahoo.com).