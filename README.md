### cql
CREATE TABLE user_movie (
  userId int,
  movId int,
  time timestamp,
  PRIMARY KEY (userId, movId)
);