# Team-1-MIST-4610-Project-Group-1

## Team Members:
1. Colten Lin cwl27381@uga.edu
2. Audrey Djunaidi ad04585@uga.edu
3. Max Trinh mlt22305@uga.edu
4. Claire Woehrman ctw49810@uga.edu
5. Nayan Magdum nm37036@uga.edu

## Problem Description:
The goal of this project is to build, design, and implement a relational database to model the key operations of Spotify's streaming ecosystem. The central entity in our model is the User entity, representing each spotify account holder. Each user may hold a subscription (Free, Student, or Premium), which is linked to billing records for payment tracking. Users can create multiple playlists, each containing songs across various genres and albums. These relationships are modeled to reflect how Spotify's users engage with artists and manage their music libraries. To simplify the database structure, we assume that each playlist is created by a single user, each song belongs to exactly one genre, and each album is associated with a single artist. These assumptions allow us to maintain referential integrity and reduce many-to-many relationship complexisty in the model. We are interested in accurately modeling these relationships, generating sample data, and populating the entities and their attributes with this sample data. Furthermore, we plan to perform SQL queries to gain important business insights. These queries will demonstrate how the relational database can support Spotify's data driven decisions regarding marketing and user retention.


## Data Model:

Our model is...

<img width="1033" height="739" alt="RD" src="https://github.com/user-attachments/assets/0a9ac47e-b413-4782-8d16-294b5b153622" />


