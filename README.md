# Smart India Hackathon Workshop
# Date: 24th November, 2026
## Reference Number: 26016995
## Name: M Vaanavil

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

HarvestBridge is a demand-driven digital marketplace designed to connect farmers and Farmer Producer Organisations (FPOs) directly with individual consumers, retailers, restaurants and other bulk buyers. Farmers can create produce listings with crop name, available quantity, expected price, harvest window, quality grade and pickup location. Buyers can browse listings or post requirements specifying crop, quantity, delivery location and required date. The platform matches buyer requirements with available produce and supports aggregation when several small farmers collectively fulfil a larger order.

Its central feature, the Smart Harvest Exchange, allows a bulk requirement to be fulfilled by combining compatible lots from multiple nearby farmers or FPOs. An AI-assisted demand intelligence module estimates upcoming demand by crop and location using historical orders, seasonal patterns, local market activity and, where reliable data is available, weather signals. The system compares estimated demand and confirmed orders with listed supply, then provides farmers and FPOs with demand alerts and indicative quantity recommendations. A logistics module groups pickups and deliveries, considers vehicle capacity and delivery windows, and recommends an efficient route. Each order has a transparent breakdown of produce price, logistics cost and platform charges. A batch-level QR code can provide origin, harvest date and handling information.

<b>How it addresses the problem:<b>

Direct market access: reduces dependence on multiple intermediaries by enabling farmers/FPOs to reach consumers and bulk buyers through one marketplace.
Demand visibility: brings buyer requirements and demand estimates together so farmers and FPOs can make better-informed selling and supply decisions.
Small-lot aggregation: combines produce from multiple farmers to help meet larger orders that an individual smallholder may not be able to fulfil alone.
Logistics coordination: consolidates nearby pickups and deliveries to improve vehicle utilization and reduce avoidable travel.
Price transparency and traceability: shows the price and cost components and records batch origin and harvest information.

<b>Innovation and uniqueness of the solution:<b>

Smart Harvest Exchange: converts one bulk-buyer requirement into a coordinated sourcing plan across multiple farmers/FPOs.
Demand-confidence labels: clearly distinguishes confirmed buyer orders from AI-estimated demand, reducing the risk that farmers mistake a forecast for a guaranteed sale.
Demand-to-logistics connection: uses the same order and supply information for matching, aggregation and route planning rather than treating marketplace and transportation as separate activities.
Farmer-friendly access: supports a simple mobile-first interface and can be extended with regional-language and voice-based interactions.
Batch-level transparency: QR-enabled produce records can show source, harvest date and order journey.

## Technical Approach
<img width="672" height="310" alt="image" src="https://github.com/user-attachments/assets/8cc86991-1dcb-4b61-a6a3-c041442b5e3d" />

2. Methodology and process for implementation:
   <img width="1658" height="1976" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/43e4b98b-ec13-4e69-ab1f-2cbe42958718" />


## Feasibility and Viability
HarvestBridge is feasible as a phased web-based solution because its core functions can be developed using widely available open-source technologies. A minimum viable product can begin with one crop, one geographic cluster and a limited set of farmer/FPO and buyer accounts. The first release can support listings, buyer requirements, basic matching, supply-gap calculations and a simple route sequence. More advanced demand forecasting and vehicle-routing optimization can be introduced as transaction and operational data becomes available. The model is scalable: additional crops, districts, FPOs, buyers and logistics providers can be added without changing the basic workflow.

Implementing the platform involves several operational, technical, and adoption risks that must be managed carefully. First, limited or poor-quality historical data may reduce the reliability of demand forecasts, while integrating verified market prices, weather, maps, and logistics data will likely require external partnerships or APIs. User adoption also faces hurdles, as farmers may have limited digital literacy, poor internet connectivity, or discomfort with app-based workflows, and broader trust can be undermined by payment disputes, cancellations, and late deliveries. Furthermore, supply chain execution presents distinct physical challenges: actual produce quality, quantity, and harvest availability may differ from initial listings, perishable goods require strict timing, careful handling, and specialized transport, and small, fragmented orders can drive up collection and delivery costs.

To ensure a reliable and scalable rollout, the platform will follow a phased implementation strategy built on strict operational safeguards and user accessibility. The deployment will begin with a small pilot utilizing clearly labeled sample data until verified transaction records are collected, evaluating demand forecasts through MAE/MAPE metrics without treating estimates as guaranteed orders. To drive adoption among rural producers, the system will feature a simple, mobile-first interface with regional-language labels, low-bandwidth-friendly forms, and assisted onboarding facilitated through FPOs. Marketplace trust and produce integrity will be maintained through listing verification, supplier ratings, buyer confirmations, standardized quality grading, and mandatory quantity checks at pickup. For logistics and fulfillment, the platform will prioritize perishable goods using strict harvest and delivery windows alongside cold-chain partnerships where needed, while aggregating nearby orders to enforce vehicle-capacity and minimum-load checks prior to dispatch. Finally, clear workflows for cancellations, disputes, refunds, and payment tracking will be backed by auditable order records, while external APIs will be integrated gradually with manual fallback entry options to ensure uninterrupted service during data outages.

## Impact and Benefits
Farmers and FPOs are the primary target users, with consumers, retailers, restaurants, bulk buyers and logistics providers as connected participants. By making demand and buyer requirements more visible, the platform aims to improve market access and enable collective fulfilment. Consumers and institutional buyers gain another channel to source produce from growers, while logistics providers can receive better-organized pickup and delivery plans. Government and ecosystem stakeholders may gain aggregated, privacy-conscious insights into demand, supply and movement patterns if the platform is deployed with appropriate data governance.

The solution delivers broad social, economic, operational, environmental, and transparency benefits across the agricultural value chain. Socially, it expands digital market access for small farmers and Farmer Producer Organizations (FPOs) by supporting regional languages and encouraging collective participation. Economically, it broadens market reach, enhances price transparency, cuts avoidable intermediary and coordination costs, and gives buyers more competitive sourcing options. From an operational standpoint, the platform streamlines supplier discovery for buyers, enables FPOs to consolidate produce volumes, and optimizes order coordination and vehicle routing. These logistical efficiencies also carry potential environmental advantages—subject to validation during a pilot phase—as better load utilization and fewer fragmented trips can lower fuel consumption and transport emissions, while improved supply-demand matching and delivery planning help minimize post-harvest spoilage. Finally, the system strengthens overall transparency and accountability through itemized cost breakdowns, digital order records, and QR-based batch traceability.

## Research and References

eNAM – National Agriculture Market — https://enam.gov.in/web/ — Government of India electronic trading portal; relevant background on transparent agricultural marketing and market linkages.

SFAC – Small Farmers’ Agribusiness Consortium — https://sfacindia.com/ — Information on FPO promotion and farmer aggregation; relevant to the collective sourcing model.

Agriculture Infrastructure Fund — https://agriinfra.dac.gov.in/ — Government scheme information related to post-harvest infrastructure and community farming assets.

AGMARKNET — https://agmarknet.gov.in/ — Agricultural marketing information and market price/arrival data; potential reference data source subject to availability and permitted use.

OpenStreetMap — https://www.openstreetmap.org/ — Open geographic data and mapping ecosystem for visualizing pickup and delivery locations.

Google OR-Tools — https://developers.google.com/optimization — Technical documentation for vehicle routing and optimization methods
