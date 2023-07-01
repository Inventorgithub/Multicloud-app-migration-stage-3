# Luxxy COVID Testing System

This repository contains the code for the Luxxy COVID Testing System. The Luxxy COVID Testing System is a software application designed to manage COVID-19 testing records.

## Getting Started

To use the Luxxy COVID Testing System, follow these steps:

2. Set up the database:

   ```sql
   -- Execute the following SQL statements to insert sample records into the `records` table
   INSERT INTO `records` VALUES (39,'Kay Crawford','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-kaycr.pdf');
   INSERT INTO `records` VALUES (40,'Ann Sharp','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-annsh.pdf');
   INSERT INTO `records` VALUES (41,'Maggie Simon','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-maggie.pdf');
   INSERT INTO `records` VALUES (42,'Stacy Bowers','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-stacy.pdf');
   INSERT INTO `records` VALUES (43,'Nicholas King','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-nichol.pdf');
   INSERT INTO `records` VALUES (44,'Victoria Paul','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-victor.pdf');
   INSERT INTO `records` VALUES (45,'Susan Leonard','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-susan.pdf');
   INSERT INTO `records` VALUES (46,'Amanda Colema','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-amanda.pdf');
   INSERT INTO `records` VALUES (47,'Billie Baldwi','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-billie.pdf');
   INSERT INTO `records` VALUES (48,'Lillie Herrer','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-lillie.pdf');
   INSERT INTO `records` VALUES (49,'Brandi Mathis','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-brandi.pdf');
   INSERT INTO `records` VALUES (50,'Melvin Massey','USA','Antigen','Negative','s029s02-as0202o9s-s29312-as-melvin.pdf');
   /*!40000 ALTER TABLE `records` ENABLE KEYS */;
   UNLOCK TABLES;
   ```

3. Synchronise PDF files with your AWS S3 Bucket 
#Sync PDF Files with your AWS S3 used for COVID-19 Testing Status System. 

4. Run the application

## File Structure

The file structure of this project is as follows:

- `.DS_Store`: macOS system file (can be ignored)
- `s029s02-as0202o9s-s29312-as-amanda.pdf`: Sample record file
- `s029s02-as0202o9s-s29312-as-annsh.pdf`: Sample record file
- `s029s02-as0202o9s-s293
