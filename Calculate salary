create function myfunction5(d_name in varchar2) return number
is v_sal number(8,2); 
begin  
select sal/31*(sysdate-add_months(round(sysdate,'month'),-1)) into v_sal 
from scott.emp 
where ename=d_name ; 
return v_sal; 
end;
