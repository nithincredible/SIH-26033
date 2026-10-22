# Smart India Hackathon Workshop
# Date: 22.10.26
## Reference Number: 26011645
## Name: Nithin S

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
Idea in one line : KisanConnect is a mobile and web app where farmers and FPOs (Farmer Producer Organisations) sell directly to consumers and bulk buyers, with built-in delivery support and AI-based price and demand predictions.

1. Detailed explanation<br>
1)Farmer/FPO side: The farmer lists crops (type, quantity, quality, expected price) in their own language, using voice or simple forms.<br>
2)Buyer side: Households, restaurants, hostels, and retailers browse fresh produce, compare prices, and order directly.<br>
3)Logistics: The app finds the nearest pickup point and delivery partner, and groups nearby orders into shared trips to cut cost.<br>
4)AI features:<br>
  &nbsp;&nbsp;-Demand forecasting tells farmers what will sell and how much to grow or send.<br>
  &nbsp;&nbsp;-Route optimization picks the shortest and cheapest delivery route.<br>
  &nbsp;&nbsp;-Fair price suggestion shows a recommended price based on mandi rates and demand.<br>
5)Payments: UPI payment goes straight to the farmer’s bank account.<br>

2. How it addresses the problem<br>
&emsp;&emsp;PROBLEM TODAY	&nbsp;&nbsp;&nbsp;&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; KISSANCONNECT'S RESPONSE<br>
Many middlemen take a share  &emsp;&nbsp;&nbsp;&nbsp;&nbsp;-&emsp;&emsp;&emsp;Direct farmer-to-buyer sale<br>
Farmers don’t know the right price&nbsp; -&nbsp; AI price suggestion plus live rates<br>
Crops spoil in transport	  &emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-&emsp;&emsp;&emsp;Optimized routes and faster delivery<br>
Consumers pay more	   &emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&emsp;-&emsp;&emsp;&emsp;Fewer layers, so lower prices<br>
Farmers get paid late   &emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp;&emsp;&emsp;&emsp;-&emsp;&emsp;&emsp;Instant UPI payment <br>

3. Innovation and uniqueness<br>
 1)Voice-based, regional-language interface for farmers with low literacy.<br>
 2)Demand forecasting before harvest, so farmers plan better.<br>
 3)Shared delivery (order pooling) so small farmers can ship affordably.<br>
 4)A transparent price breakdown showing the consumer how much goes to the farmer.<br>

## Technical Approach
1. Technologies
 Mobile app	- Flutter or React Native<br>
 Website - React.js<br>
 Backend -	Python or Node.js<br>
 Database -	PostgreSQL (main), Firebase (live updates)<br>
 AI/ML -	Python, scikit-learn, Prophet or LSTM (demand forecasting)<br>
 Route optimization	- Google Maps API or OpenStreetMap with a shortest-path algorithm (Dijkstra / A*)<br>
 Payments -	UPI <br>
 Language and voice	- Google Speech-to-Text and Translate APIs<br>
 Hosting -	AWS or Google Cloud<br>
 Data sources -	Agmarknet / data.gov.in (mandi prices), weather API<br>

2. Methodology (step-by-step process)
 1)Farmer registers and lists produce.
 2)Buyer searches, orders, and pays online.
 3)The AI engine predicts demand and suggests prices.
 4)The system assigns the nearest delivery partner and the best route.
 5)The produce is delivered, the buyer confirms, and the farmer gets paid.
 6)Ratings and feedback improve future recommendations.

3.Flowchart
 <img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/b2728ec9-1712-4aaf-8872-1e4f7dc7439a" />

4.Prototype sample<br>
<br>
  &nbsp;<img width="180" height="400" alt="image" src="https://github.com/user-attachments/assets/0bd6ec37-1f01-4dd6-9fac-043ca9d763ad" />
 <img width="180" height="400" alt="image" src="https://github.com/user-attachments/assets/78ffd118-2ff9-4bdd-8c83-6a97bdb6df41" />
 <img width="180" height="400" alt="image" src="https://github.com/user-attachments/assets/4453e4e2-fa60-463c-a337-abb0f55f0236" />
 <img width="180" height="400" alt="image" src="https://github.com/user-attachments/assets/89239188-d57b-4c80-ba82-2e09e52bf7f0" />
 <img width="180" height="400" alt="image" src="https://github.com/user-attachments/assets/c02d4c1b-274c-4870-bc8b-e1aed56348da" />

 
## Feasibility and Viability
1. Feasibility<br>
-All the technologies listed are open-source or low-cost, and mobile phones are already widespread in rural India.<br>
-The government’s UPI network and mandi price data are free and available.<br>
-We can start small with one district and one or two crops (vegetables, fruits), then scale up.<br>

2. Challenges and risks<br>
-Low digital literacy among farmers.<br>
-Poor internet connectivity in villages.<br>
-Trust issues with online selling and payments.<br>
-Delivery cost for small orders.<br>
-Quality differences in produce.<br>

## Impact and Benefits
1. Impact on the target audience<br>
-Farmers/FPOs: Higher income and quicker payment, and they can plan crops using demand data.<br>
-Consumers: Fresh produce at lower prices.v
-Bulk buyers: Reliable supply and transparent pricing.<br>
-Government: Better supply chain visibility and data for policy decisions.<br>
<br>
2. Benefits
-Social: Empowers small farmers and supports rural livelihoods.
-Economic: Reduces middlemen shares, Decrease transport charges, boosts farmer income, and lowers consumer prices.
-Environmental: Less food waste through faster delivery, and fewer fuel emissions through optimized routes.

## Research and References<br>
• Agmarknet (mandi price data):[Agmarknet.gov.in](agmarknet.gov.in)<br>
• Open Government Data Platform India:[data.gov.in](data.gov.in)<br>
• e-NAM (National Agriculture Market):[enam.gov.in](enam.gov.in)<br>
• FPO scheme details from the Ministry of Agriculture & Farmers Welfare<br>
• Google Maps Platform and OpenStreetMap documentation<br>
• News or research articles on middlemen margins in Indian agriculture<br>
• AI assistance : Claude
