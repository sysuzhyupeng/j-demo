Applet
-
Applet用来嵌入网页
```html
  <html>
    <head>
    <title>This is an applet program !</title> </head>
    <body>
    <applet code="FirstApplet.class" width=250 height=150></applet>
    </body>
   </html>
```
Servlet
-
Servlet 在服务器内部运行，通过客户端提交的请求启动运行,并将结果还回给客户端或调用它的程序
```java
  out.println("<html>"); 
  out.println("<head>"); 
  out.println("</head>"); 
  out.println("<body>");
```
Struts 框架对 Servlet 做了很好的封装，是一 种简单成熟而广泛用应的开发框架。

JSP程序
-
若所有前台的 HTML 代码都通过 Servlet 生成，则会使 Servlet 负荷重性能降低，JSP(Java Server Page)应运而生。
利用 JSP 实现前台较好的动态效果，运行 Servlet 实现后台较好的逻辑操作。 JSP 可以将静态的 HTML 与动态生成的内容混合起来。
