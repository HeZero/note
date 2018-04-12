insert into `table` (...)values(...),(...) on duplicate key update `column` = values(`column`)
  mysql 插入时检测数据库是否存在key，如果存在则更新，否则插入, 后跟update语句更新相应旧记录值为新值
