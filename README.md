# business-setup
In this repository, users, groups, and directories were created for a small business. Additionally, ownership was reassigned, and appropriate access rights were granted to the relevant groups. The commands used to accomplish these tasks are outlined below.
# Users:
•Andrew, System Administrator
•Julius, Legal
•Chizi, Human Resource Manager
•Jeniffer, Sales Manager
•Adeola, Business Strategist
•Bach, CEO
•Gozie, IT intern
•Ogochukwu, Finance Manager 
 # Groups:
•executive/Leadership:
CEO
•Administrative/Support Functions:
Human Resource Manager,
Legal
•Finance and Strategy:
Finance Manager, 
business Strategist
•Sales and Marketing:
Sales Manager
•Information Technology (IT):
System Administrator,
IT intern
# Company Documents(Directories):
•Finance Budgets
•Contract Documents
•Business Projections
•Business Models
•Employee Data
•Company Vision and Mission Statement
•Server Configuration Script

# Adding Users:
this was done using the adduser command(adduser username), as seen below

•adduser andrew
•adduser julius
•adduser chizi
•adduser jeniffer
•adduser adeola
•adduser bach
•dduser gozie
•adduser ogochukwu

# adding groups
this was done using the addgroup command(addgroup groupname), as seen below

•addgroup executive
•ddgroup administrative
•addgroup finance and strategy
•ddgroup sales and marketing 
•addgroup information technology

# creating directories
this was done using the mkdir command(mkdir company douments), as seen below

•mkdir Finance_Budgets
•mkdir Contract_Documents
•mkdir Business_Projections
•mkdir Business_Models
•mkdir Employee_Data
•mkdir Company_Vision_and_Mission_Statement
•mkdir Server_Configuration_Script

# Assigning Users To Groups:
this was done using the usermod command(sudo usermod -aG group user), as seen below

•sudo usermod -aG excecutive bach
•sudo usermod -aG administrative chizi
•sudo usermod -aG administrative julius
•sudo usermod -aG finance_and_strategy ogochukwu
•sudo usermod -aG finance_and_strategy adeola
•sudo usermod -aG sales_and_marketing jeniffer
•sudo usermod -aG information_technology andrew
•sudo usermod -aG information_technology gozie

# Changing ownership
this was done using the chown command(sudo chown user:group directory), as seen below

•sudo chown adeola:finance_and_strategy business_models
•sudo chown julius:administrative contract_documents
•sudo chown ogochukwu:finance_and_strategy finance_budgets
•sudo chown chizi:administrative employee_data
•sudo chown bach:excecutive company_vision_and_mission_statement
•sudo chown andrew:information_technology sever_configuration_script
•sudo chown adeola:finance_and_strategy business_projections

# Assigning permission
this was done using the chmod command(sudo chmod directory), as seen below

•sudo chmod 740 business_models
•sudo chmod 740 business_projections
•sudo chmod 740 company_vision_and_mission_statement
•sudo chmod 740 contract_documents
•sudo chmod 740 employee_data
•sudo chmod 740 finance_budgets
•sudo chmod 740 sever_configuration_script

N.B: the notation symbol is 740 because the user is allowed to read, write and execute, while the group can only read and others have no permission


