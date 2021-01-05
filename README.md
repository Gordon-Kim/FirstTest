# FirstTest
github-first-test
# ture coding is now

<%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c" %>
<%@ page session="false" %>
<html>
<head>
<script type="text/javascript">
	function fnCl() {
		alert("Hello World!");
	}
</script>
	<title>First Test Home</title>
</head>
<body>
<h1>
	Hello world!  
</h1>

<button onclick="fnCl()">Click</button>

<P>  The time on the server is ${serverTime}. </P>
</body>
</html>
