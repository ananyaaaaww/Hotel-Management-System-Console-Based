# Hotel-Management-System-Console-Based
The effective management of a hotel requires efficient organization and seamless coordination of various operations. In today's digital age, Hotel Management Systems (HMS) play a crucial role in enhancing operational efficiency, improving guest experiences, and ensuring smooth day-to-day functioning. This report aims to present a comprehensive overview of a Hotel Management System that utilizes file structures as a fundamental component of its design.

The implementation of file structures within the HMS provides a structured and organized approach to storing and managing data related to hotel operations. File structures, such as sequential files, indexed files, or hierarchical files, offer efficient data access, storage, and retrieval mechanisms that cater specifically to the requirements of the hotel industry.

This report will explore how the utilization of file structures in the Hotel Management System enhances the overall management process. It will delve into the various aspects of the system where file structures are employed, such as guest information management, room allocation, reservation tracking, inventory control, and financial transactions.

By leveraging file structures, the Hotel Management System optimizes data storage and retrieval operations, ensuring rapid access to information when needed. The choice of appropriate file structures for different data entities within the system contributes to efficient search and retrieval algorithms, resulting in improved system performance and reduced response times.

# System Requirement Specification

# Hardware Requirements
• Processor- 1.9 gigahertz (GHz-Base Clock Speed) x86- or x64-bit 
• RAM- 8 GB or more 
• Hard-disk – 100 GB or more 
• Input device - Standard Keyboard and Mouse 
• Output device - VGA and High resolution Monitor

# Software Requirements
• Operating System- Windows 10 or above 
• Programming Language- C++
• Libraries- 
• IDE- Visual Studio Code, CodeBlocks 
 
 # System Architecture
 <img width="427" alt="image" src="https://github.com/ananyaaaaww/Hotel-Management-System-Console-Based/assets/134645478/50ffeae6-0b48-41a1-a6d1-d35bd039034f">
 
 # Defining the Model
The `Customer` class handles operations related to managing customer bookings. It includes the following member functions:
1. `readCustomer()`: Reads and displays all the hotel bookings from a file.
2. `writeCustomer()`: Allows the user to add new customer bookings and saves them to a file.
3. `searchCustomer()`: Searches for a customer booking based on the provided ID and displays the details if found.
4. `updateCustomer()`: Updates the number of days booked for a customer based on the provided ID.
5. `deleteRecordCustomer()`: Deletes a customer booking based on the provided ID.
   
The `Room` class handles operations related to managing hotel rooms. It includes the following member functions:
1. `writeRoom()`: Allows the user to add new rooms and saves their details to a file.
2. `readRoom()`: Reads and displays all the available rooms from a file.
3. `searchRoom()`: Searches for a room based on the provided room number and displays its details if found.
4. `updateRoom()`: Updates the price of a room based on the provided room number.
5. `deleteRoom()`: Deletes a room based on the provided room number.
   
The `manageHotel()` function acts as the main menu for the hotel management system, allowing the user to choose between managing customer bookings, managing hotel rooms, or exiting the program. The code uses file handling to read from and write to text files for storing customer bookings and room details.

# Screenshots

<img width="491" alt="image" src="https://github.com/ananyaaaaww/Hotel-Management-System-Console-Based/assets/134645478/9f102328-7121-4c96-a925-38b35fc554b5">

<img width="506" alt="image" src="https://github.com/ananyaaaaww/Hotel-Management-System-Console-Based/assets/134645478/5aceebb3-358f-4f20-80c0-c1d6d6df1641">

<img width="508" alt="image" src="https://github.com/ananyaaaaww/Hotel-Management-System-Console-Based/assets/134645478/83f443e0-eac2-47ca-86f1-2602699b3cc5">

<img width="497" alt="image" src="https://github.com/ananyaaaaww/Hotel-Management-System-Console-Based/assets/134645478/f5c5e047-cccc-4754-9a20-cd346109b1d5">



 


