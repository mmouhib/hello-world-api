# hello-world-api

```url
[GET] https://mmouhib.github.io/hello-world-api/src/hw.json
```

#### Request in Js
```javascript
const Http = new XMLHttpRequest();
const url = 'https://mmouhib.github.io/hello-world-api/src/hw.json';
Http.open('GET', url);
Http.send();

Http.onreadystatechange = (e) => {
  ob = JSON.parse(Http.responseText);
};

```


#### Sample Response
```json
{
	"lang": "C#",
	"hw": [
		"class HelloWorld",
		"{",
		"    static void Main()",
		"    {",
		"        System.Console.WriteLine(\"Hello, World!\");",
		"    }",
		"}"
	],
	"release_year": "2000"
}
```

![©](https://miro.medium.com/max/700/1*G6MI9xd0POoyNuQdda69NA.jpeg)
