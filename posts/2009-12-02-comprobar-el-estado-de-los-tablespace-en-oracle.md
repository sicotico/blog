---
title: "Comprobar el estado de los tablespace en Oracle"
date: "2009-12-02"
categories: 
  - "sin-categoria"
---

SELECT tablespace\_name,SUM(bytes)/1024/1024, SUM(blocks)

FROM dba\_temp\_files

GROUP BY tablespace\_name
