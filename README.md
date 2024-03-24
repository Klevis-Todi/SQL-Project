# SQL-Project


University of Michigan Library Database Overview
Introduction
The University of Michigan Library is renowned for its commitment to academic and research excellence, offering a vast array of resources and services to support student learning and scholarly endeavors. This readme provides an overview of the database structure and conceptual model designed to serve the information needs of faculty and students at the University of Michigan.

Information Requirements
The database is designed to cater to the diverse information needs of faculty and students, employing a primarily quantitative approach to information gathering. It encompasses a wide range of materials including books, online references, and services such as tutoring and computer lab access. Each information source is meticulously organized within the database to facilitate efficient access and retrieval.

Conceptual Model
The conceptual model outlines the structure of the database tables and their relationships within the University of Michigan Library. Key entities include 'Student,' 'Person,' 'Staff,' and 'Tutoring,' each characterized by primary and foreign keys. The model illustrates the interconnectedness of these entities, with 'Person' serving as the central entity linking 'Student' and 'Staff.' Additionally, it delineates the system of item rentals facilitated by both students and staff, along with the provision of services such as tutoring, study hall, and computer lab access.

The Person table encompasses both staff and students, recognizing that individuals may fulfill both roles within the university. Relationships between tables, such as Staff to Rentals and Student to Services, are established to track item transactions and service utilization effectively. Notably, the Services table distinguishes between different service types like Computer Lab, Tutoring, and Study Hall, acknowledging that students can only utilize one service at a time.

Conclusion
The University of Michigan Library database serves as a comprehensive repository of resources and services, catering to the diverse information needs of faculty and students. Its structured design facilitates efficient access to materials and support services, aligning with the university's core principles of humanity, diversity, engagement, and excellence. This readme provides a succinct overview of the database's structure and functionality, underscoring its importance in supporting scholarly development, advancement, and research within the University of Michigan community.
