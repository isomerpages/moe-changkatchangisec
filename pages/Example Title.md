---
title: Example Title
permalink: /example-title/
description: ""
---

<html>
<head>
<style>
details {
    border: 1px solid #d4d4d4;    
    padding: .75em .75em 0;
	margin-top: 10px;
	box-shadow:0 0 20px #d4d4d4;
}

summary {	
    font-weight: bold;
    margin: -.75em -.75em 0;
    padding: .75em;
    background-color: #5f75a4;
    color: #fff;
}

details[open] {
    padding: .75em;
	border-bottom: 1px solid #d4d4d4;
}

details[open] summary {
    border-bottom: 1px solid #d4d4d4;
    margin-bottom: 10px;
}
</style>
</head>
<body>
	<details>
		<summary>Accordion One</summary>
		Body Content 1
	</details>
	<details>
		<summary>Accordion Two</summary>
		Body Content 2
	</details>
</body>
</html>