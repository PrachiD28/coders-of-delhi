🧩Overview:  

    CodeBook Social Network Analytics Engine is a pure Python data science project that analyzes social media user interactions, friendships, and page interests using JSON data.

    This project simulates a miniature social networking platform where users can:

    connect with friends,
    like pages,
    receive friend recommendations,
    and get personalized page suggestions.

🧩Features:  

    ✨User Data Analysis  
        Load JSON-based user data  
        Display user profiles and friend   connections  
        Analyze social relationships  
    ✨Data Cleaning  
        Remove users with missing names  
        Remove duplicate friend IDs  
        Handle duplicate pages  
        Group duplicate page names under the same ID  
        Friend Recommendation System

🧩Suggests:  

    ✨People You May Know  
        Recommendation logic is based on:
        mutual friends
        friend-of-friend analysis
        Page Recommendation System

    ✨Pages You Might Like
        Recommendation logic is based on:
        common interests
        shared liked pages
        collaborative filtering concepts
        Social Network Insights
        Most connected user
        Most liked pages
        User interaction analysis

    ✨Technologies Used
        Python
        JSON
        Dictionaries
        Sets
        Lists
        Functions
        File Handling

🧩Core Concepts Used: 

    ✨Graph-Based Social Network Analysis  
        Users and friendships are treated as a social graph.

🧩Friend Recommendation Logic 

    The system:  
    1.Finds direct friends of a user  
    2.Checks friends of those friends  
    3.Excludes:  
        the current user  
        already connected friends  
        Recommends users with the highest  
    4.mutual connections  

🧩Page Recommendation Logic  

    The system:  
    1.Finds users with common liked pages  
    2.Identifies additional pages liked by similar users  
    3.Suggests new pages based on shared interests  
    
🧩How to Run the Project

    ✨Step 1  
       Clone the repository:
       git clone <https://github.comPrachiD28/coders-of-delhi.git>
    ✨Step 2
        Navigate to the project folder
        cd coders_of_delhi
    ✨Step 3
        Run the Python(.ipynb) file

🧩Future Improvements  

    Possible future enhancements:  
    - SQL database integration
    - interactive dashboard
    - visualization graphs
    - Flask web application
    - advanced recommendation algorithms
    - user activity tracking
    - search functionality
    - admin analytics panel
