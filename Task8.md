# Patika SQL Task-8


#1-test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee(
    id INTEGER PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    birthday DATE,
    email VARCHAR(100)
);



#2-Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Rem', '1976-05-03', 'rtonkes0@ovh.net');
insert into employee (id, name, birthday, email) values (2, 'Eulalie', '1971-11-03', 'edacres1@google.com');
insert into employee (id, name, birthday, email) values (3, 'Aarika', '1908-08-16', 'ajosephy2@nationalgeographic.com');
insert into employee (id, name, birthday, email) values (4, 'Uta', '1932-03-03', 'uhelleckas3@vkontakte.ru');
insert into employee (id, name, birthday, email) values (5, 'Joellen', null, 'jmalyon4@tinyurl.com');
insert into employee (id, name, birthday, email) values (6, 'Gayelord', '1936-10-27', 'gbaugh5@free.fr');
insert into employee (id, name, birthday, email) values (7, 'Wolfy', '1974-10-25', 'wrudolph6@google.it');
insert into employee (id, name, birthday, email) values (8, 'Angelle', '1949-08-30', 'adavidescu7@mediafire.com');
insert into employee (id, name, birthday, email) values (9, 'Courtenay', '1991-06-05', 'cpally8@cam.ac.uk');
insert into employee (id, name, birthday, email) values (10, 'Grange', null, 'gtreffry9@1und1.de');
insert into employee (id, name, birthday, email) values (11, 'Denney', null, 'dmaggiorea@naver.com');
insert into employee (id, name, birthday, email) values (12, 'Abbey', null, 'askingleyb@zimbio.com');
insert into employee (id, name, birthday, email) values (13, 'Maddalena', '1934-04-01', null);
insert into employee (id, name, birthday, email) values (14, 'Dulcia', '1930-05-16', null);
insert into employee (id, name, birthday, email) values (15, 'Kipp', '1922-07-01', 'kdowlee@miitbeian.gov.cn');
insert into employee (id, name, birthday, email) values (16, 'Thatch', '1997-04-26', 'toldroydf@bloglovin.com');
insert into employee (id, name, birthday, email) values (17, 'Alexina', null, 'aquilterg@pagesperso-orange.fr');
insert into employee (id, name, birthday, email) values (18, 'Danya', '1907-04-08', 'dlatehouseh@devhub.com');
insert into employee (id, name, birthday, email) values (19, 'Ashly', '1916-03-30', 'abethoi@economist.com');
insert into employee (id, name, birthday, email) values (20, 'Berne', '1902-10-20', 'bdollinj@taobao.com');
insert into employee (id, name, birthday, email) values (21, 'Wells', '1941-08-07', 'wmifflink@cnet.com');
insert into employee (id, name, birthday, email) values (22, 'Joseph', '1991-07-18', 'jadamovl@bing.com');
insert into employee (id, name, birthday, email) values (23, 'Chan', '1935-09-25', 'callewellm@xrea.com');
insert into employee (id, name, birthday, email) values (24, 'Rubia', '1907-08-27', 'rhalsonn@lycos.com');
insert into employee (id, name, birthday, email) values (25, 'Alli', '1983-01-05', 'azielinskio@ftc.gov');
insert into employee (id, name, birthday, email) values (26, 'Kate', '1910-01-08', 'kgeanyp@flavors.me');
insert into employee (id, name, birthday, email) values (27, 'Valdemar', '1959-11-24', 'vmartinecq@tamu.edu');
insert into employee (id, name, birthday, email) values (28, 'Humfrey', '1951-11-28', 'hgoldsbyr@studiopress.com');
insert into employee (id, name, birthday, email) values (29, 'Prudi', '1940-04-11', 'poakenfields@phoca.cz');
insert into employee (id, name, birthday, email) values (30, 'Clarette', '1937-08-28', 'ctolputtt@wikimedia.org');
insert into employee (id, name, birthday, email) values (31, 'Leroy', '1913-06-28', 'lnowillu@youku.com');
insert into employee (id, name, birthday, email) values (32, 'Benedikt', '1968-05-10', 'bhillamv@usa.gov');
insert into employee (id, name, birthday, email) values (33, 'Charo', '1994-07-13', 'clenormandw@google.it');
insert into employee (id, name, birthday, email) values (34, 'Lucy', '1947-02-06', 'lragdalex@earthlink.net');
insert into employee (id, name, birthday, email) values (35, 'Euphemia', '1947-09-06', 'elawransony@plala.or.jp');
insert into employee (id, name, birthday, email) values (36, 'Fae', '1905-08-15', 'fposchelz@sciencedirect.com');
insert into employee (id, name, birthday, email) values (37, 'Fredrika', '1992-11-10', null);
insert into employee (id, name, birthday, email) values (38, 'Yalonda', '1977-04-21', 'ypickover11@whitehouse.gov');
insert into employee (id, name, birthday, email) values (39, 'Breanne', null, 'bpinckney12@foxnews.com');
insert into employee (id, name, birthday, email) values (40, 'Jock', null, 'jloy13@etsy.com');
insert into employee (id, name, birthday, email) values (41, 'Gaylor', '1948-01-29', 'gbertie14@weebly.com');
insert into employee (id, name, birthday, email) values (42, 'Sibel', '1962-06-21', 'swanka15@4shared.com');
insert into employee (id, name, birthday, email) values (43, 'Yorgo', '1984-09-29', 'yforce16@unc.edu');
insert into employee (id, name, birthday, email) values (44, 'Fredek', '1923-04-30', null);
insert into employee (id, name, birthday, email) values (45, 'Bev', '1915-08-13', 'bstronough18@reverbnation.com');
insert into employee (id, name, birthday, email) values (46, 'Adah', '1999-04-11', 'ajacquest19@liveinternet.ru');
insert into employee (id, name, birthday, email) values (47, 'Zara', '1996-08-03', 'zbaelde1a@comcast.net');
insert into employee (id, name, birthday, email) values (48, 'Gaston', '1986-01-01', 'gbaldery1b@bizjournals.com');
insert into employee (id, name, birthday, email) values (49, 'Laureen', null, 'lodulchonta1c@about.com');
insert into employee (id, name, birthday, email) values (50, 'Dolley', '1927-02-12', 'dclissell1d@meetup.com');

#3-Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.


UPDATE employee
SET name = 'KEZBAN'
WHERE name LIKE 'B%'
RETURNING *;


#4-Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.


DELETE FROM employee
WHERE id=4
RETURNING *;


DELETE FROM employee
WHERE name = 'furkan';


DELETE FROM employee
WHERE name = 'KEZBAN'
AND id IN (
    SELECT id FROM employee WHERE name = 'KEZBAN' LIMIT 2
)
RETURNING *;
