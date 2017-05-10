# docker_scripts

create DB
[HOST]     [CMD]  [SERVICE] [PORT]  
ssh  docker@srv1bout bash -s -- < greenbox_db_create  bringout.db.out.ba  54323
backup DB
[HOST]     [CMD]  [SERVICE]
ssh  docker@srv1bout bash -s -- < greenbox_db_backup  bringout.db.out.ba
restore DB
[HOST]     [CMD]  [SERVICE] [SOURCE]
ssh  docker@srv1bout bash -s -- < greenbox_db_restore  valpaint-nova.db.out.ba  valpaint.db.out.ba
