🔹 1️⃣ Why Sets Are Used for Enrollment

In Problem 2 (Course Enrollment System), sets are used to store student IDs inside each course. Sets are ideal for enrollment because they automatically prevent duplicate entries. A student cannot be enrolled twice in the same course, and sets ensure uniqueness without requiring extra validation logic. Additionally, sets provide efficient membership testing and support operations like union and intersection, which are useful for finding unique students across courses or identifying students enrolled in multiple courses. Because enrollment data focuses on uniqueness rather than order, sets are a logical and efficient data structure choice.

🔹 2️⃣ Why Tuples Are Used for Fixed Scores

In Problem 1 (Student Performance Analytics System), tuples are used to store student scores. Tuples are immutable, meaning their values cannot be changed after creation. Since exam scores should not be accidentally modified during processing, immutability ensures data integrity and reliability. Additionally, each student has exactly three subject scores, and tuples are well-suited for representing fixed-size collections of data. Using tuples communicates that the number of subjects is constant and that the data should remain stable throughout the system.

🔹 3️⃣ Why Dictionaries Are Suitable for Structured Mapping

Dictionaries are used in both problems because they allow structured key-value mapping. In Problem 1, each student is represented as a dictionary containing keys such as id, name, and scores. This structure allows clear labeling of data instead of relying on index positions, making the system more readable and maintainable. In Problem 2, dictionaries map course names to instructor information and enrolled students, which naturally represents hierarchical relationships. Dictionaries are ideal when data must be accessed using meaningful identifiers rather than numeric indexes, improving clarity, scalability, and flexibility of the system.

🔹 4️⃣ Why Classes Improve System Organization

Classes significantly improve system organization by grouping related data and behavior into a single structured unit. In both problems, the analytics classes (StudentAnalytics and CourseAnalytics) encapsulate attributes and methods that operate on the same dataset. This improves modularity, reusability, and maintainability. Instead of having scattered functions, the class organizes logic in a logical and scalable way. Classes also support abstraction, meaning the internal implementation details are hidden while providing clean method interfaces such as generate_report() or get_top_student(). This makes the system easier to extend, debug, and manage in larger real-world applications.

🎯 Conclusion

The choice of data structures and object-oriented design principles directly supports correctness, efficiency, readability, and scalability. Sets ensure uniqueness in enrollment, tuples protect fixed academic scores, dictionaries provide structured mapping for complex relationships, and classes organize system logic into reusable and maintainable components. Together, these design decisions create a robust and well-structured academic analytics system.