# SQL-Solved
All Practice SQL Question and Answer

***sq
select 
	employee_id
from public.employees1
	where salary < 30000
	and manager_id is not null
	and manager_id not in (select employee_id from public.employees1)
	order by employee_id;
 ***
