# ElifTechTest
ElifTech test task

Database schema:

Table 'company_list'
  `company_id` int(11) NOT NULL AUTO_INCREMENT KEY,
  
  `company_name` varchar(100) NOT NULL UNIQUE,
  
  `company_earnings` int(11) NOT NULL;

Table 'organization_tree'
  `id` int(11) NOT NULL AUTO_INCREMENT KEY,
  
  `main_id` int(11) NOT NULL,
  
  `sub_id` int(11) NOT NULL UNIQUE;
