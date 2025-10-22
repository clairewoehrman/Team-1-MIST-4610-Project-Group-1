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

Explanation of our Data Model:
Our data model is based on the structure of a music streaming platform that allows users to listen to songs, create playlists, and manage subscriptions. The goal of this design is to capture all the essential entities and their relationships in a system similar to Spotify or Apple Music.

The User entity represents individuals who use the platform. Each user has attributes such as their name, email, date of birth, and the type of subscription they hold. Because every user can only have one active subscription, there is a 

<img width="1033" height="739" alt="RD" src="https://github.com/user-attachments/assets/0a9ac47e-b413-4782-8d16-294b5b153622" />

## Data Dictionary:

![table_Album](https://github.com/user-attachments/assets/b760ba1f-42c8-4a0d-b936-602b1abac7e8)

![table_artistHasSong](https://github.com/user-attachments/assets/648a3aca-fffb-450b-bdb0-bd3e496cc820)

![table_artists](https://github.com/user-attachments/assets/ac081745-e793-4d88-979b-ceb276695ae7)

<img width="1316" height="801" alt="table_Billing" src="https://github.com/user-attachments/assets/5b02f1d3-bdbd-4fbd-8135-cb959fbf377b" />

![table_Genre](https://github.com/user-attachments/assets/f7f00b44-40f8-48ce-ad1c-f10f722b9e4c)

![table_label](https://github.com/user-attachments/assets/ba942752-946f-4539-8fd9-4c003d772816)

<img width="1318" height="449" alt="table_Playlist" src="https://github.com/user-attachments/assets/4bd91c3f-bcf4-4a98-8c1f-29fecef29dd6" />

<img width="1307" height="351" alt="table_PlaylistHasSong" src="https://github.com/user-attachments/assets/341f25a3-f49d-478c-b4d5-f39217a683ef" />

![table_Songs](https://github.com/user-attachments/assets/1cec75bb-8138-47fc-abc5-7f5d3a96bdb2)

<img width="1332" height="651" alt="table_Subscription" src="https://github.com/user-attachments/assets/64c48617-1bf1-4db1-8aa9-dd61a084aa4c" />

<img width="1314" height="473" alt="table_Users" src="https://github.com/user-attachments/assets/a9f35679-0260-40be-a371-d5356d1b1038" />


