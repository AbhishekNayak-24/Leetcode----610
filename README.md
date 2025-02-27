# Leetcode----610
Triangle Judgement 
//code in mysql
select *, 
    if(x+y>z and x+z>y and y+z>x, 'Yes', 'No') as triangle
from triangle
