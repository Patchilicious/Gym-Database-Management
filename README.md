
Section 1 – Project Description- Domain selection and Business use
Description of database: 
The Gym and Fitness Center Management Database is designed to streamline the operations of a modern fitness facility. It manages membership, class bookings, trainer assignments, equipment maintenance, and invoicing, ensuring efficient data tracking and seamless service delivery.

1.2 Database Purpose
The main objective of this database system is to handle the automated management of all essential operations within fitness centers and gyms. Traditional fitness businesses run their operations through various fragmented software systems and manual recording methods that produce operational flaws, scheduling errors, and reduced visibility. The system resolves operational problems through its relational data structure, which houses member details, check-in logs, training schedules, instructor qualifications, and equipment maintenance information. The system enables users to create up-to-the-minute analytical reports, which assist with operational efficiency decision-making.
By implementing this database system, we obtain three fundamental benefits through data precision enhancement, along with minimizing administrative staffing requirements and improving member service. The system enables efficient member enrolment and program assignments while granting trainers systematic scheduling abilities and thorough equipment status monitoring to management. This database system finds applications in multiple fitness settings such as health clubs, fitness centers, personal training studios, and university gymnasiums. Any organization benefiting from managed client interactions, program bookings, and infrastructure maintenance will find value in implementing this system.

Section 2 – Business Rules 

Each Member must be associated unique Membership ID
Every CheckInLog entry must reference a valid MemberID that has an active Membership.
Each Staff member must have a unique Staff ID
Each Manager must have a unique Manager ID
One Manager can supervise up to five Staff Members
Every Personal Trainers must hold at least one valid Fitness Certification
Each Class must be led by at least one certified Trainer
A Trainer cannot teach more than two Classes per day.
Each Class cannot have more than five active Membership ID’s enrolled
A Class cannot book more than 15 different Equipment ID’s
Each piece of equipment must have a unique Equipment ID
 Each Equipment ID must have at least one related Service Log entry
 A Staff member must perform the Service Log for each Equipment
 A Manager must review each Service Log entry
 If a Service Log has not updated within 90 days, the Equipment must be marked as Out of Service
Out of Service equipment cannot be booked for any Class.
A Class can be taught by more than one Trainer
A Trainer can be assigned to multiple Classes throughout the week.
