21. Создать внешний репозиторий c названием XML.			Github.com   xml
 22. Клонировать репозиторий XML на локальный компьютер.		git clone https://github.com/KlimentsiLiakhavets/xml.git
 23. Внутри локального XML создать файл “new.xml”.			cd xml
									touch new.xml
 24. Добавить файл под гит.						git add new.xml
 25. Закоммитить файл.							git commit -m "add new.xml"
 26. Отправить файл на внешний GitHub репозиторий.			git push
 
 27. Отредактировать содержание файла “new.xml”				vim new.xml
     написать информацию о себе 					i
     (ФИО, возраст, количество домашних животных, 			<info>
     будущая желаемая зарплата). Всё написать в формате XML.			<FIO>Liakhavets_Klimentsi_Aleksandrovich</FIO>
        									<age>39</age>
        									<animal>0</animal>
        									<salary>500</salary>
									</info>
									  Esc
									  :wq

 28. Отправить изменения на внешний репозиторий.			git add new.xml
									git commit -m "changes_new.xml"
									git push
 
 29. Создать файл preferences.xml					touch preferences.xml
									vim preferences.xml
 30. В файл preferences.xml добавить информацию о своих 		i
     предпочтениях (Любимый фильм, любимый сериал, 			
     любимая еда, любимое время года, сторона которую			<info>
     хотели бы посетить) в формате XML.						<favorit_movie>Leon</favorit_movie>
        									<favorit_TV_serial>The_fathers_rus</favorit_TV_serial>
        									<favorit_food>sandwich</favorit_food>
        									<favorit_time_of_year>summer</favorit_time_of_year>
        									<the_country_you_would_like_to_visit>USA</the_country_you_would_like_to_visit>
									</info>
									    Esc
									    :wq
     
 31. Создать файл sklls.xml добавить информацию о 			touch skills.xml
     скиллах которые будут изучены на курсе в формате XML		vim skills.xml
									i
							<info>
							   <skills>
								Basic_theory
								client-server_architecture
								Methods_of_requests_to_the_server
								Server_responses
								Structures_of_requests_and_responses
								JSON,_XML._Their_structure
								API_testing
								Removing_and_reading_logs
								Postman,_Fidler
								VPN._How_it works,_why_it_is_needed,_how_to_use,_tool_options
								Dev_Tools_of_web_browsers_Google_Chrome_FireFox
								Mobile_testing
								Feature_of_iOS,_Android,_guidelines
								Building_iOS_apps_on_XCode
								Building_Android_apps_on_ndroid_Studio
								Interception_of_mobile_traffic_via_Charles
								Proxy_settings_on_iOS_and_Android
								Command_line_terminal_Linux
								Simple_bash_scripting,_automation_of_routine_tasks_on_the_server
								Access_to_remote_servers
								SQL_Basics_Create,_Delete,_Drop,_Insert_Into,_Select,_From,_Where,_Join
								Git
								Jmeter
								Scrum_Development_Methodology
								Python._Creating_your_own_client_server_application
							   </skills>
							</info>

 32. Сделать коммит в одну строку.					git add .
									git commit -am "files"
 33. Отправить сразу 2 файла на внешний репозиторий.			git push
 34. На веб интерфейсе создать файл bug_report.xml.			.../xml
									Add file
									Create new file
									bug_report.xml
																		
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	"bug"
									Commit new file
 36. На веб интерфейсе модифицировать файл bug_report.xml,		нажать на файл bug_report.xml
     добавить баг репорт в формате XML.					Edit this file
						<info>
  							<ID>Identification_number</ID>
  							<Title_or_Summary>Brief_description_of_the_bug</Title_or_Summary>
  							<Project>Project_name_where_the_bug_was_found</Project>
  							<Detected_in_Version>The_exact_version_of_the_software_containing_the_bug</Detected_in_Version>
  							<Date_Detected>Date_of_discovery</Date_Detected>
  							<Severity>Severity_of_the_bug</Severity>
 							<Priority>Urgency_of_bug_fixing</Priority>
  							<Status>at_what_stage_is_the_bug</Status>
  							<Detected_by>The_creator_of_the_bug_report</Detected_by>
  							<Assigned_to>Who_will_fix_the_bug</Assigned_to>
  							<Test_case_Failed>Steps_to_reproduce_the_bug</Test_case_Failed>
  							<Actual_result_and_expected_result>How_the_program_works_now_and_how_the_program_should_actually_work</Actual_result_and_expected_result>
  							<Attachment>Links_screenshots_that_will_help_you_understand_the_essence_of_the_problem</Attachment>
						</info>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	"changes"
									Commit changes
 38. Синхронизировать внешний и локальный репозиторий XML		В Git Bash команда git pull
