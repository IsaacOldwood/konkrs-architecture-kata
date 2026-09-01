# Konkrs

## Overview
Konkrs is a Software-as-a-Service (SaaS) platform for organising and managing conker tournaments in local parks and community events. The platform enables organisers to create tournaments, manage participants, generate brackets, assign referees, and record match results, while players can register for events and view live standings. The service should be accessible through a website and mobile devices.

## Users
Admins, Referees, Players  
Extra: Anonymous/spectator

## Core System Requirements
Allow administrators to create and manage conker tournaments  
Allow administrators to pay for their tournament licence through an online payment system  
Allow administrators to configure tournament details, including player limits, date, time, and location  
Allow administrators to manually adjust tournament brackets where required  
Allow administrators to assign referees to matches  
Allow administrators to “seed” players within a tournament prior to bracket generation  
Allow administrators to view tournament history and results  
  
Allow referees to submit and update match results  
  
Allow players to register for tournaments and manage their registrations  
Allow players and spectators to view tournament brackets and live standings  
Allow players to view a list of upcoming tournaments and register for participation  
  
Allow the system to generate tournament brackets automatically  
Allow the system to maintain and display a live leaderboard throughout a tournament  
Allow the system to support multiple concurrent tournaments  
Selected tournament, player, and marketplace data should be routinely exported to a Data Warehouse for reporting and analytics purposes

## AI Requirements
We have purchased a licence for the latest frontier AI model Conker Classifier called CC-birch, this is an upgraded version of the original CC-alder. Soon to be upgraded again to CC-chestnut.  

Allow users to upload images of conkers for classification and rating  
Allow the system to estimate conker characteristics and assign a class rating using AI services  
Allow classification to be used for tournament “seeding”

## Auction house Requirements
Allow authorised users to create, buy, sell, and auction conkers through an integrated marketplace  
Allow users to complete marketplace transactions through an online payment system  
The system will take a fee for each Conker bought/sold

## Additional Context
Launch is September 1st 2027, just in time for Conker season  
Mobile app is for iOS and Android  
Tournaments are single elimination  
Authentication should have email and SSO options  
Users data should be stored in compliance with GDPR 

Note: The Product Owners may have additional requirements not listed here.
