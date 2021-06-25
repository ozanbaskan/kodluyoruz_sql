# kodluyoruz_sql_odev_8


## Homework
```
CREATE TABLE employee (
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(50)
);
	

insert into employee (id, name, birthday, email) values (1, 'Whitaker Roma', '1990-08-15', 'wroma0@rediff.com');
insert into employee (id, name, birthday, email) values (2, 'Evanne Heintz', '2006-03-03', null);
insert into employee (id, name, birthday, email) values (3, 'Doug Blinder', '2007-02-28', 'dblinder2@lulu.com');
insert into employee (id, name, birthday, email) values (4, 'Harlie Eastwood', '1990-07-17', 'heastwood3@oaic.gov.au');
insert into employee (id, name, birthday, email) values (5, 'Sarge McCallion', '2010-04-05', 'smccallion4@stumbleupon.com');
insert into employee (id, name, birthday, email) values (6, 'Christophe Pellew', '1991-05-02', 'cpellew5@topsy.com');
insert into employee (id, name, birthday, email) values (7, 'Harriette Palleske', '1991-07-29', null);
insert into employee (id, name, birthday, email) values (8, 'Danell Fouldes', '1994-06-24', 'dfouldes7@nytimes.com');
insert into employee (id, name, birthday, email) values (9, 'Livvy Godthaab', '2010-02-06', 'lgodthaab8@ask.com');
insert into employee (id, name, birthday, email) values (10, 'Gabrielle Sheehan', '1994-11-13', 'gsheehan9@rediff.com');
insert into employee (id, name, birthday, email) values (11, 'Traver Mitroshinov', '1995-02-24', 'tmitroshinova@reverbnation.com');
insert into employee (id, name, birthday, email) values (12, 'Terrence Grassi', null, 'tgrassib@networkadvertising.org');
insert into employee (id, name, birthday, email) values (13, 'Pincus Cowins', '1992-07-06', 'pcowinsc@chronoengine.com');
insert into employee (id, name, birthday, email) values (14, 'Nancey Baterip', null, 'nbateripd@list-manage.com');
insert into employee (id, name, birthday, email) values (15, 'Ashton Paule', '1993-12-17', null);
insert into employee (id, name, birthday, email) values (16, 'Sigismond Croote', '2003-05-22', 'scrootef@123-reg.co.uk');
insert into employee (id, name, birthday, email) values (17, 'Albert Friel', null, 'afrielg@networkadvertising.org');
insert into employee (id, name, birthday, email) values (18, 'Dodi Swires', '1991-08-04', 'dswiresh@taobao.com');
insert into employee (id, name, birthday, email) values (19, 'Melodie Coddington', '1996-12-26', 'mcoddingtoni@last.fm');
insert into employee (id, name, birthday, email) values (20, 'Reina Merritt', '1995-01-26', 'rmerrittj@ebay.com');
insert into employee (id, name, birthday, email) values (21, 'Gwyneth Tupp', '1996-03-29', 'gtuppk@bluehost.com');
insert into employee (id, name, birthday, email) values (22, 'Gilemette Cod', '1992-01-21', 'gcodl@mashable.com');
insert into employee (id, name, birthday, email) values (23, 'Cahra Zeal', '1999-06-15', 'czealm@elpais.com');
insert into employee (id, name, birthday, email) values (24, 'Alwyn Spridgeon', null, 'aspridgeonn@ebay.com');
insert into employee (id, name, birthday, email) values (25, 'Casi Yeowell', null, 'cyeowello@sakura.ne.jp');
insert into employee (id, name, birthday, email) values (26, 'Kimberly Carnow', '1995-11-29', 'kcarnowp@fc2.com');
insert into employee (id, name, birthday, email) values (27, 'Bertina Yurkov', '1991-08-30', 'byurkovq@google.com.br');
insert into employee (id, name, birthday, email) values (28, 'Marys Scoone', '1991-09-13', null);
insert into employee (id, name, birthday, email) values (29, 'Wyatan Dickins', '2006-07-15', 'wdickinss@apache.org');
insert into employee (id, name, birthday, email) values (30, 'Dieter Nials', '1990-10-12', 'dnialst@xinhuanet.com');
insert into employee (id, name, birthday, email) values (31, 'Reiko Haldane', '1995-01-24', 'rhaldaneu@spotify.com');
insert into employee (id, name, birthday, email) values (32, 'Kizzee Samuel', '2000-11-02', null);
insert into employee (id, name, birthday, email) values (33, 'Witty Saggs', '1999-01-16', 'wsaggsw@umich.edu');
insert into employee (id, name, birthday, email) values (34, 'Reinold Casterou', '2006-05-13', 'rcasteroux@oaic.gov.au');
insert into employee (id, name, birthday, email) values (35, 'Cleopatra Onion', '2007-07-05', 'coniony@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (36, 'Gerome Lote', '1992-08-25', 'glotez@nature.com');
insert into employee (id, name, birthday, email) values (37, 'Elysee Pietranek', '2010-03-22', 'epietranek10@vinaora.com');
insert into employee (id, name, birthday, email) values (38, 'Jilly Paolazzi', '2006-03-18', 'jpaolazzi11@histats.com');
insert into employee (id, name, birthday, email) values (39, 'Sheff Garrett', '2001-08-08', 'sgarrett12@alexa.com');
insert into employee (id, name, birthday, email) values (40, 'Carmita Little', '2000-09-13', 'clittle13@ow.ly');
insert into employee (id, name, birthday, email) values (41, 'Riki Annell', '1993-10-05', 'rannell14@skyrock.com');
insert into employee (id, name, birthday, email) values (42, 'Lucie Huonic', '2007-01-22', 'lhuonic15@vk.com');
insert into employee (id, name, birthday, email) values (43, 'Johannah Reihm', '2004-06-08', 'jreihm16@xinhuanet.com');
insert into employee (id, name, birthday, email) values (44, 'Curran Senussi', '1998-09-24', 'csenussi17@cisco.com');
insert into employee (id, name, birthday, email) values (45, 'Sol Fowls', '2009-06-27', 'sfowls18@geocities.jp');
insert into employee (id, name, birthday, email) values (46, 'Novelia Fearnsides', '2005-03-20', 'nfearnsides19@storify.com');
insert into employee (id, name, birthday, email) values (47, 'Noelle De Roeck', null, 'nde1a@deviantart.com');
insert into employee (id, name, birthday, email) values (48, 'Cathie McArley', '1993-03-09', null);
insert into employee (id, name, birthday, email) values (49, 'Chiquia Fehely', '1999-12-22', 'cfehely1c@usgs.gov');
insert into employee (id, name, birthday, email) values (50, 'Merell Grafhom', '1997-06-12', 'mgrafhom1d@usatoday.com');


UPDATE employee SET name = 'CENSORED' WHERE name ILIKE '%sheff%';
UPDATE employee SET email = 'company@email.com' WHERE email IS NULL;
UPDATE employee SET birthday = '1997-06-05' WHERE birthday IS NULL;
UPDATE employee SET name = 'Terrible Person' WHERE birthday > '2000-01-01';
UPDATE employee SET name = 'Cool Person' WHERE birthday <= '2000-01-01';

DELETE FROM employee WHERE birthday = '1997-06-05';
DELETE FROM employee WHERE name = 'Terrible Person';
DELETE FROM employee WHERE id > 45;
DELETE FROM employee WHERE email ILIKE '%ebay.com%';
DELETE FROM employee WHERE email = 'company@email.com';
```
