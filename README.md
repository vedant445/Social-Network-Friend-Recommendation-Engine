📌 Overview

SocialGraphX is a Streamlit-based social networking simulation that implements advanced data structures like Graph (Adjacency List) and Union-Find (Disjoint Set Union) to power:

Friend recommendations

Friend request management

Community detection

Social graph simulation

This project demonstrates practical implementation of non-linear data structures in a real-world system design scenario.

🚀 Features
👤 Profile Creation

Custom user profile setup

Interests, profession, skills, city, etc.

Automatically generates 100+ simulated users

🤝 Friend Recommendation Engine

Uses Friends-of-Friends logic

Graph traversal-based suggestions

Avoids duplicate and existing friends

📥 Friend Request System

Send multiple friend requests

Accept / Reject incoming requests

Track request status (Pending / Accepted / Rejected)

👥 Community Detection

Detects connected components in the social graph

Implemented using Union-Find (Disjoint Set Union)

Displays friend clusters (communities)

📊 Request Analytics

Separate tables for:

Sent Requests

Received Requests

Status Metrics:

Accepted

Pending

Rejected

🧠 Data Structures Used
Data Structure	Purpose
Graph (Adjacency List)	Store friendships
Set	Avoid duplicate connections
HashMap (Dictionary)	Fast user lookup
Union-Find (DSU)	Community detection
Friends-of-Friends Traversal	Recommendation logic


🏗️ Project Structure
SocialGraphX/
│
├── app.py                  # Streamlit frontend
├── social_network.py       # Core logic & data structures
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
└── .gitignore              # Ignore venv & cache files
