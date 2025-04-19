# Table Structure

## table 1 => courses

- course id **int** (primary key)
- course name **varchar** (not null)

## table 2 => Students

- student id **int** (primary key)
- student name **varchar** (not null)
- course id **int** (foreign key referencing courses(course id))
  
## table 3 => Teachers

- teacher id **int** (primary key)
- teacher name **varchar** (not null)
- course id **int** (foreign key referencing courses(course id))