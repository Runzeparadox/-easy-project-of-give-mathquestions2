# 基于-easy-project-of-give-mathquestions的简单算数抽奖程序，下面是关于本程序的一些具体信息
导入了几个用于创建JavaFX应用的包，包括Application、Scene、Button、TextArea、HBox和Stage。

导入了java.util.Random，用于生成随机数。

定义了一个名为Main的类，该类继承了Application类。

定义了main方法，用于启动JavaFX应用。

定义了start方法，该方法会在JavaFX应用启动时被调用。

在start方法中，创建了两个TextArea对象，分别命名为textArea和textArea2。

创建了一个Button对象，命名为btn。设置了按钮的文本为"重新抽取数据"。

创建了一个automath对象，命名为mat，并调用了mat的sss方法，将结果赋值给a。

-----------------------------------------------------------------------------------------------
  在这段代码中，你创建了一个JavaFX应用程序，包括两个文本区域（textArea和textArea2）和一个按钮（btn）。在main方法中，你使用launch函数启动了应用程序。在start方法中，你设置了主舞台的标题并创建了一个新场景。你还使用setStyle方法设置了textArea的样式，并使用appendText方法将文本添加到textArea中。然后你将textArea和textArea2添加到一个水平布局（HBox）中，并将这个布局添加到场景中。你还使用setOnAction方法为按钮添加了一个单击事件处理程序。当用户单击按钮时，会随机生成两个字符串，并将它们拼接到一起。最后，你使用了setMinSize和setMaxSize方法设置了钮的大小，然后使用for循环向textArea2中添加了20行练习内容,还使用了setScene方法将场景到主舞台上，并使用show方法显示舞台。
