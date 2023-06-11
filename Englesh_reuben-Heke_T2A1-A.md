# Englesh_Reuben-Heke_T2A1-A

`# T2A1 - A - Workbook

## Q1. Describe the arcitecture of a typical Flask Application

The architecture of a Flask application adheres to an easy-to-understand design pattern, enabling the development of reliable and scalable web applications. At its core, Flask is a Python-based, nimble, and adaptable web framework that makes use of the Werkzeug toolkit and the Jinja templating engine.

Incoming requests, data processing, and response generation are all handled by a variety of components working together in a typical Flask application design. The Flask object, which serves as the main hub for directing requests to the relevant views or endpoints, is the foundation of the application. Views are Python functions or methods that specify how particular routes or URLs should be handled.

Although it is frequently referred to as Model-View-Template (MVT) in the Flask context, Flask adheres to the Model-View-Controller (MVC) architectural pattern. While the views manage the request/response cycle and communicate with the models, the models represent the data structures and business logic. By using Jinja-powered templates, it is possible to create dynamic and reusable HTML pages by separating the application logic from the presentation layer.

Additionally, Flask permits the usage of a number of libraries and extensions to increase the functionality of the application. Additional functions like database integration, form handling, authentication, and others are offered via these extensions.

The Flask application design generally encourages simplicity, flexibility, and modularity, making it the perfect option for creating small to medium-sized online apps that place a priority on ease of development and maintenance.

---

## Q2. Identify a Database Management System commonly used in web applicatiom (including Flask) and discuss the pros & cons of this database.

MySQL is a popular Database Management System (DBMS) for online applications. Due to its popularity, scalability, and wide support among web developers, MySQL is an open-source relational DBMS that has grown significantly in popularity.

Pros:

- Utilisation: MySQL is noted for its simplicity, making it simple for developers to install and utilise. It is usable by both novice and seasoned developers because to its simple syntax and user-friendly UI.
- Scalability: MySQL is capable of handling massive data volumes and high traffic loads with ease. As the programme expands, it can be easily scaled and performs better because to capabilities like replication, sharding, and clustering.
- Compatibility: A wide range of programming languages and frameworks support MySQL. It is simple to combine with well-liked web technologies like PHP, Python, and Java because to its extensive APIs and drivers.
- Community and assistance: MySQL has a sizable and vibrant user base, which translates to a wealth of resources, tutorials, and forums for assistance and troubleshooting. For developers looking for advice or answers to frequent problems, this can be useful.

Cons:

- Limited Functionality: MySQL has a comparatively small number of advanced features as compared to certain other DBMS alternatives. It might not be appropriate for cases requiring specialised capabilities, like full-text search or geospatial data processing, or for sophisticated data structures.
- Due to its dependency on locking mechanisms, MySQL may have performance problems in high-concurrency settings. This might result in decreased reaction times.
- Lack of Native JSON Support: MySQL has recently added JSON support, although it lacks some sophisticated JSON querying features offered by NoSQL databases. It might be more difficult and flexible tradeoffs to handle JSON data.
- Complexity of replication: Although MySQL has options for data redundancy and high availability, setting up and managing replication settings can be challenging, especially for those with little experience with database administration.
- Overall, because of its simplicity of use, scalability, and community support, MySQL is a widely used DBMS for online applications. For highly specialised use cases or situations with strict performance requirements, it might not be the ideal option. Before selecting a DBMS, developers should assess the demands of their individual applications.

---

## Q3. Discuss the implementation of Agile project management methodology

In many industries, the way projects are carried out has changed as a result of the adoption of the Agile project management technique. Agile technique places a strong emphasis on adaptation, collaboration, and continual development. It is distinguished by its iterative and incremental approach. Agile focuses on delivering value early and regularly, in contrast to traditional project management techniques, allowing teams to react quickly to changes and client input.

Several crucial elements are involved in the execution of Agile. Projects are first broken into smaller, more manageable units known as sprints. Planning, carrying out, and assessing the work are done during each sprint, which lasts between two and four weeks. Teams are able to prioritise activities, respond to changing requirements, and make appropriate adjustments thanks to this iterative approach.

Second, Agile encourages close communication between stakeholders and team members. Daily stand-up meetings promote open dialogue, information exchange, and problem solving. Through this interaction, the team becomes more productive, develops a sense of shared ownership, and makes sure that everyone is working towards the same objectives.

Third, Agile places a focus on adaptability and flexibility. Agile teams accept change rather than sticking to a set plan and continuously improve their strategy in light of feedback and new information. Regular retrospectives provide reflection and process improvement, assisting teams in determining their areas of strength and need for improvement.

Last but not least, Agile promotes a customer-centric strategy. Teams may gain important insights, test hypotheses, and make sure the finished product satisfies customer and end-user needs by incorporating them in all stages of the development process.

Agile must be implemented with organisational support and in a way that promotes collaboration, trust, and empowerment. Kanban boards, burndown charts, and user story mapping are a some of the tools and methods that are required to support Agile practises, in addition to specialised and cross-functional teams.

Agile project management methodology, in general, offers a fluid and adaptive strategy that enables teams to efficiently deliver high-quality solutions while successfully adapting to changing requirements and client expectations.

---

## Q4. Provide an overview and description of a standard source control workflow

The major steps in a typical source control workflow are as follows:

- Establish a central repository, like Git or SVN, to house the source code.
- Using branches, you can individually work on new features or bug fixes while keeping the main branch stable.
- Development: Each developer works on a separate branch, making local modifications and committing them.
- Pull requests: Developers make a pull request to submit their modifications for review. The code is examined, and suggestions are given.
- Code review and feedback: Reviewers look over the modifications, offer input, make suggestions for enhancements, and guarantee code quality.
- Integration: After being accepted, the modifications are integrated into the main branch to keep the codebase current.
- Continuous testing and integration: Automated tests are conducted to detect any problems or regressions brought on by the modifications.
- Release or further testing of the modified code requires deployment to staging or production environments.
- Resolution of conflicts: Conflicts may occur if the same code is modified by various developers. To maintain the integrity of the code, these disputes must be resolved.
- Version tagging: Mark major milestones or stable points in the codebase by marking particular versions or releases.

This workflow offers a systematic method for managing and integrating code changes, which fosters collaboration, code quality, and stability. Parallel development is made possible, code reviews are made easier, and changes are extensively tested before being deployed thanks to it.

---

## Q5. Provide an overview and description of a standard software testing process.

The following steps are usually included in a normal software testing process:

- Test planning: Specify the testing's goals, parameters, and methodology. Determine the resources, deadlines, and test requirements.
- Test Design: Based on requirements and design standards, develop test cases and test scenarios. Explain what each test's predicted outcomes should be.
- Set up the test environment by providing the required hardware, software, and test data. Set up the frameworks and tools for testing.
- Execute the test cases in accordance with the pre-established test scenarios. Keep track of the actual findings and contrast them with what was anticipated.
- Reporting Defects: Enter any errors or shortcomings as defects in a defect tracking system. Give thorough details, including instructions for replication and supporting data.
- Prioritise defects and allocate them to the development team as part of defect management. Follow the situation and the elimination of each flaw.
- Analyse test coverage to determine how thoroughly the software has been tested. Identify any areas or gaps that need more testing.
- Test Reporting: Write up test summaries that detail the testing procedures, outcomes, and metrics. Describe your observations and suggestions for improvement.
- Regression testing: Run a subset of tests to make sure that recent modifications or fixes didn't result in the introduction of fresh flaws or affect working functionality.
- Test closure: Evaluate the testing's completion and exit criteria. Obtain the endorsement of the stakeholders and record your learnings for future projects.

Organisations can methodically find flaws, guarantee software quality, and boost overall product reliability by adhering to a standardised testing methodology.

---

## Q6. Discuss and analyse requirements related to information system security and how they relate to the project

Any project that involves the creation or deployment of an information system must meet certain information system security criteria. These standards guarantee the security of sensitive data, guard against unauthorised access, and uphold the integrity and availability of the system. The following ways they are connected to the project:

- Risk Analysis: The project needs to perform a thorough risk analysis to find any potential security threats and weaknesses. This assessment aids in identifying the precise security measures that must be put in place to successfully minimise these threats.

- Clear security policies and procedures that regulate the use, processing, and protection of sensitive information should be established as part of the project. To ensure uniform security practises, these rules specify the criteria and requirements that staff members, stakeholders, and system users must adhere to.

- Design of Systems and Development: Both the design and development phases of the system must take security concerns into account. This entails using secure coding techniques, configuring system components securely, and adhering to best practises and standards set by the industry.

- Testing and Validation: Thorough testing should be used to validate security needs. To find and fix any system flaws or vulnerabilities, this involves carrying out penetration testing, vulnerability scanning, and security audits.

- Regulations pertaining to data privacy are just one example of the compliance and regulatory requirements that the project must take into account. To prevent legal problems and penalties, the system should be created and put into use in accordance with these specifications.

The project can guarantee the confidentiality, integrity, and availability of sensitive data and reduce the risk of security breaches or unauthorised access to the system by addressing information system security needs throughout the project lifecycle.

---

## Q7. Discuss common methods of protecting information and data and how you would apply them to the project

Typical techniques for securing data and information include:

- Encryption: To avoid unauthorised access, use encryption techniques while storing and transmitting sensitive data.
- Access Control: To limit access to data based on user roles and privileges, implement robust authentication systems and role-based access controls.
- Network segmentation and firewalls: Use network segmentation to control access between various systems and components and to monitor and manage network traffic.
- Regular Backups: Make sure your data is regularly backed up so that it is always available and recoverable in the event of a system crash or data loss.
- Patching for security: To reduce vulnerabilities, keep the system updated with the newest security patches and updates.
- Use intrusion detection and prevention systems (IDPS) to identify and stop unauthorised access and malicious activity.
- Conduct training sessions to inform project team members about security best practises, such as password management and recognising social engineering attacks.

These techniques can be used in the project by including safe coding practises, putting encryption protocols into place, setting up firewalls, performing routine vulnerability assessments, enforcing access control policies, and training the project team on security awareness. Furthermore, creating an incident response strategy and carrying out regular security audits helps improve the security of information and data.

---

## Q8. Research what your legal obligations are in relation to handling user data and how they can be met for the project

When it comes to the privacy and data of users we do have a legal responsibility to protect the privacy of those who use our products. Each and every person is entitled to privacy and not have their data searched across the world to others, the privacy act 1988 regulates the way individuals personal information is held which is what companies have to abide by whenever it comes to any sort of information collecting.

It is our right throughout the project to ensure that The individual user knows how their personal information is being used. The individual is allowed to ask for accesss to their personal infromation, so they know why it is being collected, how it will be used and to whom it will be revealed. As this is a legal obligation throughout the project it is once again a LEGAL obligation to adhere to the privacy act.

---

## Q9. Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

Data is arranged and structured using the relational database model in tables, which are made up of rows and columns. The columns of each table denote attributes or properties of the relation or item they represent. A relational database has the following structure:

- Tables: The cornerstones of a relational database are tables. Each row in them represents a record or instance of the entity, and each column in them represents a particular attribute of that object. They are made up of rows and columns.

- Rows: Rows, sometimes referred to as tuples or records, house the actual values of the data. The values for the properties specified by the columns are contained in each row, which represents a distinct entry in the table.

- Columns: Also known as fields or characteristics, columns provide the type of information that can be kept in them. Name, age, or address are just a few examples of the specific traits or possessions that each column indicates for the entity.

- Each row in a table is uniquely identified by its primary key. The uniqueness of each record is ensured by a column or group of columns.

- Relationships: Keys are used to create relationships between tables. A foreign key establishes a connection between two tables by referencing the primary key of the other table in a column in one of the tables.

- The relational model places a strong emphasis on normalisation procedures to reduce data duplication and uphold data integrity. Normalisation entails creating linkages between the smaller, more manageable tables that result from splitting up the larger tables.

A versatile and structured method of storing and organising data is offered by the relational database paradigm. Through standardised SQL (Structured Query Language) operations, it enables effective data retrieval, manipulation, and querying.

---

## Q10. Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database

The relational database model includes a number of integrity features to guarantee the consistency, accuracy, and dependability of data. In a relational database, the following types of data integrity can be enforced:
Object integrity: Each row or entry in a table is guaranteed to be uniquely recognised by entity integrity. Primary keys, which must have distinct and non-null values, are used to do this. Duplicate or empty values in the key column are prevented by primary key constraints.

Referential Integrity: Referential integrity makes ensuring that linkages between tables are always consistent. Foreign keys, which create connections across tables, are used to enforce it. To avoid orphaned or invalid references, referential integrity constraints make sure that foreign key values in one table correspond to primary key values in another table.

Domain Integrity: The permitted range of values for each column in a table is specified and enforced by domain integrity. The use of data type definitions and restrictions is used to achieve it. For instance, an integer column should only permit integer values that fall inside a given range.

Additional limitations might be specified to impose particular guidelines or requirements on data. Examples include uniqueness constraints, which ensure that each value in a column is unique, check constraints, which impose particular requirements, and not-null constraints, which prevent null values from appearing in columns.

Constraints, triggers, and validation rules are frequently used in databases to enforce these integrity requirements. Database management systems offer tools for defining and enforcing these integrity standards, guaranteeing the consistency and reliability of the data.

---

## Q11. Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.

Data manipulation options provided by the relational database paradigm include the capacity to add, remove, modify, and retrieve data. The following are the primary components of data manipulation in a relational database:

- Insertion: To add data to a relational database, perform the INSERT operation. The table and the values that should be entered into each column must be given in order to do this. The new data is inserted as a new row to the table.

- Data deletion: The DELETE operation is used to remove data from a relational database. It enables the elimination of one or more rows from a table in accordance with predetermined criteria. The table's erased data is no longer present.

- Update: A relational database's UPDATE procedure enables the modification of already-existing data. The table, columns that need to be modified, and the new values must all be specified. Depending on the parameters, UPDATE can be applied to one or more rows.

- Data retrieval is accomplished in a relational database by using the SELECT operation. Users can select the columns, tables, and criteria they want to utilise to extract particular data from the database. To get the desired dataset, SELECT supports a variety of filtering, sorting, and aggregation options.

Structured Query Language (SQL) is commonly used to manipulate data in relational databases. These procedures and database interactions are carried out using SQL statements. The adaptability of the relational database model and relational operations enable accurate and efficient data processing to satisfy a variety of application requirements.

## Q12. Conduct research into a web application. Youtube

### A) List and describe the software used by the application (Youtube)

To run its video-sharing platform, YouTube makes use of a variety of programmes. Following are some essential software elements:

- Web server software: To handle incoming requests from users' browsers and deliver webpages and content, YouTube uses web server software such as Apache and Nginx.

- YouTube uses its Google Global Cache (GGC) architecture, which serves as a content delivery network (CDN), to efficiently distribute and transport video content across geographically dispersed servers all over the world.

- Software for video encoding and transcoding: In order to provide optimal streaming across devices and network circumstances, YouTube uses its own proprietary software for video encoding and transcoding, turning uploaded videos into different formats and resolutions.

- Video Streaming Technology: To ensure smooth viewing, YouTube uses adaptive streaming methods like Dynamic Adaptive Streaming over HTTP (DASH) to dynamically alter video quality based on users' internet connections and device capabilities.

- Database Management System (DBMS): To store and manage data related to user profiles, video information, comments, and engagement metrics, YouTube probably uses a powerful DBMS, such as MySQL or Google Cloud Spanner.

- Utilising machine learning algorithms and recommendation systems, YouTube tailors video recommendations for users based on their viewing habits, preferences, and user engagement patterns.

Together, these software elements support the YouTube platform's smooth video streaming, content management, and customised user experiences.

### B) Describe the hardware used to host Youtube

The hosting system used by YouTube is made up of a sizable global network of servers and data centres. It is supported by high-performance hardware, such as potent servers with several cores of processing power, lots of RAM, and big storage systems. High-speed networks connect these servers, allowing them to handle the enormous volume of data and user requests. In order to provide quicker video streaming and lower latency, YouTube also uses specialised hardware for content delivery, such as edge servers and content caching servers, which are placed strategically closer to viewers.

### C) Describe the interaction of technologies within Youtube

Processes like content uploading and processing, content delivery via a Content Delivery Network (CDN), user interface and video playback using web development technologies, personalised video recommendations using machine learning algorithms, and analytics for tracking user engagement and performance metrics are just a few of the ways that technologies interact in YouTube. Together, these technologies help the YouTube platform provide smooth video streaming, content distribution, individualised recommendations, and data analysis.

### D) Describe the way data is structured within Youtube

YouTube's data is organised in a hierarchical fashion. The main organisational elements are user profiles, channels, playlists, and videos. Each movie has meta data, including a title, a description, a duration, and a number of views. Videos and playlists are organised on channels. User profiles include personal data, subscriptions, and viewing history. Likes, comments, and shares are interactions that are connected to the corresponding videos. The platform's enormous volume of content and user-related data can be efficiently organised, retrieved from, and analysed thanks to the structured data.

### E) Identify entities which must be tracked by Youtube

To enable the functionality of the platform, numerous entities must be tracked in the database management system (DBMS) of YouTube. A few of these are:

- Users: Details on users, such as usernames, email addresses, passwords, subscriptions, and viewing patterns.
- Videos: Information on videos, including titles, descriptions, views, comments, likes, dislikes, and the dates and lengths of their upload.
- Channels: Information regarding channels, such as names, brief descriptions, subscribers, and related videos.
- Playlists: Details regarding playlists, such as playlist titles, descriptions, and the order in which the videos in each playlist are presented.
- Comments: User feedback left on videos, complete with timestamps, user data, and comment text.
  Data regarding users' channel subscriptions, keeping track of the connections between people and the channels they follow.
- Engagement Metrics: Information about user interactions, such as likes, dislikes, shares, and views, which might reveal information about user preferences and the popularity of particular videos.

These organisations play a key role in the platform's management of user profiles, video content, connections between users and channels, and user interactions. Within YouTube's DBMS, they serve as the cornerstone for data storage and retrieval.

### F) Identify the relationships and associations between the entities you have identified

In YouTube's database, there are various relationships and associations between the identified entities. Here are some key relationships:

#### Users and Videos:

- Users can upload multiple videos.
- Users can like, dislike, comment on, and share videos.
- Users can subscribe to channels and receive updates on new videos.

#### Users and Channels:

- Users can create and manage channels.
- Users can subscribe to channels to receive notifications and updates.
- Channels can have multiple subscribers.

#### Videos and Channels:

- Videos are associated with a specific channel.
- Channels can have multiple videos.
- Videos can be organized into playlists within a channel.

#### Videos and Playlists:

- Videos can be added to multiple playlists.
- Playlists can contain multiple videos in a specific order.

#### Comments and Videos/Channels:

- Users can leave comments on videos and channels.
- Comments are associated with a specific video or channel.

#### Subscriptions:

- Users can subscribe to channels, establishing a relationship between the user and the channel.
- Subscriptions allow users to receive updates and notifications about new videos from subscribed channels.

These relationships and associations form the foundation for data connectivity and provide essential information for user interactions, content organization, and personalization within the YouTube platform.

### G)Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)

![ERD Diagram](/Englesh_Reuben-Heke_T2A1-A/ERD.PNG)

The relationships between the tables/entities in the previous questions can be defined as follows:

#### Users and Videos:

- One user can upload multiple videos (One-to-Many relationship).
- One video is associated with one user who uploaded it (One-to-One relationship).

#### Users and Channels:

- One user can create and manage multiple channels (One-to-Many relationship).
- One channel is associated with one user who created it (One-to-One relationship).

#### Videos and Channels:

- One channel can have multiple videos (One-to-Many relationship).
- One video is associated with one channel (One-to-One relationship).

#### Videos and Playlists:

- One video can be added to multiple playlists (Many-to-Many relationship).
- One playlist can contain multiple videos (Many-to-Many relationship).

#### Comments and Videos/Channels:

- One video/channel can have multiple comments (One-to-Many relationship).
- One comment is associated with one video/channel (One-to-One relationship).

#### User_Subscriptions:

- One user can subscribe to multiple channels (Many-to-Many relationship).
- One channel can have multiple subscribers (Many-to-Many relationship).

These relationships define how the entities are connected and interact with each other in the database. They help maintain data integrity and enable efficient retrieval and manipulation of information within the YouTube platform.