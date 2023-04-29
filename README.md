


 
  
  STUDENT
  - student_id (PK)
  - first_name
  - last_name
  - email
  - phone_number
  - department_id (FK)

  
  LECTURER   
  - lecturer_id (PK)  
  - first_name
  - last_name  
  - email
  - phone_number
  - department_id (FK)
  
  CLASS
  - class_id (PK)
  - class_name
  - lecturer_id (FK)
  - location_id (FK)

  LOCATION
  - location_id (PK)
  - building_name
  - room_number
  - department_id (PK)
  - department_name
