1.配置servlet时不用写web.xml，写@WebServlet("/AddServlet")就行了
其中/AddServlet的含义是访问http://127.0.0.1/webname/AddServlet就来执行本文件
这个/表示项目的根，即webname是根

2.在controller.AddServlet中写request.getRequestDispatcher("page/manage.jsp");
则访问http://127.0.0.1/webname/page/manage.jsp
完全不看controller包是否是文件夹


form访问Servlet时要写上项目路径即/test/AddServlet
