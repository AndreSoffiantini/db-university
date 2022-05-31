# DB: University

## TABLES

### Departments

id:         PK NOTNULL UNIQUE INDEX AI
name:

### Degree_programs

id:         PK NOTNULL UNIQUE INDEX AI
code:
name:
description:
degree_level:
location:
duration:
official_languages:

### Courses

id:             PK NOTNULL UNIQUE INDEX AI
code:
SSD:
type:
name:           VARCHAR(100) NOTNULL
description:
semester:
cfu:            TINYINT
language:

### Course_professor

teacher_id:     FK
course_id:      FK

### Professors

id:             PK NOTNULL UNIQUE INDEX AI
name:           VARCHAR(20) NULL
lastname:       VARCHAR(20) NOTNULL
qualification: 

### Exams sessions

id:         PK NOTNULL UNIQUE INDEX AI
date:       DATE

### Students

id:         PK NOTNULL UNIQUE INDEX AI
name:       VARCHAR(20) NULL
lastname:   VARCHAR(20) NOTNULL
serial_number:


