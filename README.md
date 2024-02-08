Project Description
This project investigates traffic flow dynamics in Bangalore using anonymized and aggregated travel time data from Uber Movement. We focus on weekday analysis at four distinct time slots: 00:00, 09:00, 18:00, and 21:00. By combining temporal (travel times) and spatial (city structure) information, we aim to:

Understand how traffic behavior changes based on time of day and city topology.
Identify and characterize travel communities within the city.
Uncover potential traffic bottlenecks and their relationship to city structure.
This work builds upon a previous study at Stanford, adapting it to explore the unique mobility patterns of Bangalore. We leverage centrality measures and community detection algorithms to model traffic flow and draw insights into different aspects of urban mobility.

Methodology
Our analysis unfolds in two phases:

1. Network Construction:

Temporal network: Represents mean travel times between zones at each time slot.
Spatial network: Represents the static structural layout of Bangalore city.
2. Traffic Flow Analysis:

Node centrality: Calculate various centrality measures (degree, betweenness, closeness, PageRank, HITS) to identify important zones based on:
Popularity (origin/destination): Node degree
Potential bottlenecks: Betweenness
Accessibility: Closeness
High-demand/influential zones: PageRank, HITS
Community detection: Identify groups of zones exhibiting similar travel patterns using Louvain and k-means algorithms.
Key Findings
Centrality measures effectively capture dynamic changes in traffic patterns across different time slots.
Betweenness, PageRank, and closeness centrality highlight areas connecting city's dense regions and identify central zones based on accessibility and importance.
Community detection reveals core travel patterns around city center during the day, with peripheral zones exhibiting more dynamic behavior.
Louvain algorithm provided the most consistent community structure across temporal networks.
Future Work
Explore additional data sources (weather, demographics) and machine learning techniques for deeper insights.
Extend analysis to other cities with different layouts and mobility patterns.
Investigate potential applications of findings in city planning and traffic management.
