# Github_HW_1_XML
1. Создать внешний репозиторий c названием XML
- <https://github.com/mstepanova1/Github_HW_1_XML.git>

 2. Клонировать репозиторий XML на локальный компьютер
- `git clone https://github.com/mstepanova1/Github_HW_1_XML.git`

 3. Внутри локального XML создать файл “new.xml”
- `cd Github_HW_1_XML`
- `touch new.xml`

 4. Добавить файл под гит
- `git add new.xml`

 5. Закоммитить файл
- `git commit -m "add new.xml"`

 6. Отправить файл на внешний GitHub репозиторий
- `git push`

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML
- `vim new.xml`
- <pre><kbd>i</kbd></pre>
```
<aboutme>
	<name>John</name>
	<surname>Smith</surname>
	<age>27</age>
	<pets>
		<number>1</number>
		<kind_of_pet>cat</kind_of_pet>
		<name>Klaus</name>
	</pets>	
	<desired_salary>10000$</desired_salary>
</aboutme>
```
- <pre><kbd>esc</kbd></pre>
- `:wq`

 8. Отправить изменения на внешний репозиторий
- `git add new.xml ; git commit -m "update new.xml" ; git push`

 9. Создать файл preferences.xml
- `touch preferences.xml`

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML
- `vim preferences.xml`
- <pre><kbd>i</kbd></pre>
```
<mypreferences>
	<movie>Fight club</movie>
	<series>Friends</series>
	<food>borsch</food>
	<season>spring</season>
	<country>Portugal</country>
</mypreferences>
```
- <pre><kbd>esc</kbd></pre>
- `:wq`

 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
- `touch skills.xml`
- `vim skills.xml`
- <pre><kbd>i</kbd></pre>
```
<skills>
	<soft_skills>patiens</soft_skills>
	<hard_skills>
		<one>software testing theory</one>
		<two>client-server architecture</two>
		<three>scrum development methodology</three>
	</hard_skills>
</skills>
```
- <pre><kbd>esc</kbd></pre>
- `:wq`

 12. Сделать коммит в одну строку
- `git add . ; git commit -m "add 2 files: preferences.xml, skills.xml" `

 13. Отправить сразу 2 файла на внешний репозиторий
- `git push`

 14. На веб интерфейсе создать файл bug_report.xml
- `Add file` >> `Create new file` >> `bug_report.xml`

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
- `Commit new file`

 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
- `Edit this file`
```
<bugReport>
	<ID>1</ID>
	<Project>esculab.com</Project>
	<Summary>The text colour of the 'Get result' button merges with the background colour of the button when the cursor is hovered over the service page</Summary>
	<Actual result>The text colour of the 'Get result' button merges with the background colour of the button when the cursor is hovered over the service page</Actual result>
	<Expected result>The colour of the 'Get result' button text becomes white when the cursor is hovered over the service page</Expected result>
	<Pre-conditions>Open the service page. Example https://...</Pre-conditions>
	<Steps_to_reproduce>Place the cursor on the 'Get result' button</Steps_to_reproduce>
	<Environment>macOS BigSur v:11.2.3 Google Chrome v:94.0.4606.71 (x86_64)</Environment>
	<Severity>Trivial</Severity>
	<Priority>Low</Priority>
	<Status>Submitted</Status>
	<Attachments>Video link</Attachments>
	<Workaround>No</Workaround>
	<Reproducibility>Always</Reproducibility>
</bugReport>
```

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе
- `Commit changes`

 18. Синхронизировать внешний и локальный репозиторий XML
- `git pull`
