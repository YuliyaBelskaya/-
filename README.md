# -
дефекты "Создать расписание"
Описание системы: система представляет собой веб-приложение, в котором можно:
1. Составлять расписание тренерам
2. Записывать на занятия учеников
3. Управлять занятиями учеников и тренеров (отменять, переносить,...)
4. Вести тренерам занятия с учениками, используя чат и видеочат
5. Вести другую административную работу 
Описанные дефекты, относятся к форме «Создать расписание»
Identifier 1	
Summary: "Create schedule " is written in English on the «Create Schedule» page	
Description: When you go to the «Create Schedule» page, the page name is written in English	Precondition: Open the "Create Schedule" page	Steps: Look at the page name carefully
Actual result: The page name is written in English "Create schedule"	
Expected result: The page name is written in Russian «Создать расписание»	
Reproducibility: always	
Severity: medium	
Priority: normal	
Symptom: Localization issue	
Workaround: no	
Comments
Attachments
Identifier 2	
Summary: Date in the «Date» field is entered using the keyboard on the «Create Schedule» page	
Description: You can enter the date using the keyboard in the «Date» field on the «Create Schedule» page	
Precondition: Open the "Create Schedule" page	
Steps:  Enter the current date using the keyboard in the «Date» field on the «Create Schedule» page	
Actual result: The current date is entered in the «Date» field on the «Create Schedule» page	
Expected result: You can not enter the current date using the keyboard in the «Date» field, only select a date from the calendar	
Reproducibility: always	
Severity: major	
Priority: normal	
Symptom: Variance from specs	
Workaround: no	
Comments
Attachments
Identifier 3	
Summary: The calendar is missing in the «Date» field on the «Create Schedule» page	
Description: On the «Create Schedule» page there is no calendar for selecting a date in the «Date» field on the right side	
Precondition:  Open the "Create Schedule" page	
Steps: Look at the “Date” field on the right carefully	
Actual result: The calendar is missing in the “Date”field on the “Create Schedule” page	
Expected result: The calendar for selecting the date is located on the right side in the “Date” field	
Reproducibility: always	
Severity: major	
Priority: normal	
Symptom: Variance from specs	
Workaround: no	
Comments
Attachments
Identifier 4	
Summary: The current date is not valid on the “Create Schedule” page	
Description: When you go to the “Create Schedule” page  the current date does not correspond to reality.	
Precondition:  Open the "Create Schedule" page	
Steps: Compare the current date with the date in the “Date” field on the “Create Schedule” page	
Actual result: The current date is not valid on the “Create Schedule” page	
Expected result: The current date is today's date	
Reproducibility: always	
Severity: critical	
Priority: ASAP	
Symptom: Variance from specs	
Workaround: no	
Comments
Attachments
Identifier 5	
Summary: Two checkboxes are installed on the “Create Schedule” page	
Description: It is possible to set two checkboxes on the “Create Schedule” page.	
Precondition:  Open the "Create Schedule" page	
Steps: 1. Install the "Permanent" checkbox
2. Install the "Individual" checkbox	
Actual result: Two checkboxes are installed on the “Create Schedule” page
Expected result: It is possible to install only one checkbox	
Reproducibility: always	
Severity: critical	
Priority: ASAP	
Symptom: Missing feature	
Workaround: no	
Comments
Attachments
Identifier 6	
Summary: The class time does not match the 30-minute step in the “Class Time” field on the “Create Schedule “ page.	
Description: The class time does not match the 30-minute step in the “Class Time” field on the “Create Schedule” page. On the “Create Schedule” page when you select class time  the 30-minute step in the Class Time field is not followed. The list of times to select from the drop-down list starts from 00:00.	
Precondition: Open the "Create Schedule" page	
Steps: 1. In the “Class Time” field click on the arrow. 
2. Carefully check that the class time in the drop-down list of the “Class Time” field does not correspond to the 30-minute step.	
Actual result: The class time does not match the 30-minute step in the “Class Time “ drop-down list on the “Create Schedule” page.	
Expected result: The class time corresponds to the 30-minute step in the “Class Time” drop-down list on the “Create Schedule” page	
Reproducibility: always	
Severity: critical	
Priority: ASAP	
Symptom: Missing feature	
Workaround: no	
Comments
Attachments
Identifier 7	
Summary: Spelling error in the name of the “Треннер” field on the “Create Schedule” page	
Description: On the “Create Schedule” page the name of the «Треннер»  field contains a spelling error. The word coach is written with a single "н".	
Precondition: Open the "Create Schedule" page	
Steps: Look at the name of the «Треннер» field carefully.	
Actual result: The name of the «Треннер» field is written with two letters " н"	
Expected result: The name of the «Тренер» field is written with a single letter " н " in accordance with the rules of the Russian language.	
Reproducibility: always		
Severity: minor	
Priority: low	
Symptom: Cosmetic flaw	
Workaround: no	
Comments
Attachments

