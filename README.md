Изменения от основной версии
===

1. Добавил пункт меню во вкладку шаблоны
2. Выполнил привязку этого пункта к лисенеру общей формы
2.1 Добавил поддержку в controller
3. Добавил модели метод поддерживающий редактирование шаблона(за образец взято окно для создания шаблона)
4. Добавлена поддержка загрузки имеющихся компонент шаблона в форму
5. Пофиксил удаление areas в шаблоне FormTemplate бросало NPE
6. Модифицировал метод сохранения шаблона
7. Добавил возможость просмотра шаблона при редактировании


FormScanner
===

FormScanner is an OMR (Optical Mark Recognition) software that automatically marks multiple-choice papers. 
FormScanner not bind you to use a default template of the form, but gives you the ability to use a custom template created from a simple scan of a blank form.
The modules can be scanned as images with a simple scanner and processed with FormScanner software.
All the collected information can be easily exported to a spreadsheet.

---

Build requirements
===

* [Java 6](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Maven (2 or 3)](http://maven.apache.org/)
* [Mercurial](http://mercurial.selenic.com/) (I'm using [TortoiseHg](http://tortoisehg.bitbucket.org/) with Windows Explorer "shell" integration all-in-one installer with TortoiseHg 3.1.1 and Mercurial 3.1.1)

---

Compiling the software
===

$ hg clone http://hg.code.sf.net/p/formscanner/code formscanner-code
$ cd formscanner-code
$ mvn clean install

---

How To Contribute
===

[http://www.bugheaven.com/bugzilla/FormScanner](http://www.bugheaven.com/bugzilla/FormScanner)