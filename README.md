## Deliverables

- Make classes for an Optometrist and Dentist which inherit from a class Doctor
- Doctor must be initialized with these attributes: name, degree_institution, practice_name
  - the degree_institution and name cannot be changed after initialization
  - the practice_name can be changed
  - all doctors should have a method called bill_due which returns the string `pay your __ bill` where __ is replaced with the name of the type of doctor
  - has a class method that stores all doctors
- an Optometrist also has an optical_center attribute, make methods to `set_optical_center` and read the attribute
  - has a class method which returns only the optometrists from the list of doctors from the Doctor class
- make a module called Fearsome which has a method drill that returns a human scream
  - the drill method should be accessible to all instances of Dentist
- Dentist has a class method which returns only the dentists from the list of doctors from the Doctor class
