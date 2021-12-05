# L20_HomeWork24-11-21
1. CREATE TABLE Students (id INTEGER PRIMARY KEY, name TEXT, city TEXT, birth INTEGER);   CREATE TABLE Grade (id INTEGER PRIMARY KEY, grade INTEGER); 
2. SELECT S.id grade, S.name, S.city, P.birth FROM Students s
    join Grade g on s.id = g.id
3. select * from Grade;
select count(*) how_many_grade, avg(grade) from Grade
4. ALTER TABLE Grade ADD COLUMN EXCELLENT //לא יודעת מה הפתרון של ההמשך
5. 5.select * from Students where Grade > (select avg(Grade) from Grade)
