```
1. Создайте текстоовый файл как в первом ДЗ по Terminal.		Первое ДЗ (GitHub/.../Task_1)
 2. Сценарий перенесите в этот файл.					Liakhavets_HM_1.txt
 3. На против каждого действия - напишите команду в GitBash

JSON
 4. Создать внешний репозиторий c названием JSON.			Github.com   json
 5. Клонировать репозиторий JSON на локальный компьютер.		git clone https://github.com/KlimentsiLiakhavets/json.git
 6. Внутри локального JSON создать файл “new.json”.			cd json
									touch new.json		
 7. Добавить файл под гит.						git add new.json
 8. Закоммитить файл.							git commit -m "add new.json"
 9. Отправить файл на внешний GitHub репозиторий.			git push

10. Отредактировать содержание файла “new.json” 			vim new.json
    - написать информацию о себе (ФИО, возраст, 			i
      количество домашних животных, будущая желаемая зарплата).		{
      Всё написать в формате JSON.					      "person" : {
                								"FIO" : "Liakhavets_Klimentsi_Aleksandrovich",
               									 "age" : 39 },
                								 "animal" : null,
               									 "salary" : 500
									}
										Esc
      										:wq

11. Отправить изменения на внешний репозиторий.	
                                                                        git add new.jsongit 
                                                                        commit -m "changes new.json"
                                                                        git push

12. Создать файл preferences.json					touch preferences.json
 
 13. В файл preferences.json добавить информацию о 			vim preferences.json
     своих предпочтениях (Любимый фильм, любимый сериал, 		i
     любимая еда, любимое время года, 					{
     сторона которую хотели бы посетить) в формате JSON.			"favorit_movie" : "Leon",
        									"favorit_TV_serial" : "The_fathers_rus",
       										"favorit_food" : "sandwich",
        									"favorit_time_of_year" : "summer",
        									"the_country_you_would_like_to_visit" : "USA"
									}
										Esc
      										:wq   

14. Создать файл sklls.json добавить информацию о скиллах 		touch skills.json
     которые будут изучены на курсе в формате JSON			vim skills.json
									i
									{
        								"skills" : [ "Basic_theory",
                							"client-server_architecture",
                							"Methods_of_requests_to_the_server",
                							"Server_responses",
                							"Structures_of_requests_and_responses",
                							"JSON,_XML._Their_structure",
                							"API_testing",
                							"Removing_and_reading_logs",
                							"Postman,_Fidler",
                							"VPN._How_it works,_why_it_is_needed,_how_to_use,_tool_options",
                							"Dev_Tools_of_web_browsers_Google_Chrome_FireFox",
                							"Mobile_testing",
                							"Feature_of_iOS,_Android,_guidelines",
                							"Building_iOS_apps_on_XCode",
                							"Building_Android_apps_on_ndroid_Studio",
                							"Interception_of_mobile_traffic_via_Charles",
                							"Proxy_settings_on_iOS_and_Android",
                							"Command_line_terminal_Linux",
                							"Simple_bash_scripting,_automation_of_routine_tasks_on_the_server",
                							"Access_to_remote_servers",
                							"SQL_Basics_Create,_Delete,_Drop,_Insert_Into,_Select,_From,_Where,_Join",
                							"Git",
                							"Jmeter",
                							"Scrum_Development_Methodology",
                							"Python._Creating_your_own_client_server_application" ]
									}
									Esc
									:wq

 15. Отправить сразу 2 файла на внешний репозиторий.			git add . 
									git commit -am "favorit_and_skills"
									git push
									

 16. На веб интерфейсе создать файл bug_report.json			..../json
									Add file
									Create new file
									bug_report.json
 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	"new file"
									Commit new file

 18. На веб интерфейсе модифицировать файл bug_report.json, 		нажать на файл bug_report.json
     добавить баг репорт в формате JSON.				Edit this file
								    {
  									"ID" : "Identification_number",
  									"Title_or_Summary" : "Brief_description_of_the_bug",
  									"Project" : "Project_name_where_the_bug_was_found",
  									"Detected_in_Version" : "The_exact_version_of_the_software_containing_the_bug",
  									"Date_Detected" : "Date_of_discovery",
  									"Severity" : "Severity_of_the_bug",
  									"Priority" : "Urgency_of_bug_fixing",
  									"Status" : "at_what_stage_is_the_bug",
  									"Detected_by" : "The_creator_of_the_bug_report",
  									"Assigned_to" : "Who_will_fix_the_bug",
  									"Test_case_Failed" : "Steps_to_reproduce_the_bug",
  									"Actual_result_and_expected_result" : "How_the_program_works_now_and_how_the_program_should_actually_work",
  									"Attachment" : "Links_screenshots_that_will_help_you_understand_the_essence_of_the_problem"
								     }
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.	"changes"
									Commit changes
 20. Синхронизировать внешний и локальный репозиторий JSON		В Git Bash команда git pull
