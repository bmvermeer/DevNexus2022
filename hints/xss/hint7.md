# Hint 7

In `UserContoller.java` adjust the method `directLink()` similar to this:

```java
    @GetMapping("/user")
    public void directLink (@RequestParam String param, HttpServletResponse response) throws IOException {
        List<User> found = searchRepo.findUsersByUsername(param);
        response.setContentType("text/html");
        response.getWriter().write("<h1>User: "+ Encode.forHtml(param) + "</h1>");
        ...
```
