# 2016年4月

## 11
```javascript
/**
 * 删除所有空格
 */
function ignoreSpacesAll(string) {
	var temp = "";
	string = '' + string;
	splitstring = string.split(" ");
	for (i = 0; i < splitstring.length; i++)
		temp += splitstring[i];
	return temp; * /
}
/**
 * 删除首尾空格
 */
function ignoreSpace(string) {
	return string.replace(/(^\s*)|(\s*$)/g, "");
}
```